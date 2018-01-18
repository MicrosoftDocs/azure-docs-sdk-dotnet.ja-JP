<Type Name="NamespaceManager" FullName="Microsoft.Azure.NotificationHubs.NamespaceManager">
  <TypeSignature Language="C#" Value="public sealed class NamespaceManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamespaceManager extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamespaceManager" />
  <TypeSignature Language="F#" Value="type NamespaceManager = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="71a4a-101">キュー、トピック、サブスクリプション、およびサービスの名前空間内のルールなどのエンティティの管理に使用されるアンカー クラスを表します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-101">Represents an anchor class used in managing entities, such as queues, topics, subscriptions, and rules, in your service namespace.</span></span> <span data-ttu-id="71a4a-102">サービスの名前空間を管理するためにサービスの名前空間アドレスとアクセス資格情報を提供する必要があります。</span><span class="sxs-lookup"><span data-stu-id="71a4a-102">You must provide service namespace address and access credentials in order to manage your service namespace.</span></span></summary>
    <remarks>To be added.</remarks>
    <example>
      <code>
             <span data-ttu-id="71a4a-103">NamespaceManagerSettings nsSettings = 新しい NamespaceManagerSettings() です。資格情報と操作タイムアウト NamespaceManager マネージャーを使って新しい NamespaceManager = (新しい Uri("baseUri")、NsSettings) です。</span><span class="sxs-lookup"><span data-stu-id="71a4a-103">NamespaceManagerSettings nsSettings =  new NamespaceManagerSettings(); // with credentials and operation timeout NamespaceManager manager = new NamespaceManager(new Uri("baseUri"), NsSettings);</span></span>
              </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;string&gt; -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager addresses" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="71a4a-104">サービス名前空間の住所。</span><span class="sxs-lookup"><span data-stu-id="71a4a-104">The full addresses of the service namespace.</span></span></param>
        <summary><span data-ttu-id="71a4a-105">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />特定のアドレスを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given addresses.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="71a4a-106">アドレス フィールドが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-106">Thrown when addresses field is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="71a4a-107">アドレスの一覧が null または空の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-107">Thrown when addresses list is null or empty.</span></span></exception>
        <exception cref="T:System.UriFormatException"><span data-ttu-id="71a4a-108">アドレスの形式が正しくない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-108">Thrown when address is not correctly formed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of Uri))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;Uri&gt; -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager addresses" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="71a4a-109">サービス名前空間の完全 URI アドレス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-109">The full URI addresses of the service namespace.</span></span></param>
        <summary><span data-ttu-id="71a4a-110">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />特定のサービス名前空間 URI のベース アドレスを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-110">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace URI base addresses.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="71a4a-111">アドレス フィールドが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-111">Thrown when addresses field is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="71a4a-112">アドレスの一覧が null または空の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-112">Thrown when addresses list is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : string -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="71a4a-113">サービスの名前空間の完全なアドレスです。</span><span class="sxs-lookup"><span data-stu-id="71a4a-113">The full address of the service namespace.</span></span></param>
        <summary><span data-ttu-id="71a4a-114">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />特定のサービス名前空間のアドレスを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-114">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace address.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="71a4a-115">アドレスが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-115">Thrown when address is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : Uri -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="71a4a-116">サービス名前空間の完全な URI アドレス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-116">The full URI address of the service namespace.</span></span></param>
        <summary><span data-ttu-id="71a4a-117">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />特定のサービス名前空間 URI のベース アドレスを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-117">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace URI base address.</span></span> </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="71a4a-118">アドレスが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-118">Thrown when address is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.NotificationHubs.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of String), settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;string&gt; * Microsoft.Azure.NotificationHubs.NamespaceManagerSettings -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (addresses, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="settings" Type="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="71a4a-119">サービス名前空間の住所。</span><span class="sxs-lookup"><span data-stu-id="71a4a-119">The full addresses of the service namespace.</span></span></param>
        <param name="settings"><span data-ttu-id="71a4a-120">A<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />含むオブジェクトを<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" />と<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="71a4a-120">A <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> object, which contains the <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" /> and <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" /> properties.</span></span></param>
        <summary><span data-ttu-id="71a4a-121">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />クラスを指定したアドレスと設定を使用します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-121">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given addresses and settings.</span></span></summary>
        <remarks>
            <span data-ttu-id="71a4a-122">名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではないベース アドレス itse に指定した資格情報がある必要があります。lf</span><span class="sxs-lookup"><span data-stu-id="71a4a-122">Even though it is not allowed to include paths in the namespace address, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base addresses, i.e. it is not a must that the credentials you specify be to the base adresses itself</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="71a4a-123">場合にスローされるアドレスまたは設定が null です。</span><span class="sxs-lookup"><span data-stu-id="71a4a-123">Thrown when address or settings is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="71a4a-124">アドレスの一覧が null または空の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-124">Thrown when addresses list is null or empty.</span></span></exception>
        <exception cref="T:System.UriFormatException"><span data-ttu-id="71a4a-125">アドレスの形式が正しくない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-125">Thrown when address is not correctly formed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;string&gt; * Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (addresses, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="71a4a-126">サービス名前空間の住所。</span><span class="sxs-lookup"><span data-stu-id="71a4a-126">The full addresses of the service namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="71a4a-127">セキュリティ トークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="71a4a-127">The security token provider.</span></span></param>
        <summary><span data-ttu-id="71a4a-128">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />クラスを指定したアドレスとトークン プロバイダーを使用します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-128">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given addresses and token provider.</span></span></summary>
        <remarks>
            <span data-ttu-id="71a4a-129">名前空間アドレスにパスを含めることはできません、場合でも、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定できます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-129">Even though it is not allowed to include paths in the namespace addresses, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base addresses.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="71a4a-130">アドレス フィールドが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-130">Thrown when addresses field is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="71a4a-131">アドレスの一覧が null または空の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-131">Thrown when addresses list is null or empty.</span></span></exception>
        <exception cref="T:System.UriFormatException"><span data-ttu-id="71a4a-132">アドレスの形式が正しくない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-132">Thrown when address is not correctly formed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.Azure.NotificationHubs.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of Uri), settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;Uri&gt; * Microsoft.Azure.NotificationHubs.NamespaceManagerSettings -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (addresses, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="settings" Type="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="71a4a-133">サービス名前空間の完全 URI アドレス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-133">The full URI addresses of the service namespace.</span></span></param>
        <param name="settings"><span data-ttu-id="71a4a-134">A<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />含むオブジェクトを<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" />と<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="71a4a-134">A <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> object, which contains the <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" /> and <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" /> properties.</span></span></param>
        <summary><span data-ttu-id="71a4a-135">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />クラスが指定されたサービス名前空間 URI のベース アドレスと設定を使用します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-135">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace URI base addresses and settings.</span></span></summary>
        <remarks>
            <span data-ttu-id="71a4a-136">名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではありません必要がありますを指定する資格情報されるベース アドレスをself</span><span class="sxs-lookup"><span data-stu-id="71a4a-136">Even though it is not allowed to include paths in the namespace addresses, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base addresses, i.e. it is not a must that the credentials you specify be to the base adresses itself</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="71a4a-137">場合にスローされるアドレスや設定が null です。</span><span class="sxs-lookup"><span data-stu-id="71a4a-137">Thrown when addresses or settings is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="71a4a-138">アドレスの一覧が null または空の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-138">Thrown when addresses list is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;Uri&gt; * Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (addresses, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="71a4a-139">サービス名前空間の完全 URI アドレス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-139">The full URI addresses of the service namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="71a4a-140">セキュリティ トークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="71a4a-140">The security token provider.</span></span></param>
        <summary><span data-ttu-id="71a4a-141">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />トークン プロバイダー、指定されたサービス名前空間 URI のベース アドレスを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-141">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace URI base addresses and token provider.</span></span></summary>
        <remarks>
            <span data-ttu-id="71a4a-142">名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではありません必要がありますを指定する資格情報されるベース アドレスをself</span><span class="sxs-lookup"><span data-stu-id="71a4a-142">Even though it is not allowed to include paths in the namespace addresses, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base addresses, i.e. it is not a must that the credentials you specify be to the base adresses itself</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="71a4a-143">アドレスが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-143">Thrown if addresses is null.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="71a4a-144">型がサポートされている資格情報の種類ではない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-144">Thrown when the type is not a supported Credential type.</span></span>
            <span data-ttu-id="71a4a-145">参照してください<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" />でサポートされる型の詳細を知るにします。</span><span class="sxs-lookup"><span data-stu-id="71a4a-145">See <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" /> to know more about the supported types.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="71a4a-146">アドレスの一覧が null または空の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-146">Thrown when addresses list is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address, Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address, class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.String,Microsoft.Azure.NotificationHubs.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String, settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : string * Microsoft.Azure.NotificationHubs.NamespaceManagerSettings -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (address, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="settings" Type="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="71a4a-147">サービスの名前空間の完全なアドレスです。</span><span class="sxs-lookup"><span data-stu-id="71a4a-147">The full address of the service namespace.</span></span></param>
        <param name="settings"><span data-ttu-id="71a4a-148">A<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />含むオブジェクトを<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" />と<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="71a4a-148">A <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> object, which contains the <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" /> and <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" /> properties.</span></span></param>
        <summary><span data-ttu-id="71a4a-149">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />特定のサービス名前空間のベース アドレスを持つクラスと<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-149">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace base address and <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> object.</span></span></summary>
        <remarks>
            <span data-ttu-id="71a4a-150">名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではありません自体ベース アドレスを指定した資格情報がある必要があります。</span><span class="sxs-lookup"><span data-stu-id="71a4a-150">Even though it is not allowed to include paths in the namespace address, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base address, i.e. it is not a must that the credentials you specify be to the base adress itself</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="71a4a-151"><paramref name="address" /> または <paramref name="settings" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="71a4a-151"><paramref name="address" /> or <paramref name="settings" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="71a4a-152"><paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</span><span class="sxs-lookup"><span data-stu-id="71a4a-152"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address, Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address, class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.String,Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : string * Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="71a4a-153">サービスの名前空間の完全なアドレスです。</span><span class="sxs-lookup"><span data-stu-id="71a4a-153">The full address of the service namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="71a4a-154">セキュリティ トークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="71a4a-154">The security token provider.</span></span></param>
        <summary><span data-ttu-id="71a4a-155">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />トークン プロバイダー、指定されたサービス名前空間のベース アドレスを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-155">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace base address and token provider.</span></span></summary>
        <remarks>
            <span data-ttu-id="71a4a-156">名前空間アドレスにパスを含めることはできません、場合でも、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定できます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-156">Even though it is not allowed to include paths in the namespace address, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base address.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="71a4a-157"><paramref name="address" /> または <paramref name="token provider" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="71a4a-157"><paramref name="address" /> or <paramref name="token provider" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="71a4a-158"><paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</span><span class="sxs-lookup"><span data-stu-id="71a4a-158"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address, Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Uri,Microsoft.Azure.NotificationHubs.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri, settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : Uri * Microsoft.Azure.NotificationHubs.NamespaceManagerSettings -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (address, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="settings" Type="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="71a4a-159">サービス名前空間の完全な URI アドレス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-159">The full URI address of the service namespace.</span></span></param>
        <param name="settings"><span data-ttu-id="71a4a-160">A<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />含むオブジェクトを<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" />と<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="71a4a-160">A <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> object, which contains the <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" /> and <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" /> properties.</span></span></param>
        <summary><span data-ttu-id="71a4a-161">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />特定のサービス名前空間 URI のベース アドレスを持つクラスと<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-161">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace URI base address and <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> object.</span></span></summary>
        <remarks>
            <span data-ttu-id="71a4a-162">名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではありません自体ベース アドレスを指定した資格情報がある必要があります。</span><span class="sxs-lookup"><span data-stu-id="71a4a-162">Even though it is not allowed to include paths in the namespace address, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base address, i.e. it is not a must that the credentials you specify be to the base adress itself</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="71a4a-163"><paramref name="address" /> または <paramref name="settings" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="71a4a-163"><paramref name="address" /> or <paramref name="settings" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="71a4a-164"><paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</span><span class="sxs-lookup"><span data-stu-id="71a4a-164"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address, Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Uri,Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : Uri * Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="71a4a-165">サービス名前空間の完全な URI アドレス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-165">The full URI address of the service namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="71a4a-166">セキュリティ トークン プロバイダー オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-166">The security token provider object.</span></span></param>
        <summary><span data-ttu-id="71a4a-167">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />特定のサービス名前空間 URI のベース アドレスを持つクラスと<see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-167">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> class with the given service namespace URI base address and <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> object.</span></span></summary>
        <remarks>
            <span data-ttu-id="71a4a-168">名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではありません自体ベース アドレスを指定した資格情報がある必要があります。</span><span class="sxs-lookup"><span data-stu-id="71a4a-168">Even though it is not allowed to include paths in the namespace address, you can specify a credential that authorizes you to perform actions only on some sublevels off of the base address, i.e. it is not a must that the credentials you specify be to the base adress itself</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="71a4a-169"><paramref name="address" /> または <paramref name="token provider" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="71a4a-169"><paramref name="address" /> or <paramref name="token provider" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="71a4a-170">型がサポートされている資格情報の種類ではない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-170">Thrown when the type is not a supported Credential type.</span></span>
            <span data-ttu-id="71a4a-171">参照してください<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" />でサポートされる型の詳細を知るにします。</span><span class="sxs-lookup"><span data-stu-id="71a4a-171">See <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" /> to know more about the supported types.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="71a4a-172"><paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</span><span class="sxs-lookup"><span data-stu-id="71a4a-172"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManager.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="71a4a-173">サービス名前空間のベース アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-173">Gets the service namespace base address.</span></span></summary>
        <value><span data-ttu-id="71a4a-174">A<see cref="T:System.Uri" />サービス名前空間のベース アドレスを表すです。</span><span class="sxs-lookup"><span data-stu-id="71a4a-174">A <see cref="T:System.Uri" /> that represents the service namespace base address.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVersionInfo">
      <MemberSignature Language="C#" Value="public IAsyncResult BeginGetVersionInfo (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IAsyncResult BeginGetVersionInfo(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.BeginGetVersionInfo(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginGetVersionInfo (callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginGetVersionInfo : AsyncCallback * obj -&gt; IAsyncResult" Usage="namespaceManager.BeginGetVersionInfo (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="71a4a-175">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="71a4a-175">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="71a4a-176">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-176">A user-defined object that contains state information about the asynchronous operation.</span></span> <span data-ttu-id="71a4a-177">このオブジェクトは、操作の完了時に <see cref="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndGetVersioninfo(System.IAsyncResult)" /> デリゲートに渡されます。</span><span class="sxs-lookup"><span data-stu-id="71a4a-177">This object is passed to the <see cref="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndGetVersioninfo(System.IAsyncResult)" /> delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="71a4a-178">非同期バージョンの<see cref="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetVersionInfo(System.String)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="71a4a-178">Asynchronous version of <see cref="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetVersionInfo(System.String)" /> method.</span></span></summary>
        <returns><span data-ttu-id="71a4a-179"><see cref="T:System.IAsyncResult" />バージョン情報を取得する非同期操作を参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-179">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get the version information.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.NamespaceManager Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.NamespaceManager Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.Create" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create () As NamespaceManager" />
      <MemberSignature Language="F#" Value="static member Create : unit -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NamespaceManager</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="71a4a-180"><see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> の新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-180">Creates a new instance of <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />.</span></span></summary>
        <returns><span data-ttu-id="71a4a-181"><see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> の新しいインスタンス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-181">A new instance of <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.NamespaceManager CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.NamespaceManager CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As NamespaceManager" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NamespaceManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="71a4a-182">接続文字列を使用します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-182">The connection sting used.</span></span></param>
        <summary><span data-ttu-id="71a4a-183">新しいインスタンスを作成<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />指定された接続文字列を使用します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-183">Creates a new instance of <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> using a specified connection string.</span></span></summary>
        <returns><span data-ttu-id="71a4a-184"><see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> の新しいインスタンス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-184">A new instance of <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotificationHub">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NotificationHubDescription CreateNotificationHub (Microsoft.Azure.NotificationHubs.NotificationHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.NotificationHubs.NotificationHubDescription CreateNotificationHub(class Microsoft.Azure.NotificationHubs.NotificationHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.CreateNotificationHub(Microsoft.Azure.NotificationHubs.NotificationHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateNotificationHub (description As NotificationHubDescription) As NotificationHubDescription" />
      <MemberSignature Language="F#" Value="member this.CreateNotificationHub : Microsoft.Azure.NotificationHubs.NotificationHubDescription -&gt; Microsoft.Azure.NotificationHubs.NotificationHubDescription" Usage="namespaceManager.CreateNotificationHub description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="71a4a-185">新しい通知ハブが作成される属性を記述する説明オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-185">The description object describing the attributes with which the new notification hub will be created.</span></span></param>
        <summary><span data-ttu-id="71a4a-186">指定されたプロパティを持つ新しい通知ハブを作成、<paramref name="description" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="71a4a-186">Creates a new notification hub with the properties specified in the <paramref name="description" /> parameter.</span></span></summary>
        <returns><span data-ttu-id="71a4a-187">A<see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" />新しく作成された通知ハブの説明を持つオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-187">A <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> object with the description of the newly created notification hub.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotificationHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; CreateNotificationHubAsync (Microsoft.Azure.NotificationHubs.NotificationHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; CreateNotificationHubAsync(class Microsoft.Azure.NotificationHubs.NotificationHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.CreateNotificationHubAsync(Microsoft.Azure.NotificationHubs.NotificationHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateNotificationHubAsync (description As NotificationHubDescription) As Task(Of NotificationHubDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateNotificationHubAsync : Microsoft.Azure.NotificationHubs.NotificationHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;" Usage="namespaceManager.CreateNotificationHubAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="71a4a-188">新しい通知ハブが作成される属性を記述する説明オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-188">The description object describing the attributes with which the new notification hub will be created.</span></span></param>
        <summary><span data-ttu-id="71a4a-189">指定されたプロパティを持つ新しい通知ハブを非同期に作成、<paramref name="description" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="71a4a-189">Asynchronously creates a new notification hub with the properties specified in the <paramref name="description" /> parameter.</span></span></summary>
        <returns><span data-ttu-id="71a4a-190">A<see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" />新しく作成された通知ハブの説明を持つオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-190">A <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> object with the description of the newly created notification hub.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNotificationHub">
      <MemberSignature Language="C#" Value="public void DeleteNotificationHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteNotificationHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.DeleteNotificationHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteNotificationHub (path As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteNotificationHub : string -&gt; unit" Usage="namespaceManager.DeleteNotificationHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="71a4a-191">通知ハブへのパス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-191">The path to the notification hub.</span></span></param>
        <summary><span data-ttu-id="71a4a-192">指定された通知ハブを削除<paramref name="path" />です。</span><span class="sxs-lookup"><span data-stu-id="71a4a-192">Deletes a notification hub at the provided <paramref name="path" />.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNotificationHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNotificationHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNotificationHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.DeleteNotificationHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteNotificationHubAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteNotificationHubAsync : string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteNotificationHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="71a4a-193">通知ハブへのパス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-193">The path to the notification hub.</span></span></param>
        <summary><span data-ttu-id="71a4a-194">指定された通知ハブを非同期に削除<paramref name="path" />です。</span><span class="sxs-lookup"><span data-stu-id="71a4a-194">Asynchronously deletes a notification hub at the provided <paramref name="path" />.</span></span></summary>
        <returns><span data-ttu-id="71a4a-195">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="71a4a-195">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteInstallation">
      <MemberSignature Language="C#" Value="public void EndDeleteInstallation (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EndDeleteInstallation(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndDeleteInstallation(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Sub EndDeleteInstallation (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="member this.EndDeleteInstallation : IAsyncResult -&gt; unit" Usage="namespaceManager.EndDeleteInstallation result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="71a4a-196">待機する保留状態の非同期要求への参照。</span><span class="sxs-lookup"><span data-stu-id="71a4a-196">The reference to the pending asynchronous request to wait for.</span></span></param>
        <summary>
            <span data-ttu-id="71a4a-197">非同期の削除が保留中のインストールが完了するまで待機します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-197">Waits for the pending asynchronous delete installation to complete.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteRegistration">
      <MemberSignature Language="C#" Value="public void EndDeleteRegistration (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EndDeleteRegistration(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndDeleteRegistration(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Sub EndDeleteRegistration (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="member this.EndDeleteRegistration : IAsyncResult -&gt; unit" Usage="namespaceManager.EndDeleteRegistration result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="71a4a-198"><see cref="T:System.IAsyncResult" />登録削除操作の結果を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-198">An <see cref="T:System.IAsyncResult" /> object that represents the result of the registration deletion operation.</span></span></param>
        <summary><span data-ttu-id="71a4a-199">登録を削除する非同期の要求を終了します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-199">Ends an asynchronous request to delete a registration.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetVersionInfo">
      <MemberSignature Language="C#" Value="public string EndGetVersionInfo (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string EndGetVersionInfo(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndGetVersionInfo(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndGetVersionInfo (result As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="member this.EndGetVersionInfo : IAsyncResult -&gt; string" Usage="namespaceManager.EndGetVersionInfo result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="71a4a-200"><see cref="T:System.IAsyncResult" />バージョン情報の取得の結果を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-200">An <see cref="T:System.IAsyncResult" /> object that represents the result of the get version information.</span></span></param>
        <summary><span data-ttu-id="71a4a-201">バージョン情報を取得する非同期要求を終了します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-201">Ends an asynchronous request to get version information.</span></span></summary>
        <returns><span data-ttu-id="71a4a-202">バージョン情報です。</span><span class="sxs-lookup"><span data-stu-id="71a4a-202">The version information.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHub">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NotificationHubDescription GetNotificationHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.NotificationHubs.NotificationHubDescription GetNotificationHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHub (path As String) As NotificationHubDescription" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHub : string -&gt; Microsoft.Azure.NotificationHubs.NotificationHubDescription" Usage="namespaceManager.GetNotificationHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="71a4a-203">サービスの名前空間へのパス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-203">The path to the service namespace.</span></span></param>
        <summary><span data-ttu-id="71a4a-204">サービスの名前空間から通知ハブの説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-204">Retrieves the description of a notification hub from the service namespace.</span></span></summary>
        <returns><span data-ttu-id="71a4a-205"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" />サービス名前空間からです。</span><span class="sxs-lookup"><span data-stu-id="71a4a-205">The <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> from the service namespace.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; GetNotificationHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; GetNotificationHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubAsync (path As String) As Task(Of NotificationHubDescription)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;" Usage="namespaceManager.GetNotificationHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="71a4a-206">サービスの名前空間へのパス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-206">The path to the service namespace.</span></span></param>
        <summary><span data-ttu-id="71a4a-207">非同期的に、サービス名前空間から通知ハブの説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-207">Asynchronously retrieves the description of a notification hub from the service namespace.</span></span></summary>
        <returns><span data-ttu-id="71a4a-208">サービスの名前空間から通知ハブの説明を取得する非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="71a4a-208">The asynchronous operation that retrieves the description of a notification hub from the service namespace.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; GetNotificationHubJobAsync (string jobId, string notificationHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; GetNotificationHubJobAsync(string jobId, string notificationHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubJobAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubJobAsync (jobId As String, notificationHubPath As String) As Task(Of NotificationHubJob)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubJobAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;" Usage="namespaceManager.GetNotificationHubJobAsync (jobId, notificationHubPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="notificationHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="71a4a-209">ジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="71a4a-209">The ID of the job.</span></span></param>
        <param name="notificationHubPath"><span data-ttu-id="71a4a-210">通知ハブへのパス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-210">The path to the notification hub.</span></span></param>
        <summary><span data-ttu-id="71a4a-211">指定された通知ハブのジョブを非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-211">Asynchronously gets a specified notification hubs job.</span></span></summary>
        <returns><span data-ttu-id="71a4a-212"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-212">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubJobsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt; GetNotificationHubJobsAsync (string notificationHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt; GetNotificationHubJobsAsync(string notificationHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubJobsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubJobsAsync (notificationHubPath As String) As Task(Of IEnumerable(Of NotificationHubJob))" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubJobsAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt;" Usage="namespaceManager.GetNotificationHubJobsAsync notificationHubPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notificationHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="notificationHubPath"><span data-ttu-id="71a4a-213">通知ハブへのパス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-213">The path to the notification hub.</span></span></param>
        <summary><span data-ttu-id="71a4a-214">非同期的に一連のすべての通知ハブのジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-214">Asynchronously gets a set of all notification hubs jobs.</span></span></summary>
        <returns><span data-ttu-id="71a4a-215"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-215">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; GetNotificationHubs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; GetNotificationHubs() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubs" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubs () As IEnumerable(Of NotificationHubDescription)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubs : unit -&gt; seq&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;" Usage="namespaceManager.GetNotificationHubs " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="71a4a-216">サービスの名前空間から通知ハブの説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-216">Retrieves the description of a notification hub from the service namespace.</span></span></summary>
        <returns><span data-ttu-id="71a4a-217">サービスの名前空間からの通知ハブの説明の一覧。</span><span class="sxs-lookup"><span data-stu-id="71a4a-217">The list of description of a notification hub from the service namespace.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;&gt; GetNotificationHubsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;&gt; GetNotificationHubsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubsAsync () As Task(Of IEnumerable(Of NotificationHubDescription))" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;&gt;" Usage="namespaceManager.GetNotificationHubsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="71a4a-218">非同期的に、サービス名前空間から通知ハブの説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-218">Asynchronously retrieves the description of a notification hub from the service namespace.</span></span></summary>
        <returns><span data-ttu-id="71a4a-219">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="71a4a-219">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVersionInfo">
      <MemberSignature Language="C#" Value="public string GetVersionInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetVersionInfo() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetVersionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVersionInfo () As String" />
      <MemberSignature Language="F#" Value="member this.GetVersionInfo : unit -&gt; string" Usage="namespaceManager.GetVersionInfo " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="71a4a-220">サーバーまたはサービスが処理できる最大のサポートされているプロトコルのバージョンを示す"YYYY MM"形式の文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-220">Retrieves a string of the format "YYYY-MM" that indicates the maximum supported protocol version that the server or service can handle.</span></span></summary>
        <returns><span data-ttu-id="71a4a-221">サーバーまたはサービスが処理できる最大のサポートされているプロトコルのバージョンを示す文字列です。</span><span class="sxs-lookup"><span data-stu-id="71a4a-221">A string that indicates the maximum supported protocol version that the server or service can handle.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVersionInfoAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetVersionInfoAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetVersionInfoAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetVersionInfoAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVersionInfoAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetVersionInfoAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="namespaceManager.GetVersionInfoAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="71a4a-222">非同期的に、サーバーまたはサービスが処理できる最大のサポートされているプロトコルのバージョンを示す"YYYY MM"形式の文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-222">Asynchronously retrieves a string of the format "YYYY-MM" that indicates the maximum supported protocol version that the server or service can handle.</span></span></summary>
        <returns><span data-ttu-id="71a4a-223">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="71a4a-223">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationHubExists">
      <MemberSignature Language="C#" Value="public bool NotificationHubExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool NotificationHubExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.NotificationHubExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function NotificationHubExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.NotificationHubExists : string -&gt; bool" Usage="namespaceManager.NotificationHubExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="71a4a-224">通知ハブへのパス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-224">The path to the notification hub.</span></span></param>
        <summary><span data-ttu-id="71a4a-225">指定された通知ハブがあるかどうかを判断<paramref name="path" />サービス名前空間にします。</span><span class="sxs-lookup"><span data-stu-id="71a4a-225">Determines whether there is a notification hub at the specified <paramref name="path" /> in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="71a4a-226">内の指定した通知ハブがある場合は true。<paramref name="path" />サービス名前空間です。 それ以外の場合は false。</span><span class="sxs-lookup"><span data-stu-id="71a4a-226">true if there is a notification hub at the specified <paramref name="path" /> in the service namespace; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationHubExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; NotificationHubExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; NotificationHubExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.NotificationHubExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function NotificationHubExistsAsync (path As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NotificationHubExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.NotificationHubExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="71a4a-227">通知ハブへのパス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-227">The path to the notification hub.</span></span></param>
        <summary><span data-ttu-id="71a4a-228">指定された通知ハブがあるかどうかを非同期に判断<paramref name="path" />サービス名前空間にします。</span><span class="sxs-lookup"><span data-stu-id="71a4a-228">Asynchronously determines whether there is a notification hub at the specified <paramref name="path" /> in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="71a4a-229">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="71a4a-229">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtocolVersion">
      <MemberSignature Language="C#" Value="public const string ProtocolVersion;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ProtocolVersion" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.NamespaceManager.ProtocolVersion" />
      <MemberSignature Language="VB.NET" Value="Public Const ProtocolVersion As String " />
      <MemberSignature Language="F#" Value="val mutable ProtocolVersion : string" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.ProtocolVersion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="71a4a-230">クライアントのプロトコルのバージョンを示す"YYYY MM"の形式の文字列を指定します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-230">Specifies the string of the format "YYYY-MM" that indicates the client's protocol version.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NamespaceManagerSettings Settings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManager.Settings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Settings As NamespaceManagerSettings" />
      <MemberSignature Language="F#" Value="member this.Settings : Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NamespaceManagerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="71a4a-231">サービス名前空間のクライアント設定を取得します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-231">Gets the service namespace client settings.</span></span></summary>
        <value><span data-ttu-id="71a4a-232">A<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />サービス名前空間のクライアント設定を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-232">A <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> object that represents the service namespace client settings.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitNotificationHubJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; SubmitNotificationHubJobAsync (Microsoft.Azure.NotificationHubs.NotificationHubJob job, string notificationHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; SubmitNotificationHubJobAsync(class Microsoft.Azure.NotificationHubs.NotificationHubJob job, string notificationHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubmitNotificationHubJobAsync (job As NotificationHubJob, notificationHubPath As String) As Task(Of NotificationHubJob)" />
      <MemberSignature Language="F#" Value="member this.SubmitNotificationHubJobAsync : Microsoft.Azure.NotificationHubs.NotificationHubJob * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;" Usage="namespaceManager.SubmitNotificationHubJobAsync (job, notificationHubPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.NotificationHubs.NotificationHubJob" />
        <Parameter Name="notificationHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="job"><span data-ttu-id="71a4a-233">A<see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />を送信するジョブを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-233">A <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" /> object representing the job to submit.</span></span></param>
        <param name="notificationHubPath"><span data-ttu-id="71a4a-234">通知ハブへのパス。</span><span class="sxs-lookup"><span data-stu-id="71a4a-234">The path to the notification hub.</span></span></param>
        <summary><span data-ttu-id="71a4a-235">処理の通知ハブのジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-235">Submits a notification hub job for processing.</span></span></summary>
        <returns><span data-ttu-id="71a4a-236"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="71a4a-236">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateNotificationHub">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NotificationHubDescription UpdateNotificationHub (Microsoft.Azure.NotificationHubs.NotificationHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.NotificationHubs.NotificationHubDescription UpdateNotificationHub(class Microsoft.Azure.NotificationHubs.NotificationHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.UpdateNotificationHub(Microsoft.Azure.NotificationHubs.NotificationHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateNotificationHub (description As NotificationHubDescription) As NotificationHubDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateNotificationHub : Microsoft.Azure.NotificationHubs.NotificationHubDescription -&gt; Microsoft.Azure.NotificationHubs.NotificationHubDescription" Usage="namespaceManager.UpdateNotificationHub description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="71a4a-237">通知ハブの更新する属性を記述する説明オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-237">The description object describing the attributes with which the notification hub will be updated.</span></span></param>
        <summary><span data-ttu-id="71a4a-238">指定されたパスに、既存の通知ハブを更新、<paramref name="description" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="71a4a-238">Updates an existing notification hub at the path specified in the <paramref name="description" /> parameter.</span></span> <span data-ttu-id="71a4a-239">指定したで通知ハブのすべてのプロパティが上書きされます、<paramref name="description" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="71a4a-239">All the notification hub properties are overwritten with the ones specified in the <paramref name="description" /> parameter.</span></span> </summary>
        <returns><span data-ttu-id="71a4a-240">A<see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" />更新された通知ハブの説明を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-240">A <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> object containing a description of the updated notification hub.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateNotificationHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; UpdateNotificationHubAsync (Microsoft.Azure.NotificationHubs.NotificationHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; UpdateNotificationHubAsync(class Microsoft.Azure.NotificationHubs.NotificationHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.UpdateNotificationHubAsync(Microsoft.Azure.NotificationHubs.NotificationHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateNotificationHubAsync (description As NotificationHubDescription) As Task(Of NotificationHubDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateNotificationHubAsync : Microsoft.Azure.NotificationHubs.NotificationHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;" Usage="namespaceManager.UpdateNotificationHubAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="71a4a-241">通知ハブの更新する属性を記述する説明オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-241">The description object describing the attributes with which the notification hub will be updated.</span></span></param>
        <summary><span data-ttu-id="71a4a-242">指定されたパスに、既存の通知ハブを非同期に更新、<paramref name="description" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="71a4a-242">Asynchronously updates an existing notification hub at the path specified in the <paramref name="description" /> parameter.</span></span> <span data-ttu-id="71a4a-243">指定したで通知ハブのすべてのプロパティが上書きされます、<paramref name="description" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="71a4a-243">All the notification hub properties are overwritten with the ones specified in the <paramref name="description" /> parameter.</span></span></summary>
        <returns><span data-ttu-id="71a4a-244">A<see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" />更新された通知ハブの説明を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="71a4a-244">A <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> object containing a description of the updated notification hub.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>