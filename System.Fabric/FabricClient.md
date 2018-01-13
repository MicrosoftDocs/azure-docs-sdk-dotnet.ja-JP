<Type Name="FabricClient" FullName="System.Fabric.FabricClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FabricClient extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type FabricClient = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1201:ElementsMustAppearInTheCorrectOrder", Justification="Preserve order of public members from V1.")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1204:StaticElementsMustAppearBeforeInstanceElements", Justification="Current grouping improves readability.")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1202:ElementsMustBeOrderedByAccess", Justification="Current grouping improves readability.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>作成し、Service Fabric サービスとその他のエンティティを管理します。</para>
    </summary>
    <remarks>
      <para>可能な限り FabricClients を共有することを強くお勧めします。
                これは、FabricClient にキャッシュし、それ以外の場合を十分に活用することはできません、バッチ処理などの複数の最適化があるためです。
                </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.FabricClient" /> クラスの新しいインスタンスを初期化します。 このコンス トラクターは、クラスター内で実行されているコードで使用する必要があります。 これにより、<see cref="T:System.Fabric.FabricClient" />インスタンスと同じノードで実行されているローカル ゲートウェイ サービスを経由してクラスターに接続します。</para>
        </summary>
        <remarks>
          <para>このコンス トラクターは、th クラスターへの接続に同じノードで実行されているローカル ゲートウェイ サービスを使用するため、クライアントは、追加のネットワーク ホップをバイパスできます。 クラスター外で実行されているコードから、クラスターに接続するには、接続パラメーターを明示的に指定できる別のコンス トラクターを使用します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.FabricClientRole clientRole);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricClientRole clientRole) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.FabricClientRole)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientRole As FabricClientRole)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.FabricClientRole -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient clientRole" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientRole" Type="System.Fabric.FabricClientRole" />
      </Parameters>
      <Docs>
        <param name="clientRole">
          <para>Fabric クライアントの役割です。</para>
        </param>
        <summary>
          <para>
            新しいインスタンスを初期化、 <see cref="T:System.Fabric.FabricClient" /> - 指定されたファブリック クライアントの役割を持つクラス<see cref="T:System.Fabric.FabricClientRole" />です。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.FabricClientSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClientSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.FabricClientSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (settings As FabricClientSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.FabricClientSettings -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient settings" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para>Fabric クライアントによって使用されるファブリックのクライアント設定します。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.FabricClient" />目的を持つクラス<see cref="T:System.Fabric.FabricClientSettings" />です。 場合、 <see cref="T:System.Fabric.FabricClient" /> 、サービスと同じクラスターには、ローカルを使用して<see cref="T:System.Fabric.FabricClient" />です。 ローカル<see cref="T:System.Fabric.FabricClient" />できるサービス ファブリックの機能、<see cref="T:System.Fabric.FabricClient" />一覧から選択することではなくローカル ゲートウェイ サービスに接続します。 これにより、クライアントは、追加のネットワーク ホップをバイパスできます。 場合、サービスは、同じクラスター内の別のサービス パーティションを解決し、ローカルを使用することをお勧め<see cref="T:System.Fabric.FabricClient" />の自動負荷分散を有効にし、パフォーマンスが向上します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient hostEndpoints" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="hostEndpoints">
          <para>ゲートウェイ アドレスのセットを定義、<see cref="T:System.Fabric.FabricClient" />クラスターへの接続に使用できます。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.FabricClient" />サービス ファブリック ゲートウェイ アドレスを指定したクラスです。 これらのホストのエンドポイントの一覧は、':' 区切りの文字列で最初の部分は、クラスターの ip アドレスと 2 番目の部分は、クライアント接続のエンドポイント ポートです。 </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.FabricClientSettings settings, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClientSettings settings, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.FabricClientSettings,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (settings As FabricClientSettings, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.FabricClientSettings * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (settings, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="settings">
          <para>Fabric クライアント設定します。</para>
        </param>
        <param name="hostEndpoints">
          <para>ゲートウェイ アドレスのセットを定義、<see cref="T:System.Fabric.FabricClient" />クラスターへの接続に使用できます。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.FabricClient" />サービス ファブリックのゲートウェイ アドレスと、目的の指定したクラス<see cref="T:System.Fabric.FabricClientSettings" />です。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.SecurityCredentials credential, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.SecurityCredentials,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.SecurityCredentials * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (credential, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential">
          <para>
            <see cref="T:System.Fabric.SecurityCredentials" />セキュリティ設定を定義、<see cref="T:System.Fabric.FabricClient" />です。</para>
        </param>
        <param name="hostEndpoints">
          <para>ゲートウェイ アドレスのセットを定義、<see cref="T:System.Fabric.FabricClient" />クラスターへの接続に使用できます。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.FabricClient" />クラスに指定されたサービス ファブリック ゲートウェイ アドレスと<see cref="T:System.Fabric.SecurityCredentials" />です。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (TimeSpan keepAliveInterval, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan keepAliveInterval, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.TimeSpan,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keepAliveInterval As TimeSpan, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : TimeSpan * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (keepAliveInterval, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Deprecated", true)</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="keepAliveInterval" Type="System.TimeSpan" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="keepAliveInterval">
          <para>定期的なキープ アライブ メッセージの間隔を定義します。</para>
        </param>
        <param name="hostEndpoints">
          <para> ゲートウェイ アドレスのセットを定義、<see cref="T:System.Fabric.FabricClient" />クラスターへの接続に使用できます。</para>
        </param>
        <summary>
          <para>推奨されなくなりました。 新しいインスタンスを初期化、 <see cref="T:System.Fabric.FabricClient" /> keepAliveInterval および Service Fabric ゲートウェイ アドレス (hostEndpoints) 指定されているクラスです。</para>
        </summary>
        <remarks>
          <para>接続の維持を定期的にメッセージを必要とするクライアントからクラスターへの接続の間の外部のデバイスがある場合 FabricClient のキープア ライブの機能を使用することを確認してください。 ユーザーは、FabricClient の初期化中に、TimeSpan keepAliveInterval を指定できます。 この引数を指定すると、FabricClient は定期的に ping を実行 Service Fabric のゲートウェイ サービスと現在通信保留中の操作がある限り、します。 この機能は便利なシナリオの例では、Windows Azure です。 場合、 <see cref="T:System.Fabric.FabricClient" /> Windows Azure の外部では、クラスターは、Windows Azure 内で、すべての接続はを介して、Azure ロード バランサー (alb モード) を参照してください。 Alb モードでは、60 秒より長くアイドル状態になっている接続を終了します。 そのため、これらの状況で<see cref="T:System.Fabric.FabricClient" />KeepAliveInterval に設定を作成する&lt;59 の秒数 (20-30 をお勧めします)。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.SecurityCredentials credential, System.Fabric.FabricClientSettings settings, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, class System.Fabric.FabricClientSettings settings, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.SecurityCredentials,System.Fabric.FabricClientSettings,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, settings As FabricClientSettings, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.SecurityCredentials * System.Fabric.FabricClientSettings * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (credential, settings, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential">
          <para>
            <see cref="T:System.Fabric.SecurityCredentials" />セキュリティ設定を定義、<see cref="T:System.Fabric.FabricClient" />です。</para>
        </param>
        <param name="settings">
          <para>Fabric クライアント設定します。</para>
        </param>
        <param name="hostEndpoints">
          <para>ゲートウェイ アドレスのセットを定義、<see cref="T:System.Fabric.FabricClient" />クラスターへの接続に使用できます。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.FabricClient" />指定されたサービス ファブリック ゲートウェイ アドレス クラス<see cref="T:System.Fabric.SecurityCredentials" />と<see cref="T:System.Fabric.FabricClientSettings" />です。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.SecurityCredentials credential, TimeSpan keepAliveInterval, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, valuetype System.TimeSpan keepAliveInterval, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.SecurityCredentials,System.TimeSpan,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, keepAliveInterval As TimeSpan, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.SecurityCredentials * TimeSpan * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (credential, keepAliveInterval, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Deprecated", true)</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="keepAliveInterval" Type="System.TimeSpan" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential">セキュリティ資格情報を定義します。</param>
        <param name="keepAliveInterval">
          <para>定期的なキープ アライブ メッセージの間隔を定義します。</para>
        </param>
        <param name="hostEndpoints">
          <para> ゲートウェイ アドレスのセットを定義、<see cref="T:System.Fabric.FabricClient" />クラスターへの接続に使用できます。</para>
        </param>
        <summary>
          <para>推奨されなくなりました。 新しいインスタンスを初期化、<see cref="T:System.Fabric.FabricClient" />が指定されている資格情報、keepAliveInterval Service Fabric ゲートウェイ アドレス (hostEndpoints) クラスします。</para>
        </summary>
        <remarks>
          <para>接続の維持を定期的にメッセージを必要とするクライアントからクラスターへの接続の間の外部のデバイスがある場合 FabricClient のキープア ライブの機能を使用することを確認してください。 ユーザーは、FabricClient の初期化中に、TimeSpan keepAliveInterval を指定できます。 この引数を指定すると、FabricClient は定期的に ping を実行 Service Fabric のゲートウェイ サービスと現在通信保留中の操作がある限り、します。 この機能は便利なシナリオの例では、Windows Azure です。 場合、 <see cref="T:System.Fabric.FabricClient" /> Windows Azure の外部では、クラスターは、Windows Azure 内で、すべての接続はを介して、Azure ロード バランサー (alb モード) を参照してください。 Alb モードでは、60 秒より長くアイドル状態になっている接続を終了します。 そのため、これらの状況で<see cref="T:System.Fabric.FabricClient" />KeepAliveInterval に設定を作成する&lt;59 の秒数 (20-30 をお勧めします)。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ApplicationManagementClient ApplicationManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ApplicationManagementClient ApplicationManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ApplicationManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationManager As FabricClient.ApplicationManagementClient" />
      <MemberSignature Language="F#" Value="member this.ApplicationManager : System.Fabric.FabricClient.ApplicationManagementClient" Usage="System.Fabric.FabricClient.ApplicationManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ApplicationManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得、<see cref="P:System.Fabric.FabricClient.ApplicationManager" />アプリケーションおよびアプリケーションの種類に関連する操作の実行に使用できます。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.FabricClient.ApplicationManager" />アプリケーションおよびアプリケーションの種類に関連する操作の実行に使用できます。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClaimsRetrieval">
      <MemberSignature Language="C#" Value="public event System.Fabric.FabricClient.ClaimsRetrievalEventHandler ClaimsRetrieval;" />
      <MemberSignature Language="ILAsm" Value=".event class System.Fabric.FabricClient/ClaimsRetrievalEventHandler ClaimsRetrieval" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.FabricClient.ClaimsRetrieval" />
      <MemberSignature Language="VB.NET" Value="Public Event ClaimsRetrieval As FabricClient.ClaimsRetrievalEventHandler " />
      <MemberSignature Language="F#" Value="member this.ClaimsRetrieval : System.Fabric.FabricClient.ClaimsRetrievalEventHandler " Usage="member this.ClaimsRetrieval : System.Fabric.FabricClient.ClaimsRetrievalEventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ClaimsRetrievalEventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クライアントは、ゲートウェイと承認の要求トークンを提供する必要がある場合に発生します。
            </summary>
        <remarks>
          <para>
            参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster#connect-to-a-secure-cluster-using-the-fabricclient-apis" />Azure Active Directory 認証を使用してセキュリティで保護されたクラスターに接続するためです。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientConnected">
      <MemberSignature Language="C#" Value="public event EventHandler ClientConnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler ClientConnected" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.FabricClient.ClientConnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientConnected As EventHandler " />
      <MemberSignature Language="F#" Value="member this.ClientConnected : EventHandler " Usage="member this.ClientConnected : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クライアントがゲートウェイに接続しているときに発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientDisconnected">
      <MemberSignature Language="C#" Value="public event EventHandler ClientDisconnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler ClientDisconnected" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.FabricClient.ClientDisconnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientDisconnected As EventHandler " />
      <MemberSignature Language="F#" Value="member this.ClientDisconnected : EventHandler " Usage="member this.ClientDisconnected : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クライアントが、ゲートウェイから切断されている場合に発生します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ClusterManagementClient ClusterManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ClusterManagementClient ClusterManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ClusterManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterManager As FabricClient.ClusterManagementClient" />
      <MemberSignature Language="F#" Value="member this.ClusterManager : System.Fabric.FabricClient.ClusterManagementClient" Usage="System.Fabric.FabricClient.ClusterManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ClusterManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得、 <see cref="P:System.Fabric.FabricClient.ClusterManager" /> Service Fabric クラスターに関連する操作の実行に使用できます。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.FabricClient.ClusterManager" /> Service Fabric クラスターに関連する操作の実行に使用できます。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComposeDeploymentManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ComposeDeploymentClient ComposeDeploymentManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ComposeDeploymentClient ComposeDeploymentManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ComposeDeploymentManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComposeDeploymentManager As FabricClient.ComposeDeploymentClient" />
      <MemberSignature Language="F#" Value="member this.ComposeDeploymentManager : System.Fabric.FabricClient.ComposeDeploymentClient" Usage="System.Fabric.FabricClient.ComposeDeploymentManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ComposeDeploymentClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得、<see cref="T:System.Fabric.FabricClient.ComposeDeploymentClient" />展開の作成に関連する操作の実行に使用できます。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.FabricClient.ComposeDeploymentManager" />展開の作成に関連する操作の実行に使用できます。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="fabricClient.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            Fabric クライアントを破棄します。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FabricSystemApplication">
      <MemberSignature Language="C#" Value="public readonly Uri FabricSystemApplication;" />
      <MemberSignature Language="ILAsm" Value=".field public initonly class System.Uri FabricSystemApplication" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FabricClient.FabricSystemApplication" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly FabricSystemApplication As Uri " />
      <MemberSignature Language="F#" Value="val mutable FabricSystemApplication : Uri" Usage="System.Fabric.FabricClient.FabricSystemApplication" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービス ファブリック システム アプリケーションです。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FaultManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.FaultManagementClient FaultManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/FaultManagementClient FaultManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.FaultManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FaultManager As FabricClient.FaultManagementClient" />
      <MemberSignature Language="F#" Value="member this.FaultManager : System.Fabric.FabricClient.FaultManagementClient" Usage="System.Fabric.FabricClient.FaultManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+FaultManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="T:System.Fabric.FabricClient.FaultManagementClient" />を強制実行エラー。 たとえば、RestartNodeAsync です。
            </summary>
        <value>
          <para><see cref="T:System.Fabric.FabricClient.FaultManagementClient" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Finalize">
      <MemberSignature Language="C#" Value="~FabricClient ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Finalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.Finalize" />
      <MemberSignature Language="VB.NET" Value="Finalize ()" />
      <MemberSignature Language="F#" Value="override this.Finalize : unit -&gt; unit" Usage="fabricClient.Finalize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            Fabric クライアントのデストラクターです。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.HealthClient HealthManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/HealthClient HealthManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.HealthManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthManager As FabricClient.HealthClient" />
      <MemberSignature Language="F#" Value="member this.HealthManager : System.Fabric.FabricClient.HealthClient" Usage="System.Fabric.FabricClient.HealthManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+HealthClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>関連するヘルスを実行するために使用する正常性のクライアントを取得、操作などの正常性のレポートまたはエンティティのヘルスを取得します。</para>
        </summary>
        <value>
          <para>正常性のクライアント正常性を実行するために使用するには、レポートの正常性アドインまたは get エンティティのヘルスなどの操作が関連します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InfrastructureManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.InfrastructureServiceClient InfrastructureManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/InfrastructureServiceClient InfrastructureManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.InfrastructureManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InfrastructureManager As FabricClient.InfrastructureServiceClient" />
      <MemberSignature Language="F#" Value="member this.InfrastructureManager : System.Fabric.FabricClient.InfrastructureServiceClient" Usage="System.Fabric.FabricClient.InfrastructureManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+InfrastructureServiceClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得、<see cref="T:System.Fabric.FabricClient.InfrastructureServiceClient" />クラスターが実行されているインフラストラクチャに関連する操作の実行に使用できます。</para>
          <para>このプロパティは、Service Fabric プラットフォームをサポートしています。コードから直接呼び出されるものではありません。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.FabricClient.InfrastructureServiceClient" />クラスターが実行されているインフラストラクチャに関連する操作の実行に使用できます。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.PropertyManagementClient PropertyManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/PropertyManagementClient PropertyManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.PropertyManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyManager As FabricClient.PropertyManagementClient" />
      <MemberSignature Language="F#" Value="member this.PropertyManager : System.Fabric.FabricClient.PropertyManagementClient" Usage="System.Fabric.FabricClient.PropertyManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+PropertyManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得、<see cref="P:System.Fabric.FabricClient.PropertyManager" />名前およびプロパティに関連する操作の実行に使用できます。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.FabricClient.PropertyManager" />名前およびプロパティに関連する操作の実行に使用できます。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.QueryClient QueryManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/QueryClient QueryManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.QueryManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueryManager As FabricClient.QueryClient" />
      <MemberSignature Language="F#" Value="member this.QueryManager : System.Fabric.FabricClient.QueryClient" Usage="System.Fabric.FabricClient.QueryManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+QueryClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Service Fabric クラスターに対してクエリを実行するために使用するクエリ マネージャーを取得します。</para>
        </summary>
        <value>
          <para>Service Fabric クラスターに対するクエリの実行に使用できるクエリ マネージャー。</para>
        </value>
        <remarks>
          <para>クラスターに対してクエリを実行するクエリ マネージャーを使用できます。
            ほとんどのクエリが分散されます。 さまざまな情報を取得する複数のシステム コンポーネントを呼び出すことができます。
            システム コンポーネントへの呼び出しを並列で実行し、返される結果の共通のキーに基づき集計します。
            たとえば、クラスター内のノードの一覧を取得する、<see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" />クエリはフェールオーバー マネージャー、クラスター マネージャー、およびヘルス マネージャーのシステム サービスに移動します。
            このため、一部のクエリは手間がかかります。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RepairManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.RepairManagementClient RepairManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/RepairManagementClient RepairManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.RepairManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RepairManager As FabricClient.RepairManagementClient" />
      <MemberSignature Language="F#" Value="member this.RepairManager : System.Fabric.FabricClient.RepairManagementClient" Usage="System.Fabric.FabricClient.RepairManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+RepairManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得、<see cref="T:System.Fabric.FabricClient.RepairManagementClient" />修復作業の管理に使用できます。</para>
          <para>このプロパティは、Service Fabric プラットフォームをサポートしています。コードから直接呼び出されるものではありません。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.FabricClient.RepairManagementClient" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceGroupManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ServiceGroupManagementClient ServiceGroupManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ServiceGroupManagementClient ServiceGroupManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ServiceGroupManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceGroupManager As FabricClient.ServiceGroupManagementClient" />
      <MemberSignature Language="F#" Value="member this.ServiceGroupManager : System.Fabric.FabricClient.ServiceGroupManagementClient" Usage="System.Fabric.FabricClient.ServiceGroupManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ServiceGroupManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得、<see cref="P:System.Fabric.FabricClient.ServiceGroupManager" />サービス グループに関連する操作の実行に使用できます。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.FabricClient.ServiceGroupManager" />サービス グループに関連する操作の実行に使用できます。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ServiceManagementClient ServiceManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ServiceManagementClient ServiceManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ServiceManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManager As FabricClient.ServiceManagementClient" />
      <MemberSignature Language="F#" Value="member this.ServiceManager : System.Fabric.FabricClient.ServiceManagementClient" Usage="System.Fabric.FabricClient.ServiceManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ServiceManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得、<see cref="P:System.Fabric.FabricClient.ServiceManager" />サービスとサービスの種類に関連する操作の実行に使用できます。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.FabricClient.ServiceManager" />サービスとサービスの種類に関連する操作の実行に使用できます。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClientSettings Settings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClientSettings Settings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.Settings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Settings As FabricClientSettings" />
      <MemberSignature Language="F#" Value="member this.Settings : System.Fabric.FabricClientSettings" Usage="System.Fabric.FabricClient.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClientSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ファブリックのクライアント設定を取得します。</para>
        </summary>
        <value>
          <para>Fabric クライアント設定します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.TestManagementClient TestManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/TestManagementClient TestManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.TestManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TestManager As FabricClient.TestManagementClient" />
      <MemberSignature Language="F#" Value="member this.TestManager : System.Fabric.FabricClient.TestManagementClient" Usage="System.Fabric.FabricClient.TestManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+TestManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、 <see cref="T:System.Fabric.FabricClient.TestManagementClient" /> FaultAnalysisService を通過する複雑なアクションを実行します。 たとえば、StartPartitionDataLossAsync です。
            これも (つまり FaultAnalysisService を通過しない) の検証の Api をサポートします。 たとえば、ValidateServiceAsync です。
            </summary>
        <value>
          <para><see cref="T:System.Fabric.FabricClient.TestManagementClient" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecurityCredentials">
      <MemberSignature Language="C#" Value="public void UpdateSecurityCredentials (System.Fabric.SecurityCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateSecurityCredentials(class System.Fabric.SecurityCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.UpdateSecurityCredentials(System.Fabric.SecurityCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateSecurityCredentials (credentials As SecurityCredentials)" />
      <MemberSignature Language="F#" Value="member this.UpdateSecurityCredentials : System.Fabric.SecurityCredentials -&gt; unit" Usage="fabricClient.UpdateSecurityCredentials credentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="System.Fabric.SecurityCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">使用する新しいセキュリティ資格情報。</param>
        <summary>
            Fabric クライアントのセキュリティ資格情報を更新します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSettings">
      <MemberSignature Language="C#" Value="public void UpdateSettings (System.Fabric.FabricClientSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateSettings(class System.Fabric.FabricClientSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.UpdateSettings(System.Fabric.FabricClientSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateSettings (settings As FabricClientSettings)" />
      <MemberSignature Language="F#" Value="member this.UpdateSettings : System.Fabric.FabricClientSettings -&gt; unit" Usage="fabricClient.UpdateSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para>使用する新しい fabric クライアントの設定をします。</para>
        </param>
        <summary>
          <para>Fabric クライアント設定を更新します。</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>指定した fabric クライアント設定を null にすることはできません。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
            <see cref="P:System.Fabric.FabricClientSettings.AuthTokenBufferSize" />0 以上にする必要があります。</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>