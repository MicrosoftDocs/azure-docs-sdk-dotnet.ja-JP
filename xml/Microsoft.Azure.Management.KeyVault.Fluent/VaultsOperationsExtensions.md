<Type Name="VaultsOperationsExtensions" FullName="Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VaultsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VaultsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VaultsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VaultsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9eb0c-101">VaultsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-101">Extension methods for VaultsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultCreateOrUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultCreateOrUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations,System.String,System.String,Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultCreateOrUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations * string * string * Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultCreateOrUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;" Usage="Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, vaultName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultCreateOrUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9eb0c-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9eb0c-103">サーバーが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-103">The name of the Resource Group to which the server belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="9eb0c-104">コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="9eb0c-104">Name of the vault</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9eb0c-105">パラメーターを作成または資格情報コンテナーの更新</span><span class="sxs-lookup"><span data-stu-id="9eb0c-105">Parameters to create or update the vault</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9eb0c-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9eb0c-107">作成または指定したサブスクリプションでキー資格情報コンテナーを更新します。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-107">Create or update a key vault in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string resourceGroupName, string vaultName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string resourceGroupName, string vaultName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.DeleteAsync (operations, resourceGroupName, vaultName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9eb0c-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9eb0c-109">資格情報コンテナーが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-109">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="9eb0c-110">削除する資格情報コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="9eb0c-110">The name of the vault to delete</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9eb0c-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9eb0c-112">指定した Azure key vault を削除します。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-112">Deletes the specified Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt; GetAsync (this Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string resourceGroupName, string vaultName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt; GetAsync(class Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string resourceGroupName, string vaultName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.GetAsync(Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;" Usage="Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.GetAsync (operations, resourceGroupName, vaultName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9eb0c-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9eb0c-114">資格情報コンテナーが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-114">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="9eb0c-115">資格情報コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-115">The name of the vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9eb0c-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9eb0c-117">指定した Azure key vault を取得します。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-117">Gets the specified Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.ListAsync(Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.ListAsync (operations, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions/&lt;ListAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9eb0c-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-118">The operations group for this extension method.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="9eb0c-119">返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-119">Maximum number of results to return.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9eb0c-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9eb0c-121">一覧操作では、サブスクリプションに関連付けられている資格情報コンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-121">The List operation gets information about the vaults associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string resourceGroupName, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string resourceGroupName, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9eb0c-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9eb0c-123">資格情報コンテナーが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-123">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="9eb0c-124">返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-124">Maximum number of results to return.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9eb0c-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9eb0c-126">一覧操作では、および指定されたリソース グループ内で、サブスクリプションに関連付けられている資格情報コンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-126">The List operation gets information about the vaults associated with the subscription and within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9eb0c-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-127">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9eb0c-128">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-128">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9eb0c-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9eb0c-130">一覧操作では、および指定されたリソース グループ内で、サブスクリプションに関連付けられている資格情報コンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-130">The List operation gets information about the vaults associated with the subscription and within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.Fluent.VaultsOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9eb0c-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-131">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9eb0c-132">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-132">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9eb0c-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9eb0c-134">一覧操作では、サブスクリプションに関連付けられている資格情報コンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="9eb0c-134">The List operation gets information about the vaults associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>