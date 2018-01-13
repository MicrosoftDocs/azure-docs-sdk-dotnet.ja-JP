<Type Name="TcpRelayConnectionMode" FullName="Microsoft.ServiceBus.TcpRelayConnectionMode">
  <TypeSignature Language="C#" Value="public enum TcpRelayConnectionMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TcpRelayConnectionMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.TcpRelayConnectionMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum TcpRelayConnectionMode" />
  <TypeSignature Language="F#" Value="type TcpRelayConnectionMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>接続モードをについて説明します、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />です。 </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Hybrid">
      <MemberSignature Language="C#" Value="Hybrid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.TcpRelayConnectionMode Hybrid = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Hybrid" />
      <MemberSignature Language="VB.NET" Value="Hybrid" />
      <MemberSignature Language="F#" Value="Hybrid = 1" Usage="Microsoft.ServiceBus.TcpRelayConnectionMode.Hybrid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayConnectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>通信は、クライアントとサービスのエンドポイントが互いに直接ソケット接続をネゴシエート中に、Azure Service Bus インフラストラクチャを介して中継されます。 この直接接続の調整は、Azure Service Bus クラウド サービスによって制御されます。 直接ソケット接続アルゴリズムはファイアウォールや NAT の両後ろに配置された 2 つのパーティ間の直接接続を確立できるデバイス。 アルゴリズムはファイアウォール トラバーサルで発信接続のみを使用して、NAT トラバーサル用相互ポート予測アルゴリズムに依存しています。 アルゴリズムがクライアントの数が少ないホーム ネットワークまたは小規模ビジネスのシナリオは非常に高い成功率に NAT トラバーサル アルゴリズムが非常に限定された時間指定の調整と NAT に予期される動作は最善の推測の予測に依存するので、大きな Nat とその成功率が低下するとします。 直接接続を確立することができる場合、リレー接続はメッセージまたはデータを失わずに直接接続を自動的にアップグレードします。 直接接続を確立できない場合は、データを Azure Service Bus リレーを通過継続されます。 
            
            さらに、このモードでは、NAT 予測アルゴリズムの送信ポート 819 が必要です。 多くの個人のファイアウォール製品の直接によって確立されているが送信ソケットを接続接続モードも必要になります (個人用の Windows ファイアウォールと他の製品が通常プロンプトを表示、ユーザーを許可する、1 回限りのポリシー例外ユーザー)、ホスト アプリケーションにします。 
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Relayed">
      <MemberSignature Language="C#" Value="Relayed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.TcpRelayConnectionMode Relayed = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Relayed" />
      <MemberSignature Language="VB.NET" Value="Relayed" />
      <MemberSignature Language="F#" Value="Relayed = 0" Usage="Microsoft.ServiceBus.TcpRelayConnectionMode.Relayed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayConnectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>すべての通信は、Azure Service Bus クラウドを介して中継されます。 SSL で保護された制御接続を使用して、クライアント サービスのすべての通信を通過するリレー型のエンド ツー エンドのソケット接続をネゴシエートします。 接続が確立されると、Azure Service Bus のインフラストラクチャは非常によく似た双方向のバイト ストリームをリレーするソケット フォワーダー プロキシという役割を果たします。 さらに、このモードでは、NAT 予測アルゴリズムの送信ポート 819 が必要です。 多くの個人のファイアウォール製品の直接によって確立されているが送信ソケットを接続接続モードも必要になります (個人用の Windows ファイアウォールと他の製品が通常プロンプトを表示、ユーザーを許可する、1 回限りのポリシー例外ユーザー)、ホスト アプリケーションにします。</summary>
      </Docs>
    </Member>
  </Members>
</Type>