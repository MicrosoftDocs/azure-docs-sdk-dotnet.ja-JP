<Type Name="ProviderOperationsExtensions" FullName="Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProviderOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProviderOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProviderOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProviderOperationsExtensions = class" />
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
            <span data-ttu-id="73a96-101">ProviderOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="73a96-101">Extension methods for ProviderOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAvailableStacks">
      <MemberSignature Language="C#" Value="public static object GetAvailableStacks (this Microsoft.Azure.Management.WebSites.IProviderOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object GetAvailableStacks(class Microsoft.Azure.Management.WebSites.IProviderOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions.GetAvailableStacks(Microsoft.Azure.Management.WebSites.IProviderOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAvailableStacks (operations As IProviderOperations) As Object" />
      <MemberSignature Language="F#" Value="static member GetAvailableStacks : Microsoft.Azure.Management.WebSites.IProviderOperations -&gt; obj" Usage="Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions.GetAvailableStacks operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IProviderOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="73a96-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="73a96-102">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73a96-103">使用可能なアプリケーション フレームワークと、それらのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="73a96-103">Get available application frameworks and their versions</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73a96-104">使用可能なアプリケーション フレームワークと、それらのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="73a96-104">Get available application frameworks and their versions</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAvailableStacksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; GetAvailableStacksAsync (this Microsoft.Azure.Management.WebSites.IProviderOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; GetAvailableStacksAsync(class Microsoft.Azure.Management.WebSites.IProviderOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions.GetAvailableStacksAsync(Microsoft.Azure.Management.WebSites.IProviderOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAvailableStacksAsync : Microsoft.Azure.Management.WebSites.IProviderOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions.GetAvailableStacksAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions/&lt;GetAvailableStacksAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IProviderOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="73a96-105">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="73a96-105">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73a96-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="73a96-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73a96-107">使用可能なアプリケーション フレームワークと、それらのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="73a96-107">Get available application frameworks and their versions</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73a96-108">使用可能なアプリケーション フレームワークと、それらのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="73a96-108">Get available application frameworks and their versions</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAvailableStacksOnPrem">
      <MemberSignature Language="C#" Value="public static object GetAvailableStacksOnPrem (this Microsoft.Azure.Management.WebSites.IProviderOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object GetAvailableStacksOnPrem(class Microsoft.Azure.Management.WebSites.IProviderOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions.GetAvailableStacksOnPrem(Microsoft.Azure.Management.WebSites.IProviderOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAvailableStacksOnPrem (operations As IProviderOperations) As Object" />
      <MemberSignature Language="F#" Value="static member GetAvailableStacksOnPrem : Microsoft.Azure.Management.WebSites.IProviderOperations -&gt; obj" Usage="Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions.GetAvailableStacksOnPrem operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IProviderOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="73a96-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="73a96-109">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73a96-110">使用可能なアプリケーション フレームワークと、それらのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="73a96-110">Get available application frameworks and their versions</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73a96-111">使用可能なアプリケーション フレームワークと、それらのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="73a96-111">Get available application frameworks and their versions</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAvailableStacksOnPremAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; GetAvailableStacksOnPremAsync (this Microsoft.Azure.Management.WebSites.IProviderOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; GetAvailableStacksOnPremAsync(class Microsoft.Azure.Management.WebSites.IProviderOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions.GetAvailableStacksOnPremAsync(Microsoft.Azure.Management.WebSites.IProviderOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAvailableStacksOnPremAsync : Microsoft.Azure.Management.WebSites.IProviderOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions.GetAvailableStacksOnPremAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions/&lt;GetAvailableStacksOnPremAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IProviderOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="73a96-112">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="73a96-112">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73a96-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="73a96-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73a96-114">使用可能なアプリケーション フレームワークと、それらのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="73a96-114">Get available application frameworks and their versions</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73a96-115">使用可能なアプリケーション フレームワークと、それらのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="73a96-115">Get available application frameworks and their versions</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOperations">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmOperationDescription&gt; ListOperations (this Microsoft.Azure.Management.WebSites.IProviderOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmOperationDescription&gt; ListOperations(class Microsoft.Azure.Management.WebSites.IProviderOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions.ListOperations(Microsoft.Azure.Management.WebSites.IProviderOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListOperations (operations As IProviderOperations) As IPage(Of CsmOperationDescription)" />
      <MemberSignature Language="F#" Value="static member ListOperations : Microsoft.Azure.Management.WebSites.IProviderOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmOperationDescription&gt;" Usage="Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions.ListOperations operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmOperationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IProviderOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="73a96-116">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="73a96-116">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73a96-117">Microsoft.Web リソース プロバイダーの使用可能なすべての操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="73a96-117">Gets all available operations for the Microsoft.Web resource provider.</span></span> <span data-ttu-id="73a96-118">また、リソース メトリックの定義</span><span class="sxs-lookup"><span data-stu-id="73a96-118">Also exposes resource metric definitions</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73a96-119">Microsoft.Web リソース プロバイダーの使用可能なすべての操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="73a96-119">Gets all available operations for the Microsoft.Web resource provider.</span></span> <span data-ttu-id="73a96-120">また、リソース メトリックの定義</span><span class="sxs-lookup"><span data-stu-id="73a96-120">Also exposes resource metric definitions</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOperationsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmOperationDescription&gt;&gt; ListOperationsAsync (this Microsoft.Azure.Management.WebSites.IProviderOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmOperationDescription&gt;&gt; ListOperationsAsync(class Microsoft.Azure.Management.WebSites.IProviderOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions.ListOperationsAsync(Microsoft.Azure.Management.WebSites.IProviderOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOperationsAsync : Microsoft.Azure.Management.WebSites.IProviderOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmOperationDescription&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions.ListOperationsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions/&lt;ListOperationsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmOperationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IProviderOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="73a96-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="73a96-121">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73a96-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="73a96-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73a96-123">Microsoft.Web リソース プロバイダーの使用可能なすべての操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="73a96-123">Gets all available operations for the Microsoft.Web resource provider.</span></span> <span data-ttu-id="73a96-124">また、リソース メトリックの定義</span><span class="sxs-lookup"><span data-stu-id="73a96-124">Also exposes resource metric definitions</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73a96-125">Microsoft.Web リソース プロバイダーの使用可能なすべての操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="73a96-125">Gets all available operations for the Microsoft.Web resource provider.</span></span> <span data-ttu-id="73a96-126">また、リソース メトリックの定義</span><span class="sxs-lookup"><span data-stu-id="73a96-126">Also exposes resource metric definitions</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOperationsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmOperationDescription&gt; ListOperationsNext (this Microsoft.Azure.Management.WebSites.IProviderOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmOperationDescription&gt; ListOperationsNext(class Microsoft.Azure.Management.WebSites.IProviderOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions.ListOperationsNext(Microsoft.Azure.Management.WebSites.IProviderOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListOperationsNext (operations As IProviderOperations, nextPageLink As String) As IPage(Of CsmOperationDescription)" />
      <MemberSignature Language="F#" Value="static member ListOperationsNext : Microsoft.Azure.Management.WebSites.IProviderOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmOperationDescription&gt;" Usage="Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions.ListOperationsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmOperationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IProviderOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="73a96-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="73a96-127">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="73a96-128">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="73a96-128">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73a96-129">Microsoft.Web リソース プロバイダーの使用可能なすべての操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="73a96-129">Gets all available operations for the Microsoft.Web resource provider.</span></span> <span data-ttu-id="73a96-130">また、リソース メトリックの定義</span><span class="sxs-lookup"><span data-stu-id="73a96-130">Also exposes resource metric definitions</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73a96-131">Microsoft.Web リソース プロバイダーの使用可能なすべての操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="73a96-131">Gets all available operations for the Microsoft.Web resource provider.</span></span> <span data-ttu-id="73a96-132">また、リソース メトリックの定義</span><span class="sxs-lookup"><span data-stu-id="73a96-132">Also exposes resource metric definitions</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOperationsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmOperationDescription&gt;&gt; ListOperationsNextAsync (this Microsoft.Azure.Management.WebSites.IProviderOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmOperationDescription&gt;&gt; ListOperationsNextAsync(class Microsoft.Azure.Management.WebSites.IProviderOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions.ListOperationsNextAsync(Microsoft.Azure.Management.WebSites.IProviderOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOperationsNextAsync : Microsoft.Azure.Management.WebSites.IProviderOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmOperationDescription&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions.ListOperationsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.ProviderOperationsExtensions/&lt;ListOperationsNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmOperationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IProviderOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="73a96-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="73a96-133">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="73a96-134">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="73a96-134">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73a96-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="73a96-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73a96-136">Microsoft.Web リソース プロバイダーの使用可能なすべての操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="73a96-136">Gets all available operations for the Microsoft.Web resource provider.</span></span> <span data-ttu-id="73a96-137">また、リソース メトリックの定義</span><span class="sxs-lookup"><span data-stu-id="73a96-137">Also exposes resource metric definitions</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73a96-138">Microsoft.Web リソース プロバイダーの使用可能なすべての操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="73a96-138">Gets all available operations for the Microsoft.Web resource provider.</span></span> <span data-ttu-id="73a96-139">また、リソース メトリックの定義</span><span class="sxs-lookup"><span data-stu-id="73a96-139">Also exposes resource metric definitions</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>