<Type Name="TransportType" FullName="Microsoft.Azure.Devices.TransportType">
  <TypeSignature Language="C#" Value="public enum TransportType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TransportType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.TransportType" />
  <TypeSignature Language="VB.NET" Value="Public Enum TransportType" />
  <TypeSignature Language="F#" Value="type TransportType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            トランスポートによってサポートされる型への Amqp および Amqp のみ WebSocket 経由で
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Amqp">
      <MemberSignature Language="C#" Value="Amqp" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.TransportType Amqp = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.TransportType.Amqp" />
      <MemberSignature Language="VB.NET" Value="Amqp" />
      <MemberSignature Language="F#" Value="Amqp = 0" Usage="Microsoft.Azure.Devices.TransportType.Amqp" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.TransportType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            メッセージ キューのプロトコルのトランスポートの詳細。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Amqp_WebSocket_Only">
      <MemberSignature Language="C#" Value="Amqp_WebSocket_Only" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.TransportType Amqp_WebSocket_Only = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.TransportType.Amqp_WebSocket_Only" />
      <MemberSignature Language="VB.NET" Value="Amqp_WebSocket_Only" />
      <MemberSignature Language="F#" Value="Amqp_WebSocket_Only = 1" Usage="Microsoft.Azure.Devices.TransportType.Amqp_WebSocket_Only" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.TransportType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            高度なメッセージ キュー プロトコルのトランスポート WebSocket 経由でのみです。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>