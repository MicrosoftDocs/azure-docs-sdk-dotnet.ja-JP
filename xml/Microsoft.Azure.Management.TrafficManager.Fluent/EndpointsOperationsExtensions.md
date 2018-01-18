<Type Name="EndpointsOperationsExtensions" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class EndpointsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EndpointsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EndpointsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type EndpointsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e3e76-101">EndpointsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="e3e76-101">Extension methods for EndpointsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations * string * string * string * string * Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, profileName, endpointType, endpointName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e3e76-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e3e76-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e3e76-103">作成または更新する Traffic Manager エンドポイントを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e3e76-103">The name of the resource group containing the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="e3e76-104">Traffic Manager プロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="e3e76-104">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="e3e76-105">作成または更新する Traffic Manager エンドポイントの型。</span><span class="sxs-lookup"><span data-stu-id="e3e76-105">The type of the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="e3e76-106">作成または更新する Traffic Manager エンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="e3e76-106">The name of the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e3e76-107">CreateOrUpdate 操作に指定された Traffic Manager エンドポイント パラメーター。</span><span class="sxs-lookup"><span data-stu-id="e3e76-107">The Traffic Manager endpoint parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e3e76-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e3e76-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e3e76-109">作成または Traffic Manager エンドポイントを更新します。</span><span class="sxs-lookup"><span data-stu-id="e3e76-109">Create or update a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt; DeleteAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt; DeleteAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.DeleteAsync (operations, resourceGroupName, profileName, endpointType, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointType">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; GetAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; GetAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.GetAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, endpointType, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e3e76-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e3e76-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e3e76-111">Traffic Manager エンドポイントを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e3e76-111">The name of the resource group containing the Traffic Manager endpoint.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="e3e76-112">Traffic Manager プロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="e3e76-112">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="e3e76-113">Traffic Manager エンドポイントの型。</span><span class="sxs-lookup"><span data-stu-id="e3e76-113">The type of the Traffic Manager endpoint.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="e3e76-114">Traffic Manager エンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="e3e76-114">The name of the Traffic Manager endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e3e76-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e3e76-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e3e76-116">Traffic Manager エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="e3e76-116">Gets a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; UpdateAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; UpdateAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations * string * string * string * string * Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions.UpdateAsync (operations, resourceGroupName, profileName, endpointType, endpointName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.EndpointsOperationsExtensions/&lt;UpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e3e76-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e3e76-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e3e76-118">更新する Traffic Manager エンドポイントを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e3e76-118">The name of the resource group containing the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="e3e76-119">Traffic Manager プロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="e3e76-119">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="e3e76-120">更新する Traffic Manager エンドポイントの型。</span><span class="sxs-lookup"><span data-stu-id="e3e76-120">The type of the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="e3e76-121">更新する Traffic Manager エンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="e3e76-121">The name of the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e3e76-122">更新操作に指定された Traffic Manager エンドポイントのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="e3e76-122">The Traffic Manager endpoint parameters supplied to the Update operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e3e76-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e3e76-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e3e76-124">Traffic Manager エンドポイントを更新します。</span><span class="sxs-lookup"><span data-stu-id="e3e76-124">Update a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>