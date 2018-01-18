<Type Name="BatchAccountOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BatchAccountOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BatchAccountOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BatchAccountOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BatchAccountOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c26be-101">BatchAccountOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="c26be-101">Extension methods for BatchAccountOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchAccount BeginCreate (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchAccount BeginCreate(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.BeginCreate(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String, parameters As BatchAccountCreateParameters) As BatchAccount" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccount" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.BeginCreate (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-103">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-103">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-104">領域内で一意でなければなりません Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-104">A name for the Batch account which must be unique within the region.</span></span> <span data-ttu-id="c26be-105">Batch アカウント名は 3 ~ 24 文字にする必要があり、数字と小文字のアルファベットだけを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c26be-105">Batch account names must be between 3 and 24 characters in length and must use only numbers and lowercase letters.</span></span> <span data-ttu-id="c26be-106">この名前は、バッチ サービスは、アカウントを作成する領域のアクセスに使用される DNS 名の一部として使用されます。</span><span class="sxs-lookup"><span data-stu-id="c26be-106">This name is used as part of the DNS name that is used to access the Batch service in the region in which the account is created.</span></span> <span data-ttu-id="c26be-107">例: http://accountname.region.batch.azure.com/ です。</span><span class="sxs-lookup"><span data-stu-id="c26be-107">For example: http://accountname.region.batch.azure.com/.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c26be-108">アカウントの作成に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c26be-108">Additional parameters for account creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-109">指定したパラメーターを使用して、新しい Batch アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="c26be-109">Creates a new Batch account with the specified parameters.</span></span> <span data-ttu-id="c26be-110">既存のアカウントは、この API を更新できませんおよび更新バッチ アカウントの API を代わりに更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c26be-110">Existing accounts cannot be updated with this API and should instead be updated with the Update Batch Account API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; BeginCreateAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; BeginCreateAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;BeginCreateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-112">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-112">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-113">領域内で一意でなければなりません Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-113">A name for the Batch account which must be unique within the region.</span></span> <span data-ttu-id="c26be-114">Batch アカウント名は 3 ~ 24 文字にする必要があり、数字と小文字のアルファベットだけを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c26be-114">Batch account names must be between 3 and 24 characters in length and must use only numbers and lowercase letters.</span></span> <span data-ttu-id="c26be-115">この名前は、バッチ サービスは、アカウントを作成する領域のアクセスに使用される DNS 名の一部として使用されます。</span><span class="sxs-lookup"><span data-stu-id="c26be-115">This name is used as part of the DNS name that is used to access the Batch service in the region in which the account is created.</span></span> <span data-ttu-id="c26be-116">例: http://accountname.region.batch.azure.com/ です。</span><span class="sxs-lookup"><span data-stu-id="c26be-116">For example: http://accountname.region.batch.azure.com/.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c26be-117">アカウントの作成に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c26be-117">Additional parameters for account creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26be-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26be-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-119">指定したパラメーターを使用して、新しい Batch アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="c26be-119">Creates a new Batch account with the specified parameters.</span></span> <span data-ttu-id="c26be-120">既存のアカウントは、この API を更新できませんおよび更新バッチ アカウントの API を代わりに更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c26be-120">Existing accounts cannot be updated with this API and should instead be updated with the Update Batch Account API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders BeginDelete (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders BeginDelete(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String) As BatchAccountDeleteHeaders" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.BeginDelete (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-122">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-122">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-123">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-123">The name of the Batch account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-124">指定した Batch アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="c26be-124">Deletes the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;BeginDeleteAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-126">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-126">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-127">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-127">The name of the Batch account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26be-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26be-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-129">指定した Batch アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="c26be-129">Deletes the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchAccount Create (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchAccount Create(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.Create(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String, parameters As BatchAccountCreateParameters) As BatchAccount" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccount" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.Create (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-131">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-131">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-132">領域内で一意でなければなりません Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-132">A name for the Batch account which must be unique within the region.</span></span> <span data-ttu-id="c26be-133">Batch アカウント名は 3 ~ 24 文字にする必要があり、数字と小文字のアルファベットだけを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c26be-133">Batch account names must be between 3 and 24 characters in length and must use only numbers and lowercase letters.</span></span> <span data-ttu-id="c26be-134">この名前は、バッチ サービスは、アカウントを作成する領域のアクセスに使用される DNS 名の一部として使用されます。</span><span class="sxs-lookup"><span data-stu-id="c26be-134">This name is used as part of the DNS name that is used to access the Batch service in the region in which the account is created.</span></span> <span data-ttu-id="c26be-135">例: http://accountname.region.batch.azure.com/ です。</span><span class="sxs-lookup"><span data-stu-id="c26be-135">For example: http://accountname.region.batch.azure.com/.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c26be-136">アカウントの作成に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c26be-136">Additional parameters for account creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-137">指定したパラメーターを使用して、新しい Batch アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="c26be-137">Creates a new Batch account with the specified parameters.</span></span> <span data-ttu-id="c26be-138">既存のアカウントは、この API を更新できませんおよび更新バッチ アカウントの API を代わりに更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c26be-138">Existing accounts cannot be updated with this API and should instead be updated with the Update Batch Account API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; CreateAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; CreateAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-140">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-140">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-141">領域内で一意でなければなりません Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-141">A name for the Batch account which must be unique within the region.</span></span> <span data-ttu-id="c26be-142">Batch アカウント名は 3 ~ 24 文字にする必要があり、数字と小文字のアルファベットだけを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c26be-142">Batch account names must be between 3 and 24 characters in length and must use only numbers and lowercase letters.</span></span> <span data-ttu-id="c26be-143">この名前は、バッチ サービスは、アカウントを作成する領域のアクセスに使用される DNS 名の一部として使用されます。</span><span class="sxs-lookup"><span data-stu-id="c26be-143">This name is used as part of the DNS name that is used to access the Batch service in the region in which the account is created.</span></span> <span data-ttu-id="c26be-144">例: http://accountname.region.batch.azure.com/ です。</span><span class="sxs-lookup"><span data-stu-id="c26be-144">For example: http://accountname.region.batch.azure.com/.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c26be-145">アカウントの作成に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c26be-145">Additional parameters for account creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26be-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26be-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-147">指定したパラメーターを使用して、新しい Batch アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="c26be-147">Creates a new Batch account with the specified parameters.</span></span> <span data-ttu-id="c26be-148">既存のアカウントは、この API を更新できませんおよび更新バッチ アカウントの API を代わりに更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c26be-148">Existing accounts cannot be updated with this API and should instead be updated with the Update Batch Account API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders Delete (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders Delete(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.Delete(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String) As BatchAccountDeleteHeaders" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.Delete (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-149">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-150">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-150">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-151">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-151">The name of the Batch account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-152">指定した Batch アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="c26be-152">Deletes the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-154">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-154">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-155">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-155">The name of the Batch account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26be-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26be-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-157">指定した Batch アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="c26be-157">Deletes the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchAccount Get (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchAccount Get(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.Get(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String) As BatchAccount" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccount" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.Get (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-159">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-159">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-160">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-160">The name of the Batch account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-161">指定されたバッチ アカウントに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c26be-161">Gets information about the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; GetAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; GetAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.GetAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-162">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-163">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-163">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-164">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-164">The name of the Batch account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26be-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26be-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-166">指定されたバッチ アカウントに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c26be-166">Gets information about the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchAccountKeys GetKeys (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchAccountKeys GetKeys(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.GetKeys(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetKeys (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String) As BatchAccountKeys" />
      <MemberSignature Language="F#" Value="static member GetKeys : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccountKeys" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.GetKeys (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchAccountKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-168">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-168">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-169">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-169">The name of the Batch account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-170">指定されたバッチ アカウントのアカウント キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="c26be-170">Gets the account keys for the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="c26be-171">この操作は、'BatchService' の poolAllocationMode で作成されたバッチ アカウントのみに適用されます。</span><span class="sxs-lookup"><span data-stu-id="c26be-171">This operation applies only to Batch accounts created with a poolAllocationMode of 'BatchService'.</span></span> <span data-ttu-id="c26be-172">クライアントが認証にキーへのアクセスを使用できない 'UserSubscription' の poolAllocationMode で Batch アカウントが作成されている場合、代わりに Azure Active Directory を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c26be-172">If the Batch account was created with a poolAllocationMode of 'UserSubscription', clients cannot use access to keys to authenticate, and must use Azure Active Directory instead.</span></span> <span data-ttu-id="c26be-173">この場合、キーの取得は失敗します。</span><span class="sxs-lookup"><span data-stu-id="c26be-173">In this case, getting the keys will fail.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountKeys&gt; GetKeysAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccountKeys&gt; GetKeysAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.GetKeysAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeysAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountKeys&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.GetKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;GetKeysAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-174">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-174">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-175">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-175">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-176">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-176">The name of the Batch account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26be-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26be-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-178">指定されたバッチ アカウントのアカウント キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="c26be-178">Gets the account keys for the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="c26be-179">この操作は、'BatchService' の poolAllocationMode で作成されたバッチ アカウントのみに適用されます。</span><span class="sxs-lookup"><span data-stu-id="c26be-179">This operation applies only to Batch accounts created with a poolAllocationMode of 'BatchService'.</span></span> <span data-ttu-id="c26be-180">クライアントが認証にキーへのアクセスを使用できない 'UserSubscription' の poolAllocationMode で Batch アカウントが作成されている場合、代わりに Azure Active Directory を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c26be-180">If the Batch account was created with a poolAllocationMode of 'UserSubscription', clients cannot use access to keys to authenticate, and must use Azure Active Directory instead.</span></span> <span data-ttu-id="c26be-181">この場合、キーの取得は失敗します。</span><span class="sxs-lookup"><span data-stu-id="c26be-181">In this case, getting the keys will fail.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; List (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; List(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.List(Microsoft.Azure.Management.Batch.IBatchAccountOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IBatchAccountOperations) As IPage(Of BatchAccount)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Batch.IBatchAccountOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-182">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-183">サブスクリプションに関連付けられているバッチ アカウントに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c26be-183">Gets information about the Batch accounts associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt; ListAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt; ListAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-184">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-184">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26be-185">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26be-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-186">サブスクリプションに関連付けられているバッチ アカウントに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c26be-186">Gets information about the Batch accounts associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; ListByResourceGroup (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; ListByResourceGroup(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IBatchAccountOperations, resourceGroupName As String) As IPage(Of BatchAccount)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-187">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-187">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-188">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-188">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-189">指定されたリソース グループに関連付けられているバッチ アカウントに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c26be-189">Gets information about the Batch accounts associated with the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-191">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-191">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26be-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26be-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-193">指定されたリソース グループに関連付けられているバッチ アカウントに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c26be-193">Gets information about the Batch accounts associated with the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IBatchAccountOperations, nextPageLink As String) As IPage(Of BatchAccount)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-194">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c26be-195">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c26be-195">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-196">指定されたリソース グループに関連付けられているバッチ アカウントに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c26be-196">Gets information about the Batch accounts associated with the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-197">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-197">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c26be-198">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c26be-198">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26be-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26be-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-200">指定されたリソース グループに関連付けられているバッチ アカウントに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c26be-200">Gets information about the Batch accounts associated with the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; ListNext (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; ListNext(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListNext(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IBatchAccountOperations, nextPageLink As String) As IPage(Of BatchAccount)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-201">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-201">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c26be-202">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c26be-202">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-203">サブスクリプションに関連付けられているバッチ アカウントに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c26be-203">Gets information about the Batch accounts associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;ListNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-204">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-204">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c26be-205">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c26be-205">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26be-206">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26be-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-207">サブスクリプションに関連付けられているバッチ アカウントに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c26be-207">Gets information about the Batch accounts associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchAccountKeys RegenerateKey (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Models.AccountKeyType keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchAccountKeys RegenerateKey(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype Microsoft.Azure.Management.Batch.Models.AccountKeyType keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.RegenerateKey(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Models.AccountKeyType)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKey (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String, keyName As AccountKeyType) As BatchAccountKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateKey : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Models.AccountKeyType -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccountKeys" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.RegenerateKey (operations, resourceGroupName, accountName, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchAccountKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyName" Type="Microsoft.Azure.Management.Batch.Models.AccountKeyType" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-209">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-209">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-210">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-210">The name of the Batch account.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="c26be-211">アカウント キーを再生成の型。</span><span class="sxs-lookup"><span data-stu-id="c26be-211">The type of account key to regenerate.</span></span> <span data-ttu-id="c26be-212">使用可能な値が含まれます 'Primary'、'セカンダリ'。</span><span class="sxs-lookup"><span data-stu-id="c26be-212">Possible values include: 'Primary', 'Secondary'</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-213">Batch アカウントの指定されたアカウント キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="c26be-213">Regenerates the specified account key for the Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountKeys&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Models.AccountKeyType keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccountKeys&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype Microsoft.Azure.Management.Batch.Models.AccountKeyType keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Models.AccountKeyType,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Models.AccountKeyType * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountKeys&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, accountName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccountKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyName" Type="Microsoft.Azure.Management.Batch.Models.AccountKeyType" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-214">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-215">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-215">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-216">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-216">The name of the Batch account.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="c26be-217">アカウント キーを再生成の型。</span><span class="sxs-lookup"><span data-stu-id="c26be-217">The type of account key to regenerate.</span></span> <span data-ttu-id="c26be-218">使用可能な値が含まれます 'Primary'、'セカンダリ'。</span><span class="sxs-lookup"><span data-stu-id="c26be-218">Possible values include: 'Primary', 'Secondary'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26be-219">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26be-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-220">Batch アカウントの指定されたアカウント キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="c26be-220">Regenerates the specified account key for the Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SynchronizeAutoStorageKeys">
      <MemberSignature Language="C#" Value="public static void SynchronizeAutoStorageKeys (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SynchronizeAutoStorageKeys(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.SynchronizeAutoStorageKeys(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SynchronizeAutoStorageKeys (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String)" />
      <MemberSignature Language="F#" Value="static member SynchronizeAutoStorageKeys : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.SynchronizeAutoStorageKeys (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-221">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-222">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-222">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-223">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-223">The name of the Batch account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-224">指定されたバッチ アカウント用に構成された記憶域の自動アカウントのアクセス キーを同期します。</span><span class="sxs-lookup"><span data-stu-id="c26be-224">Synchronizes access keys for the auto-storage account configured for the specified Batch account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SynchronizeAutoStorageKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SynchronizeAutoStorageKeysAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SynchronizeAutoStorageKeysAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.SynchronizeAutoStorageKeysAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SynchronizeAutoStorageKeysAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.SynchronizeAutoStorageKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;SynchronizeAutoStorageKeysAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-225">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-225">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-226">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-226">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-227">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-227">The name of the Batch account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26be-228">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26be-228">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-229">指定されたバッチ アカウント用に構成された記憶域の自動アカウントのアクセス キーを同期します。</span><span class="sxs-lookup"><span data-stu-id="c26be-229">Synchronizes access keys for the auto-storage account configured for the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.BatchAccount Update (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.BatchAccount Update(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.Update(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IBatchAccountOperations, resourceGroupName As String, accountName As String, parameters As BatchAccountUpdateParameters) As BatchAccount" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccount" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.Update (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.BatchAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-230">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-230">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-231">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-231">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-232">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-232">The name of the Batch account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c26be-233">アカウントの更新プログラムの追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c26be-233">Additional parameters for account update.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-234">既存のバッチ アカウントのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="c26be-234">Updates the properties of an existing Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; UpdateAsync (this Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchAccount&gt; UpdateAsync(class Microsoft.Azure.Management.Batch.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Batch.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Batch.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;" Usage="Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.BatchAccountOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.BatchAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.BatchAccountUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c26be-235">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c26be-235">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c26be-236">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-236">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c26be-237">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c26be-237">The name of the Batch account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c26be-238">アカウントの更新プログラムの追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c26be-238">Additional parameters for account update.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26be-239">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26be-239">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26be-240">既存のバッチ アカウントのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="c26be-240">Updates the properties of an existing Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>