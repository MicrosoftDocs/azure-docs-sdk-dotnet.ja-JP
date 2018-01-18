<Type Name="ServiceQueryDescription" FullName="System.Fabric.Description.ServiceQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceQueryDescription" />
  <TypeSignature Language="F#" Value="type ServiceQueryDescription = class" />
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
      <para><span data-ttu-id="5708e-101">戻り値を調整するために指定できる複数のフィルターを表します。</span><span class="sxs-lookup"><span data-stu-id="5708e-101">Represents the multiple filters that can be specified to refine the return.</span></span>
            <span data-ttu-id="5708e-102"><see cref="M:System.Fabric.FabricClient.QueryClient.GetServicePagedListAsync(System.Fabric.Description.ServiceQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" /> で使用されます。</span><span class="sxs-lookup"><span data-stu-id="5708e-102">Used by <see cref="M:System.Fabric.FabricClient.QueryClient.GetServicePagedListAsync(System.Fabric.Description.ServiceQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceQueryDescription (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceQueryDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceQueryDescription : Uri -&gt; System.Fabric.Description.ServiceQueryDescription" Usage="new System.Fabric.Description.ServiceQueryDescription applicationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">To be added.</param>
        <summary>
          <para><span data-ttu-id="5708e-103"><see cref="T:System.Fabric.Description.ServiceQueryDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5708e-103">Initializes a new instance of the <see cref="T:System.Fabric.Description.ServiceQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceQueryDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.ServiceQueryDescription.ApplicationName" />
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
          <para><span data-ttu-id="5708e-104">クエリを実行するサービスを含んでいるアプリケーションの URI 名を取得します。</span><span class="sxs-lookup"><span data-stu-id="5708e-104">Gets the URI name of application that contains services to query for.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5708e-105">クエリを実行するサービスを含んでいるアプリケーションの URI 名です。</span><span class="sxs-lookup"><span data-stu-id="5708e-105">The URI name of application that contains services to query for.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceQueryDescription.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="System.Fabric.Description.ServiceQueryDescription.ContinuationToken" />
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
          <para><span data-ttu-id="5708e-106">取得または次のページを取得するクエリで使用できるトークンを設定します。</span><span class="sxs-lookup"><span data-stu-id="5708e-106">Gets or sets the token that can be used by queries to get the next page.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5708e-107">次のページを取得するクエリで使用できるトークンです。</span><span class="sxs-lookup"><span data-stu-id="5708e-107">The token that can be used by queries to get the next page.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="5708e-108">ContinuationToken は、前のクエリによって受信されます。</span><span class="sxs-lookup"><span data-stu-id="5708e-108">ContinuationToken is received by a previous query.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceNameFilter">
      <MemberSignature Language="C#" Value="public Uri ServiceNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceQueryDescription.ServiceNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceNameFilter As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceNameFilter : Uri with get, set" Usage="System.Fabric.Description.ServiceQueryDescription.ServiceNameFilter" />
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
          <para><span data-ttu-id="5708e-109">取得またはクエリを実行するサービスの URI 名を設定します。</span><span class="sxs-lookup"><span data-stu-id="5708e-109">Gets or sets the URI name of service to query for.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5708e-110">クエリの実行にサービスの URI 名です。</span><span class="sxs-lookup"><span data-stu-id="5708e-110">The URI name of service to query for.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="5708e-111">ServiceNameFilter と ServiceTypeNameFilter を同時に指定するはありません。</span><span class="sxs-lookup"><span data-stu-id="5708e-111">ServiceNameFilter and ServiceTypeNameFilter can not be specified together.</span></span></para>
          <para><span data-ttu-id="5708e-112">ServiceNameFilter も ServiceTypeNameFilter のどちらも指定されていない場合は、指定したアプリケーションのすべてのサービスが返されます。</span><span class="sxs-lookup"><span data-stu-id="5708e-112">If neither ServiceNameFilter nor ServiceTypeNameFilter is specified, all services of the specified application are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeNameFilter">
      <MemberSignature Language="C#" Value="public string ServiceTypeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceQueryDescription.ServiceTypeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceTypeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeNameFilter : string with get, set" Usage="System.Fabric.Description.ServiceQueryDescription.ServiceTypeNameFilter" />
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
          <para><span data-ttu-id="5708e-113">取得またはクエリを実行するサービスをフィルター処理するために使用するサービスの種類名を設定します。</span><span class="sxs-lookup"><span data-stu-id="5708e-113">Gets or sets the service type name used to filter the services to query for.</span></span>
            <span data-ttu-id="5708e-114">このサービスの種類は、サービスが返されます。</span><span class="sxs-lookup"><span data-stu-id="5708e-114">Services that are of this service type will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5708e-115">クエリを実行するサービスをフィルター処理するために使用されるサービスの種類名。</span><span class="sxs-lookup"><span data-stu-id="5708e-115">The service type name used to filter the services to query for.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="5708e-116">ServiceNameFilter と ServiceTypeNameFilter を同時に指定するはありません。</span><span class="sxs-lookup"><span data-stu-id="5708e-116">ServiceNameFilter and ServiceTypeNameFilter can not be specified together.</span></span></para>
          <para><span data-ttu-id="5708e-117">ServiceNameFilter も ServiceTypeNameFilter のどちらも指定されていない場合は、指定したアプリケーションのすべてのサービスが返されます。</span><span class="sxs-lookup"><span data-stu-id="5708e-117">If neither ServiceNameFilter nor ServiceTypeNameFilter is specified, all services of the specified application are returned.</span></span></para>
          <para><span data-ttu-id="5708e-118">このフィルターは、大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="5708e-118">This filter is case sensitive.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>