<Type Name="ConnectivityMode" FullName="Microsoft.Azure.NotificationHubs.ConnectivityMode">
  <TypeSignature Language="C#" Value="public enum ConnectivityMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConnectivityMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.ConnectivityMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ConnectivityMode" />
  <TypeSignature Language="F#" Value="type ConnectivityMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>接続モードをについて説明します。 </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AutoDetect">
      <MemberSignature Language="C#" Value="AutoDetect" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.NotificationHubs.ConnectivityMode AutoDetect = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.ConnectivityMode.AutoDetect" />
      <MemberSignature Language="VB.NET" Value="AutoDetect" />
      <MemberSignature Language="F#" Value="AutoDetect = 2" Usage="Microsoft.Azure.NotificationHubs.ConnectivityMode.AutoDetect" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>自動検出モードです。 現在のネットワーク環境のいずれかの接続オプションがあるかどうかを調べる自動検出メカニズムに基づいて、TCP、HTTP および HTTPS モード間で自動的に選択します。 両方がある場合、システムでは、既定で TCP を選択します。</summary>
      </Docs>
    </Member>
    <Member MemberName="Http">
      <MemberSignature Language="C#" Value="Http" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.NotificationHubs.ConnectivityMode Http = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.ConnectivityMode.Http" />
      <MemberSignature Language="VB.NET" Value="Http" />
      <MemberSignature Language="F#" Value="Http = 0" Usage="Microsoft.Azure.NotificationHubs.ConnectivityMode.Http" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>HTTP モードです。 リスナーは、Windows Azure Service Bus サービスとメッセージのポーリングを使用した HTTPS 接続での後に、HTTP 接続を試みます。 簡単に TCP ポートの制約を回避するためよりこれを許可する可能性があります。</summary>
      </Docs>
    </Member>
    <Member MemberName="Tcp">
      <MemberSignature Language="C#" Value="Tcp" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.NotificationHubs.ConnectivityMode Tcp = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.ConnectivityMode.Tcp" />
      <MemberSignature Language="VB.NET" Value="Tcp" />
      <MemberSignature Language="F#" Value="Tcp = 1" Usage="Microsoft.Azure.NotificationHubs.ConnectivityMode.Tcp" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>TCP モード (既定)。 リスナーは、9350 から 9354 の範囲内で宛先のポートを Windows Azure Service Bus サービスへの TCP 接続を作成します。</summary>
      </Docs>
    </Member>
  </Members>
</Type>