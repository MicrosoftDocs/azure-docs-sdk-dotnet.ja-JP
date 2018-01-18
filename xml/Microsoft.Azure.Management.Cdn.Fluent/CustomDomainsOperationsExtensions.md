<Type Name="CustomDomainsOperationsExtensions" FullName="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CustomDomainsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CustomDomainsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CustomDomainsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CustomDomainsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5433f-101">CustomDomainsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="5433f-101">Extension methods for CustomDomainsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; BeginCreateAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; BeginCreateAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, hostName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;BeginCreateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5433f-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5433f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5433f-103">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-103">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="5433f-104">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-104">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="5433f-105">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-105">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="5433f-106">エンドポイント内でカスタム ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-106">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="hostName">
            <span data-ttu-id="5433f-107">カスタム ドメインのホスト名。</span><span class="sxs-lookup"><span data-stu-id="5433f-107">The host name of the custom domain.</span></span> <span data-ttu-id="5433f-108">ドメイン名である必要があります。</span><span class="sxs-lookup"><span data-stu-id="5433f-108">Must be a domain name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5433f-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5433f-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5433f-110">エンドポイント内の新しいカスタム ドメインを作成します。</span><span class="sxs-lookup"><span data-stu-id="5433f-110">Creates a new custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5433f-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5433f-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5433f-112">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-112">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="5433f-113">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-113">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="5433f-114">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-114">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="5433f-115">エンドポイント内でカスタム ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-115">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5433f-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5433f-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5433f-117">エンドポイント内の既存のカスタム ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="5433f-117">Deletes an existing custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; CreateAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; CreateAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.CreateAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, hostName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;CreateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5433f-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5433f-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5433f-119">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-119">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="5433f-120">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-120">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="5433f-121">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-121">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="5433f-122">エンドポイント内でカスタム ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-122">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="hostName">
            <span data-ttu-id="5433f-123">カスタム ドメインのホスト名。</span><span class="sxs-lookup"><span data-stu-id="5433f-123">The host name of the custom domain.</span></span> <span data-ttu-id="5433f-124">ドメイン名である必要があります。</span><span class="sxs-lookup"><span data-stu-id="5433f-124">Must be a domain name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5433f-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5433f-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5433f-126">エンドポイント内の新しいカスタム ドメインを作成します。</span><span class="sxs-lookup"><span data-stu-id="5433f-126">Creates a new custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; DeleteAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; DeleteAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.DeleteAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5433f-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5433f-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5433f-128">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-128">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="5433f-129">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-129">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="5433f-130">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-130">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="5433f-131">エンドポイント内でカスタム ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-131">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5433f-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5433f-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5433f-133">エンドポイント内の既存のカスタム ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="5433f-133">Deletes an existing custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableCustomHttpsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; DisableCustomHttpsAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; DisableCustomHttpsAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.DisableCustomHttpsAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableCustomHttpsAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.DisableCustomHttpsAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;DisableCustomHttpsAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5433f-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5433f-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5433f-135">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-135">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="5433f-136">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-136">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="5433f-137">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-137">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="5433f-138">エンドポイント内でカスタム ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-138">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5433f-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5433f-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5433f-140">カスタム ドメインの https 配信を無効にします。</span><span class="sxs-lookup"><span data-stu-id="5433f-140">Disable https delivery of the custom domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableCustomHttpsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; EnableCustomHttpsAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; EnableCustomHttpsAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.EnableCustomHttpsAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableCustomHttpsAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.EnableCustomHttpsAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;EnableCustomHttpsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5433f-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5433f-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5433f-142">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-142">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="5433f-143">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-143">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="5433f-144">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-144">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="5433f-145">エンドポイント内でカスタム ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-145">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5433f-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5433f-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5433f-147">カスタム ドメインの https 配信を有効にします。</span><span class="sxs-lookup"><span data-stu-id="5433f-147">Enable https delivery of the custom domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; GetAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; GetAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5433f-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5433f-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5433f-149">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-149">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="5433f-150">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-150">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="5433f-151">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-151">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="5433f-152">エンドポイント内でカスタム ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-152">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5433f-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5433f-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5433f-154">エンドポイント内の既存のカスタム ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="5433f-154">Gets an exisitng custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; ListByEndpointAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; ListByEndpointAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.ListByEndpointAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByEndpointAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.ListByEndpointAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;ListByEndpointAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5433f-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5433f-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5433f-156">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-156">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="5433f-157">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-157">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="5433f-158">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="5433f-158">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5433f-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5433f-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5433f-160">すべてのエンドポイント内の既存のカスタム ドメインの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="5433f-160">Lists all of the existing custom domains within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; ListByEndpointNextAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; ListByEndpointNextAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.ListByEndpointNextAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByEndpointNextAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.ListByEndpointNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;ListByEndpointNextAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5433f-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5433f-161">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="5433f-162">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5433f-162">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5433f-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5433f-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5433f-164">すべてのエンドポイント内の既存のカスタム ドメインの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="5433f-164">Lists all of the existing custom domains within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>