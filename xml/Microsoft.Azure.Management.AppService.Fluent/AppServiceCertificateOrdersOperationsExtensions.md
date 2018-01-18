<Type Name="AppServiceCertificateOrdersOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AppServiceCertificateOrdersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AppServiceCertificateOrdersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AppServiceCertificateOrdersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AppServiceCertificateOrdersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b804e-101">AppServiceCertificateOrdersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="b804e-101">Extension methods for AppServiceCertificateOrdersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner certificateDistinguishedName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner certificateDistinguishedName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, certificateOrderName, certificateDistinguishedName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="certificateDistinguishedName" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-103">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="b804e-104">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-104">Name of the certificate order.</span></span>
            </param>
        <param name="certificateDistinguishedName">
            <span data-ttu-id="b804e-105">証明書の順序を使用するための識別名。</span><span class="sxs-lookup"><span data-stu-id="b804e-105">Distinguished name to to use for the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-107">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="b804e-107">Create or update a certificate purchase order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-108">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="b804e-108">Create or update a certificate purchase order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; BeginCreateOrUpdateCertificateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner keyVaultCertificate, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; BeginCreateOrUpdateCertificateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner keyVaultCertificate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateCertificateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateCertificateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateCertificateAsync (operations, resourceGroupName, certificateOrderName, name, keyVaultCertificate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;BeginCreateOrUpdateCertificateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyVaultCertificate" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-110">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-110">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="b804e-111">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-111">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="b804e-112">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-112">Name of the certificate.</span></span>
            </param>
        <param name="keyVaultCertificate">
            <span data-ttu-id="b804e-113">資格情報コンテナー証明書リソース id。</span><span class="sxs-lookup"><span data-stu-id="b804e-113">Key vault certificate resource Id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-115">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="b804e-115">Creates or updates a certificate and associates with key vault secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-116">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="b804e-116">Creates or updates a certificate and associates with key vault secret.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner certificateDistinguishedName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner certificateDistinguishedName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, certificateOrderName, certificateDistinguishedName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="certificateDistinguishedName" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-118">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-118">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="b804e-119">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-119">Name of the certificate order.</span></span>
            </param>
        <param name="certificateDistinguishedName">
            <span data-ttu-id="b804e-120">証明書の順序を使用するための識別名。</span><span class="sxs-lookup"><span data-stu-id="b804e-120">Distinguished name to to use for the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-122">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="b804e-122">Create or update a certificate purchase order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-123">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="b804e-123">Create or update a certificate purchase order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; CreateOrUpdateCertificateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner keyVaultCertificate, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; CreateOrUpdateCertificateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner keyVaultCertificate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateCertificateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateCertificateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateCertificateAsync (operations, resourceGroupName, certificateOrderName, name, keyVaultCertificate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;CreateOrUpdateCertificateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyVaultCertificate" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-125">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-125">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="b804e-126">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-126">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="b804e-127">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-127">Name of the certificate.</span></span>
            </param>
        <param name="keyVaultCertificate">
            <span data-ttu-id="b804e-128">資格情報コンテナー証明書リソース id。</span><span class="sxs-lookup"><span data-stu-id="b804e-128">Key vault certificate resource Id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-130">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="b804e-130">Creates or updates a certificate and associates with key vault secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-131">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="b804e-131">Creates or updates a certificate and associates with key vault secret.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.DeleteAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-133">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-133">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="b804e-134">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-134">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-136">既存の証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="b804e-136">Delete an existing certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-137">既存の証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="b804e-137">Delete an existing certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteCertificateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteCertificateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.DeleteCertificateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.DeleteCertificateAsync (operations, resourceGroupName, certificateOrderName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;DeleteCertificateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-139">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-139">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="b804e-140">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-140">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="b804e-141">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-141">Name of the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-143">証明書の順序に関連付けられている証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="b804e-143">Delete the certificate associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-144">証明書の順序に関連付けられている証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="b804e-144">Delete the certificate associated with a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; GetAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; GetAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.GetAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.GetAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-145">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-146">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-146">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="b804e-147">証明書の順序の名前。</span><span class="sxs-lookup"><span data-stu-id="b804e-147">Name of the certificate order..</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-149">証明書の順序を取得します。</span><span class="sxs-lookup"><span data-stu-id="b804e-149">Get a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-150">証明書の順序を取得します。</span><span class="sxs-lookup"><span data-stu-id="b804e-150">Get a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; GetCertificateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; GetCertificateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.GetCertificateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.GetCertificateAsync (operations, resourceGroupName, certificateOrderName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;GetCertificateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-152">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-152">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="b804e-153">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-153">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="b804e-154">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-154">Name of the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-156">証明書の順序に関連付けられている証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="b804e-156">Get the certificate associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-157">証明書の順序に関連付けられている証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="b804e-157">Get the certificate associated with a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-158">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-160">サブスクリプションのすべての証明書の注文を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b804e-160">List all certificate orders in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-161">サブスクリプションのすべての証明書の注文を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b804e-161">List all certificate orders in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-162">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-163">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-163">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-165">リソース グループ内の証明書の注文を取得します。</span><span class="sxs-lookup"><span data-stu-id="b804e-165">Get certificate orders in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-166">リソース グループ内の証明書の注文を取得します。</span><span class="sxs-lookup"><span data-stu-id="b804e-166">Get certificate orders in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-167">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b804e-168">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="b804e-168">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-169">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-170">リソース グループ内の証明書の注文を取得します。</span><span class="sxs-lookup"><span data-stu-id="b804e-170">Get certificate orders in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-171">リソース グループ内の証明書の注文を取得します。</span><span class="sxs-lookup"><span data-stu-id="b804e-171">Get certificate orders in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCertificatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt; ListCertificatesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt; ListCertificatesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCertificatesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListCertificatesAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-173">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-173">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="b804e-174">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-174">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-175">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-176">証明書の順序に関連付けられているすべての証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b804e-176">List all certificates associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-177">証明書の順序に関連付けられているすべての証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b804e-177">List all certificates associated with a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCertificatesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt; ListCertificatesNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt; ListCertificatesNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCertificatesNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListCertificatesNextAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-178">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-178">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b804e-179">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="b804e-179">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-181">証明書の順序に関連付けられているすべての証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b804e-181">List all certificates associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-182">証明書の順序に関連付けられているすべての証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b804e-182">List all certificates associated with a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListNextAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-183">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b804e-184">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="b804e-184">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-185">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-186">サブスクリプションのすべての証明書の注文を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b804e-186">List all certificate orders in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-187">サブスクリプションのすべての証明書の注文を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b804e-187">List all certificate orders in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReissueAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ReissueAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.ReissueCertificateOrderRequestInner reissueCertificateOrderRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ReissueAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.ReissueCertificateOrderRequestInner reissueCertificateOrderRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ReissueAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ReissueCertificateOrderRequestInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReissueAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.ReissueCertificateOrderRequestInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ReissueAsync (operations, resourceGroupName, certificateOrderName, reissueCertificateOrderRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ReissueAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="reissueCertificateOrderRequest" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ReissueCertificateOrderRequestInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-188">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-188">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-189">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-189">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="b804e-190">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-190">Name of the certificate order.</span></span>
            </param>
        <param name="reissueCertificateOrderRequest">
            <span data-ttu-id="b804e-191">パラメーター、再実行してください。</span><span class="sxs-lookup"><span data-stu-id="b804e-191">Parameters for the reissue.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-193">既存の証明書の順序を再実行します。</span><span class="sxs-lookup"><span data-stu-id="b804e-193">Reissue an existing certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-194">既存の証明書の順序を再実行します。</span><span class="sxs-lookup"><span data-stu-id="b804e-194">Reissue an existing certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RenewAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.RenewCertificateOrderRequestInner renewCertificateOrderRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RenewAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.RenewCertificateOrderRequestInner renewCertificateOrderRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RenewAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.RenewCertificateOrderRequestInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RenewAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.RenewCertificateOrderRequestInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RenewAsync (operations, resourceGroupName, certificateOrderName, renewCertificateOrderRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;RenewAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="renewCertificateOrderRequest" Type="Microsoft.Azure.Management.AppService.Fluent.Models.RenewCertificateOrderRequestInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-196">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-196">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="b804e-197">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-197">Name of the certificate order.</span></span>
            </param>
        <param name="renewCertificateOrderRequest">
            <span data-ttu-id="b804e-198">パラメーターを更新します。</span><span class="sxs-lookup"><span data-stu-id="b804e-198">Renew parameters</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-200">既存の証明書の順序を更新します。</span><span class="sxs-lookup"><span data-stu-id="b804e-200">Renew an existing certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-201">既存の証明書の順序を更新します。</span><span class="sxs-lookup"><span data-stu-id="b804e-201">Renew an existing certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResendEmailAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResendEmailAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResendEmailAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ResendEmailAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResendEmailAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ResendEmailAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ResendEmailAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-202">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-202">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-203">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-203">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="b804e-204">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-204">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-205">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-205">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-206">証明書の電子メールの再送信します。</span><span class="sxs-lookup"><span data-stu-id="b804e-206">Resend certificate email.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-207">証明書の電子メールの再送信します。</span><span class="sxs-lookup"><span data-stu-id="b804e-207">Resend certificate email.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResendRequestEmailsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResendRequestEmailsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner nameIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResendRequestEmailsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner nameIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ResendRequestEmailsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResendRequestEmailsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ResendRequestEmailsAsync (operations, resourceGroupName, certificateOrderName, nameIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ResendRequestEmailsAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="nameIdentifier" Type="Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="certificateOrderName">To be added.</param>
        <param name="nameIdentifier">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveCertificateActionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner&gt;&gt; RetrieveCertificateActionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner&gt;&gt; RetrieveCertificateActionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateActionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RetrieveCertificateActionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateActionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;RetrieveCertificateActionsAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-209">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-209">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="b804e-210">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-210">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-211">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-211">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-212">証明書の操作の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b804e-212">Retrieve the list of certificate actions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-213">証明書の操作の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b804e-213">Retrieve the list of certificate actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveCertificateEmailHistoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateEmailInner&gt;&gt; RetrieveCertificateEmailHistoryAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateEmailInner&gt;&gt; RetrieveCertificateEmailHistoryAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateEmailHistoryAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RetrieveCertificateEmailHistoryAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateEmailInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateEmailHistoryAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;RetrieveCertificateEmailHistoryAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateEmailInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-214">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-215">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-215">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="b804e-216">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-216">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-217">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-218">電子メールの履歴を取得します。</span><span class="sxs-lookup"><span data-stu-id="b804e-218">Retrieve email history.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-219">電子メールの履歴を取得します。</span><span class="sxs-lookup"><span data-stu-id="b804e-219">Retrieve email history.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveSiteSealAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealInner&gt; RetrieveSiteSealAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealRequestInner siteSealRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealInner&gt; RetrieveSiteSealAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealRequestInner siteSealRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveSiteSealAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealRequestInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RetrieveSiteSealAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealRequestInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveSiteSealAsync (operations, resourceGroupName, certificateOrderName, siteSealRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;RetrieveSiteSealAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="siteSealRequest" Type="Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealRequestInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-220">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-220">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-221">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-221">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="b804e-222">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-222">Name of the certificate order.</span></span>
            </param>
        <param name="siteSealRequest">
            <span data-ttu-id="b804e-223">サイトでは、要求を封印します。</span><span class="sxs-lookup"><span data-stu-id="b804e-223">Site seal request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-224">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-224">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-225">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="b804e-225">Verify domain ownership for this certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-226">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="b804e-226">Verify domain ownership for this certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidatePurchaseInformationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ValidatePurchaseInformationAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner appServiceCertificateOrder, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ValidatePurchaseInformationAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner appServiceCertificateOrder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ValidatePurchaseInformationAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidatePurchaseInformationAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ValidatePurchaseInformationAsync (operations, appServiceCertificateOrder, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ValidatePurchaseInformationAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="appServiceCertificateOrder" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-227">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-227">The operations group for this extension method.</span></span>
            </param>
        <param name="appServiceCertificateOrder">
            <span data-ttu-id="b804e-228">証明書の順序の情報です。</span><span class="sxs-lookup"><span data-stu-id="b804e-228">Information for a certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-229">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-229">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-230">証明書の順序の情報を検証します。</span><span class="sxs-lookup"><span data-stu-id="b804e-230">Validate information for a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-231">証明書の順序の情報を検証します。</span><span class="sxs-lookup"><span data-stu-id="b804e-231">Validate information for a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnershipAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task VerifyDomainOwnershipAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task VerifyDomainOwnershipAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.VerifyDomainOwnershipAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyDomainOwnershipAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.VerifyDomainOwnershipAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;VerifyDomainOwnershipAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b804e-232">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b804e-232">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b804e-233">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-233">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="b804e-234">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="b804e-234">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b804e-235">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b804e-235">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b804e-236">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="b804e-236">Verify domain ownership for this certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b804e-237">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="b804e-237">Verify domain ownership for this certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>