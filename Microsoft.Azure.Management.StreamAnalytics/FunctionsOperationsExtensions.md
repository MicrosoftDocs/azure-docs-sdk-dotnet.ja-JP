<Type Name="FunctionsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FunctionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FunctionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FunctionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FunctionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="39e1b-101">FunctionsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="39e1b-101">Extension methods for FunctionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginTest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.BeginTest(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function)" />
      <MemberSignature Language="F#" Value="static member BeginTest : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.BeginTest (operations, resourceGroupName, jobName, functionName, function)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="39e1b-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="39e1b-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="39e1b-105">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-105">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="39e1b-106">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-106">The name of the function.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="39e1b-107">指定された関数が既に存在しない場合、このパラメーターは、テストするためのもので、フル機能定義を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="39e1b-107">If the function specified does not already exist, this parameter must contain the full function definition intended to be tested.</span></span> <span data-ttu-id="39e1b-108">既に指定された関数が存在する場合は、この省略可能ですが、または指定した場合、既存の関数をテストする場合は null、(PATCH 操作) とまったく同じ既存の関数に対応するプロパティを指定したプロパティが上書きされますおよび結果として得られる関数がテストされます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-108">If the function specified already exists, this parameter can be left null to test the existing function as is or if specified, the properties specified will overwrite the corresponding properties in the existing function (exactly like a PATCH operation) and the resulting function will be tested.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-109">関数の提供情報が有効かどうか。</span><span class="sxs-lookup"><span data-stu-id="39e1b-109">Tests if the information provided for a function is valid.</span></span> <span data-ttu-id="39e1b-110">関数の背後にある、基になる web サービスへの接続をテストまたは指定された関数のコードの構文が正しいことを確認してから範囲で指定できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-110">This can range from testing the connection to the underlying web service behind the function or making sure the function code provided is syntactically correct.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginTestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.BeginTestAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginTestAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.BeginTestAsync (operations, resourceGroupName, jobName, functionName, function, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;BeginTestAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="39e1b-112">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-112">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="39e1b-113">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-113">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="39e1b-114">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-114">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="39e1b-115">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-115">The name of the function.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="39e1b-116">指定された関数が既に存在しない場合、このパラメーターは、テストするためのもので、フル機能定義を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="39e1b-116">If the function specified does not already exist, this parameter must contain the full function definition intended to be tested.</span></span> <span data-ttu-id="39e1b-117">既に指定された関数が存在する場合は、この省略可能ですが、または指定した場合、既存の関数をテストする場合は null、(PATCH 操作) とまったく同じ既存の関数に対応するプロパティを指定したプロパティが上書きされますおよび結果として得られる関数がテストされます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-117">If the function specified already exists, this parameter can be left null to test the existing function as is or if specified, the properties specified will overwrite the corresponding properties in the existing function (exactly like a PATCH operation) and the resulting function will be tested.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="39e1b-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="39e1b-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-119">関数の提供情報が有効かどうか。</span><span class="sxs-lookup"><span data-stu-id="39e1b-119">Tests if the information provided for a function is valid.</span></span> <span data-ttu-id="39e1b-120">関数の背後にある、基になる web サービスへの接続をテストまたは指定された関数のコードの構文が正しいことを確認してから範囲で指定できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-120">This can range from testing the connection to the underlying web service behind the function or making sure the function code provided is syntactically correct.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Function CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Function CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.CreateOrReplace (operations, function, resourceGroupName, jobName, functionName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Function</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-121">The operations group for this extension method.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="39e1b-122">新しい関数を作成するか、ストリーミング ジョブの下にある既存のものを置き換えるに使用される関数の定義。</span><span class="sxs-lookup"><span data-stu-id="39e1b-122">The definition of the function that will be used to create a new function or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="39e1b-123">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-123">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="39e1b-124">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-124">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="39e1b-125">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-125">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="39e1b-126">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-126">The name of the function.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="39e1b-127">関数の ETag です。</span><span class="sxs-lookup"><span data-stu-id="39e1b-127">The ETag of the function.</span></span> <span data-ttu-id="39e1b-128">常に現在の関数を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-128">Omit this value to always overwrite the current function.</span></span> <span data-ttu-id="39e1b-129">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-129">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="39e1b-130">設定 ' \*' を作成する新しい関数を既存の関数の更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="39e1b-130">Set to '\*' to allow a new function to be created, but to prevent updating an existing function.</span></span> <span data-ttu-id="39e1b-131">その他の値は、412 の前提条件が失敗の応答になります。</span><span class="sxs-lookup"><span data-stu-id="39e1b-131">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-132">関数を作成するか、既存のストリーミング ジョブの下で既に既存の関数を置き換えます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-132">Creates a function or replaces an already existing function under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.CreateOrReplaceAsync (operations, function, resourceGroupName, jobName, functionName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-133">The operations group for this extension method.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="39e1b-134">新しい関数を作成するか、ストリーミング ジョブの下にある既存のものを置き換えるに使用される関数の定義。</span><span class="sxs-lookup"><span data-stu-id="39e1b-134">The definition of the function that will be used to create a new function or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="39e1b-135">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-135">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="39e1b-136">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-136">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="39e1b-137">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-137">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="39e1b-138">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-138">The name of the function.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="39e1b-139">関数の ETag です。</span><span class="sxs-lookup"><span data-stu-id="39e1b-139">The ETag of the function.</span></span> <span data-ttu-id="39e1b-140">常に現在の関数を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-140">Omit this value to always overwrite the current function.</span></span> <span data-ttu-id="39e1b-141">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-141">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="39e1b-142">設定 ' \*' を作成する新しい関数を既存の関数の更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="39e1b-142">Set to '\*' to allow a new function to be created, but to prevent updating an existing function.</span></span> <span data-ttu-id="39e1b-143">その他の値は、412 の前提条件が失敗の応答になります。</span><span class="sxs-lookup"><span data-stu-id="39e1b-143">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="39e1b-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="39e1b-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-145">関数を作成するか、既存のストリーミング ジョブの下で既に既存の関数を置き換えます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-145">Creates a function or replaces an already existing function under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Delete(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IFunctionsOperations, resourceGroupName As String, jobName As String, functionName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Delete (operations, resourceGroupName, jobName, functionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="39e1b-147">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-147">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="39e1b-148">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-148">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="39e1b-149">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-149">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="39e1b-150">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-150">The name of the function.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-151">ストリーミング ジョブから関数を削除します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-151">Deletes a function from the streaming job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, jobName, functionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-152">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="39e1b-153">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-153">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="39e1b-154">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-154">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="39e1b-155">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-155">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="39e1b-156">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-156">The name of the function.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="39e1b-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="39e1b-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-158">ストリーミング ジョブから関数を削除します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-158">Deletes a function from the streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Function Get (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Function Get(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IFunctionsOperations, resourceGroupName As String, jobName As String, functionName As String) As Function" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Get (operations, resourceGroupName, jobName, functionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Function</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="39e1b-160">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-160">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="39e1b-161">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-161">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="39e1b-162">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-162">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="39e1b-163">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-163">The name of the function.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-164">指定された関数の詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-164">Gets details about the specified function.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, functionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-165">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="39e1b-166">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-166">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="39e1b-167">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-167">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="39e1b-168">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-168">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="39e1b-169">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-169">The name of the function.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="39e1b-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="39e1b-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-171">指定された関数の詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-171">Gets details about the specified function.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; ListByStreamingJob (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string select = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; ListByStreamingJob(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string select) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJob(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJob (operations As IFunctionsOperations, resourceGroupName As String, jobName As String, Optional select As String = null) As IPage(Of Function)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJob : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJob (operations, resourceGroupName, jobName, select)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="39e1b-173">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-173">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="39e1b-174">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-174">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="39e1b-175">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-175">The name of the streaming job.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="39e1b-176">$Select OData クエリ パラメーター。</span><span class="sxs-lookup"><span data-stu-id="39e1b-176">The $select OData query parameter.</span></span> <span data-ttu-id="39e1b-177">これは、応答に含める構造型プロパティのコンマ区切りの一覧または"*"すべてのプロパティを含めます。既定では、診断を除くすべてのプロパティが返されます。現在のみを受け入れる '*' 有効な値として。</span><span class="sxs-lookup"><span data-stu-id="39e1b-177">This is a comma-separated list of structural properties to include in the response, or “*” to include all properties. By default, all properties are returned except diagnostics. Currently only accepts '*' as a valid value.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-178">すべての指定したストリーミング ジョブの下で関数の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-178">Lists all of the functions under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; ListByStreamingJobAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; ListByStreamingJobAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobAsync (operations, resourceGroupName, jobName, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;ListByStreamingJobAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="39e1b-180">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-180">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="39e1b-181">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-181">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="39e1b-182">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-182">The name of the streaming job.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="39e1b-183">$Select OData クエリ パラメーター。</span><span class="sxs-lookup"><span data-stu-id="39e1b-183">The $select OData query parameter.</span></span> <span data-ttu-id="39e1b-184">これは、応答に含める構造型プロパティのコンマ区切りの一覧または"*"すべてのプロパティを含めます。既定では、診断を除くすべてのプロパティが返されます。現在のみを受け入れる '*' 有効な値として。</span><span class="sxs-lookup"><span data-stu-id="39e1b-184">This is a comma-separated list of structural properties to include in the response, or “*” to include all properties. By default, all properties are returned except diagnostics. Currently only accepts '*' as a valid value.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="39e1b-185">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="39e1b-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-186">すべての指定したストリーミング ジョブの下で関数の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-186">Lists all of the functions under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; ListByStreamingJobNext (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; ListByStreamingJobNext(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobNext(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJobNext (operations As IFunctionsOperations, nextPageLink As String) As IPage(Of Function)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNext : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-187">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-187">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="39e1b-188">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="39e1b-188">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-189">すべての指定したストリーミング ジョブの下で関数の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-189">Lists all of the functions under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; ListByStreamingJobNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; ListByStreamingJobNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobNextAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNextAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;ListByStreamingJobNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-190">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="39e1b-191">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="39e1b-191">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="39e1b-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="39e1b-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-193">すべての指定したストリーミング ジョブの下で関数の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-193">Lists all of the functions under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveDefaultDefinition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Function RetrieveDefaultDefinition (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Function RetrieveDefaultDefinition(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.RetrieveDefaultDefinition(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters)" />
      <MemberSignature Language="F#" Value="static member RetrieveDefaultDefinition : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.RetrieveDefaultDefinition (operations, resourceGroupName, jobName, functionName, functionRetrieveDefaultDefinitionParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Function</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="functionRetrieveDefaultDefinitionParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-194">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="39e1b-195">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-195">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="39e1b-196">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-196">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="39e1b-197">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-197">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="39e1b-198">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-198">The name of the function.</span></span>
            </param>
        <param name="functionRetrieveDefaultDefinitionParameters">
            <span data-ttu-id="39e1b-199">パラメーターの既定の定義を取得する関数の種類を指定するために使用します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-199">Parameters used to specify the type of function to retrieve the default definition for.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-200">指定されたパラメーターに基づいて関数の既定の定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-200">Retrieves the default definition of a function based on the parameters specified.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveDefaultDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; RetrieveDefaultDefinitionAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; RetrieveDefaultDefinitionAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.RetrieveDefaultDefinitionAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RetrieveDefaultDefinitionAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.RetrieveDefaultDefinitionAsync (operations, resourceGroupName, jobName, functionName, functionRetrieveDefaultDefinitionParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;RetrieveDefaultDefinitionAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="functionRetrieveDefaultDefinitionParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-201">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="39e1b-202">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-202">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="39e1b-203">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-203">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="39e1b-204">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-204">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="39e1b-205">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-205">The name of the function.</span></span>
            </param>
        <param name="functionRetrieveDefaultDefinitionParameters">
            <span data-ttu-id="39e1b-206">パラメーターの既定の定義を取得する関数の種類を指定するために使用します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-206">Parameters used to specify the type of function to retrieve the default definition for.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="39e1b-207">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="39e1b-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-208">指定されたパラメーターに基づいて関数の既定の定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-208">Retrieves the default definition of a function based on the parameters specified.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Test">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Test(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function)" />
      <MemberSignature Language="F#" Value="static member Test : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Test (operations, resourceGroupName, jobName, functionName, function)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-209">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-209">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="39e1b-210">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-210">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="39e1b-211">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-211">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="39e1b-212">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-212">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="39e1b-213">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-213">The name of the function.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="39e1b-214">指定された関数が既に存在しない場合、このパラメーターは、テストするためのもので、フル機能定義を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="39e1b-214">If the function specified does not already exist, this parameter must contain the full function definition intended to be tested.</span></span> <span data-ttu-id="39e1b-215">既に指定された関数が存在する場合は、この省略可能ですが、または指定した場合、既存の関数をテストする場合は null、(PATCH 操作) とまったく同じ既存の関数に対応するプロパティを指定したプロパティが上書きされますおよび結果として得られる関数がテストされます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-215">If the function specified already exists, this parameter can be left null to test the existing function as is or if specified, the properties specified will overwrite the corresponding properties in the existing function (exactly like a PATCH operation) and the resulting function will be tested.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-216">関数の提供情報が有効かどうか。</span><span class="sxs-lookup"><span data-stu-id="39e1b-216">Tests if the information provided for a function is valid.</span></span> <span data-ttu-id="39e1b-217">関数の背後にある、基になる web サービスへの接続をテストまたは指定された関数のコードの構文が正しいことを確認してから範囲で指定できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-217">This can range from testing the connection to the underlying web service behind the function or making sure the function code provided is syntactically correct.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.TestAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TestAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.TestAsync (operations, resourceGroupName, jobName, functionName, function, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;TestAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-218">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-218">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="39e1b-219">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-219">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="39e1b-220">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-220">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="39e1b-221">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-221">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="39e1b-222">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-222">The name of the function.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="39e1b-223">指定された関数が既に存在しない場合、このパラメーターは、テストするためのもので、フル機能定義を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="39e1b-223">If the function specified does not already exist, this parameter must contain the full function definition intended to be tested.</span></span> <span data-ttu-id="39e1b-224">既に指定された関数が存在する場合は、この省略可能ですが、または指定した場合、既存の関数をテストする場合は null、(PATCH 操作) とまったく同じ既存の関数に対応するプロパティを指定したプロパティが上書きされますおよび結果として得られる関数がテストされます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-224">If the function specified already exists, this parameter can be left null to test the existing function as is or if specified, the properties specified will overwrite the corresponding properties in the existing function (exactly like a PATCH operation) and the resulting function will be tested.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="39e1b-225">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="39e1b-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-226">関数の提供情報が有効かどうか。</span><span class="sxs-lookup"><span data-stu-id="39e1b-226">Tests if the information provided for a function is valid.</span></span> <span data-ttu-id="39e1b-227">関数の背後にある、基になる web サービスへの接続をテストまたは指定された関数のコードの構文が正しいことを確認してから範囲で指定できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-227">This can range from testing the connection to the underlying web service behind the function or making sure the function code provided is syntactically correct.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Function Update (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Function Update(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Update (operations, function, resourceGroupName, jobName, functionName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Function</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-228">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-228">The operations group for this extension method.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="39e1b-229">関数オブジェクトを指定します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-229">A function object.</span></span> <span data-ttu-id="39e1b-230">ここで指定されたプロパティ (ie 既存の関数に対応するプロパティが上書きされます。そのプロパティが更新されます)。</span><span class="sxs-lookup"><span data-stu-id="39e1b-230">The properties specified here will overwrite the corresponding properties in the existing function (ie. Those properties will be updated).</span></span> <span data-ttu-id="39e1b-231">ここでは null に設定されている任意のプロパティがありことを意味の既存の関数に対応するプロパティは同じままこの PATCH 操作の結果として変更されません。</span><span class="sxs-lookup"><span data-stu-id="39e1b-231">Any properties that are set to null here will mean that the corresponding property in the existing function will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="39e1b-232">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-232">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="39e1b-233">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-233">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="39e1b-234">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-234">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="39e1b-235">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-235">The name of the function.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="39e1b-236">関数の ETag です。</span><span class="sxs-lookup"><span data-stu-id="39e1b-236">The ETag of the function.</span></span> <span data-ttu-id="39e1b-237">常に現在の関数を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-237">Omit this value to always overwrite the current function.</span></span> <span data-ttu-id="39e1b-238">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-238">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-239">既存のストリーミング ジョブの下にある既存の関数を更新します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-239">Updates an existing function under an existing streaming job.</span></span> <span data-ttu-id="39e1b-240">これは、(ie 部分的に更新を使用できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-240">This can be used to partially update (ie.</span></span> <span data-ttu-id="39e1b-241">1 つまたは 2 つのプロパティの更新)、残りのジョブまたは関数の定義に影響を与えず関数。</span><span class="sxs-lookup"><span data-stu-id="39e1b-241">update one or two properties) a function without affecting the rest the job or function definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.UpdateAsync (operations, function, resourceGroupName, jobName, functionName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="39e1b-242">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="39e1b-242">The operations group for this extension method.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="39e1b-243">関数オブジェクトを指定します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-243">A function object.</span></span> <span data-ttu-id="39e1b-244">ここで指定されたプロパティ (ie 既存の関数に対応するプロパティが上書きされます。そのプロパティが更新されます)。</span><span class="sxs-lookup"><span data-stu-id="39e1b-244">The properties specified here will overwrite the corresponding properties in the existing function (ie. Those properties will be updated).</span></span> <span data-ttu-id="39e1b-245">ここでは null に設定されている任意のプロパティがありことを意味の既存の関数に対応するプロパティは同じままこの PATCH 操作の結果として変更されません。</span><span class="sxs-lookup"><span data-stu-id="39e1b-245">Any properties that are set to null here will mean that the corresponding property in the existing function will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="39e1b-246">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-246">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="39e1b-247">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-247">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="39e1b-248">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-248">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="39e1b-249">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="39e1b-249">The name of the function.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="39e1b-250">関数の ETag です。</span><span class="sxs-lookup"><span data-stu-id="39e1b-250">The ETag of the function.</span></span> <span data-ttu-id="39e1b-251">常に現在の関数を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-251">Omit this value to always overwrite the current function.</span></span> <span data-ttu-id="39e1b-252">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-252">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="39e1b-253">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="39e1b-253">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="39e1b-254">既存のストリーミング ジョブの下にある既存の関数を更新します。</span><span class="sxs-lookup"><span data-stu-id="39e1b-254">Updates an existing function under an existing streaming job.</span></span> <span data-ttu-id="39e1b-255">これは、(ie 部分的に更新を使用できます。</span><span class="sxs-lookup"><span data-stu-id="39e1b-255">This can be used to partially update (ie.</span></span> <span data-ttu-id="39e1b-256">1 つまたは 2 つのプロパティの更新)、残りのジョブまたは関数の定義に影響を与えず関数。</span><span class="sxs-lookup"><span data-stu-id="39e1b-256">update one or two properties) a function without affecting the rest the job or function definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>