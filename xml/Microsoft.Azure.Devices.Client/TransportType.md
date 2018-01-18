<Type Name="TransportType" FullName="Microsoft.Azure.Devices.Client.TransportType">
  <TypeSignature Language="C#" Value="public enum TransportType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TransportType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.TransportType" />
  <TypeSignature Language="VB.NET" Value="Public Enum TransportType" />
  <TypeSignature Language="F#" Value="type TransportType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="4bf66-101">HTTP 1.1、MQTT/TCP、AMQP/WS、MQTT/WS DeviceClient - AMQP/TCP でのトランスポートの種類がサポートされます。</span><span class="sxs-lookup"><span data-stu-id="4bf66-101">Transport types supported by DeviceClient - AMQP/TCP, HTTP 1.1, MQTT/TCP, AMQP/WS, MQTT/WS</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Amqp">
      <MemberSignature Language="C#" Value="Amqp" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.Client.TransportType Amqp = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Client.TransportType.Amqp" />
      <MemberSignature Language="VB.NET" Value="Amqp" />
      <MemberSignature Language="F#" Value="Amqp = 0" Usage="Microsoft.Azure.Devices.Client.TransportType.Amqp" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.TransportType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4bf66-102">メッセージ キューのプロトコルのトランスポートの詳細。</span><span class="sxs-lookup"><span data-stu-id="4bf66-102">Advanced Message Queuing Protocol transport.</span></span>
            <span data-ttu-id="4bf66-103">失敗した場合は、WebSocket 経由で最初および Amqp への切り替えを TCP 経由で Amqp を再試行します。</span><span class="sxs-lookup"><span data-stu-id="4bf66-103">Try Amqp over TCP first and fallback to Amqp over WebSocket if that fails</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Amqp_Tcp_Only">
      <MemberSignature Language="C#" Value="Amqp_Tcp_Only" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.Client.TransportType Amqp_Tcp_Only = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Client.TransportType.Amqp_Tcp_Only" />
      <MemberSignature Language="VB.NET" Value="Amqp_Tcp_Only" />
      <MemberSignature Language="F#" Value="Amqp_Tcp_Only = 3" Usage="Microsoft.Azure.Devices.Client.TransportType.Amqp_Tcp_Only" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.TransportType</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4bf66-104">ネイティブでのみ TCP 経由でメッセージ キュー プロトコル トランスポートの詳細</span><span class="sxs-lookup"><span data-stu-id="4bf66-104">Advanced Message Queuing Protocol transport over native TCP only</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Amqp_WebSocket_Only">
      <MemberSignature Language="C#" Value="Amqp_WebSocket_Only" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.Client.TransportType Amqp_WebSocket_Only = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Client.TransportType.Amqp_WebSocket_Only" />
      <MemberSignature Language="VB.NET" Value="Amqp_WebSocket_Only" />
      <MemberSignature Language="F#" Value="Amqp_WebSocket_Only = 2" Usage="Microsoft.Azure.Devices.Client.TransportType.Amqp_WebSocket_Only" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.TransportType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4bf66-105">高度なメッセージ キュー プロトコルのトランスポート WebSocket 経由でのみです。</span><span class="sxs-lookup"><span data-stu-id="4bf66-105">Advanced Message Queuing Protocol transport over WebSocket only.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Http1">
      <MemberSignature Language="C#" Value="Http1" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.Client.TransportType Http1 = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Client.TransportType.Http1" />
      <MemberSignature Language="VB.NET" Value="Http1" />
      <MemberSignature Language="F#" Value="Http1 = 1" Usage="Microsoft.Azure.Devices.Client.TransportType.Http1" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.TransportType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4bf66-106">ハイパー テキスト転送プロトコルのバージョン 1 のトランスポート。</span><span class="sxs-lookup"><span data-stu-id="4bf66-106">HyperText Transfer Protocol version 1 transport.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Mqtt">
      <MemberSignature Language="C#" Value="Mqtt" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.Client.TransportType Mqtt = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Client.TransportType.Mqtt" />
      <MemberSignature Language="VB.NET" Value="Mqtt" />
      <MemberSignature Language="F#" Value="Mqtt = 4" Usage="Microsoft.Azure.Devices.Client.TransportType.Mqtt" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.TransportType</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4bf66-107">製品利用統計情報のキューのトランスポートをメッセージします。</span><span class="sxs-lookup"><span data-stu-id="4bf66-107">Message Queuing Telemetry Transport.</span></span>
            <span data-ttu-id="4bf66-108">失敗した場合は、WebSocket 経由で最初と Mqtt への切り替えを TCP 経由で Mqtt を再試行します。</span><span class="sxs-lookup"><span data-stu-id="4bf66-108">Try Mqtt over TCP first and fallback to Mqtt over WebSocket if that fails</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Mqtt_Tcp_Only">
      <MemberSignature Language="C#" Value="Mqtt_Tcp_Only" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.Client.TransportType Mqtt_Tcp_Only = int32(6)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Client.TransportType.Mqtt_Tcp_Only" />
      <MemberSignature Language="VB.NET" Value="Mqtt_Tcp_Only" />
      <MemberSignature Language="F#" Value="Mqtt_Tcp_Only = 6" Usage="Microsoft.Azure.Devices.Client.TransportType.Mqtt_Tcp_Only" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.TransportType</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4bf66-109">ネイティブでのみ TCP 経由のメッセージ キュー製品利用統計情報トランスポート</span><span class="sxs-lookup"><span data-stu-id="4bf66-109">Message Queuing Telemetry Transport over native TCP only</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Mqtt_WebSocket_Only">
      <MemberSignature Language="C#" Value="Mqtt_WebSocket_Only" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.Client.TransportType Mqtt_WebSocket_Only = int32(5)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Client.TransportType.Mqtt_WebSocket_Only" />
      <MemberSignature Language="VB.NET" Value="Mqtt_WebSocket_Only" />
      <MemberSignature Language="F#" Value="Mqtt_WebSocket_Only = 5" Usage="Microsoft.Azure.Devices.Client.TransportType.Mqtt_WebSocket_Only" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.TransportType</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4bf66-110">メッセージのキューの遠隔測定トランスポート Websocket 経由でのみです。</span><span class="sxs-lookup"><span data-stu-id="4bf66-110">Message Queuing Telemetry Transport over Websocket only.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>