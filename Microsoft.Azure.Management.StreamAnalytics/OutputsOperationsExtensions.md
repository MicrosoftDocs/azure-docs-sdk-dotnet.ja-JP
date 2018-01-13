<Type Name="OutputsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class OutputsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit OutputsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module OutputsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type OutputsOperationsExtensions = class" />
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
            <span data-ttu-id="30ad3-101">OutputsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="30ad3-101">Extension methods for OutputsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginTest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, Microsoft.Azure.Management.StreamAnalytics.Models.Output output = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Output output) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.BeginTest(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Output)" />
      <MemberSignature Language="F#" Value="static member BeginTest : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Output -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.BeginTest (operations, resourceGroupName, jobName, outputName, output)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="30ad3-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="30ad3-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="30ad3-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="30ad3-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="30ad3-105">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-105">The name of the streaming job.</span></span>
            </param>
        <param name="outputName">
            <span data-ttu-id="30ad3-106">出力の名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-106">The name of the output.</span></span>
            </param>
        <param name="output">
            <span data-ttu-id="30ad3-107">指定された出力が既に存在しない場合、このパラメーターは、テストするためのもので、完全な出力の定義を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="30ad3-107">If the output specified does not already exist, this parameter must contain the full output definition intended to be tested.</span></span> <span data-ttu-id="30ad3-108">このパラメーターは省略可能、既存の出力が格納されるかをテストする場合は null または (PATCH 操作) とまったく同じ既存の出力と、その結果で対応するプロパティを指定したプロパティが上書きされます、指定した場合の出力が既に指定されて存在する場合、出力がテストされます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-108">If the output specified already exists, this parameter can be left null to test the existing output as is or if specified, the properties specified will overwrite the corresponding properties in the existing output (exactly like a PATCH operation) and the resulting output will be tested.</span></span>
            </param>
        <summary>
            <span data-ttu-id="30ad3-109">出力のデータ ソースが到達可能で、Azure Stream Analytics サービスで使用できるかどうかをテストします。</span><span class="sxs-lookup"><span data-stu-id="30ad3-109">Tests whether an output’s datasource is reachable and usable by the Azure Stream Analytics service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginTestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, Microsoft.Azure.Management.StreamAnalytics.Models.Output output = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Output output, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.BeginTestAsync(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Output,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginTestAsync : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Output * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.BeginTestAsync (operations, resourceGroupName, jobName, outputName, output, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions/&lt;BeginTestAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="30ad3-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="30ad3-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="30ad3-111">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-111">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="30ad3-112">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-112">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="30ad3-113">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-113">The name of the streaming job.</span></span>
            </param>
        <param name="outputName">
            <span data-ttu-id="30ad3-114">出力の名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-114">The name of the output.</span></span>
            </param>
        <param name="output">
            <span data-ttu-id="30ad3-115">指定された出力が既に存在しない場合、このパラメーターは、テストするためのもので、完全な出力の定義を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="30ad3-115">If the output specified does not already exist, this parameter must contain the full output definition intended to be tested.</span></span> <span data-ttu-id="30ad3-116">このパラメーターは省略可能、既存の出力が格納されるかをテストする場合は null または (PATCH 操作) とまったく同じ既存の出力と、その結果で対応するプロパティを指定したプロパティが上書きされます、指定した場合の出力が既に指定されて存在する場合、出力がテストされます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-116">If the output specified already exists, this parameter can be left null to test the existing output as is or if specified, the properties specified will overwrite the corresponding properties in the existing output (exactly like a PATCH operation) and the resulting output will be tested.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="30ad3-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="30ad3-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="30ad3-118">出力のデータ ソースが到達可能で、Azure Stream Analytics サービスで使用できるかどうかをテストします。</span><span class="sxs-lookup"><span data-stu-id="30ad3-118">Tests whether an output’s datasource is reachable and usable by the Azure Stream Analytics service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Output CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Output output, string resourceGroupName, string jobName, string outputName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Output CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Output output, string resourceGroupName, string jobName, string outputName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Output,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Output * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Output" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.CreateOrReplace (operations, output, resourceGroupName, jobName, outputName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Output</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="30ad3-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="30ad3-119">The operations group for this extension method.</span></span>
            </param>
        <param name="output">
            <span data-ttu-id="30ad3-120">新しい出力を作成するか、ストリーミング ジョブの下にある既存のものを置き換えるに使用される出力の定義。</span><span class="sxs-lookup"><span data-stu-id="30ad3-120">The definition of the output that will be used to create a new output or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="30ad3-121">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-121">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="30ad3-122">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-122">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="30ad3-123">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-123">The name of the streaming job.</span></span>
            </param>
        <param name="outputName">
            <span data-ttu-id="30ad3-124">出力の名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-124">The name of the output.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="30ad3-125">出力の ETag です。</span><span class="sxs-lookup"><span data-stu-id="30ad3-125">The ETag of the output.</span></span> <span data-ttu-id="30ad3-126">常に現在の出力を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-126">Omit this value to always overwrite the current output.</span></span> <span data-ttu-id="30ad3-127">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-127">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="30ad3-128">設定 ' \*'、新しい出力を作成するが、既存の出力の更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="30ad3-128">Set to '\*' to allow a new output to be created, but to prevent updating an existing output.</span></span> <span data-ttu-id="30ad3-129">その他の値は、412 の前提条件が失敗の応答になります。</span><span class="sxs-lookup"><span data-stu-id="30ad3-129">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <summary>
            <span data-ttu-id="30ad3-130">出力を作成するか、既存のストリーミング ジョブの下にある既存の出力を置き換えます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-130">Creates an output or replaces an already existing output under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Output output, string resourceGroupName, string jobName, string outputName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Output output, string resourceGroupName, string jobName, string outputName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Output,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Output * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.CreateOrReplaceAsync (operations, output, resourceGroupName, jobName, outputName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="30ad3-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="30ad3-131">The operations group for this extension method.</span></span>
            </param>
        <param name="output">
            <span data-ttu-id="30ad3-132">新しい出力を作成するか、ストリーミング ジョブの下にある既存のものを置き換えるに使用される出力の定義。</span><span class="sxs-lookup"><span data-stu-id="30ad3-132">The definition of the output that will be used to create a new output or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="30ad3-133">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-133">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="30ad3-134">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-134">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="30ad3-135">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-135">The name of the streaming job.</span></span>
            </param>
        <param name="outputName">
            <span data-ttu-id="30ad3-136">出力の名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-136">The name of the output.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="30ad3-137">出力の ETag です。</span><span class="sxs-lookup"><span data-stu-id="30ad3-137">The ETag of the output.</span></span> <span data-ttu-id="30ad3-138">常に現在の出力を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-138">Omit this value to always overwrite the current output.</span></span> <span data-ttu-id="30ad3-139">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-139">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="30ad3-140">設定 ' \*'、新しい出力を作成するが、既存の出力の更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="30ad3-140">Set to '\*' to allow a new output to be created, but to prevent updating an existing output.</span></span> <span data-ttu-id="30ad3-141">その他の値は、412 の前提条件が失敗の応答になります。</span><span class="sxs-lookup"><span data-stu-id="30ad3-141">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="30ad3-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="30ad3-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="30ad3-143">出力を作成するか、既存のストリーミング ジョブの下にある既存の出力を置き換えます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-143">Creates an output or replaces an already existing output under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.Delete(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IOutputsOperations, resourceGroupName As String, jobName As String, outputName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.Delete (operations, resourceGroupName, jobName, outputName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="30ad3-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="30ad3-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="30ad3-145">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-145">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="30ad3-146">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-146">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="30ad3-147">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-147">The name of the streaming job.</span></span>
            </param>
        <param name="outputName">
            <span data-ttu-id="30ad3-148">出力の名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-148">The name of the output.</span></span>
            </param>
        <summary>
            <span data-ttu-id="30ad3-149">ストリーミング ジョブから出力を削除します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-149">Deletes an output from the streaming job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.DeleteAsync (operations, resourceGroupName, jobName, outputName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="30ad3-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="30ad3-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="30ad3-151">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-151">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="30ad3-152">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-152">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="30ad3-153">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-153">The name of the streaming job.</span></span>
            </param>
        <param name="outputName">
            <span data-ttu-id="30ad3-154">出力の名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-154">The name of the output.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="30ad3-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="30ad3-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="30ad3-156">ストリーミング ジョブから出力を削除します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-156">Deletes an output from the streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Output Get (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Output Get(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IOutputsOperations, resourceGroupName As String, jobName As String, outputName As String) As Output" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Output" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.Get (operations, resourceGroupName, jobName, outputName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Output</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="30ad3-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="30ad3-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="30ad3-158">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-158">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="30ad3-159">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-159">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="30ad3-160">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-160">The name of the streaming job.</span></span>
            </param>
        <param name="outputName">
            <span data-ttu-id="30ad3-161">出力の名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-161">The name of the output.</span></span>
            </param>
        <summary>
            <span data-ttu-id="30ad3-162">指定された出力に関する詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-162">Gets details about the specified output.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, outputName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="30ad3-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="30ad3-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="30ad3-164">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-164">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="30ad3-165">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-165">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="30ad3-166">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-166">The name of the streaming job.</span></span>
            </param>
        <param name="outputName">
            <span data-ttu-id="30ad3-167">出力の名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-167">The name of the output.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="30ad3-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="30ad3-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="30ad3-169">指定された出力に関する詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-169">Gets details about the specified output.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; ListByStreamingJob (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string select = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; ListByStreamingJob(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string select) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.ListByStreamingJob(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJob (operations As IOutputsOperations, resourceGroupName As String, jobName As String, Optional select As String = null) As IPage(Of Output)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJob : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.ListByStreamingJob (operations, resourceGroupName, jobName, select)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="30ad3-170">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="30ad3-170">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="30ad3-171">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-171">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="30ad3-172">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-172">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="30ad3-173">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-173">The name of the streaming job.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="30ad3-174">$Select OData クエリ パラメーター。</span><span class="sxs-lookup"><span data-stu-id="30ad3-174">The $select OData query parameter.</span></span> <span data-ttu-id="30ad3-175">これは、応答に含める構造型プロパティのコンマ区切りの一覧または"*"すべてのプロパティを含めます。既定では、診断を除くすべてのプロパティが返されます。現在のみを受け入れる '*' 有効な値として。</span><span class="sxs-lookup"><span data-stu-id="30ad3-175">This is a comma-separated list of structural properties to include in the response, or “*” to include all properties. By default, all properties are returned except diagnostics. Currently only accepts '*' as a valid value.</span></span>
            </param>
        <summary>
            <span data-ttu-id="30ad3-176">すべての指定したストリーミング ジョブの下で出力を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-176">Lists all of the outputs under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;&gt; ListByStreamingJobAsync (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;&gt; ListByStreamingJobAsync(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.ListByStreamingJobAsync(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobAsync : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.ListByStreamingJobAsync (operations, resourceGroupName, jobName, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions/&lt;ListByStreamingJobAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="30ad3-177">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="30ad3-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="30ad3-178">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-178">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="30ad3-179">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-179">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="30ad3-180">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-180">The name of the streaming job.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="30ad3-181">$Select OData クエリ パラメーター。</span><span class="sxs-lookup"><span data-stu-id="30ad3-181">The $select OData query parameter.</span></span> <span data-ttu-id="30ad3-182">これは、応答に含める構造型プロパティのコンマ区切りの一覧または"*"すべてのプロパティを含めます。既定では、診断を除くすべてのプロパティが返されます。現在のみを受け入れる '*' 有効な値として。</span><span class="sxs-lookup"><span data-stu-id="30ad3-182">This is a comma-separated list of structural properties to include in the response, or “*” to include all properties. By default, all properties are returned except diagnostics. Currently only accepts '*' as a valid value.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="30ad3-183">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="30ad3-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="30ad3-184">すべての指定したストリーミング ジョブの下で出力を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-184">Lists all of the outputs under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; ListByStreamingJobNext (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; ListByStreamingJobNext(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.ListByStreamingJobNext(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJobNext (operations As IOutputsOperations, nextPageLink As String) As IPage(Of Output)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNext : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.ListByStreamingJobNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="30ad3-185">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="30ad3-185">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="30ad3-186">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="30ad3-186">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="30ad3-187">すべての指定したストリーミング ジョブの下で出力を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-187">Lists all of the outputs under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;&gt; ListByStreamingJobNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;&gt; ListByStreamingJobNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.ListByStreamingJobNextAsync(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNextAsync : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.ListByStreamingJobNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions/&lt;ListByStreamingJobNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="30ad3-188">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="30ad3-188">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="30ad3-189">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="30ad3-189">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="30ad3-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="30ad3-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="30ad3-191">すべての指定したストリーミング ジョブの下で出力を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-191">Lists all of the outputs under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Test">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, Microsoft.Azure.Management.StreamAnalytics.Models.Output output = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Output output) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.Test(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Output)" />
      <MemberSignature Language="F#" Value="static member Test : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Output -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.Test (operations, resourceGroupName, jobName, outputName, output)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="30ad3-192">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="30ad3-192">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="30ad3-193">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-193">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="30ad3-194">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-194">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="30ad3-195">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-195">The name of the streaming job.</span></span>
            </param>
        <param name="outputName">
            <span data-ttu-id="30ad3-196">出力の名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-196">The name of the output.</span></span>
            </param>
        <param name="output">
            <span data-ttu-id="30ad3-197">指定された出力が既に存在しない場合、このパラメーターは、テストするためのもので、完全な出力の定義を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="30ad3-197">If the output specified does not already exist, this parameter must contain the full output definition intended to be tested.</span></span> <span data-ttu-id="30ad3-198">このパラメーターは省略可能、既存の出力が格納されるかをテストする場合は null または (PATCH 操作) とまったく同じ既存の出力と、その結果で対応するプロパティを指定したプロパティが上書きされます、指定した場合の出力が既に指定されて存在する場合、出力がテストされます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-198">If the output specified already exists, this parameter can be left null to test the existing output as is or if specified, the properties specified will overwrite the corresponding properties in the existing output (exactly like a PATCH operation) and the resulting output will be tested.</span></span>
            </param>
        <summary>
            <span data-ttu-id="30ad3-199">出力のデータ ソースが到達可能で、Azure Stream Analytics サービスで使用できるかどうかをテストします。</span><span class="sxs-lookup"><span data-stu-id="30ad3-199">Tests whether an output’s datasource is reachable and usable by the Azure Stream Analytics service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, Microsoft.Azure.Management.StreamAnalytics.Models.Output output = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Output output, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.TestAsync(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Output,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TestAsync : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Output * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.TestAsync (operations, resourceGroupName, jobName, outputName, output, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions/&lt;TestAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="30ad3-200">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="30ad3-200">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="30ad3-201">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-201">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="30ad3-202">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-202">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="30ad3-203">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-203">The name of the streaming job.</span></span>
            </param>
        <param name="outputName">
            <span data-ttu-id="30ad3-204">出力の名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-204">The name of the output.</span></span>
            </param>
        <param name="output">
            <span data-ttu-id="30ad3-205">指定された出力が既に存在しない場合、このパラメーターは、テストするためのもので、完全な出力の定義を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="30ad3-205">If the output specified does not already exist, this parameter must contain the full output definition intended to be tested.</span></span> <span data-ttu-id="30ad3-206">このパラメーターは省略可能、既存の出力が格納されるかをテストする場合は null または (PATCH 操作) とまったく同じ既存の出力と、その結果で対応するプロパティを指定したプロパティが上書きされます、指定した場合の出力が既に指定されて存在する場合、出力がテストされます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-206">If the output specified already exists, this parameter can be left null to test the existing output as is or if specified, the properties specified will overwrite the corresponding properties in the existing output (exactly like a PATCH operation) and the resulting output will be tested.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="30ad3-207">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="30ad3-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="30ad3-208">出力のデータ ソースが到達可能で、Azure Stream Analytics サービスで使用できるかどうかをテストします。</span><span class="sxs-lookup"><span data-stu-id="30ad3-208">Tests whether an output’s datasource is reachable and usable by the Azure Stream Analytics service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Output Update (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Output output, string resourceGroupName, string jobName, string outputName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Output Update(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Output output, string resourceGroupName, string jobName, string outputName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Output,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Output * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Output" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.Update (operations, output, resourceGroupName, jobName, outputName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Output</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="30ad3-209">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="30ad3-209">The operations group for this extension method.</span></span>
            </param>
        <param name="output">
            <span data-ttu-id="30ad3-210">出力オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="30ad3-210">An Output object.</span></span> <span data-ttu-id="30ad3-211">ここで指定されたプロパティ (ie 既存の出力に対応するプロパティが上書きされます。そのプロパティが更新されます)。</span><span class="sxs-lookup"><span data-stu-id="30ad3-211">The properties specified here will overwrite the corresponding properties in the existing output (ie. Those properties will be updated).</span></span> <span data-ttu-id="30ad3-212">ここでは null に設定されている任意のプロパティがありことを意味、既存の出力に対応するプロパティは同じままこの PATCH 操作の結果として変更されません。</span><span class="sxs-lookup"><span data-stu-id="30ad3-212">Any properties that are set to null here will mean that the corresponding property in the existing output will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="30ad3-213">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-213">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="30ad3-214">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-214">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="30ad3-215">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-215">The name of the streaming job.</span></span>
            </param>
        <param name="outputName">
            <span data-ttu-id="30ad3-216">出力の名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-216">The name of the output.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="30ad3-217">出力の ETag です。</span><span class="sxs-lookup"><span data-stu-id="30ad3-217">The ETag of the output.</span></span> <span data-ttu-id="30ad3-218">常に現在の出力を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-218">Omit this value to always overwrite the current output.</span></span> <span data-ttu-id="30ad3-219">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-219">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="30ad3-220">既存のストリーミング ジョブの下にある既存の出力を更新します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-220">Updates an existing output under an existing streaming job.</span></span> <span data-ttu-id="30ad3-221">これは、(ie 部分的に更新を使用できます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-221">This can be used to partially update (ie.</span></span> <span data-ttu-id="30ad3-222">1 つまたは 2 つのプロパティの更新)、残りのジョブまたは出力の定義に影響を与えずに出力します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-222">update one or two properties) an output without affecting the rest the job or output definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Output output, string resourceGroupName, string jobName, string outputName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Output output, string resourceGroupName, string jobName, string outputName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Output,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Output * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.UpdateAsync (operations, output, resourceGroupName, jobName, outputName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="30ad3-223">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="30ad3-223">The operations group for this extension method.</span></span>
            </param>
        <param name="output">
            <span data-ttu-id="30ad3-224">出力オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="30ad3-224">An Output object.</span></span> <span data-ttu-id="30ad3-225">ここで指定されたプロパティ (ie 既存の出力に対応するプロパティが上書きされます。そのプロパティが更新されます)。</span><span class="sxs-lookup"><span data-stu-id="30ad3-225">The properties specified here will overwrite the corresponding properties in the existing output (ie. Those properties will be updated).</span></span> <span data-ttu-id="30ad3-226">ここでは null に設定されている任意のプロパティがありことを意味、既存の出力に対応するプロパティは同じままこの PATCH 操作の結果として変更されません。</span><span class="sxs-lookup"><span data-stu-id="30ad3-226">Any properties that are set to null here will mean that the corresponding property in the existing output will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="30ad3-227">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-227">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="30ad3-228">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-228">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="30ad3-229">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-229">The name of the streaming job.</span></span>
            </param>
        <param name="outputName">
            <span data-ttu-id="30ad3-230">出力の名前。</span><span class="sxs-lookup"><span data-stu-id="30ad3-230">The name of the output.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="30ad3-231">出力の ETag です。</span><span class="sxs-lookup"><span data-stu-id="30ad3-231">The ETag of the output.</span></span> <span data-ttu-id="30ad3-232">常に現在の出力を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-232">Omit this value to always overwrite the current output.</span></span> <span data-ttu-id="30ad3-233">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-233">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="30ad3-234">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="30ad3-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="30ad3-235">既存のストリーミング ジョブの下にある既存の出力を更新します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-235">Updates an existing output under an existing streaming job.</span></span> <span data-ttu-id="30ad3-236">これは、(ie 部分的に更新を使用できます。</span><span class="sxs-lookup"><span data-stu-id="30ad3-236">This can be used to partially update (ie.</span></span> <span data-ttu-id="30ad3-237">1 つまたは 2 つのプロパティの更新)、残りのジョブまたは出力の定義に影響を与えずに出力します。</span><span class="sxs-lookup"><span data-stu-id="30ad3-237">update one or two properties) an output without affecting the rest the job or output definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>