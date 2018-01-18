<Type Name="ApplicationGatewaysOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ApplicationGatewaysOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ApplicationGatewaysOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ApplicationGatewaysOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ApplicationGatewaysOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="da554-101">ApplicationGatewaysOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="da554-101">Extension methods for ApplicationGatewaysOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BackendHealthAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthInner&gt; BackendHealthAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthInner&gt; BackendHealthAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BackendHealthAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BackendHealthAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BackendHealthAsync (operations, resourceGroupName, applicationGatewayName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;BackendHealthAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da554-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da554-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da554-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-103">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="da554-104">アプリケーション ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-104">The name of the application gateway.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="da554-105">BackendAddressPool とバックエンドの正常性で参照されている BackendHttpSettings を展開します。</span><span class="sxs-lookup"><span data-stu-id="da554-105">Expands BackendAddressPool and BackendHttpSettings referenced in backend health.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da554-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da554-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da554-107">リソース グループ内の指定したアプリケーション ゲートウェイのバックエンド正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="da554-107">Gets the backend health of the specified application gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginBackendHealthAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthInner&gt; BeginBackendHealthAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthInner&gt; BeginBackendHealthAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginBackendHealthAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginBackendHealthAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginBackendHealthAsync (operations, resourceGroupName, applicationGatewayName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;BeginBackendHealthAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHealthInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da554-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da554-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da554-109">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-109">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="da554-110">アプリケーション ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-110">The name of the application gateway.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="da554-111">BackendAddressPool とバックエンドの正常性で参照されている BackendHttpSettings を展開します。</span><span class="sxs-lookup"><span data-stu-id="da554-111">Expands BackendAddressPool and BackendHttpSettings referenced in backend health.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da554-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da554-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da554-113">リソース グループ内の指定したアプリケーション ゲートウェイのバックエンド正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="da554-113">Gets the backend health of the specified application gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, applicationGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da554-114">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da554-114">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da554-115">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-115">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="da554-116">アプリケーション ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-116">The name of the application gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="da554-117">作成または更新アプリケーション ゲートウェイの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="da554-117">Parameters supplied to the create or update application gateway operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da554-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da554-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da554-119">作成するか、指定したアプリケーション ゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="da554-119">Creates or updates the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;BeginDeleteAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da554-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da554-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da554-121">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-121">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="da554-122">アプリケーション ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-122">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da554-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da554-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da554-124">指定したアプリケーション ゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="da554-124">Deletes the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStartAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStartAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginStartAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;BeginStartAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da554-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da554-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da554-126">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-126">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="da554-127">アプリケーション ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-127">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da554-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da554-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da554-129">指定したアプリケーション ゲートウェイを開始します。</span><span class="sxs-lookup"><span data-stu-id="da554-129">Starts the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStopAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStopAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginStopAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStopAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.BeginStopAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;BeginStopAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da554-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da554-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da554-131">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-131">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="da554-132">アプリケーション ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-132">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da554-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da554-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da554-134">リソース グループ内の指定したアプリケーション ゲートウェイを停止します。</span><span class="sxs-lookup"><span data-stu-id="da554-134">Stops the specified application gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, applicationGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da554-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da554-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da554-136">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-136">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="da554-137">アプリケーション ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-137">The name of the application gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="da554-138">作成または更新アプリケーション ゲートウェイの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="da554-138">Parameters supplied to the create or update application gateway operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da554-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da554-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da554-140">作成するか、指定したアプリケーション ゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="da554-140">Creates or updates the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.DeleteAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da554-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da554-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da554-142">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-142">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="da554-143">アプリケーション ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-143">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da554-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da554-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da554-145">指定したアプリケーション ゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="da554-145">Deletes the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.GetAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da554-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da554-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da554-147">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-147">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="da554-148">アプリケーション ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-148">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da554-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da554-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da554-150">指定したアプリケーション ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="da554-150">Gets the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSslPredefinedPolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt; GetSslPredefinedPolicyAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string predefinedPolicyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt; GetSslPredefinedPolicyAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string predefinedPolicyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.GetSslPredefinedPolicyAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSslPredefinedPolicyAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.GetSslPredefinedPolicyAsync (operations, predefinedPolicyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;GetSslPredefinedPolicyAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="predefinedPolicyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="predefinedPolicyName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;ListAllAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da554-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da554-151">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da554-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da554-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da554-153">サブスクリプションのすべてのアプリケーション ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="da554-153">Gets all the application gateways in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;ListAllNextAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da554-154">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da554-154">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="da554-155">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="da554-155">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da554-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da554-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da554-157">サブスクリプションのすべてのアプリケーション ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="da554-157">Gets all the application gateways in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da554-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da554-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da554-159">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-159">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da554-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da554-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da554-161">リソース グループ内のすべてのアプリケーション ゲートウェイを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="da554-161">Lists all application gateways in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSslOptionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAvailableSslOptionsInner&gt; ListAvailableSslOptionsAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAvailableSslOptionsInner&gt; ListAvailableSslOptionsAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAvailableSslOptionsAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSslOptionsAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAvailableSslOptionsInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAvailableSslOptionsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;ListAvailableSslOptionsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAvailableSslOptionsInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSslPredefinedPoliciesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;&gt; ListAvailableSslPredefinedPoliciesAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;&gt; ListAvailableSslPredefinedPoliciesAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAvailableSslPredefinedPoliciesAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSslPredefinedPoliciesAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAvailableSslPredefinedPoliciesAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;ListAvailableSslPredefinedPoliciesAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSslPredefinedPoliciesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;&gt; ListAvailableSslPredefinedPoliciesNextAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;&gt; ListAvailableSslPredefinedPoliciesNextAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAvailableSslPredefinedPoliciesNextAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSslPredefinedPoliciesNextAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAvailableSslPredefinedPoliciesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;ListAvailableSslPredefinedPoliciesNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySslPredefinedPolicyInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableWafRuleSetsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAvailableWafRuleSetsResultInner&gt; ListAvailableWafRuleSetsAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAvailableWafRuleSetsResultInner&gt; ListAvailableWafRuleSetsAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAvailableWafRuleSetsAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableWafRuleSetsAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAvailableWafRuleSetsResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListAvailableWafRuleSetsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;ListAvailableWafRuleSetsAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayAvailableWafRuleSetsResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;ListNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da554-162">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da554-162">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="da554-163">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="da554-163">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da554-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da554-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da554-165">リソース グループ内のすべてのアプリケーション ゲートウェイを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="da554-165">Lists all application gateways in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StartAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StartAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.StartAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.StartAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;StartAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da554-166">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da554-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da554-167">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-167">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="da554-168">アプリケーション ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-168">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da554-169">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da554-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da554-170">指定したアプリケーション ゲートウェイを開始します。</span><span class="sxs-lookup"><span data-stu-id="da554-170">Starts the specified application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StopAsync (this Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StopAsync(class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations operations, string resourceGroupName, string applicationGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.StopAsync(Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions.StopAsync (operations, resourceGroupName, applicationGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaysOperationsExtensions/&lt;StopAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="applicationGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da554-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da554-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da554-172">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-172">The name of the resource group.</span></span>
            </param>
        <param name="applicationGatewayName">
            <span data-ttu-id="da554-173">アプリケーション ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="da554-173">The name of the application gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da554-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da554-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da554-175">リソース グループ内の指定したアプリケーション ゲートウェイを停止します。</span><span class="sxs-lookup"><span data-stu-id="da554-175">Stops the specified application gateway in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>