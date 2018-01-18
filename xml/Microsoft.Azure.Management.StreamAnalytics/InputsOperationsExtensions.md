<Type Name="InputsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class InputsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit InputsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module InputsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type InputsOperationsExtensions = class" />
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
            <span data-ttu-id="86f59-101">InputsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="86f59-101">Extension methods for InputsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginTest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.BeginTest(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input)" />
      <MemberSignature Language="F#" Value="static member BeginTest : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.BeginTest (operations, resourceGroupName, jobName, inputName, input)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86f59-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86f59-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86f59-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="86f59-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="86f59-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="86f59-105">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-105">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="86f59-106">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-106">The name of the input.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="86f59-107">指定された入力が既に存在しない場合、このパラメーターは、テストするためのもので、完全な入力定義を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="86f59-107">If the input specified does not already exist, this parameter must contain the full input definition intended to be tested.</span></span> <span data-ttu-id="86f59-108">既に指定した入力が存在する場合、このパラメーターは省略可能、既存の現状有姿の入力をテストする場合は null またはプロパティが指定されましたが (PATCH 操作) とまったく同じ既存の入力と、その結果で対応するプロパティを上書き指定した場合入力がテストされます。</span><span class="sxs-lookup"><span data-stu-id="86f59-108">If the input specified already exists, this parameter can be left null to test the existing input as is or if specified, the properties specified will overwrite the corresponding properties in the existing input (exactly like a PATCH operation) and the resulting input will be tested.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86f59-109">入力のデータ ソースが到達可能で、Azure Stream Analytics サービスで使用できるかどうかをテストします。</span><span class="sxs-lookup"><span data-stu-id="86f59-109">Tests whether an input’s datasource is reachable and usable by the Azure Stream Analytics service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginTestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.BeginTestAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginTestAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.BeginTestAsync (operations, resourceGroupName, jobName, inputName, input, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;BeginTestAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86f59-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86f59-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86f59-111">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-111">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="86f59-112">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="86f59-112">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="86f59-113">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-113">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="86f59-114">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-114">The name of the input.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="86f59-115">指定された入力が既に存在しない場合、このパラメーターは、テストするためのもので、完全な入力定義を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="86f59-115">If the input specified does not already exist, this parameter must contain the full input definition intended to be tested.</span></span> <span data-ttu-id="86f59-116">既に指定した入力が存在する場合、このパラメーターは省略可能、既存の現状有姿の入力をテストする場合は null またはプロパティが指定されましたが (PATCH 操作) とまったく同じ既存の入力と、その結果で対応するプロパティを上書き指定した場合入力がテストされます。</span><span class="sxs-lookup"><span data-stu-id="86f59-116">If the input specified already exists, this parameter can be left null to test the existing input as is or if specified, the properties specified will overwrite the corresponding properties in the existing input (exactly like a PATCH operation) and the resulting input will be tested.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="86f59-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="86f59-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86f59-118">入力のデータ ソースが到達可能で、Azure Stream Analytics サービスで使用できるかどうかをテストします。</span><span class="sxs-lookup"><span data-stu-id="86f59-118">Tests whether an input’s datasource is reachable and usable by the Azure Stream Analytics service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Input CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Input CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Input" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.CreateOrReplace (operations, input, resourceGroupName, jobName, inputName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Input</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86f59-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86f59-119">The operations group for this extension method.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="86f59-120">新しい入力を作成するか、ストリーミング ジョブの下にある既存のものを置き換えるに使用される入力の定義。</span><span class="sxs-lookup"><span data-stu-id="86f59-120">The definition of the input that will be used to create a new input or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86f59-121">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-121">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="86f59-122">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="86f59-122">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="86f59-123">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-123">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="86f59-124">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-124">The name of the input.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="86f59-125">入力の ETag です。</span><span class="sxs-lookup"><span data-stu-id="86f59-125">The ETag of the input.</span></span> <span data-ttu-id="86f59-126">常に現在の入力を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="86f59-126">Omit this value to always overwrite the current input.</span></span> <span data-ttu-id="86f59-127">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="86f59-127">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="86f59-128">設定 ' \*' を作成するが、既存の入力の更新を防ぐために、新しい入力を許可します。</span><span class="sxs-lookup"><span data-stu-id="86f59-128">Set to '\*' to allow a new input to be created, but to prevent updating an existing input.</span></span> <span data-ttu-id="86f59-129">その他の値は、412 の前提条件が失敗の応答になります。</span><span class="sxs-lookup"><span data-stu-id="86f59-129">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86f59-130">入力を作成するか、既存のストリーミング ジョブの下で、既に既存の入力を置き換えます。</span><span class="sxs-lookup"><span data-stu-id="86f59-130">Creates an input or replaces an already existing input under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.CreateOrReplaceAsync (operations, input, resourceGroupName, jobName, inputName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86f59-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86f59-131">The operations group for this extension method.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="86f59-132">新しい入力を作成するか、ストリーミング ジョブの下にある既存のものを置き換えるに使用される入力の定義。</span><span class="sxs-lookup"><span data-stu-id="86f59-132">The definition of the input that will be used to create a new input or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86f59-133">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-133">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="86f59-134">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="86f59-134">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="86f59-135">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-135">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="86f59-136">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-136">The name of the input.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="86f59-137">入力の ETag です。</span><span class="sxs-lookup"><span data-stu-id="86f59-137">The ETag of the input.</span></span> <span data-ttu-id="86f59-138">常に現在の入力を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="86f59-138">Omit this value to always overwrite the current input.</span></span> <span data-ttu-id="86f59-139">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="86f59-139">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="86f59-140">設定 ' \*' を作成するが、既存の入力の更新を防ぐために、新しい入力を許可します。</span><span class="sxs-lookup"><span data-stu-id="86f59-140">Set to '\*' to allow a new input to be created, but to prevent updating an existing input.</span></span> <span data-ttu-id="86f59-141">その他の値は、412 の前提条件が失敗の応答になります。</span><span class="sxs-lookup"><span data-stu-id="86f59-141">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="86f59-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="86f59-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86f59-143">入力を作成するか、既存のストリーミング ジョブの下で、既に既存の入力を置き換えます。</span><span class="sxs-lookup"><span data-stu-id="86f59-143">Creates an input or replaces an already existing input under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Delete(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IInputsOperations, resourceGroupName As String, jobName As String, inputName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Delete (operations, resourceGroupName, jobName, inputName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86f59-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86f59-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86f59-145">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-145">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="86f59-146">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="86f59-146">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="86f59-147">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-147">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="86f59-148">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-148">The name of the input.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86f59-149">ストリーミング ジョブから入力を削除します。</span><span class="sxs-lookup"><span data-stu-id="86f59-149">Deletes an input from the streaming job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.DeleteAsync (operations, resourceGroupName, jobName, inputName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86f59-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86f59-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86f59-151">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-151">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="86f59-152">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="86f59-152">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="86f59-153">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-153">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="86f59-154">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-154">The name of the input.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="86f59-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="86f59-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86f59-156">ストリーミング ジョブから入力を削除します。</span><span class="sxs-lookup"><span data-stu-id="86f59-156">Deletes an input from the streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Input Get (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Input Get(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IInputsOperations, resourceGroupName As String, jobName As String, inputName As String) As Input" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Input" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Get (operations, resourceGroupName, jobName, inputName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Input</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86f59-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86f59-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86f59-158">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-158">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="86f59-159">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="86f59-159">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="86f59-160">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-160">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="86f59-161">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-161">The name of the input.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86f59-162">詳細については、指定された入力を取得します。</span><span class="sxs-lookup"><span data-stu-id="86f59-162">Gets details about the specified input.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, inputName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86f59-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86f59-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86f59-164">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-164">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="86f59-165">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="86f59-165">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="86f59-166">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-166">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="86f59-167">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-167">The name of the input.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="86f59-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="86f59-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86f59-169">詳細については、指定された入力を取得します。</span><span class="sxs-lookup"><span data-stu-id="86f59-169">Gets details about the specified input.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; ListByStreamingJob (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string select = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; ListByStreamingJob(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string select) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJob(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJob (operations As IInputsOperations, resourceGroupName As String, jobName As String, Optional select As String = null) As IPage(Of Input)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJob : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJob (operations, resourceGroupName, jobName, select)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86f59-170">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86f59-170">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86f59-171">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-171">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="86f59-172">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="86f59-172">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="86f59-173">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-173">The name of the streaming job.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="86f59-174">$Select OData クエリ パラメーター。</span><span class="sxs-lookup"><span data-stu-id="86f59-174">The $select OData query parameter.</span></span> <span data-ttu-id="86f59-175">これは、応答に含める構造型プロパティのコンマ区切りの一覧または"*"すべてのプロパティを含めます。既定では、診断を除くすべてのプロパティが返されます。現在のみを受け入れる '*' 有効な値として。</span><span class="sxs-lookup"><span data-stu-id="86f59-175">This is a comma-separated list of structural properties to include in the response, or “*” to include all properties. By default, all properties are returned except diagnostics. Currently only accepts '*' as a valid value.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86f59-176">すべての指定したストリーミング ジョブの下にある入力の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="86f59-176">Lists all of the inputs under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt; ListByStreamingJobAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt; ListByStreamingJobAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobAsync (operations, resourceGroupName, jobName, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;ListByStreamingJobAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86f59-177">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86f59-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86f59-178">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-178">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="86f59-179">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="86f59-179">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="86f59-180">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-180">The name of the streaming job.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="86f59-181">$Select OData クエリ パラメーター。</span><span class="sxs-lookup"><span data-stu-id="86f59-181">The $select OData query parameter.</span></span> <span data-ttu-id="86f59-182">これは、応答に含める構造型プロパティのコンマ区切りの一覧または"*"すべてのプロパティを含めます。既定では、診断を除くすべてのプロパティが返されます。現在のみを受け入れる '*' 有効な値として。</span><span class="sxs-lookup"><span data-stu-id="86f59-182">This is a comma-separated list of structural properties to include in the response, or “*” to include all properties. By default, all properties are returned except diagnostics. Currently only accepts '*' as a valid value.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="86f59-183">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="86f59-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86f59-184">すべての指定したストリーミング ジョブの下にある入力の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="86f59-184">Lists all of the inputs under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; ListByStreamingJobNext (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; ListByStreamingJobNext(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobNext(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJobNext (operations As IInputsOperations, nextPageLink As String) As IPage(Of Input)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNext : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86f59-185">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86f59-185">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="86f59-186">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="86f59-186">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86f59-187">すべての指定したストリーミング ジョブの下にある入力の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="86f59-187">Lists all of the inputs under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt; ListByStreamingJobNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt; ListByStreamingJobNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobNextAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNextAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;ListByStreamingJobNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86f59-188">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86f59-188">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="86f59-189">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="86f59-189">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="86f59-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="86f59-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86f59-191">すべての指定したストリーミング ジョブの下にある入力の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="86f59-191">Lists all of the inputs under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Test">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Test(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input)" />
      <MemberSignature Language="F#" Value="static member Test : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Test (operations, resourceGroupName, jobName, inputName, input)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86f59-192">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86f59-192">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86f59-193">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-193">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="86f59-194">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="86f59-194">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="86f59-195">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-195">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="86f59-196">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-196">The name of the input.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="86f59-197">指定された入力が既に存在しない場合、このパラメーターは、テストするためのもので、完全な入力定義を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="86f59-197">If the input specified does not already exist, this parameter must contain the full input definition intended to be tested.</span></span> <span data-ttu-id="86f59-198">既に指定した入力が存在する場合、このパラメーターは省略可能、既存の現状有姿の入力をテストする場合は null またはプロパティが指定されましたが (PATCH 操作) とまったく同じ既存の入力と、その結果で対応するプロパティを上書き指定した場合入力がテストされます。</span><span class="sxs-lookup"><span data-stu-id="86f59-198">If the input specified already exists, this parameter can be left null to test the existing input as is or if specified, the properties specified will overwrite the corresponding properties in the existing input (exactly like a PATCH operation) and the resulting input will be tested.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86f59-199">入力のデータ ソースが到達可能で、Azure Stream Analytics サービスで使用できるかどうかをテストします。</span><span class="sxs-lookup"><span data-stu-id="86f59-199">Tests whether an input’s datasource is reachable and usable by the Azure Stream Analytics service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.TestAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TestAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.TestAsync (operations, resourceGroupName, jobName, inputName, input, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;TestAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86f59-200">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86f59-200">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86f59-201">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-201">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="86f59-202">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="86f59-202">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="86f59-203">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-203">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="86f59-204">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-204">The name of the input.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="86f59-205">指定された入力が既に存在しない場合、このパラメーターは、テストするためのもので、完全な入力定義を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="86f59-205">If the input specified does not already exist, this parameter must contain the full input definition intended to be tested.</span></span> <span data-ttu-id="86f59-206">既に指定した入力が存在する場合、このパラメーターは省略可能、既存の現状有姿の入力をテストする場合は null またはプロパティが指定されましたが (PATCH 操作) とまったく同じ既存の入力と、その結果で対応するプロパティを上書き指定した場合入力がテストされます。</span><span class="sxs-lookup"><span data-stu-id="86f59-206">If the input specified already exists, this parameter can be left null to test the existing input as is or if specified, the properties specified will overwrite the corresponding properties in the existing input (exactly like a PATCH operation) and the resulting input will be tested.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="86f59-207">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="86f59-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86f59-208">入力のデータ ソースが到達可能で、Azure Stream Analytics サービスで使用できるかどうかをテストします。</span><span class="sxs-lookup"><span data-stu-id="86f59-208">Tests whether an input’s datasource is reachable and usable by the Azure Stream Analytics service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Input Update (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Input Update(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Input" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Update (operations, input, resourceGroupName, jobName, inputName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Input</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86f59-209">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86f59-209">The operations group for this extension method.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="86f59-210">入力オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="86f59-210">An Input object.</span></span> <span data-ttu-id="86f59-211">ここで指定されたプロパティ (ie 既存の入力の対応するプロパティが上書きされます。そのプロパティが更新されます)。</span><span class="sxs-lookup"><span data-stu-id="86f59-211">The properties specified here will overwrite the corresponding properties in the existing input (ie. Those properties will be updated).</span></span> <span data-ttu-id="86f59-212">ここでは null に設定されている任意のプロパティがありことを意味既存の入力の対応するプロパティは同じままこの PATCH 操作の結果として変更されません。</span><span class="sxs-lookup"><span data-stu-id="86f59-212">Any properties that are set to null here will mean that the corresponding property in the existing input will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86f59-213">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-213">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="86f59-214">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="86f59-214">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="86f59-215">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-215">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="86f59-216">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-216">The name of the input.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="86f59-217">入力の ETag です。</span><span class="sxs-lookup"><span data-stu-id="86f59-217">The ETag of the input.</span></span> <span data-ttu-id="86f59-218">常に現在の入力を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="86f59-218">Omit this value to always overwrite the current input.</span></span> <span data-ttu-id="86f59-219">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="86f59-219">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86f59-220">既存のストリーミング ジョブの下で、既存の入力を更新します。</span><span class="sxs-lookup"><span data-stu-id="86f59-220">Updates an existing input under an existing streaming job.</span></span> <span data-ttu-id="86f59-221">これは、(ie 部分的に更新を使用できます。</span><span class="sxs-lookup"><span data-stu-id="86f59-221">This can be used to partially update (ie.</span></span> <span data-ttu-id="86f59-222">1 つまたは 2 つのプロパティの更新)、残りのジョブまたは入力の定義に影響を与えずに入力します。</span><span class="sxs-lookup"><span data-stu-id="86f59-222">update one or two properties) an input without affecting the rest the job or input definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.UpdateAsync (operations, input, resourceGroupName, jobName, inputName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86f59-223">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86f59-223">The operations group for this extension method.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="86f59-224">入力オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="86f59-224">An Input object.</span></span> <span data-ttu-id="86f59-225">ここで指定されたプロパティ (ie 既存の入力の対応するプロパティが上書きされます。そのプロパティが更新されます)。</span><span class="sxs-lookup"><span data-stu-id="86f59-225">The properties specified here will overwrite the corresponding properties in the existing input (ie. Those properties will be updated).</span></span> <span data-ttu-id="86f59-226">ここでは null に設定されている任意のプロパティがありことを意味既存の入力の対応するプロパティは同じままこの PATCH 操作の結果として変更されません。</span><span class="sxs-lookup"><span data-stu-id="86f59-226">Any properties that are set to null here will mean that the corresponding property in the existing input will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86f59-227">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-227">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="86f59-228">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="86f59-228">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="86f59-229">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-229">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="86f59-230">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="86f59-230">The name of the input.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="86f59-231">入力の ETag です。</span><span class="sxs-lookup"><span data-stu-id="86f59-231">The ETag of the input.</span></span> <span data-ttu-id="86f59-232">常に現在の入力を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="86f59-232">Omit this value to always overwrite the current input.</span></span> <span data-ttu-id="86f59-233">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="86f59-233">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="86f59-234">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="86f59-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86f59-235">既存のストリーミング ジョブの下で、既存の入力を更新します。</span><span class="sxs-lookup"><span data-stu-id="86f59-235">Updates an existing input under an existing streaming job.</span></span> <span data-ttu-id="86f59-236">これは、(ie 部分的に更新を使用できます。</span><span class="sxs-lookup"><span data-stu-id="86f59-236">This can be used to partially update (ie.</span></span> <span data-ttu-id="86f59-237">1 つまたは 2 つのプロパティの更新)、残りのジョブまたは入力の定義に影響を与えずに入力します。</span><span class="sxs-lookup"><span data-stu-id="86f59-237">update one or two properties) an input without affecting the rest the job or input definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>