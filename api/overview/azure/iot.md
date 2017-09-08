---
title: ".NET 用 Azure IoT ライブラリ"
description: ".NET 用 Azure IoT ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, IoT
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/21/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: bdbcc37affb55336d1a3fafe24b8e7ffd78ec180
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-iot-libraries-for-net"></a>.NET 用 Azure IoT ライブラリ

## <a name="overview"></a>概要

[Azure IoT Hub](https://azure.microsoft.com/services/iot-hub/) は、何百万ものデバイスとソリューション バック エンド間で、セキュリティで保護された信頼性のある双方向通信を実現する、完全に管理されたサービスです。

ネットワークに接続された単純なセンサーから、強力なスタンドアロン コンピューティング デバイスまで、広範なデバイスとデータ ソースを IoT ソリューションに含めることができます。 デバイスの処理能力、メモリ、通信帯域幅、通信プロトコルのサポートは限られていてもかまいません。 IoT の[デバイス SDK](https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-sdks) を使うと、さまざまなデバイスやバックエンド アプリケーションのためのクライアント アプリケーションを実装できます。

.NET 用のデバイス SDK を使うと、.NET を実行して Azure IoT Hub に接続するデバイスの作成が容易になります。

.NET 用のサービス SDK を使うと、デバイスを管理し、クラウドからのデバイスの制御を可能にする、.NET を使うバックエンド アプリケーションの作成が容易になります。

[Azure IoT についての詳細](https://docs.microsoft.com/azure/iot-hub/)。


## <a name="client-library"></a>クライアント ライブラリ

IoT Hub に接続してメッセージを送信するには、.NET IoT デバイス クライアントを使います。

[NuGet パッケージ]( https://www.nuget.org/packages/Microsoft.Azure.Devices.Client)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Devices.Client
```

```bash
dotnet add package Microsoft.Azure.Devices.Client
```
### <a name="code-examples"></a>コード例 

この例では、IoT Hub に接続し、1 秒あたり 1 つのメッセージを送信します。

```csharp
string deviceKey = "<deviceKey>";
string deviceId = "<deviceId>";
string iotHubHostName = "<IoTHubHostname>";
DeviceAuthenticationWithRegistrySymmetricKeyvar deviceAuthentication = new DeviceAuthenticationWithRegistrySymmetricKey(deviceId, deviceKey);

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
> [クライアント API を探す](/dotnet/api/overview/azure/iot/client)

## <a name="samples"></a>サンプル

- [汎用 Web サービスから Event Hub へのシナリオ](https://azure.microsoft.com/resources/samples/event-hubs-dotnet-importfromweb/)

Azure IoT のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=iot-hub)をご覧ください。

詳しくは、[Azure IoT Hub 開発者ガイド](https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide)をご覧ください。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
