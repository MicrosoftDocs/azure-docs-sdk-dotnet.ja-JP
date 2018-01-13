<Type Name="HybridConnectionState" FullName="Microsoft.ServiceBus.HybridConnectionState">
  <TypeSignature Language="C#" Value="public enum HybridConnectionState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed HybridConnectionState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.HybridConnectionState" />
  <TypeSignature Language="VB.NET" Value="Public Enum HybridConnectionState" />
  <TypeSignature Language="F#" Value="type HybridConnectionState = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>ハイブリッド接続の現在の接続状態を説明します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Direct">
      <MemberSignature Language="C#" Value="Direct" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.HybridConnectionState Direct = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.HybridConnectionState.Direct" />
      <MemberSignature Language="VB.NET" Value="Direct" />
      <MemberSignature Language="F#" Value="Direct = 1" Usage="Microsoft.ServiceBus.HybridConnectionState.Direct" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.HybridConnectionState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>直接接続します。 通信している相手は、Azure Service Bus のインフラストラクチャではなく、直接的なネットワーク パス上のルーティング ソケットの使用を接続します。 </summary>
      </Docs>
    </Member>
    <Member MemberName="Relayed">
      <MemberSignature Language="C#" Value="Relayed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.HybridConnectionState Relayed = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.HybridConnectionState.Relayed" />
      <MemberSignature Language="VB.NET" Value="Relayed" />
      <MemberSignature Language="F#" Value="Relayed = 0" Usage="Microsoft.ServiceBus.HybridConnectionState.Relayed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.HybridConnectionState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>リレーされる接続。 通信している相手は、リレー型ソケットと、Azure Service Bus インフラストラクチャから接続できます。 </summary>
      </Docs>
    </Member>
  </Members>
</Type>