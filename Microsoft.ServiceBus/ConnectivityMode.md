<Type Name="ConnectivityMode" FullName="Microsoft.ServiceBus.ConnectivityMode">
  <TypeSignature Language="C#" Value="public enum ConnectivityMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConnectivityMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.ConnectivityMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ConnectivityMode" />
  <TypeSignature Language="F#" Value="type ConnectivityMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>Service Bus との通信に使用される基になるワイヤレベル プロトコルを設定します。 </summary>
    <remarks>接続モードとは異なります、<see cref="T:Microsoft.ServiceBus.Messaging.TransportType" />プロトコル サービスがクライアントとの通信を指定します。 トランスポートの種類は、使用するバインディングによって決まります。 関係なく<see cref="T:Microsoft.ServiceBus.Messaging.TransportType" />(NetMessaging または AMQP) を選択する、選択した接続モードで、通信が行われます。 たとえば、AMQP が TCP または HTTP (S) 経由で発生することができます。 </remarks>
  </Docs>
  <Members>
    <Member MemberName="AutoDetect">
      <MemberSignature Language="C#" Value="AutoDetect" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.ConnectivityMode AutoDetect = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivityMode.AutoDetect" />
      <MemberSignature Language="VB.NET" Value="AutoDetect" />
      <MemberSignature Language="F#" Value="AutoDetect = 2" Usage="Microsoft.ServiceBus.ConnectivityMode.AutoDetect" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>自動検出モードです。 現在のネットワーク環境のいずれかの接続オプションがあるかどうかを調べる自動検出メカニズムに基づいて、TCP、HTTP および HTTPS モード間で自動的に選択します。 両方がある場合、システムでは、既定で TCP を選択します。</summary>
      </Docs>
    </Member>
    <Member MemberName="Http">
      <MemberSignature Language="C#" Value="Http" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.ConnectivityMode Http = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivityMode.Http" />
      <MemberSignature Language="VB.NET" Value="Http" />
      <MemberSignature Language="F#" Value="Http = 0" Usage="Microsoft.ServiceBus.ConnectivityMode.Http" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>HTTP モードです。 リスナーは、メッセージを待って、Service Bus サービスに HTTPS 接続での後に、HTTP 接続を試行します。 簡単に TCP ポートの制約を回避するためよりこれを許可する可能性があります。</summary>
      </Docs>
    </Member>
    <Member MemberName="Https">
      <MemberSignature Language="C#" Value="Https" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.ConnectivityMode Https = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivityMode.Https" />
      <MemberSignature Language="VB.NET" Value="Https" />
      <MemberSignature Language="F#" Value="Https = 3" Usage="Microsoft.ServiceBus.ConnectivityMode.Https" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>HTTPS モードです。 リスナーは、Service Bus サービスとの HTTPS 接続を試行し、メッセージを待機します。 </summary>
      </Docs>
    </Member>
    <Member MemberName="Tcp">
      <MemberSignature Language="C#" Value="Tcp" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.ConnectivityMode Tcp = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivityMode.Tcp" />
      <MemberSignature Language="VB.NET" Value="Tcp" />
      <MemberSignature Language="F#" Value="Tcp = 1" Usage="Microsoft.ServiceBus.ConnectivityMode.Tcp" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>TCP モード (既定)。 リスナーは、9350 から 9354 の範囲内で宛先ポートに Service Bus サービスへの TCP 接続を作成します。</summary>
      </Docs>
    </Member>
  </Members>
</Type>