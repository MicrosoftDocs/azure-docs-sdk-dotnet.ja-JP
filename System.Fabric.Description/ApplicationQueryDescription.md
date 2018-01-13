<Type Name="ApplicationQueryDescription" FullName="System.Fabric.Description.ApplicationQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationQueryDescription" />
  <TypeSignature Language="F#" Value="type ApplicationQueryDescription = class" />
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
      <para><span data-ttu-id="b11c6-101">使用されるクエリの入力を表す<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationPagedListAsync(System.Fabric.Description.ApplicationQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="b11c6-101">Represents the query input used by <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationPagedListAsync(System.Fabric.Description.ApplicationQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="b11c6-102"><see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b11c6-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationDefinitionKindFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationDefinitionKindFilter ApplicationDefinitionKindFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ApplicationDefinitionKindFilter ApplicationDefinitionKindFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationQueryDescription.ApplicationDefinitionKindFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationDefinitionKindFilter As ApplicationDefinitionKindFilter" />
      <MemberSignature Language="F#" Value="member this.ApplicationDefinitionKindFilter : System.Fabric.Description.ApplicationDefinitionKindFilter with get, set" Usage="System.Fabric.Description.ApplicationQueryDescription.ApplicationDefinitionKindFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b11c6-103">取得または設定の定義の種類が返されるアプリケーションをフィルター処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="b11c6-103">Gets or sets the definition kind used to filter the applications that will be returned.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="b11c6-104">定義の種類をアプリケーションをフィルター処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="b11c6-104">The definition kind used to filter the applications.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b11c6-105">ApplicationNameFilter、ApplicationTypeNameFilter、または ApplicationDefinitionKindFilter の 1 つを指定することができます。</span><span class="sxs-lookup"><span data-stu-id="b11c6-105">At most one of ApplicationNameFilter, ApplicationTypeNameFilter, or ApplicationDefinitionKindFilter can be specified.</span></span></para>
          <para><span data-ttu-id="b11c6-106">フィルターが指定されていない場合に適しているのページのすべてのアプリケーションが返されます。</span><span class="sxs-lookup"><span data-stu-id="b11c6-106">If no filters are specified, all applications are returned which fits a page.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationNameFilter">
      <MemberSignature Language="C#" Value="public Uri ApplicationNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationQueryDescription.ApplicationNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationNameFilter As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationNameFilter : Uri with get, set" Usage="System.Fabric.Description.ApplicationQueryDescription.ApplicationNameFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b11c6-107">取得またはクエリを実行するアプリケーションの URI 名を設定します。</span><span class="sxs-lookup"><span data-stu-id="b11c6-107">Gets or sets the URI name of application to query for.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b11c6-108">クエリの実行にアプリケーションの URI 名です。</span><span class="sxs-lookup"><span data-stu-id="b11c6-108">The URI name of application to query for.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b11c6-109">ApplicationNameFilter、ApplicationTypeNameFilter、または ApplicationDefinitionKindFilter の 1 つを指定することができます。</span><span class="sxs-lookup"><span data-stu-id="b11c6-109">At most one of ApplicationNameFilter, ApplicationTypeNameFilter, or ApplicationDefinitionKindFilter can be specified.</span></span></para>
          <para><span data-ttu-id="b11c6-110">フィルターが指定されていない場合、ページに合わせてすべてのアプリケーションが返されます。</span><span class="sxs-lookup"><span data-stu-id="b11c6-110">If no filters are specified, all applications which fit a page are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeNameFilter">
      <MemberSignature Language="C#" Value="public string ApplicationTypeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationQueryDescription.ApplicationTypeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeNameFilter : string with get, set" Usage="System.Fabric.Description.ApplicationQueryDescription.ApplicationTypeNameFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b11c6-111">取得またはクエリを実行するアプリケーションをフィルター処理するために使用するアプリケーションの種類名を設定します。</span><span class="sxs-lookup"><span data-stu-id="b11c6-111">Gets or sets the application type name used to filter the applications to query for.</span></span>
            <span data-ttu-id="b11c6-112">このアプリケーションの種類は、アプリケーションが返されます。</span><span class="sxs-lookup"><span data-stu-id="b11c6-112">Applications that are of this application type will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b11c6-113">アプリケーションの種類名はクエリを実行するアプリケーションをフィルター処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="b11c6-113">The application type name used to filter the applications to query for.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b11c6-114">ApplicationNameFilter、ApplicationTypeNameFilter、または ApplicationDefinitionKindFilter の 1 つを指定することができます。</span><span class="sxs-lookup"><span data-stu-id="b11c6-114">At most one of ApplicationNameFilter, ApplicationTypeNameFilter, or ApplicationDefinitionKindFilter can be specified.</span></span></para>
          <para><span data-ttu-id="b11c6-115">フィルターが指定されていない場合、ページに合わせてすべてのアプリケーションが返されます。</span><span class="sxs-lookup"><span data-stu-id="b11c6-115">If no filters are specified, all applications which fit a page are returned.</span></span></para>
          <para><span data-ttu-id="b11c6-116">このフィルターは、大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="b11c6-116">This filter is case sensitive.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationQueryDescription.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="System.Fabric.Description.ApplicationQueryDescription.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b11c6-117">取得または次のページを取得するクエリで使用できるトークンを設定します。</span><span class="sxs-lookup"><span data-stu-id="b11c6-117">Gets or sets the token that can be used by queries to get the next page.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b11c6-118">次のページを取得するクエリで使用できるトークンです。</span><span class="sxs-lookup"><span data-stu-id="b11c6-118">The token that can be used by queries to get the next page.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b11c6-119">ContinuationToken は、前のクエリによって受信されます。</span><span class="sxs-lookup"><span data-stu-id="b11c6-119">ContinuationToken is received by a previous query.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeApplicationParameters">
      <MemberSignature Language="C#" Value="public bool ExcludeApplicationParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeApplicationParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationQueryDescription.ExcludeApplicationParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeApplicationParameters As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeApplicationParameters : bool with get, set" Usage="System.Fabric.Description.ApplicationQueryDescription.ExcludeApplicationParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b11c6-120">取得またはアプリケーションのパラメーターを結果から除外するかどうかを指定するフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="b11c6-120">Gets or sets the flag that specifies whether application parameters will be excluded from the result.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b11c6-121">アプリケーションのパラメーターを結果から除外するかどうかを指定するフラグ。</span><span class="sxs-lookup"><span data-stu-id="b11c6-121">Flag that specifies whether application parameters will be excluded from the result.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b11c6-122">このフラグは、パラメーターが大きなサイズの結果を制限するためには、true に設定することができます。</span><span class="sxs-lookup"><span data-stu-id="b11c6-122">This flag can be set to true in order to limit the result size when parameters are huge.</span></span>
            <span data-ttu-id="b11c6-123">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="b11c6-123">Default value is false.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>