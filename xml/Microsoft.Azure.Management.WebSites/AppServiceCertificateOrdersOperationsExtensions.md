<Type Name="AppServiceCertificateOrdersOperationsExtensions" FullName="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AppServiceCertificateOrdersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AppServiceCertificateOrdersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AppServiceCertificateOrdersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AppServiceCertificateOrdersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1b3a4-101">AppServiceCertificateOrdersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-101">Extension methods for AppServiceCertificateOrdersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder BeginCreateOrUpdate (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder certificateDistinguishedName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder BeginCreateOrUpdate(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder certificateDistinguishedName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IAppServiceCertificateOrdersOperations, resourceGroupName As String, certificateOrderName As String, certificateDistinguishedName As AppServiceCertificateOrder) As AppServiceCertificateOrder" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, certificateOrderName, certificateDistinguishedName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="certificateDistinguishedName" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-103">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-104">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-104">Name of the certificate order.</span></span>
            </param>
        <param name="certificateDistinguishedName">
            <span data-ttu-id="1b3a4-105">証明書の順序を使用するための識別名。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-105">Distinguished name to to use for the certificate order.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-106">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-106">Create or update a certificate purchase order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-107">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-107">Create or update a certificate purchase order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder certificateDistinguishedName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder certificateDistinguishedName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, certificateOrderName, certificateDistinguishedName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="certificateDistinguishedName" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-109">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-109">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-110">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-110">Name of the certificate order.</span></span>
            </param>
        <param name="certificateDistinguishedName">
            <span data-ttu-id="1b3a4-111">証明書の順序を使用するための識別名。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-111">Distinguished name to to use for the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-113">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-113">Create or update a certificate purchase order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-114">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-114">Create or update a certificate purchase order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateCertificate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource BeginCreateOrUpdateCertificate (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource keyVaultCertificate);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource BeginCreateOrUpdateCertificate(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource keyVaultCertificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateCertificate(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateCertificate (operations As IAppServiceCertificateOrdersOperations, resourceGroupName As String, certificateOrderName As String, name As String, keyVaultCertificate As AppServiceCertificateResource) As AppServiceCertificateResource" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateCertificate : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateCertificate (operations, resourceGroupName, certificateOrderName, name, keyVaultCertificate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyVaultCertificate" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-116">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-116">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-117">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-117">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1b3a4-118">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-118">Name of the certificate.</span></span>
            </param>
        <param name="keyVaultCertificate">
            <span data-ttu-id="1b3a4-119">資格情報コンテナー証明書リソース id。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-119">Key vault certificate resource Id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-120">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-120">Creates or updates a certificate and associates with key vault secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-121">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-121">Creates or updates a certificate and associates with key vault secret.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt; BeginCreateOrUpdateCertificateAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource keyVaultCertificate, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt; BeginCreateOrUpdateCertificateAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource keyVaultCertificate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateCertificateAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateCertificateAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateCertificateAsync (operations, resourceGroupName, certificateOrderName, name, keyVaultCertificate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;BeginCreateOrUpdateCertificateAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyVaultCertificate" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-123">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-123">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-124">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-124">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1b3a4-125">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-125">Name of the certificate.</span></span>
            </param>
        <param name="keyVaultCertificate">
            <span data-ttu-id="1b3a4-126">資格情報コンテナー証明書リソース id。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-126">Key vault certificate resource Id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-128">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-128">Creates or updates a certificate and associates with key vault secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-129">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-129">Creates or updates a certificate and associates with key vault secret.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder CreateOrUpdate (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder certificateDistinguishedName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder CreateOrUpdate(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder certificateDistinguishedName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IAppServiceCertificateOrdersOperations, resourceGroupName As String, certificateOrderName As String, certificateDistinguishedName As AppServiceCertificateOrder) As AppServiceCertificateOrder" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, certificateOrderName, certificateDistinguishedName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="certificateDistinguishedName" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-131">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-131">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-132">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-132">Name of the certificate order.</span></span>
            </param>
        <param name="certificateDistinguishedName">
            <span data-ttu-id="1b3a4-133">証明書の順序を使用するための識別名。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-133">Distinguished name to to use for the certificate order.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-134">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-134">Create or update a certificate purchase order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-135">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-135">Create or update a certificate purchase order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder certificateDistinguishedName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder certificateDistinguishedName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, certificateOrderName, certificateDistinguishedName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="certificateDistinguishedName" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-137">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-137">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-138">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-138">Name of the certificate order.</span></span>
            </param>
        <param name="certificateDistinguishedName">
            <span data-ttu-id="1b3a4-139">証明書の順序を使用するための識別名。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-139">Distinguished name to to use for the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-141">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-141">Create or update a certificate purchase order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-142">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-142">Create or update a certificate purchase order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateCertificate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource CreateOrUpdateCertificate (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource keyVaultCertificate);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource CreateOrUpdateCertificate(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource keyVaultCertificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateCertificate(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateCertificate (operations As IAppServiceCertificateOrdersOperations, resourceGroupName As String, certificateOrderName As String, name As String, keyVaultCertificate As AppServiceCertificateResource) As AppServiceCertificateResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateCertificate : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateCertificate (operations, resourceGroupName, certificateOrderName, name, keyVaultCertificate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyVaultCertificate" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-144">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-144">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-145">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-145">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1b3a4-146">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-146">Name of the certificate.</span></span>
            </param>
        <param name="keyVaultCertificate">
            <span data-ttu-id="1b3a4-147">資格情報コンテナー証明書リソース id。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-147">Key vault certificate resource Id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-148">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-148">Creates or updates a certificate and associates with key vault secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-149">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-149">Creates or updates a certificate and associates with key vault secret.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt; CreateOrUpdateCertificateAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource keyVaultCertificate, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt; CreateOrUpdateCertificateAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource keyVaultCertificate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateCertificateAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateCertificateAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateCertificateAsync (operations, resourceGroupName, certificateOrderName, name, keyVaultCertificate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;CreateOrUpdateCertificateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyVaultCertificate" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-151">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-151">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-152">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-152">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1b3a4-153">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-153">Name of the certificate.</span></span>
            </param>
        <param name="keyVaultCertificate">
            <span data-ttu-id="1b3a4-154">資格情報コンテナー証明書リソース id。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-154">Key vault certificate resource Id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-156">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-156">Creates or updates a certificate and associates with key vault secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-157">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-157">Creates or updates a certificate and associates with key vault secret.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.Delete(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IAppServiceCertificateOrdersOperations, resourceGroupName As String, certificateOrderName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.Delete (operations, resourceGroupName, certificateOrderName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-159">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-159">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-160">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-160">Name of the certificate order.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-161">既存の証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-161">Delete an existing certificate order.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="1b3a4-162">既存の証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-162">Delete an existing certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.DeleteAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;DeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-164">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-164">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-165">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-165">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-167">既存の証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-167">Delete an existing certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-168">既存の証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-168">Delete an existing certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificate">
      <MemberSignature Language="C#" Value="public static void DeleteCertificate (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteCertificate(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.DeleteCertificate(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteCertificate (operations As IAppServiceCertificateOrdersOperations, resourceGroupName As String, certificateOrderName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificate : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.DeleteCertificate (operations, resourceGroupName, certificateOrderName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-169">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-169">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-170">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-170">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-171">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-171">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1b3a4-172">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-172">Name of the certificate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-173">証明書の順序に関連付けられている証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-173">Delete the certificate associated with a certificate order.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="1b3a4-174">証明書の順序に関連付けられている証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-174">Delete the certificate associated with a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteCertificateAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteCertificateAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.DeleteCertificateAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificateAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.DeleteCertificateAsync (operations, resourceGroupName, certificateOrderName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;DeleteCertificateAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-175">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-176">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-176">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-177">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-177">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1b3a4-178">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-178">Name of the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-179">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-180">証明書の順序に関連付けられている証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-180">Delete the certificate associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-181">証明書の順序に関連付けられている証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-181">Delete the certificate associated with a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder Get (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder Get(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.Get(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IAppServiceCertificateOrdersOperations, resourceGroupName As String, certificateOrderName As String) As AppServiceCertificateOrder" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.Get (operations, resourceGroupName, certificateOrderName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-183">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-183">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-184">証明書の順序の名前。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-184">Name of the certificate order..</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-185">証明書の順序を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-185">Get a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-186">証明書の順序を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-186">Get a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt; GetAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt; GetAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.GetAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.GetAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-187">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-187">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-188">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-188">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-189">証明書の順序の名前。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-189">Name of the certificate order..</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-191">証明書の順序を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-191">Get a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-192">証明書の順序を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-192">Get a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource GetCertificate (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource GetCertificate(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.GetCertificate(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCertificate (operations As IAppServiceCertificateOrdersOperations, resourceGroupName As String, certificateOrderName As String, name As String) As AppServiceCertificateResource" />
      <MemberSignature Language="F#" Value="static member GetCertificate : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.GetCertificate (operations, resourceGroupName, certificateOrderName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-193">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-193">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-194">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-194">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-195">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-195">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1b3a4-196">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-196">Name of the certificate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-197">証明書の順序に関連付けられている証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-197">Get the certificate associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-198">証明書の順序に関連付けられている証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-198">Get the certificate associated with a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt; GetCertificateAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt; GetCertificateAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.GetCertificateAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.GetCertificateAsync (operations, resourceGroupName, certificateOrderName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;GetCertificateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-199">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-199">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-200">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-200">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-201">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-201">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1b3a4-202">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-202">Name of the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-203">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-204">証明書の順序に関連付けられている証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-204">Get the certificate associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-205">証明書の順序に関連付けられている証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-205">Get the certificate associated with a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt; List (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt; List(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.List(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IAppServiceCertificateOrdersOperations) As IPage(Of AppServiceCertificateOrder)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-206">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-206">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-207">サブスクリプションのすべての証明書の注文を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-207">List all certificate orders in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-208">サブスクリプションのすべての証明書の注文を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-208">List all certificate orders in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt; ListAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt; ListAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-209">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-209">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-210">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-211">サブスクリプションのすべての証明書の注文を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-211">List all certificate orders in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-212">サブスクリプションのすべての証明書の注文を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-212">List all certificate orders in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt; ListByResourceGroup (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt; ListByResourceGroup(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IAppServiceCertificateOrdersOperations, resourceGroupName As String) As IPage(Of AppServiceCertificateOrder)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-213">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-213">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-214">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-214">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-215">リソース グループ内の証明書の注文を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-215">Get certificate orders in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-216">リソース グループ内の証明書の注文を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-216">Get certificate orders in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-217">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-217">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-218">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-218">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-219">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-220">リソース グループ内の証明書の注文を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-220">Get certificate orders in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-221">リソース グループ内の証明書の注文を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-221">Get certificate orders in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IAppServiceCertificateOrdersOperations, nextPageLink As String) As IPage(Of AppServiceCertificateOrder)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-222">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-222">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1b3a4-223">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-223">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-224">リソース グループ内の証明書の注文を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-224">Get certificate orders in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-225">リソース グループ内の証明書の注文を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-225">Get certificate orders in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-226">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-226">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1b3a4-227">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-227">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-228">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-228">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-229">リソース グループ内の証明書の注文を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-229">Get certificate orders in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-230">リソース グループ内の証明書の注文を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-230">Get certificate orders in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCertificates">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt; ListCertificates (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt; ListCertificates(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListCertificates(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListCertificates (operations As IAppServiceCertificateOrdersOperations, resourceGroupName As String, certificateOrderName As String) As IPage(Of AppServiceCertificateResource)" />
      <MemberSignature Language="F#" Value="static member ListCertificates : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListCertificates (operations, resourceGroupName, certificateOrderName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-231">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-231">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-232">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-232">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-233">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-233">Name of the certificate order.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-234">証明書の順序に関連付けられているすべての証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-234">List all certificates associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-235">証明書の順序に関連付けられているすべての証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-235">List all certificates associated with a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCertificatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt; ListCertificatesAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt; ListCertificatesAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCertificatesAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;ListCertificatesAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-236">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-237">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-237">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-238">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-238">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-239">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-239">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-240">証明書の順序に関連付けられているすべての証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-240">List all certificates associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-241">証明書の順序に関連付けられているすべての証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-241">List all certificates associated with a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCertificatesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt; ListCertificatesNext (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt; ListCertificatesNext(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesNext(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListCertificatesNext (operations As IAppServiceCertificateOrdersOperations, nextPageLink As String) As IPage(Of AppServiceCertificateResource)" />
      <MemberSignature Language="F#" Value="static member ListCertificatesNext : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-242">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-242">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1b3a4-243">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-243">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-244">証明書の順序に関連付けられているすべての証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-244">List all certificates associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-245">証明書の順序に関連付けられているすべての証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-245">List all certificates associated with a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCertificatesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt; ListCertificatesNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt; ListCertificatesNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCertificatesNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;ListCertificatesNextAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-246">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-246">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1b3a4-247">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-247">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-248">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-248">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-249">証明書の順序に関連付けられているすべての証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-249">List all certificates associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-250">証明書の順序に関連付けられているすべての証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-250">List all certificates associated with a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt; ListNext (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt; ListNext(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListNext(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IAppServiceCertificateOrdersOperations, nextPageLink As String) As IPage(Of AppServiceCertificateOrder)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-251">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-251">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1b3a4-252">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-252">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-253">サブスクリプションのすべての証明書の注文を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-253">List all certificate orders in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-254">サブスクリプションのすべての証明書の注文を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-254">List all certificate orders in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;ListNextAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-255">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-255">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1b3a4-256">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-256">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-257">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-257">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-258">サブスクリプションのすべての証明書の注文を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-258">List all certificate orders in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-259">サブスクリプションのすべての証明書の注文を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-259">List all certificate orders in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Reissue">
      <MemberSignature Language="C#" Value="public static void Reissue (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.ReissueCertificateOrderRequest reissueCertificateOrderRequest);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Reissue(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.ReissueCertificateOrderRequest reissueCertificateOrderRequest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.Reissue(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.ReissueCertificateOrderRequest)" />
      <MemberSignature Language="F#" Value="static member Reissue : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.WebSites.Models.ReissueCertificateOrderRequest -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.Reissue (operations, resourceGroupName, certificateOrderName, reissueCertificateOrderRequest)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="reissueCertificateOrderRequest" Type="Microsoft.Azure.Management.WebSites.Models.ReissueCertificateOrderRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-260">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-260">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-261">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-261">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-262">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-262">Name of the certificate order.</span></span>
            </param>
        <param name="reissueCertificateOrderRequest">
            <span data-ttu-id="1b3a4-263">パラメーター、再実行してください。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-263">Parameters for the reissue.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-264">既存の証明書の順序を再実行します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-264">Reissue an existing certificate order.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="1b3a4-265">既存の証明書の順序を再実行します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-265">Reissue an existing certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReissueAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ReissueAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.ReissueCertificateOrderRequest reissueCertificateOrderRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ReissueAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.ReissueCertificateOrderRequest reissueCertificateOrderRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ReissueAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.ReissueCertificateOrderRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReissueAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.WebSites.Models.ReissueCertificateOrderRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ReissueAsync (operations, resourceGroupName, certificateOrderName, reissueCertificateOrderRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;ReissueAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="reissueCertificateOrderRequest" Type="Microsoft.Azure.Management.WebSites.Models.ReissueCertificateOrderRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-266">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-266">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-267">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-267">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-268">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-268">Name of the certificate order.</span></span>
            </param>
        <param name="reissueCertificateOrderRequest">
            <span data-ttu-id="1b3a4-269">パラメーター、再実行してください。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-269">Parameters for the reissue.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-270">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-270">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-271">既存の証明書の順序を再実行します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-271">Reissue an existing certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-272">既存の証明書の順序を再実行します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-272">Reissue an existing certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Renew">
      <MemberSignature Language="C#" Value="public static void Renew (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest renewCertificateOrderRequest);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Renew(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest renewCertificateOrderRequest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.Renew(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest)" />
      <MemberSignature Language="F#" Value="static member Renew : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.Renew (operations, resourceGroupName, certificateOrderName, renewCertificateOrderRequest)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="renewCertificateOrderRequest" Type="Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-273">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-273">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-274">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-274">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-275">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-275">Name of the certificate order.</span></span>
            </param>
        <param name="renewCertificateOrderRequest">
            <span data-ttu-id="1b3a4-276">パラメーターを更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-276">Renew parameters</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-277">既存の証明書の順序を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-277">Renew an existing certificate order.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="1b3a4-278">既存の証明書の順序を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-278">Renew an existing certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RenewAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest renewCertificateOrderRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RenewAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest renewCertificateOrderRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.RenewAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RenewAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.RenewAsync (operations, resourceGroupName, certificateOrderName, renewCertificateOrderRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;RenewAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="renewCertificateOrderRequest" Type="Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-279">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-279">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-280">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-280">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-281">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-281">Name of the certificate order.</span></span>
            </param>
        <param name="renewCertificateOrderRequest">
            <span data-ttu-id="1b3a4-282">パラメーターを更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-282">Renew parameters</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-283">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-283">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-284">既存の証明書の順序を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-284">Renew an existing certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-285">既存の証明書の順序を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-285">Renew an existing certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResendEmail">
      <MemberSignature Language="C#" Value="public static void ResendEmail (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ResendEmail(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ResendEmail(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ResendEmail (operations As IAppServiceCertificateOrdersOperations, resourceGroupName As String, certificateOrderName As String)" />
      <MemberSignature Language="F#" Value="static member ResendEmail : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ResendEmail (operations, resourceGroupName, certificateOrderName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-286">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-286">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-287">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-287">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-288">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-288">Name of the certificate order.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-289">証明書の電子メールの再送信します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-289">Resend certificate email.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="1b3a4-290">証明書の電子メールの再送信します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-290">Resend certificate email.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResendEmailAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResendEmailAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResendEmailAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ResendEmailAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResendEmailAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ResendEmailAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;ResendEmailAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-291">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-291">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-292">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-292">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-293">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-293">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-294">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-294">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-295">証明書の電子メールの再送信します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-295">Resend certificate email.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-296">証明書の電子メールの再送信します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-296">Resend certificate email.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResendRequestEmails">
      <MemberSignature Language="C#" Value="public static void ResendRequestEmails (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.NameIdentifier nameIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ResendRequestEmails(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.NameIdentifier nameIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ResendRequestEmails(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.NameIdentifier)" />
      <MemberSignature Language="F#" Value="static member ResendRequestEmails : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.WebSites.Models.NameIdentifier -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ResendRequestEmails (operations, resourceGroupName, certificateOrderName, nameIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="nameIdentifier" Type="Microsoft.Azure.Management.WebSites.Models.NameIdentifier" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-297">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-297">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-298">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-298">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-299">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-299">Name of the certificate order.</span></span>
            </param>
        <param name="nameIdentifier">
            <span data-ttu-id="1b3a4-300">電子メール アドレス</span><span class="sxs-lookup"><span data-stu-id="1b3a4-300">Email address</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-301">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-301">Verify domain ownership for this certificate order.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="1b3a4-302">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-302">Verify domain ownership for this certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResendRequestEmailsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResendRequestEmailsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.NameIdentifier nameIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResendRequestEmailsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.NameIdentifier nameIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ResendRequestEmailsAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.NameIdentifier,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResendRequestEmailsAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.WebSites.Models.NameIdentifier * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ResendRequestEmailsAsync (operations, resourceGroupName, certificateOrderName, nameIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;ResendRequestEmailsAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="nameIdentifier" Type="Microsoft.Azure.Management.WebSites.Models.NameIdentifier" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-303">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-303">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-304">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-304">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-305">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-305">Name of the certificate order.</span></span>
            </param>
        <param name="nameIdentifier">
            <span data-ttu-id="1b3a4-306">電子メール アドレス</span><span class="sxs-lookup"><span data-stu-id="1b3a4-306">Email address</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-307">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-307">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-308">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-308">Verify domain ownership for this certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-309">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-309">Verify domain ownership for this certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveCertificateActions">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction&gt; RetrieveCertificateActions (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction&gt; RetrieveCertificateActions(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateActions(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RetrieveCertificateActions (operations As IAppServiceCertificateOrdersOperations, resourceGroupName As String, name As String) As IList(Of CertificateOrderAction)" />
      <MemberSignature Language="F#" Value="static member RetrieveCertificateActions : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateActions (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-310">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-310">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-311">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-311">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1b3a4-312">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-312">Name of the certificate order.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-313">証明書の操作の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-313">Retrieve the list of certificate actions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-314">証明書の操作の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-314">Retrieve the list of certificate actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveCertificateActionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction&gt;&gt; RetrieveCertificateActionsAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction&gt;&gt; RetrieveCertificateActionsAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateActionsAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RetrieveCertificateActionsAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateActionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;RetrieveCertificateActionsAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-315">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-315">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-316">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-316">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1b3a4-317">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-317">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-318">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-318">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-319">証明書の操作の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-319">Retrieve the list of certificate actions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-320">証明書の操作の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-320">Retrieve the list of certificate actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveCertificateEmailHistory">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateEmail&gt; RetrieveCertificateEmailHistory (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.CertificateEmail&gt; RetrieveCertificateEmailHistory(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateEmailHistory(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RetrieveCertificateEmailHistory (operations As IAppServiceCertificateOrdersOperations, resourceGroupName As String, name As String) As IList(Of CertificateEmail)" />
      <MemberSignature Language="F#" Value="static member RetrieveCertificateEmailHistory : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateEmail&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateEmailHistory (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateEmail&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-321">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-321">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-322">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-322">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1b3a4-323">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-323">Name of the certificate order.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-324">電子メールの履歴を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-324">Retrieve email history.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-325">電子メールの履歴を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-325">Retrieve email history.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveCertificateEmailHistoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateEmail&gt;&gt; RetrieveCertificateEmailHistoryAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.CertificateEmail&gt;&gt; RetrieveCertificateEmailHistoryAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateEmailHistoryAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RetrieveCertificateEmailHistoryAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateEmail&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateEmailHistoryAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;RetrieveCertificateEmailHistoryAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateEmail&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-326">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-326">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-327">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-327">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1b3a4-328">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-328">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-329">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-329">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-330">電子メールの履歴を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-330">Retrieve email history.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-331">電子メールの履歴を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-331">Retrieve email history.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveSiteSeal">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.SiteSeal RetrieveSiteSeal (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.SiteSealRequest siteSealRequest);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.SiteSeal RetrieveSiteSeal(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.SiteSealRequest siteSealRequest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.RetrieveSiteSeal(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.SiteSealRequest)" />
      <MemberSignature Language="F#" Value="static member RetrieveSiteSeal : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.WebSites.Models.SiteSealRequest -&gt; Microsoft.Azure.Management.WebSites.Models.SiteSeal" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.RetrieveSiteSeal (operations, resourceGroupName, certificateOrderName, siteSealRequest)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SiteSeal</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="siteSealRequest" Type="Microsoft.Azure.Management.WebSites.Models.SiteSealRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-332">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-332">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-333">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-333">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-334">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-334">Name of the certificate order.</span></span>
            </param>
        <param name="siteSealRequest">
            <span data-ttu-id="1b3a4-335">サイトでは、要求を封印します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-335">Site seal request.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-336">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-336">Verify domain ownership for this certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-337">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-337">Verify domain ownership for this certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveSiteSealAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SiteSeal&gt; RetrieveSiteSealAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.SiteSealRequest siteSealRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.SiteSeal&gt; RetrieveSiteSealAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.SiteSealRequest siteSealRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.RetrieveSiteSealAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.SiteSealRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RetrieveSiteSealAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.WebSites.Models.SiteSealRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SiteSeal&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.RetrieveSiteSealAsync (operations, resourceGroupName, certificateOrderName, siteSealRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;RetrieveSiteSealAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SiteSeal&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="siteSealRequest" Type="Microsoft.Azure.Management.WebSites.Models.SiteSealRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-338">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-338">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-339">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-339">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-340">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-340">Name of the certificate order.</span></span>
            </param>
        <param name="siteSealRequest">
            <span data-ttu-id="1b3a4-341">サイトでは、要求を封印します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-341">Site seal request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-342">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-342">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-343">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-343">Verify domain ownership for this certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-344">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-344">Verify domain ownership for this certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder Update (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource certificateDistinguishedName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder Update(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource certificateDistinguishedName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.Update(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IAppServiceCertificateOrdersOperations, resourceGroupName As String, certificateOrderName As String, certificateDistinguishedName As AppServiceCertificateOrderPatchResource) As AppServiceCertificateOrder" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.Update (operations, resourceGroupName, certificateOrderName, certificateDistinguishedName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="certificateDistinguishedName" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-345">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-345">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-346">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-346">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-347">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-347">Name of the certificate order.</span></span>
            </param>
        <param name="certificateDistinguishedName">
            <span data-ttu-id="1b3a4-348">証明書の順序を使用するための識別名。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-348">Distinguished name to to use for the certificate order.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-349">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-349">Create or update a certificate purchase order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-350">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-350">Create or update a certificate purchase order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt; UpdateAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource certificateDistinguishedName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt; UpdateAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource certificateDistinguishedName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.UpdateAsync (operations, resourceGroupName, certificateOrderName, certificateDistinguishedName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;UpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="certificateDistinguishedName" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-351">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-351">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-352">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-352">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-353">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-353">Name of the certificate order.</span></span>
            </param>
        <param name="certificateDistinguishedName">
            <span data-ttu-id="1b3a4-354">証明書の順序を使用するための識別名。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-354">Distinguished name to to use for the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-355">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-355">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-356">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-356">Create or update a certificate purchase order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-357">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-357">Create or update a certificate purchase order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource UpdateCertificate (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource keyVaultCertificate);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource UpdateCertificate(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource keyVaultCertificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.UpdateCertificate(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateCertificate (operations As IAppServiceCertificateOrdersOperations, resourceGroupName As String, certificateOrderName As String, name As String, keyVaultCertificate As AppServiceCertificatePatchResource) As AppServiceCertificateResource" />
      <MemberSignature Language="F#" Value="static member UpdateCertificate : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.UpdateCertificate (operations, resourceGroupName, certificateOrderName, name, keyVaultCertificate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyVaultCertificate" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-358">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-358">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-359">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-359">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-360">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-360">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1b3a4-361">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-361">Name of the certificate.</span></span>
            </param>
        <param name="keyVaultCertificate">
            <span data-ttu-id="1b3a4-362">資格情報コンテナー証明書リソース id。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-362">Key vault certificate resource Id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-363">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-363">Creates or updates a certificate and associates with key vault secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-364">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-364">Creates or updates a certificate and associates with key vault secret.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt; UpdateCertificateAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource keyVaultCertificate, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt; UpdateCertificateAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource keyVaultCertificate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.UpdateCertificateAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCertificateAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.UpdateCertificateAsync (operations, resourceGroupName, certificateOrderName, name, keyVaultCertificate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;UpdateCertificateAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyVaultCertificate" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-365">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-365">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-366">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-366">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-367">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-367">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1b3a4-368">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-368">Name of the certificate.</span></span>
            </param>
        <param name="keyVaultCertificate">
            <span data-ttu-id="1b3a4-369">資格情報コンテナー証明書リソース id。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-369">Key vault certificate resource Id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-370">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-370">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-371">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-371">Creates or updates a certificate and associates with key vault secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-372">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-372">Creates or updates a certificate and associates with key vault secret.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidatePurchaseInformation">
      <MemberSignature Language="C#" Value="public static void ValidatePurchaseInformation (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder appServiceCertificateOrder);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidatePurchaseInformation(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder appServiceCertificateOrder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ValidatePurchaseInformation(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder)" />
      <MemberSignature Language="F#" Value="static member ValidatePurchaseInformation : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ValidatePurchaseInformation (operations, appServiceCertificateOrder)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="appServiceCertificateOrder" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-373">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-373">The operations group for this extension method.</span></span>
            </param>
        <param name="appServiceCertificateOrder">
            <span data-ttu-id="1b3a4-374">証明書の順序の情報です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-374">Information for a certificate order.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-375">証明書の順序の情報を検証します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-375">Validate information for a certificate order.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="1b3a4-376">証明書の順序の情報を検証します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-376">Validate information for a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidatePurchaseInformationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ValidatePurchaseInformationAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder appServiceCertificateOrder, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ValidatePurchaseInformationAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder appServiceCertificateOrder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ValidatePurchaseInformationAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidatePurchaseInformationAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.ValidatePurchaseInformationAsync (operations, appServiceCertificateOrder, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;ValidatePurchaseInformationAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="appServiceCertificateOrder" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-377">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-377">The operations group for this extension method.</span></span>
            </param>
        <param name="appServiceCertificateOrder">
            <span data-ttu-id="1b3a4-378">証明書の順序の情報です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-378">Information for a certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-379">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-379">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-380">証明書の順序の情報を検証します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-380">Validate information for a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-381">証明書の順序の情報を検証します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-381">Validate information for a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnership">
      <MemberSignature Language="C#" Value="public static void VerifyDomainOwnership (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void VerifyDomainOwnership(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.VerifyDomainOwnership(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub VerifyDomainOwnership (operations As IAppServiceCertificateOrdersOperations, resourceGroupName As String, certificateOrderName As String)" />
      <MemberSignature Language="F#" Value="static member VerifyDomainOwnership : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.VerifyDomainOwnership (operations, resourceGroupName, certificateOrderName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-382">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-382">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-383">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-383">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-384">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-384">Name of the certificate order.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-385">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-385">Verify domain ownership for this certificate order.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="1b3a4-386">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-386">Verify domain ownership for this certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnershipAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task VerifyDomainOwnershipAsync (this Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task VerifyDomainOwnershipAsync(class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.VerifyDomainOwnershipAsync(Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyDomainOwnershipAsync : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions.VerifyDomainOwnershipAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServiceCertificateOrdersOperationsExtensions/&lt;VerifyDomainOwnershipAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b3a4-387">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-387">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1b3a4-388">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-388">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="1b3a4-389">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-389">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b3a4-390">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-390">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b3a4-391">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-391">Verify domain ownership for this certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b3a4-392">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="1b3a4-392">Verify domain ownership for this certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>