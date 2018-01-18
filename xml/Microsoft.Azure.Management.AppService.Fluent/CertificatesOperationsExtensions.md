<Type Name="CertificatesOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CertificatesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CertificatesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CertificatesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CertificatesOperationsExtensions = class" />
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
            <span data-ttu-id="816b4-101">CertificatesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="816b4-101">Extension methods for CertificatesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner certificateEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner certificateEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, name, certificateEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="certificateEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="816b4-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="816b4-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="816b4-103">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="816b4-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="816b4-104">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="816b4-104">Name of the certificate.</span></span>
            </param>
        <param name="certificateEnvelope">
            <span data-ttu-id="816b4-105">既に存在する場合、証明書の詳細です。</span><span class="sxs-lookup"><span data-stu-id="816b4-105">Details of certificate, if it exists already.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="816b4-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="816b4-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="816b4-107">作成または証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="816b4-107">Create or update a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="816b4-108">作成または証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="816b4-108">Create or update a certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions/&lt;DeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="816b4-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="816b4-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="816b4-110">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="816b4-110">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="816b4-111">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="816b4-111">Name of the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="816b4-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="816b4-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="816b4-113">証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="816b4-113">Delete a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="816b4-114">証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="816b4-114">Delete a certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt; GetAsync (this Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt; GetAsync(class Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.GetAsync(Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="816b4-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="816b4-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="816b4-116">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="816b4-116">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="816b4-117">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="816b4-117">Name of the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="816b4-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="816b4-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="816b4-119">証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="816b4-119">Get a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="816b4-120">証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="816b4-120">Get a certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="816b4-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="816b4-121">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="816b4-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="816b4-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="816b4-123">サブスクリプションのすべての証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="816b4-123">Get all certificates for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="816b4-124">サブスクリプションのすべての証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="816b4-124">Get all certificates for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="816b4-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="816b4-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="816b4-126">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="816b4-126">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="816b4-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="816b4-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="816b4-128">リソース グループ内のすべての証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="816b4-128">Get all certificates in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="816b4-129">リソース グループ内のすべての証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="816b4-129">Get all certificates in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="816b4-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="816b4-130">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="816b4-131">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="816b4-131">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="816b4-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="816b4-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="816b4-133">リソース グループ内のすべての証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="816b4-133">Get all certificates in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="816b4-134">リソース グループ内のすべての証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="816b4-134">Get all certificates in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="816b4-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="816b4-135">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="816b4-136">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="816b4-136">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="816b4-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="816b4-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="816b4-138">サブスクリプションのすべての証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="816b4-138">Get all certificates for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="816b4-139">サブスクリプションのすべての証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="816b4-139">Get all certificates for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt; UpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner certificateEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt; UpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner certificateEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions.UpdateAsync (operations, resourceGroupName, name, certificateEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.CertificatesOperationsExtensions/&lt;UpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="certificateEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="816b4-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="816b4-140">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="816b4-141">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="816b4-141">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="816b4-142">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="816b4-142">Name of the certificate.</span></span>
            </param>
        <param name="certificateEnvelope">
            <span data-ttu-id="816b4-143">既に存在する場合、証明書の詳細です。</span><span class="sxs-lookup"><span data-stu-id="816b4-143">Details of certificate, if it exists already.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="816b4-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="816b4-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="816b4-145">作成または証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="816b4-145">Create or update a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="816b4-146">作成または証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="816b4-146">Create or update a certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>