---
title: .NET 用 Azure IoT ライブラリ
description: .NET 用 Azure IoT ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: iot-hub
ms.openlocfilehash: 667663c5f5e3452fcc5ec0c4f3ded997370c5852
ms.sourcegitcommit: 7f1a1bf275d8489f8df266b746baa33d66fcb2c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/21/2018
ms.locfileid: "53737077"
---
# <a name="azure-iot-libraries-for-net"></a><span data-ttu-id="d69ed-103">.NET 用 Azure IoT ライブラリ</span><span class="sxs-lookup"><span data-stu-id="d69ed-103">Azure IoT libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="d69ed-104">概要</span><span class="sxs-lookup"><span data-stu-id="d69ed-104">Overview</span></span>

<span data-ttu-id="d69ed-105">[Azure IoT Hub](https://azure.microsoft.com/services/iot-hub/) は、何百万ものデバイスとソリューション バック エンド間で、セキュリティで保護された信頼性のある双方向通信を実現する、フル マネージドのサービスです。</span><span class="sxs-lookup"><span data-stu-id="d69ed-105">[Azure IoT Hub](https://azure.microsoft.com/services/iot-hub/) is a fully managed service that enables reliable and secure bi-directional communications between millions of devices and a solution back end.</span></span>

<span data-ttu-id="d69ed-106">ネットワークに接続された単純なセンサーから、強力なスタンドアロン コンピューティング デバイスまで、広範なデバイスとデータ ソースを IoT ソリューションに含めることができます。</span><span class="sxs-lookup"><span data-stu-id="d69ed-106">Devices and data sources in an IoT solution can range from a simple network-connected sensor to a powerful, standalone computing device.</span></span> <span data-ttu-id="d69ed-107">デバイスの処理能力、メモリ、通信帯域幅、通信プロトコルのサポートは限られていてもかまいません。</span><span class="sxs-lookup"><span data-stu-id="d69ed-107">Devices may have limited processing capability, memory, communication bandwidth, and communication protocol support.</span></span> <span data-ttu-id="d69ed-108">IoT の[デバイス SDK](https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-sdks) を使うと、さまざまなデバイスやバックエンド アプリケーションのためのクライアント アプリケーションを実装できます。</span><span class="sxs-lookup"><span data-stu-id="d69ed-108">The IoT [device SDKs](https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-sdks) enable you to implement client applications for a wide variety of devices and back-end applications.</span></span>

<span data-ttu-id="d69ed-109">.NET 用のデバイス SDK を使うと、.NET を実行して Azure IoT Hub に接続するデバイスの作成が容易になります。</span><span class="sxs-lookup"><span data-stu-id="d69ed-109">The device SDK for .NET facilitates building devices running .NET that connect to Azure IoT Hub.</span></span>

<span data-ttu-id="d69ed-110">.NET 用のサービス SDK を使うと、デバイスを管理し、クラウドからのデバイスの制御を可能にする、.NET を使うバックエンド アプリケーションの作成が容易になります。</span><span class="sxs-lookup"><span data-stu-id="d69ed-110">The service SDK for .NET facilitates building back-end applications using .NET that manage and allow controlling devices from the Cloud.</span></span>

<span data-ttu-id="d69ed-111">[Azure IoT についての詳細](https://docs.microsoft.com/azure/iot-hub/)。</span><span class="sxs-lookup"><span data-stu-id="d69ed-111">[Learn more about Azure IoT](https://docs.microsoft.com/azure/iot-hub/).</span></span>


## <a name="client-library"></a><span data-ttu-id="d69ed-112">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="d69ed-112">Client library</span></span>

<span data-ttu-id="d69ed-113">IoT Hub に接続してメッセージを送信するには、.NET IoT デバイス クライアントを使います。</span><span class="sxs-lookup"><span data-stu-id="d69ed-113">Use the .NET IoT devices client to connect and send messages to your IoT Hub.</span></span>

<span data-ttu-id="d69ed-114">[NuGet パッケージ]( https://www.nuget.org/packages/Microsoft.Azure.Devices.Client)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="d69ed-114">Install the [NuGet package]( https://www.nuget.org/packages/Microsoft.Azure.Devices.Client) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="d69ed-115">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="d69ed-115">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Devices.Client
```

```bash
dotnet add package Microsoft.Azure.Devices.Client
```
### <a name="code-examples"></a><span data-ttu-id="d69ed-116">コード例</span><span class="sxs-lookup"><span data-stu-id="d69ed-116">Code Examples</span></span> 

<span data-ttu-id="d69ed-117">この例では、IoT Hub に接続し、1 秒あたり 1 つのメッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="d69ed-117">This example connects to the IoT Hub and sends one message per second.</span></span>

```csharp
string deviceKey = "<deviceKey>";
string deviceId = "<deviceId>";
string iotHubHostName = "<IoTHubHostname>";
var deviceAuthentication = new DeviceAuthenticationWithRegistrySymmetricKey(deviceId, deviceKey);

DeviceClient deviceClient = DeviceClient.Create(iotHubHostName, deviceAuthentication, TransportType.Mqtt);

while (true)
{
    double currentTemperature = 20 + Rand.NextDouble() * 15;
    double currentHumidity = 60 + Rand.NextDouble() * 20;

    var telemetryDataPoint = new
    {
        messageId = _messageId++,
        deviceId = deviceId,
        temperature = currentTemperature,
        humidity = currentHumidity
    };
    string messageString = JsonConvert.SerializeObject(telemetryDataPoint);
    Message message = new Message(Encoding.ASCII.GetBytes(messageString));
    message.Properties.Add("temperatureAlert", (currentTemperature > 30) ? "true" : "false");

    await deviceClient.SendEventAsync(message);
    Console.WriteLine("{0} > Sending message: {1}", DateTime.Now, messageString);

    await Task.Delay(1000);
}
```


> [!div class="nextstepaction"]
> [<span data-ttu-id="d69ed-118">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="d69ed-118">Explore the client APIs</span></span>](/dotnet/api/overview/azure/iot/client)

## <a name="samples"></a><span data-ttu-id="d69ed-119">サンプル</span><span class="sxs-lookup"><span data-stu-id="d69ed-119">Samples</span></span>

- [<span data-ttu-id="d69ed-120">汎用 Web サービスから Event Hub へのシナリオ</span><span class="sxs-lookup"><span data-stu-id="d69ed-120">Generic Web Service to Event Hub scenario</span></span>](https://azure.microsoft.com/resources/samples/event-hubs-dotnet-importfromweb/)

<span data-ttu-id="d69ed-121">Azure IoT のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=iot-hub)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="d69ed-121">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=iot-hub) of Azure IoT Upsamples.</span></span>

<span data-ttu-id="d69ed-122">詳しくは、[Azure IoT Hub 開発者ガイド](https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="d69ed-122">View the [Azure IoT Hub developer guide](https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide) for more guidance.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
