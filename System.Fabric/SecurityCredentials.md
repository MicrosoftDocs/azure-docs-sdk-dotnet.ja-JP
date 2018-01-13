<Type Name="SecurityCredentials" FullName="System.Fabric.SecurityCredentials">
  <TypeSignature Language="C#" Value="public abstract class SecurityCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit SecurityCredentials extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.SecurityCredentials" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class SecurityCredentials" />
  <TypeSignature Language="F#" Value="type SecurityCredentials = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>セキュリティ資格情報を表す型の抽象基本クラスです。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CredentialType">
      <MemberSignature Language="C#" Value="public System.Fabric.CredentialType CredentialType { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.CredentialType CredentialType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.SecurityCredentials.CredentialType" />
      <MemberSignature Language="VB.NET" Value="Public Property CredentialType As CredentialType" />
      <MemberSignature Language="F#" Value="member this.CredentialType : System.Fabric.CredentialType with get, set" Usage="System.Fabric.SecurityCredentials.CredentialType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CredentialType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>型を示す – クラスターを保護するために使用するセキュリティ資格情報の有効な値は"none"、"x509"、"Windows"です。</para>
        </summary>
        <value>
          <para>クラスターを保護するために使用するセキュリティ資格情報の種類。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public static System.Fabric.SecurityCredentials LoadFrom (System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.SecurityCredentials LoadFrom(class System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.SecurityCredentials.LoadFrom(System.Fabric.CodePackageActivationContext,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member LoadFrom : System.Fabric.CodePackageActivationContext * string * string -&gt; System.Fabric.SecurityCredentials" Usage="System.Fabric.SecurityCredentials.LoadFrom (codePackageActivationContext, configPackageName, sectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SecurityCredentials</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codePackageActivationContext" Type="System.Fabric.CodePackageActivationContext" />
        <Parameter Name="configPackageName" Type="System.String" />
        <Parameter Name="sectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codePackageActivationContext">
          <para>現在のコード パッケージのアクティベーション コンテキスト<see cref="T:System.Fabric.CodePackageActivationContext" />です。</para>
        </param>
        <param name="configPackageName">
          <para>現在の構成パッケージ名。</para>
        </param>
        <param name="sectionName">
          <para>すべてのセキュリティ設定を定義する構成ファイル内のセクションです。</para>
        </param>
        <summary>
          <para>インスタンス化<see cref="T:System.Fabric.SecurityCredentials" />サービス構成設定ファイルからオブジェクト</para>
        </summary>
        <returns>セキュリティ資格情報。</returns>
        <remarks>
          <para> サービスの構成フォルダー内の構成設定ファイル (settings.xml) を作成するために必要なすべてのセキュリティ設定を含める必要があります<see cref="T:System.Fabric.SecurityCredentials" />オブジェクトを渡す、<see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />メソッドです。
            通常、負担が settings.xml ファイルを読み取り、値を解析し、適切に構築するには、サービス作成者には、<see cref="T:System.Fabric.SecurityCredentials" />オブジェクト。</para>
          <para>現在のヘルパー メソッドを使用してサービスの作成者は、上記のプロセスをバイパスできます。</para>
          <para>サービスの構成を上記の解析中に自動的に実行する windows fabric で認識できる"settings.xml"で指定されるべきパラメーター名を次に示します。</para>
          <list type="number">
            <item>
              <description>
                <para>CredentialType – 資格情報の種類をセキュリティで保護された通信チャネルを使用する: X509 (X509 証明書の資格情報) または Windows (Windows 資格情報を active directory が必要です)</para>
              </description>
            </item>
          </list>
          <para> CredentialType X509 を =</para>
          <list type="number">
            <item>
              <description>
                <para>証明書を検索する StoreLocation ストアの場所: CurrentUser または LocalMachine</para>
              </description>
            </item>
            <item>
              <description>
                <para>証明書を検索するか、証明書ストアの StoreName-名前</para>
              </description>
            </item>
            <item>
              <description>
                <para>FindValue パラメーターによって指定された値の型を FindType 識別: は、FindByThumbPrint、FindBySubjectName または</para>
              </description>
            </item>
            <item>
              <description>
                <para>証明書を検索するため、findvalue という検索対象</para>
              </description>
            </item>
            <item>
              <description>
                <para>証明書の共通名と dns 名の AllowedCommonNames A のコンマ区切り一覧。 この一覧は、レプリケーターによって使用されるすべての証明書を含める必要があります、受信した証明書の検証に使用されます。</para>
              </description>
            </item>
            <item>
              <description>
                <para>発行者の証明書の拇印の IssuerThumbprints A のコンマ区切り一覧。 指定した場合、チェーンの検証に加えて、リストのエントリのいずれかでこれが発行される場合、受信した証明書が検証します。</para>
              </description>
            </item>
            <item>
              <description>
                <para>証明書の拇印の RemoteCertThumbprints A のコンマ区切り一覧。 この一覧は、レプリケーターによって使用されるすべての証明書を含める必要があります、受信した証明書の検証に使用されます。</para>
              </description>
            </item>
            <item>
              <description>
                <para>ProtectionLevel 示すデータを保護する方法: 符号または EncryptAndSign または None です。</para>
              </description>
            </item>
          </list>
          <para> CredentialType Windows を =</para>
          <list type="number">
            <item>
              <description>
                <para>ServicePrincipalName-サービス プリンシパル名がサービスに登録します。 コンピューター アカウントとしてサービス/アクター ホスト プロセスが実行する場合は空にすることができます (例:: NetworkService、LocalSystem などです)。</para>
              </description>
            </item>
            <item>
              <description>
                <para>WindowsIdentities A のコンマ区切りリストのすべてのサービス/アクター ホスト プロセスの windows id。</para>
              </description>
            </item>
            <item>
              <description>
                <para>ProtectionLevel 示すデータを保護する方法: 符号または EncryptAndSign または None です。</para>
              </description>
            </item>
          </list>
          <para>X509 スニペット サンプルの構成</para>
          <code>
            &lt;セクション名 ="SecurityConfig"&gt; &lt;パラメーター名"CredentialType"の値を = ="X509"/&gt; &lt;パラメーター名"FindType"の値を = ="は、FindByThumbprint"/&gt; &lt;パラメーター名 ="FindValue"値 ="9d c9 06 b1 69 dc 4f af fd 16 97 ac 78 1e 80 67 90 74 9 d 2f"/&gt; &lt;パラメーター名"StoreLocation"の値を = ="LocalMachine"/&gt; &lt;パラメーター名"StoreName"の値を = ="My"/&lt; c9 &gt; &gt;&lt;パラメーター名"ProtectionLevel"の値を = ="EncryptAndSign"/&gt; &lt;パラメーター名"AllowedCommonNames"Value="My-Test-SAN1-Alice,My-Test-SAN1-Bob を ="/&gt; &lt;/セクション&gt;
              </code>
          <para>Windows の構成スニペット例 1: すべてのサービス/アクター ホスト プロセスが NetworkService または LocalSystem として実行します。</para>
          <code>&lt;セクション名 ="SecurityConfig"&gt; &lt;パラメーター名"CredentialType"の値を = ="Windows"/&gt; &lt;パラメーター名「サービス プリンシパル名」の値を = =""/&gt; &lt;!--このマシングループには、- クラスターのすべてのマシンが含まれています&gt;&lt;パラメーター名"WindowsIdentities"の値を = ="redmond\ClusterMachineGroup"/&gt; &lt;パラメーター名"ProtectionLevel"の値を ="EncryptAndSign を =。"/&gt; &lt;/Section&gt;</code>
          <para>Windows の構成スニペット例 1: グループ管理サービス アカウントとしてサービス/アクターのすべてのホスト プロセスを実行します。</para>
          <code>&lt;セクション名 ="SecurityConfig"&gt; &lt;パラメーター名"CredentialType"の値を = ="Windows"/&gt; &lt;パラメーター名"ServicePrincipalName"Value="servicefabric/cluster.microsoft.com を ="/&gt; &lt;--すべてのアクター/サービス ホスト プロセスが redmond\GroupManagedServiceAccount として実行する--&gt; &lt;パラメーター名"WindowsIdentities"の値を = ="redmond\GroupManagedServiceAccount"/&gt;&lt;パラメーター名"ProtectionLevel"の値を = ="EncryptAndSign"/&gt; &lt;/section&gt;</code>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>