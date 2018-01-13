<Type Name="FeaturesOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FeaturesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FeaturesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FeaturesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FeaturesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0c3ff-101">FeaturesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-101">Extension methods for FeaturesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.FeatureResult Get (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult Get(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IFeaturesOperations, resourceProviderNamespace As String, featureName As String) As FeatureResult" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.FeatureResult" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.Get (operations, resourceProviderNamespace, featureName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.FeatureResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0c3ff-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="0c3ff-103">リソース プロバイダーの名前空間の機能です。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-103">The resource provider namespace for the feature.</span></span>
            </param>
        <param name="featureName">
            <span data-ttu-id="0c3ff-104">取得する機能の名前です。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-104">The name of the feature to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0c3ff-105">プレビュー機能は、指定した名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-105">Gets the preview feature with the specified name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.GetAsync (operations, resourceProviderNamespace, featureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0c3ff-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-106">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="0c3ff-107">リソース プロバイダーの名前空間の機能です。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-107">The resource provider namespace for the feature.</span></span>
            </param>
        <param name="featureName">
            <span data-ttu-id="0c3ff-108">取得する機能の名前です。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-108">The name of the feature to get.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0c3ff-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0c3ff-110">プレビュー機能は、指定した名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-110">Gets the preview feature with the specified name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; List (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; List(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IFeaturesOperations, resourceProviderNamespace As String) As IPage(Of FeatureResult)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.List (operations, resourceProviderNamespace)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0c3ff-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="0c3ff-112">機能を取得するためのリソース プロバイダーの名前空間。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-112">The namespace of the resource provider for getting features.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0c3ff-113">サブスクリプションの AFEC から使用可能なプロバイダーの名前空間のすべてのプレビュー機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-113">Gets all the preview features in a provider namespace that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListAll (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListAll(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAll(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As IFeaturesOperations) As IPage(Of FeatureResult)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0c3ff-114">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-114">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0c3ff-115">サブスクリプションの AFEC から使用可能なすべてのプレビュー機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-115">Gets all the preview features that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;ListAllAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0c3ff-116">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-116">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0c3ff-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0c3ff-118">サブスクリプションの AFEC から使用可能なすべてのプレビュー機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-118">Gets all the preview features that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListAllNext (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListAllNext(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllNext(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As IFeaturesOperations, nextPageLink As String) As IPage(Of FeatureResult)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0c3ff-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-119">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0c3ff-120">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-120">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0c3ff-121">サブスクリプションの AFEC から使用可能なすべてのプレビュー機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-121">Gets all the preview features that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;ListAllNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0c3ff-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-122">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0c3ff-123">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-123">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0c3ff-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0c3ff-125">サブスクリプションの AFEC から使用可能なすべてのプレビュー機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-125">Gets all the preview features that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListAsync (operations, resourceProviderNamespace, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0c3ff-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="0c3ff-127">機能を取得するためのリソース プロバイダーの名前空間。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-127">The namespace of the resource provider for getting features.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0c3ff-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0c3ff-129">サブスクリプションの AFEC から使用可能なプロバイダーの名前空間のすべてのプレビュー機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-129">Gets all the preview features in a provider namespace that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IFeaturesOperations, nextPageLink As String) As IPage(Of FeatureResult)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0c3ff-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-130">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0c3ff-131">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-131">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0c3ff-132">サブスクリプションの AFEC から使用可能なプロバイダーの名前空間のすべてのプレビュー機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-132">Gets all the preview features in a provider namespace that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0c3ff-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-133">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0c3ff-134">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-134">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0c3ff-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0c3ff-136">サブスクリプションの AFEC から使用可能なプロバイダーの名前空間のすべてのプレビュー機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-136">Gets all the preview features in a provider namespace that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Register">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.FeatureResult Register (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult Register(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.Register(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Register (operations As IFeaturesOperations, resourceProviderNamespace As String, featureName As String) As FeatureResult" />
      <MemberSignature Language="F#" Value="static member Register : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.FeatureResult" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.Register (operations, resourceProviderNamespace, featureName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.FeatureResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0c3ff-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="0c3ff-138">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-138">The namespace of the resource provider.</span></span>
            </param>
        <param name="featureName">
            <span data-ttu-id="0c3ff-139">登録する機能の名前です。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-139">The name of the feature to register.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0c3ff-140">サブスクリプションのプレビュー機能を登録します。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-140">Registers the preview feature for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; RegisterAsync (this Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt; RegisterAsync(class Microsoft.Azure.Management.ResourceManager.IFeaturesOperations operations, string resourceProviderNamespace, string featureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.RegisterAsync(Microsoft.Azure.Management.ResourceManager.IFeaturesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegisterAsync : Microsoft.Azure.Management.ResourceManager.IFeaturesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions.RegisterAsync (operations, resourceProviderNamespace, featureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.FeaturesOperationsExtensions/&lt;RegisterAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.FeatureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0c3ff-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="0c3ff-142">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-142">The namespace of the resource provider.</span></span>
            </param>
        <param name="featureName">
            <span data-ttu-id="0c3ff-143">登録する機能の名前です。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-143">The name of the feature to register.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0c3ff-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0c3ff-145">サブスクリプションのプレビュー機能を登録します。</span><span class="sxs-lookup"><span data-stu-id="0c3ff-145">Registers the preview feature for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>