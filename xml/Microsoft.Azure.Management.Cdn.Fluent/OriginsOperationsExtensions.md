<Type Name="OriginsOperationsExtensions" FullName="Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class OriginsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit OriginsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module OriginsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type OriginsOperationsExtensions = class" />
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
            <span data-ttu-id="6d358-101">OriginsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="6d358-101">Extension methods for OriginsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string resourceGroupName, string profileName, string endpointName, string originName, Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner originUpdateProperties, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string resourceGroupName, string profileName, string endpointName, string originName, class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner originUpdateProperties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations * string * string * string * string * Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, profileName, endpointName, originName, originUpdateProperties, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="originName" Type="System.String" />
        <Parameter Name="originUpdateProperties" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d358-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6d358-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6d358-103">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="6d358-103">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="6d358-104">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="6d358-104">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="6d358-105">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="6d358-105">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="originName">
            <span data-ttu-id="6d358-106">これは、エンドポイント内で一意で元の名前です。</span><span class="sxs-lookup"><span data-stu-id="6d358-106">Name of the origin which is unique within the endpoint.</span></span>
            </param>
        <param name="originUpdateProperties">
            <span data-ttu-id="6d358-107">配信元のプロパティ</span><span class="sxs-lookup"><span data-stu-id="6d358-107">Origin properties</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6d358-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6d358-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d358-109">エンドポイント内の既存の配信元を更新します。</span><span class="sxs-lookup"><span data-stu-id="6d358-109">Updates an existing origin within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt; GetAsync (this Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string resourceGroupName, string profileName, string endpointName, string originName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt; GetAsync(class Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string resourceGroupName, string profileName, string endpointName, string originName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, endpointName, originName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="originName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d358-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6d358-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6d358-111">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="6d358-111">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="6d358-112">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="6d358-112">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="6d358-113">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="6d358-113">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="originName">
            <span data-ttu-id="6d358-114">これは、エンドポイント内で一意で元の名前です。</span><span class="sxs-lookup"><span data-stu-id="6d358-114">Name of the origin which is unique within the endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6d358-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6d358-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d358-116">エンドポイント内の既存の原点を取得します。</span><span class="sxs-lookup"><span data-stu-id="6d358-116">Gets an existing origin within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt; ListByEndpointAsync (this Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt; ListByEndpointAsync(class Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.ListByEndpointAsync(Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByEndpointAsync : Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.ListByEndpointAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions/&lt;ListByEndpointAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d358-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6d358-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6d358-118">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="6d358-118">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="6d358-119">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="6d358-119">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="6d358-120">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="6d358-120">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6d358-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6d358-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d358-122">すべてのエンドポイント内の既存の origin の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="6d358-122">Lists all of the existing origins within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt; ListByEndpointNextAsync (this Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt; ListByEndpointNextAsync(class Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.ListByEndpointNextAsync(Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByEndpointNextAsync : Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.ListByEndpointNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions/&lt;ListByEndpointNextAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d358-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6d358-123">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6d358-124">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="6d358-124">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6d358-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6d358-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d358-126">すべてのエンドポイント内の既存の origin の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="6d358-126">Lists all of the existing origins within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt; UpdateAsync (this Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string resourceGroupName, string profileName, string endpointName, string originName, Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner originUpdateProperties, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt; UpdateAsync(class Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations operations, string resourceGroupName, string profileName, string endpointName, string originName, class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner originUpdateProperties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations * string * string * string * string * Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions.UpdateAsync (operations, resourceGroupName, profileName, endpointName, originName, originUpdateProperties, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.OriginsOperationsExtensions/&lt;UpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="originName" Type="System.String" />
        <Parameter Name="originUpdateProperties" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d358-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6d358-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6d358-128">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="6d358-128">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="6d358-129">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="6d358-129">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="6d358-130">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="6d358-130">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="originName">
            <span data-ttu-id="6d358-131">これは、エンドポイント内で一意で元の名前です。</span><span class="sxs-lookup"><span data-stu-id="6d358-131">Name of the origin which is unique within the endpoint.</span></span>
            </param>
        <param name="originUpdateProperties">
            <span data-ttu-id="6d358-132">配信元のプロパティ</span><span class="sxs-lookup"><span data-stu-id="6d358-132">Origin properties</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6d358-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6d358-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d358-134">エンドポイント内の既存の配信元を更新します。</span><span class="sxs-lookup"><span data-stu-id="6d358-134">Updates an existing origin within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>