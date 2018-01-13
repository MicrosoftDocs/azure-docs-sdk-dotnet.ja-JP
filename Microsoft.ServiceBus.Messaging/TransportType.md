<Type Name="TransportType" FullName="Microsoft.ServiceBus.Messaging.TransportType">
  <TypeSignature Language="C#" Value="public enum TransportType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TransportType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.TransportType" />
  <TypeSignature Language="VB.NET" Value="Public Enum TransportType" />
  <TypeSignature Language="F#" Value="type TransportType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>メッセージング プロトコルを NetMessaging (Azure Service Bus に独自のプロトコル) または AMQP (業界標準) のいずれかに設定する列挙です。</summary>
    <remarks>NetMessaging には、既定値が、AMQP、優先プロトコルです。 (NetMessaging または AMQP) を選択するどのトランスポートの種類に関係なく、通信を介した、選択した<see cref="T:Microsoft.ServiceBus.ConnectivityMode" />です。 たとえば、AMQP が TCP または HTTP (S) 経由で発生することができます。</remarks>
    <altmember cref="T:Microsoft.ServiceBus.ConnectivityMode" />
  </Docs>
  <Members>
    <Member MemberName="Amqp">
      <MemberSignature Language="C#" Value="Amqp" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.TransportType Amqp = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.TransportType.Amqp" />
      <MemberSignature Language="VB.NET" Value="Amqp" />
      <MemberSignature Language="F#" Value="Amqp = 1" Usage="Microsoft.ServiceBus.Messaging.TransportType.Amqp" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TransportType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>Advanced Message Queuing Protocol (AMQP) トランスポートの種類。</summary>
      </Docs>
    </Member>
    <Member MemberName="NetMessaging">
      <MemberSignature Language="C#" Value="NetMessaging" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.TransportType NetMessaging = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.TransportType.NetMessaging" />
      <MemberSignature Language="VB.NET" Value="NetMessaging" />
      <MemberSignature Language="F#" Value="NetMessaging = 0" Usage="Microsoft.ServiceBus.Messaging.TransportType.NetMessaging" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TransportType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>ネットワークのメッセージング トランスポート種類。</summary>
      </Docs>
    </Member>
  </Members>
</Type>