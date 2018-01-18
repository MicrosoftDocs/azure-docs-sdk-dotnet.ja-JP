<Type Name="DataLakeAnalyticsUSQLActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsUSQLActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsUSQLActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsUSQLActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsUSQLActivity = class&#xA;    inherit ExecutionActivity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("DataLakeAnalyticsU-SQL")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c1b82-101">データ Lake Analytics U-SQL アクティビティ。</span><span class="sxs-lookup"><span data-stu-id="c1b82-101">Data Lake Analytics U-SQL activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsUSQLActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c1b82-102">DataLakeAnalyticsUSQLActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c1b82-102">Initializes a new instance of the DataLakeAnalyticsUSQLActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsUSQLActivity (string name, object scriptPath, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference scriptLinkedService, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, object degreeOfParallelism = null, object priority = null, System.Collections.Generic.IDictionary&lt;string,object&gt; parameters = null, object runtimeVersion = null, object compilationMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object scriptPath, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference scriptLinkedService, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, object degreeOfParallelism, object priority, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; parameters, object runtimeVersion, object compilationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.#ctor(System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, scriptPath As Object, scriptLinkedService As LinkedServiceReference, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional degreeOfParallelism As Object = null, Optional priority As Object = null, Optional parameters As IDictionary(Of String, Object) = null, Optional runtimeVersion As Object = null, Optional compilationMode As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity : string * obj * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity (name, scriptPath, scriptLinkedService, additionalProperties, description, dependsOn, linkedServiceName, policy, degreeOfParallelism, priority, parameters, runtimeVersion, compilationMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="scriptPath" Type="System.Object" />
        <Parameter Name="scriptLinkedService" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="degreeOfParallelism" Type="System.Object" />
        <Parameter Name="priority" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="runtimeVersion" Type="System.Object" />
        <Parameter Name="compilationMode" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c1b82-103">アクティビティ名。</span><span class="sxs-lookup"><span data-stu-id="c1b82-103">Activity name.</span></span></param>
        <param name="scriptPath"><span data-ttu-id="c1b82-104">大文字小文字を区別フォルダー パスを U-SQL スクリプトが含まれています。</span><span class="sxs-lookup"><span data-stu-id="c1b82-104">Case-sensitive path to folder that contains the U-SQL script.</span></span> <span data-ttu-id="c1b82-105">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c1b82-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="scriptLinkedService"><span data-ttu-id="c1b82-106">スクリプトには、サービス参照の追加がリンクされています。</span><span class="sxs-lookup"><span data-stu-id="c1b82-106">Script linked service reference.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="c1b82-107">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="c1b82-107">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="c1b82-108">アクティビティの説明です。</span><span class="sxs-lookup"><span data-stu-id="c1b82-108">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="c1b82-109">アクティビティは、条件によって異なります。</span><span class="sxs-lookup"><span data-stu-id="c1b82-109">Activity depends on condition.</span></span></param>
        <param name="linkedServiceName"><span data-ttu-id="c1b82-110">リンクされたサービスの参照。</span><span class="sxs-lookup"><span data-stu-id="c1b82-110">Linked service reference.</span></span></param>
        <param name="policy"><span data-ttu-id="c1b82-111">アクティビティ ポリシー。</span><span class="sxs-lookup"><span data-stu-id="c1b82-111">Activity policy.</span></span></param>
        <param name="degreeOfParallelism"><span data-ttu-id="c1b82-112">ジョブを実行するために同時に使用される最大ノード数。</span><span class="sxs-lookup"><span data-stu-id="c1b82-112">The maximum number of nodes simultaneously used to run the job.</span></span> <span data-ttu-id="c1b82-113">既定値は 1 です。</span><span class="sxs-lookup"><span data-stu-id="c1b82-113">Default value is 1.</span></span> <span data-ttu-id="c1b82-114">型: 整数 (または式と resultType 整数)、最小値。</span><span class="sxs-lookup"><span data-stu-id="c1b82-114">Type: integer (or Expression with resultType integer), minimum:</span></span>
            1.</param>
        <param name="priority"><span data-ttu-id="c1b82-115">キューされているすべてのジョブのうち、先に実行するジョブを決定します。</span><span class="sxs-lookup"><span data-stu-id="c1b82-115">Determines which jobs out of all that are queued should be selected to run first.</span></span> <span data-ttu-id="c1b82-116">数値が小さいほど、優先度は高くなります。</span><span class="sxs-lookup"><span data-stu-id="c1b82-116">The lower the number, the higher the priority.</span></span> <span data-ttu-id="c1b82-117">既定値は 1,000 です。</span><span class="sxs-lookup"><span data-stu-id="c1b82-117">Default value is 1000.</span></span> <span data-ttu-id="c1b82-118">型: 整数 (または式と resultType 整数)、最小値: 1。</span><span class="sxs-lookup"><span data-stu-id="c1b82-118">Type: integer (or Expression with resultType integer), minimum: 1.</span></span></param>
        <param name="parameters"><span data-ttu-id="c1b82-119">U-SQL ジョブ要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c1b82-119">Parameters for U-SQL job request.</span></span></param>
        <param name="runtimeVersion"><span data-ttu-id="c1b82-120">使用する U SQL エンジンのランタイムのバージョン。</span><span class="sxs-lookup"><span data-stu-id="c1b82-120">Runtime version of the U-SQL engine to use.</span></span> <span data-ttu-id="c1b82-121">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c1b82-121">Type: string (or Expression with resultType string).</span></span></param>
        <param name="compilationMode"><span data-ttu-id="c1b82-122">U-SQL のコンパイル モード。</span><span class="sxs-lookup"><span data-stu-id="c1b82-122">Compilation mode of U-SQL.</span></span> <span data-ttu-id="c1b82-123">これらの値のいずれかを指定する必要があります: セマンティック、フル インストール オプションと SingleBox です。</span><span class="sxs-lookup"><span data-stu-id="c1b82-123">Must be one of these values : Semantic, Full and SingleBox.</span></span> <span data-ttu-id="c1b82-124">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c1b82-124">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="c1b82-125">DataLakeAnalyticsUSQLActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c1b82-125">Initializes a new instance of the DataLakeAnalyticsUSQLActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompilationMode">
      <MemberSignature Language="C#" Value="public object CompilationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object CompilationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.CompilationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property CompilationMode As Object" />
      <MemberSignature Language="F#" Value="member this.CompilationMode : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.CompilationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.compilationMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1b82-126">取得または U SQL のコンパイル モードを設定します。</span><span class="sxs-lookup"><span data-stu-id="c1b82-126">Gets or sets compilation mode of U-SQL.</span></span> <span data-ttu-id="c1b82-127">これらの値のいずれかを指定する必要があります: セマンティック、フル インストール オプションと SingleBox です。</span><span class="sxs-lookup"><span data-stu-id="c1b82-127">Must be one of these values : Semantic, Full and SingleBox.</span></span> <span data-ttu-id="c1b82-128">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c1b82-128">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DegreeOfParallelism">
      <MemberSignature Language="C#" Value="public object DegreeOfParallelism { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object DegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.DegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public Property DegreeOfParallelism As Object" />
      <MemberSignature Language="F#" Value="member this.DegreeOfParallelism : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.DegreeOfParallelism" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.degreeOfParallelism")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1b82-129">取得またはジョブの実行に同時に使用されるノードの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="c1b82-129">Gets or sets the maximum number of nodes simultaneously used to run the job.</span></span> <span data-ttu-id="c1b82-130">既定値は 1 です。</span><span class="sxs-lookup"><span data-stu-id="c1b82-130">Default value is 1.</span></span> <span data-ttu-id="c1b82-131">型: 整数 (または式と resultType 整数)、最小値: 1。</span><span class="sxs-lookup"><span data-stu-id="c1b82-131">Type: integer (or Expression with resultType integer), minimum: 1.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1b82-132">取得または U-SQL ジョブ要求のパラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="c1b82-132">Gets or sets parameters for U-SQL job request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public object Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Object" />
      <MemberSignature Language="F#" Value="member this.Priority : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1b82-133">取得または設定は、最初に実行するどのジョブからすべてのキューに入っていることを選択する必要がありますを決定します。</span><span class="sxs-lookup"><span data-stu-id="c1b82-133">Gets or sets determines which jobs out of all that are queued should be selected to run first.</span></span> <span data-ttu-id="c1b82-134">数値が小さいほど、優先度は高くなります。</span><span class="sxs-lookup"><span data-stu-id="c1b82-134">The lower the number, the higher the priority.</span></span> <span data-ttu-id="c1b82-135">既定値は 1,000 です。</span><span class="sxs-lookup"><span data-stu-id="c1b82-135">Default value is 1000.</span></span> <span data-ttu-id="c1b82-136">型: 整数 (または式と resultType 整数)、最小値: 1。</span><span class="sxs-lookup"><span data-stu-id="c1b82-136">Type: integer (or Expression with resultType integer), minimum: 1.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeVersion">
      <MemberSignature Language="C#" Value="public object RuntimeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RuntimeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.RuntimeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property RuntimeVersion As Object" />
      <MemberSignature Language="F#" Value="member this.RuntimeVersion : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.RuntimeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.runtimeVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1b82-137">取得または使用する U SQL エンジンのランタイムのバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="c1b82-137">Gets or sets runtime version of the U-SQL engine to use.</span></span> <span data-ttu-id="c1b82-138">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c1b82-138">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptLinkedService">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference ScriptLinkedService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference ScriptLinkedService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptLinkedService As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.ScriptLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.scriptLinkedService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1b82-139">取得またはサービス参照のリンクされているスクリプトを設定します。</span><span class="sxs-lookup"><span data-stu-id="c1b82-139">Gets or sets script linked service reference.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptPath">
      <MemberSignature Language="C#" Value="public object ScriptPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ScriptPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptPath As Object" />
      <MemberSignature Language="F#" Value="member this.ScriptPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.scriptPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1b82-140">取得または U-SQL スクリプトを含むフォルダーに区別するパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="c1b82-140">Gets or sets case-sensitive path to folder that contains the U-SQL script.</span></span> <span data-ttu-id="c1b82-141">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="c1b82-141">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="dataLakeAnalyticsUSQLActivity.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c1b82-142">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="c1b82-142">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c1b82-143">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c1b82-143">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>