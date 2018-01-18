<Type Name="BatchAccountOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BatchAccountOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BatchAccountOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BatchAccountOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BatchAccountOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="92264-101">BatchAccountOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="92264-101">Extension methods for BatchAccountOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; BeginCreateAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; BeginCreateAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;BeginCreateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="92264-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="92264-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="92264-103">新しい Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="92264-103">The name of the resource group that contains the new Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="92264-104">領域内で一意でなければなりません Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="92264-104">A name for the Batch account which must be unique within the region.</span></span> <span data-ttu-id="92264-105">Batch アカウント名は 3 ~ 24 文字にする必要があり、数字と小文字のアルファベットだけを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="92264-105">Batch account names must be between 3 and 24 characters in length and must use only numbers and lowercase letters.</span></span> <span data-ttu-id="92264-106">この名前は、バッチ サービスは、アカウントを作成する領域のアクセスに使用される DNS 名の一部として使用されます。</span><span class="sxs-lookup"><span data-stu-id="92264-106">This name is used as part of the DNS name that is used to access the Batch service in the region in which the account is created.</span></span> <span data-ttu-id="92264-107">例: http://accountname.region.batch.azure.com/ です。</span><span class="sxs-lookup"><span data-stu-id="92264-107">For example: http://accountname.region.batch.azure.com/.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="92264-108">アカウントの作成に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="92264-108">Additional parameters for account creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="92264-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92264-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92264-110">指定したパラメーターを使用して、新しい Batch アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="92264-110">Creates a new Batch account with the specified parameters.</span></span> <span data-ttu-id="92264-111">既存のアカウントは、この API を更新できませんおよび更新バッチ アカウントの API を代わりに更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="92264-111">Existing accounts cannot be updated with this API and should instead be updated with the Update Batch Account API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;BeginDeleteAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="92264-112">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="92264-112">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="92264-113">削除するバッチ アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="92264-113">The name of the resource group that contains the Batch account to be deleted.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="92264-114">削除するアカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="92264-114">The name of the account to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="92264-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92264-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92264-116">指定した Batch アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="92264-116">Deletes the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; CreateAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; CreateAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;CreateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="92264-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="92264-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="92264-118">新しい Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="92264-118">The name of the resource group that contains the new Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="92264-119">領域内で一意でなければなりません Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="92264-119">A name for the Batch account which must be unique within the region.</span></span> <span data-ttu-id="92264-120">Batch アカウント名は 3 ~ 24 文字にする必要があり、数字と小文字のアルファベットだけを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="92264-120">Batch account names must be between 3 and 24 characters in length and must use only numbers and lowercase letters.</span></span> <span data-ttu-id="92264-121">この名前は、バッチ サービスは、アカウントを作成する領域のアクセスに使用される DNS 名の一部として使用されます。</span><span class="sxs-lookup"><span data-stu-id="92264-121">This name is used as part of the DNS name that is used to access the Batch service in the region in which the account is created.</span></span> <span data-ttu-id="92264-122">例: http://accountname.region.batch.azure.com/ です。</span><span class="sxs-lookup"><span data-stu-id="92264-122">For example: http://accountname.region.batch.azure.com/.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="92264-123">アカウントの作成に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="92264-123">Additional parameters for account creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="92264-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92264-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92264-125">指定したパラメーターを使用して、新しい Batch アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="92264-125">Creates a new Batch account with the specified parameters.</span></span> <span data-ttu-id="92264-126">既存のアカウントは、この API を更新できませんおよび更新バッチ アカウントの API を代わりに更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="92264-126">Existing accounts cannot be updated with this API and should instead be updated with the Update Batch Account API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt; DeleteAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt; DeleteAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="92264-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="92264-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="92264-128">削除するバッチ アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="92264-128">The name of the resource group that contains the Batch account to be deleted.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="92264-129">削除するアカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="92264-129">The name of the account to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="92264-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92264-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92264-131">指定した Batch アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="92264-131">Deletes the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; GetAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; GetAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.GetAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="92264-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="92264-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="92264-133">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="92264-133">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="92264-134">アカウントの名前です。</span><span class="sxs-lookup"><span data-stu-id="92264-134">The name of the account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="92264-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92264-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92264-136">指定されたバッチ アカウントに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="92264-136">Gets information about the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt; GetKeysAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt; GetKeysAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.GetKeysAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeysAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.GetKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;GetKeysAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="92264-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="92264-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="92264-138">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="92264-138">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="92264-139">アカウントの名前です。</span><span class="sxs-lookup"><span data-stu-id="92264-139">The name of the account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="92264-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92264-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92264-141">指定されたバッチ アカウントのアカウント キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="92264-141">Gets the account keys for the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;ListAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="92264-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="92264-142">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="92264-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92264-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92264-144">サブスクリプションに関連付けられているバッチ アカウントに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="92264-144">Gets information about the Batch accounts associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="92264-145">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="92264-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="92264-146">リソースの名前を一覧表示するバッチ アカウントを持つをグループ化します。</span><span class="sxs-lookup"><span data-stu-id="92264-146">The name of the resource group whose Batch accounts to list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="92264-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92264-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92264-148">指定されたリソース グループ内で関連付けられているバッチ アカウントに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="92264-148">Gets information about the Batch accounts associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="92264-149">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="92264-149">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="92264-150">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="92264-150">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="92264-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92264-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92264-152">指定されたリソース グループ内で関連付けられているバッチ アカウントに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="92264-152">Gets information about the Batch accounts associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="92264-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="92264-153">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="92264-154">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="92264-154">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="92264-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92264-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92264-156">サブスクリプションに関連付けられているバッチ アカウントに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="92264-156">Gets information about the Batch accounts associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountRegenerateKeyParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountRegenerateKeyParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountRegenerateKeyParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountRegenerateKeyParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountRegenerateKeyParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="accountName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SynchronizeAutoStorageKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SynchronizeAutoStorageKeysAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SynchronizeAutoStorageKeysAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.SynchronizeAutoStorageKeysAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SynchronizeAutoStorageKeysAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.SynchronizeAutoStorageKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;SynchronizeAutoStorageKeysAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="92264-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="92264-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="92264-158">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="92264-158">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="92264-159">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="92264-159">The name of the Batch account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="92264-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92264-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92264-161">指定されたバッチ アカウント用に構成された自動ストレージ アカウントのアクセス キーを同期します。</span><span class="sxs-lookup"><span data-stu-id="92264-161">Synchronizes access keys for the auto storage account configured for the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; UpdateAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; UpdateAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;UpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="92264-162">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="92264-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="92264-163">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="92264-163">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="92264-164">アカウントの名前です。</span><span class="sxs-lookup"><span data-stu-id="92264-164">The name of the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="92264-165">アカウントの更新プログラムの追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="92264-165">Additional parameters for account update.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="92264-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92264-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92264-167">既存のバッチ アカウントのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="92264-167">Updates the properties of an existing Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>