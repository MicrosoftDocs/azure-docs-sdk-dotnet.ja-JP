<Type Name="FeaturesOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FeaturesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FeaturesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FeaturesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FeaturesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5ec11-101">FeaturesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="5ec11-101">Extension methods for FeaturesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations operations, string resourceProviderNamespace, string featureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations operations, string resourceProviderNamespace, string featureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions.GetAsync (operations, resourceProviderNamespace, featureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ec11-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ec11-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="5ec11-103">リソース プロバイダーの名前空間の機能です。</span><span class="sxs-lookup"><span data-stu-id="5ec11-103">The resource provider namespace for the feature.</span></span>
            </param>
        <param name="featureName">
            <span data-ttu-id="5ec11-104">取得する機能の名前です。</span><span class="sxs-lookup"><span data-stu-id="5ec11-104">The name of the feature to get.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5ec11-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5ec11-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ec11-106">プレビュー機能は、指定した名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="5ec11-106">Gets the preview feature with the specified name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions/&lt;ListAllAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ec11-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ec11-107">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5ec11-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5ec11-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ec11-109">サブスクリプションの AFEC から使用可能なすべてのプレビュー機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="5ec11-109">Gets all the preview features that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions/&lt;ListAllNextAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ec11-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ec11-110">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="5ec11-111">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5ec11-111">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5ec11-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5ec11-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ec11-113">サブスクリプションの AFEC から使用可能なすべてのプレビュー機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="5ec11-113">Gets all the preview features that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations operations, string resourceProviderNamespace, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations operations, string resourceProviderNamespace, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions.ListAsync (operations, resourceProviderNamespace, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ec11-114">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ec11-114">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="5ec11-115">機能を取得するためのリソース プロバイダーの名前空間。</span><span class="sxs-lookup"><span data-stu-id="5ec11-115">The namespace of the resource provider for getting features.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5ec11-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5ec11-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ec11-117">サブスクリプションの AFEC から使用可能なプロバイダーの名前空間のすべてのプレビュー機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="5ec11-117">Gets all the preview features in a provider namespace that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ec11-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ec11-118">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="5ec11-119">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5ec11-119">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5ec11-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5ec11-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ec11-121">サブスクリプションの AFEC から使用可能なプロバイダーの名前空間のすべてのプレビュー機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="5ec11-121">Gets all the preview features in a provider namespace that are available through AFEC for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt; RegisterAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations operations, string resourceProviderNamespace, string featureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt; RegisterAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations operations, string resourceProviderNamespace, string featureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions.RegisterAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegisterAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions.RegisterAsync (operations, resourceProviderNamespace, featureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.FeaturesOperationsExtensions/&lt;RegisterAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.FeatureResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IFeaturesOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ec11-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ec11-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="5ec11-123">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="5ec11-123">The namespace of the resource provider.</span></span>
            </param>
        <param name="featureName">
            <span data-ttu-id="5ec11-124">登録する機能の名前です。</span><span class="sxs-lookup"><span data-stu-id="5ec11-124">The name of the feature to register.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5ec11-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5ec11-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ec11-126">サブスクリプションのプレビュー機能を登録します。</span><span class="sxs-lookup"><span data-stu-id="5ec11-126">Registers the preview feature for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>