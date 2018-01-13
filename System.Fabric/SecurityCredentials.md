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
      <para><span data-ttu-id="70859-101">セキュリティ資格情報を表す型の抽象基本クラスです。</span><span class="sxs-lookup"><span data-stu-id="70859-101">An abstract base class for types that represent security credentials.</span></span></para>
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
          <para><span data-ttu-id="70859-102">型を示す – クラスターを保護するために使用するセキュリティ資格情報の有効な値は"none"、"x509"、"Windows"です。</span><span class="sxs-lookup"><span data-stu-id="70859-102">Indicates the type of security credentials to use in order to secure the cluster – valid values are "none", "x509", "Windows".</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="70859-103">クラスターを保護するために使用するセキュリティ資格情報の種類。</span><span class="sxs-lookup"><span data-stu-id="70859-103">The type of security credentials to use in order to secure the cluster.</span></span></para>
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
          <para><span data-ttu-id="70859-104">現在のコード パッケージのアクティベーション コンテキスト<see cref="T:System.Fabric.CodePackageActivationContext" />です。</span><span class="sxs-lookup"><span data-stu-id="70859-104">The current code package activation context <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span></para>
        </param>
        <param name="configPackageName">
          <para><span data-ttu-id="70859-105">現在の構成パッケージ名。</span><span class="sxs-lookup"><span data-stu-id="70859-105">The current configuration package name.</span></span></para>
        </param>
        <param name="sectionName">
          <para><span data-ttu-id="70859-106">すべてのセキュリティ設定を定義する構成ファイル内のセクションです。</span><span class="sxs-lookup"><span data-stu-id="70859-106">The section within the configuration file that defines all the security settings.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="70859-107">インスタンス化<see cref="T:System.Fabric.SecurityCredentials" />サービス構成設定ファイルからオブジェクト</span><span class="sxs-lookup"><span data-stu-id="70859-107">Instantiate <see cref="T:System.Fabric.SecurityCredentials" /> object from service configuration settings file</span></span></para>
        </summary>
        <returns><span data-ttu-id="70859-108">セキュリティ資格情報。</span><span class="sxs-lookup"><span data-stu-id="70859-108">The security credentials.</span></span></returns>
        <remarks>
          <para> <span data-ttu-id="70859-109">サービスの構成フォルダー内の構成設定ファイル (settings.xml) を作成するために必要なすべてのセキュリティ設定を含める必要があります<see cref="T:System.Fabric.SecurityCredentials" />オブジェクトを渡す、<see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="70859-109">The configuration settings file (settings.xml) within the service configuration folder should contain all the security settings that is needed to create <see cref="T:System.Fabric.SecurityCredentials" /> object and pass to the <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" /> method.</span></span>
            <span data-ttu-id="70859-110">通常、負担が settings.xml ファイルを読み取り、値を解析し、適切に構築するには、サービス作成者には、<see cref="T:System.Fabric.SecurityCredentials" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="70859-110">Typically, the onus is on the service author to read the settings.xml file, parse the values and appropriately construct the <see cref="T:System.Fabric.SecurityCredentials" /> object.</span></span></para>
          <para><span data-ttu-id="70859-111">現在のヘルパー メソッドを使用してサービスの作成者は、上記のプロセスをバイパスできます。</span><span class="sxs-lookup"><span data-stu-id="70859-111">With the current helper method, the service author can bypass the above process.</span></span></para>
          <para><span data-ttu-id="70859-112">サービスの構成を上記の解析中に自動的に実行する windows fabric で認識できる"settings.xml"で指定されるべきパラメーター名を次に示します。</span><span class="sxs-lookup"><span data-stu-id="70859-112">The following are the parameter names that should be provided in the service configuration "settings.xml", to be recognizable by windows fabric to perform the above parsing automatically:</span></span></para>
          <list type="number">
            <item>
              <description>
                <para><span data-ttu-id="70859-113">CredentialType – 資格情報の種類をセキュリティで保護された通信チャネルを使用する: X509 (X509 証明書の資格情報) または Windows (Windows 資格情報を active directory が必要です)</span><span class="sxs-lookup"><span data-stu-id="70859-113">CredentialType–type of credentials to use to secure communication channel: X509 (X509 certificate credentials) or Windows (Windows credentials, requires active directory)</span></span></para>
              </description>
            </item>
          </list>
          <para> <span data-ttu-id="70859-114">CredentialType X509 を =</span><span class="sxs-lookup"><span data-stu-id="70859-114">CredentialType=X509</span></span></para>
          <list type="number">
            <item>
              <description>
                <para><span data-ttu-id="70859-115">証明書を検索する StoreLocation ストアの場所: CurrentUser または LocalMachine</span><span class="sxs-lookup"><span data-stu-id="70859-115">StoreLocation-Store location to find the certificate: CurrentUser or LocalMachine</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="70859-116">証明書を検索するか、証明書ストアの StoreName-名前</span><span class="sxs-lookup"><span data-stu-id="70859-116">StoreName-name of the certificate store where the certificate should be searched</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="70859-117">FindValue パラメーターによって指定された値の型を FindType 識別: は、FindByThumbPrint、FindBySubjectName または</span><span class="sxs-lookup"><span data-stu-id="70859-117">FindType-Identifies the type of value provided by in the FindValue parameter: FindBySubjectName or FindByThumbPrint</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="70859-118">証明書を検索するため、findvalue という検索対象</span><span class="sxs-lookup"><span data-stu-id="70859-118">FindValue-Search target for finding the certificate</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="70859-119">証明書の共通名と dns 名の AllowedCommonNames A のコンマ区切り一覧。</span><span class="sxs-lookup"><span data-stu-id="70859-119">AllowedCommonNames-A comma separated list of certificate common names/dns names.</span></span> <span data-ttu-id="70859-120">この一覧は、レプリケーターによって使用されるすべての証明書を含める必要があります、受信した証明書の検証に使用されます。</span><span class="sxs-lookup"><span data-stu-id="70859-120">This list should include all certificates used by replicators, it is used to validate incoming certificate.</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="70859-121">発行者の証明書の拇印の IssuerThumbprints A のコンマ区切り一覧。</span><span class="sxs-lookup"><span data-stu-id="70859-121">IssuerThumbprints-A comma separated list of issuer certificate thumbprints.</span></span> <span data-ttu-id="70859-122">指定した場合、チェーンの検証に加えて、リストのエントリのいずれかでこれが発行される場合、受信した証明書が検証します。</span><span class="sxs-lookup"><span data-stu-id="70859-122">When specified, the incoming certificate is validated if it is issued by one of the entries in the list, in addition to chain validation.</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="70859-123">証明書の拇印の RemoteCertThumbprints A のコンマ区切り一覧。</span><span class="sxs-lookup"><span data-stu-id="70859-123">RemoteCertThumbprints-A comma separated list of certificate thumbprints.</span></span> <span data-ttu-id="70859-124">この一覧は、レプリケーターによって使用されるすべての証明書を含める必要があります、受信した証明書の検証に使用されます。</span><span class="sxs-lookup"><span data-stu-id="70859-124">This list should include all certificates used by replicators, it is used to validate incoming certificate.</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="70859-125">ProtectionLevel 示すデータを保護する方法: 符号または EncryptAndSign または None です。</span><span class="sxs-lookup"><span data-stu-id="70859-125">ProtectionLevel-Indicates how the data is protected: Sign or EncryptAndSign or None.</span></span></para>
              </description>
            </item>
          </list>
          <para> <span data-ttu-id="70859-126">CredentialType Windows を =</span><span class="sxs-lookup"><span data-stu-id="70859-126">CredentialType=Windows</span></span></para>
          <list type="number">
            <item>
              <description>
                <para><span data-ttu-id="70859-127">ServicePrincipalName-サービス プリンシパル名がサービスに登録します。</span><span class="sxs-lookup"><span data-stu-id="70859-127">ServicePrincipalName-Service Principal name registered for the service.</span></span> <span data-ttu-id="70859-128">コンピューター アカウントとしてサービス/アクター ホスト プロセスが実行する場合は空にすることができます (例:: NetworkService、LocalSystem などです)。</span><span class="sxs-lookup"><span data-stu-id="70859-128">Can be empty if the service/actor host processes runs as a machine account (e.g: NetworkService, LocalSystem etc.)</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="70859-129">WindowsIdentities A のコンマ区切りリストのすべてのサービス/アクター ホスト プロセスの windows id。</span><span class="sxs-lookup"><span data-stu-id="70859-129">WindowsIdentities-A comma separated list of windows identities of all service/actor host processes.</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="70859-130">ProtectionLevel 示すデータを保護する方法: 符号または EncryptAndSign または None です。</span><span class="sxs-lookup"><span data-stu-id="70859-130">ProtectionLevel-Indicates how the data is protected: Sign or EncryptAndSign or None.</span></span></para>
              </description>
            </item>
          </list>
          <para><span data-ttu-id="70859-131">X509 スニペット サンプルの構成</span><span class="sxs-lookup"><span data-stu-id="70859-131">X509 configuration snippet sample</span></span></para>
          <code>
            <span data-ttu-id="70859-132">&lt;セクション名 ="SecurityConfig"&gt; &lt;パラメーター名"CredentialType"の値を = ="X509"/&gt; &lt;パラメーター名"FindType"の値を = ="は、FindByThumbprint"/&gt; &lt;パラメーター名 ="FindValue"値 ="9d c9 06 b1 69 dc 4f af fd 16 97 ac 78 1e 80 67 90 74 9 d 2f"/&gt; &lt;パラメーター名"StoreLocation"の値を = ="LocalMachine"/&gt; &lt;パラメーター名"StoreName"の値を = ="My"/&lt; c9 &gt; &gt;&lt;パラメーター名"ProtectionLevel"の値を = ="EncryptAndSign"/&gt; &lt;パラメーター名"AllowedCommonNames"Value="My-Test-SAN1-Alice,My-Test-SAN1-Bob を ="/&gt; &lt;/セクション&gt;</span><span class="sxs-lookup"><span data-stu-id="70859-132">&lt;Section Name="SecurityConfig"&gt; &lt;Parameter Name="CredentialType" Value="X509" /&gt; &lt;Parameter Name="FindType" Value="FindByThumbprint" /&gt; &lt;Parameter Name="FindValue" Value="9d c9 06 b1 69 dc 4f af fd 16 97 ac 78 1e 80 67 90 74 9d 2f" /&gt; &lt;Parameter Name="StoreLocation" Value="LocalMachine" /&gt; &lt;Parameter Name="StoreName" Value="My" /&gt; &lt;Parameter Name="ProtectionLevel" Value="EncryptAndSign" /&gt; &lt;Parameter Name="AllowedCommonNames" Value="My-Test-SAN1-Alice,My-Test-SAN1-Bob" /&gt; &lt;/Section&gt;</span></span>
              </code>
          <para><span data-ttu-id="70859-133">Windows の構成スニペット例 1: すべてのサービス/アクター ホスト プロセスが NetworkService または LocalSystem として実行します。</span><span class="sxs-lookup"><span data-stu-id="70859-133">Windows configuration snippet sample 1: all the service/actor host processes run as NetworkService or LocalSystem.</span></span></para>
          <code><span data-ttu-id="70859-134">&lt;セクション名 ="SecurityConfig"&gt; &lt;パラメーター名"CredentialType"の値を = ="Windows"/&gt; &lt;パラメーター名「サービス プリンシパル名」の値を = =""/&gt; &lt;!--このマシングループには、- クラスターのすべてのマシンが含まれています&gt;&lt;パラメーター名"WindowsIdentities"の値を = ="redmond\ClusterMachineGroup"/&gt; &lt;パラメーター名"ProtectionLevel"の値を ="EncryptAndSign を =。"/&gt; &lt;/Section&gt;</span><span class="sxs-lookup"><span data-stu-id="70859-134">&lt;Section Name="SecurityConfig"&gt; &lt;Parameter Name="CredentialType" Value="Windows" /&gt; &lt;Parameter Name="ServicePrincipalName" Value="" /&gt; &lt;!--This machine group contains all machines in a cluster--&gt; &lt;Parameter Name="WindowsIdentities" Value="redmond\ClusterMachineGroup" /&gt; &lt;Parameter Name="ProtectionLevel" Value="EncryptAndSign" /&gt; &lt;/Section&gt;</span></span></code>
          <para><span data-ttu-id="70859-135">Windows の構成スニペット例 1: グループ管理サービス アカウントとしてサービス/アクターのすべてのホスト プロセスを実行します。</span><span class="sxs-lookup"><span data-stu-id="70859-135">Windows configuration snippet sample 1: all service/actor host processes run as a group managed service account.</span></span></para>
          <code><span data-ttu-id="70859-136">&lt;セクション名 ="SecurityConfig"&gt; &lt;パラメーター名"CredentialType"の値を = ="Windows"/&gt; &lt;パラメーター名"ServicePrincipalName"Value="servicefabric/cluster.microsoft.com を ="/&gt; &lt;--すべてのアクター/サービス ホスト プロセスが redmond\GroupManagedServiceAccount として実行する--&gt; &lt;パラメーター名"WindowsIdentities"の値を = ="redmond\GroupManagedServiceAccount"/&gt;&lt;パラメーター名"ProtectionLevel"の値を = ="EncryptAndSign"/&gt; &lt;/section&gt;</span><span class="sxs-lookup"><span data-stu-id="70859-136">&lt;Section Name="SecurityConfig"&gt; &lt;Parameter Name="CredentialType" Value="Windows" /&gt; &lt;Parameter Name="ServicePrincipalName" Value="servicefabric/cluster.microsoft.com" /&gt; &lt;--All actor/service host processes run as redmond\GroupManagedServiceAccount--&gt; &lt;Parameter Name="WindowsIdentities" Value="redmond\GroupManagedServiceAccount" /&gt; &lt;Parameter Name="ProtectionLevel" Value="EncryptAndSign" /&gt; &lt;/Section&gt;</span></span></code>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>