<Type Name="EndpointKind" FullName="Microsoft.Azure.Devices.EndpointKind">
  <TypeSignature Language="C#" Value="public enum EndpointKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed EndpointKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.EndpointKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum EndpointKind" />
  <TypeSignature Language="F#" Value="type EndpointKind = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="3cf5b-101">IOT hub によって公開されるエンドポイント</span><span class="sxs-lookup"><span data-stu-id="3cf5b-101">Endpoints exposed by IOT hub</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeviceBound">
      <MemberSignature Language="C#" Value="DeviceBound" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.EndpointKind DeviceBound = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.EndpointKind.DeviceBound" />
      <MemberSignature Language="VB.NET" Value="DeviceBound" />
      <MemberSignature Language="F#" Value="DeviceBound = 0" Usage="Microsoft.Azure.Devices.EndpointKind.DeviceBound" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.EndpointKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf5b-102">デバイスにコマンドを送信します。</span><span class="sxs-lookup"><span data-stu-id="3cf5b-102">sends commands to device</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Events">
      <MemberSignature Language="C#" Value="Events" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.EndpointKind Events = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.EndpointKind.Events" />
      <MemberSignature Language="VB.NET" Value="Events" />
      <MemberSignature Language="F#" Value="Events = 1" Usage="Microsoft.Azure.Devices.EndpointKind.Events" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.EndpointKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf5b-103">デバイスのテレメトリの入口</span><span class="sxs-lookup"><span data-stu-id="3cf5b-103">device telemetry ingress</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Feedback">
      <MemberSignature Language="C#" Value="Feedback" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.EndpointKind Feedback = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.EndpointKind.Feedback" />
      <MemberSignature Language="VB.NET" Value="Feedback" />
      <MemberSignature Language="F#" Value="Feedback = 3" Usage="Microsoft.Azure.Devices.EndpointKind.Feedback" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.EndpointKind</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf5b-104">ack または nack システム - から&gt;クラウド</span><span class="sxs-lookup"><span data-stu-id="3cf5b-104">acks/nacks from system -&gt; cloud</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="FileNotification">
      <MemberSignature Language="C#" Value="FileNotification" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.EndpointKind FileNotification = int32(5)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.EndpointKind.FileNotification" />
      <MemberSignature Language="VB.NET" Value="FileNotification" />
      <MemberSignature Language="F#" Value="FileNotification = 5" Usage="Microsoft.Azure.Devices.EndpointKind.FileNotification" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.EndpointKind</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf5b-105">デバイスから通知メッセージ ファイルのアップロードします。</span><span class="sxs-lookup"><span data-stu-id="3cf5b-105">Notification messages for file uploads from devices</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="Response" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.EndpointKind Response = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.EndpointKind.Response" />
      <MemberSignature Language="VB.NET" Value="Response" />
      <MemberSignature Language="F#" Value="Response = 4" Usage="Microsoft.Azure.Devices.EndpointKind.Response" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.EndpointKind</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf5b-106">デバイスからの応答の相関&gt;クラウド</span><span class="sxs-lookup"><span data-stu-id="3cf5b-106">correlated responses from device -&gt; cloud</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ServiceBound">
      <MemberSignature Language="C#" Value="ServiceBound" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.EndpointKind ServiceBound = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.EndpointKind.ServiceBound" />
      <MemberSignature Language="VB.NET" Value="ServiceBound" />
      <MemberSignature Language="F#" Value="ServiceBound = 2" Usage="Microsoft.Azure.Devices.EndpointKind.ServiceBound" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.EndpointKind</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cf5b-107">デバイスから照会&gt;クラウド</span><span class="sxs-lookup"><span data-stu-id="3cf5b-107">inquiries from device -&gt; cloud</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>