<Type Name="HDInsightStreamingActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity">
  <TypeSignature Language="C#" Value="public class HDInsightStreamingActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HDInsightStreamingActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class HDInsightStreamingActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type HDInsightStreamingActivity = class&#xA;    inherit ExecutionActivity" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("HDInsightStreaming")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5be81-101">HDInsight ストリーミング アクティビティの種類。</span><span class="sxs-lookup"><span data-stu-id="5be81-101">HDInsight streaming activity type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightStreamingActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.#ctor" />
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
            <span data-ttu-id="5be81-102">HDInsightStreamingActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5be81-102">Initializes a new instance of the HDInsightStreamingActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightStreamingActivity (string name, object mapper, object reducer, object input, object output, System.Collections.Generic.IList&lt;object&gt; filePaths, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; storageLinkedServices = null, System.Collections.Generic.IList&lt;object&gt; arguments = null, string getDebugInfo = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference fileLinkedService = null, object combiner = null, System.Collections.Generic.IList&lt;object&gt; commandEnvironment = null, System.Collections.Generic.IDictionary&lt;string,object&gt; defines = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object mapper, object reducer, object input, object output, class System.Collections.Generic.IList`1&lt;object&gt; filePaths, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; storageLinkedServices, class System.Collections.Generic.IList`1&lt;object&gt; arguments, string getDebugInfo, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference fileLinkedService, object combiner, class System.Collections.Generic.IList`1&lt;object&gt; commandEnvironment, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; defines) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.#ctor(System.String,System.Object,System.Object,System.Object,System.Object,System.Collections.Generic.IList{System.Object},System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference},System.Collections.Generic.IList{System.Object},System.String,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object,System.Collections.Generic.IList{System.Object},System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, mapper As Object, reducer As Object, input As Object, output As Object, filePaths As IList(Of Object), Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional storageLinkedServices As IList(Of LinkedServiceReference) = null, Optional arguments As IList(Of Object) = null, Optional getDebugInfo As String = null, Optional fileLinkedService As LinkedServiceReference = null, Optional combiner As Object = null, Optional commandEnvironment As IList(Of Object) = null, Optional defines As IDictionary(Of String, Object) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity : string * obj * obj * obj * obj * System.Collections.Generic.IList&lt;obj&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; * System.Collections.Generic.IList&lt;obj&gt; * string * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj * System.Collections.Generic.IList&lt;obj&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity (name, mapper, reducer, input, output, filePaths, additionalProperties, description, dependsOn, linkedServiceName, policy, storageLinkedServices, arguments, getDebugInfo, fileLinkedService, combiner, commandEnvironment, defines)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="mapper" Type="System.Object" />
        <Parameter Name="reducer" Type="System.Object" />
        <Parameter Name="input" Type="System.Object" />
        <Parameter Name="output" Type="System.Object" />
        <Parameter Name="filePaths" Type="System.Collections.Generic.IList&lt;System.Object&gt;" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="storageLinkedServices" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt;" />
        <Parameter Name="arguments" Type="System.Collections.Generic.IList&lt;System.Object&gt;" />
        <Parameter Name="getDebugInfo" Type="System.String" />
        <Parameter Name="fileLinkedService" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="combiner" Type="System.Object" />
        <Parameter Name="commandEnvironment" Type="System.Collections.Generic.IList&lt;System.Object&gt;" />
        <Parameter Name="defines" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5be81-103">アクティビティ名。</span><span class="sxs-lookup"><span data-stu-id="5be81-103">Activity name.</span></span></param>
        <param name="mapper"><span data-ttu-id="5be81-104">マッパー実行可能ファイル名。</span><span class="sxs-lookup"><span data-stu-id="5be81-104">Mapper executable name.</span></span> <span data-ttu-id="5be81-105">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5be81-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="reducer"><span data-ttu-id="5be81-106">Reducer 実行可能ファイル名。</span><span class="sxs-lookup"><span data-stu-id="5be81-106">Reducer executable name.</span></span> <span data-ttu-id="5be81-107">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5be81-107">Type: string (or Expression with resultType string).</span></span></param>
        <param name="input"><span data-ttu-id="5be81-108">入力 blob のパス。</span><span class="sxs-lookup"><span data-stu-id="5be81-108">Input blob path.</span></span> <span data-ttu-id="5be81-109">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5be81-109">Type: string (or Expression with resultType string).</span></span></param>
        <param name="output"><span data-ttu-id="5be81-110">出力 blob パス。</span><span class="sxs-lookup"><span data-stu-id="5be81-110">Output blob path.</span></span> <span data-ttu-id="5be81-111">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5be81-111">Type: string (or Expression with resultType string).</span></span></param>
        <param name="filePaths"><span data-ttu-id="5be81-112">ストリーミング ジョブ ファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="5be81-112">Paths to streaming job files.</span></span> <span data-ttu-id="5be81-113">ディレクトリを指定できます。</span><span class="sxs-lookup"><span data-stu-id="5be81-113">Can be directories.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="5be81-114">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="5be81-114">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="5be81-115">アクティビティの説明です。</span><span class="sxs-lookup"><span data-stu-id="5be81-115">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="5be81-116">アクティビティは、条件によって異なります。</span><span class="sxs-lookup"><span data-stu-id="5be81-116">Activity depends on condition.</span></span></param>
        <param name="linkedServiceName"><span data-ttu-id="5be81-117">リンクされたサービスの参照。</span><span class="sxs-lookup"><span data-stu-id="5be81-117">Linked service reference.</span></span></param>
        <param name="policy"><span data-ttu-id="5be81-118">アクティビティ ポリシー。</span><span class="sxs-lookup"><span data-stu-id="5be81-118">Activity policy.</span></span></param>
        <param name="storageLinkedServices"><span data-ttu-id="5be81-119">ストレージのリンクされたサービスの参照。</span><span class="sxs-lookup"><span data-stu-id="5be81-119">Storage linked service references.</span></span></param>
        <param name="arguments"><span data-ttu-id="5be81-120">ユーザーは、HDInsightActivity への引数を指定します。</span><span class="sxs-lookup"><span data-stu-id="5be81-120">User specified arguments to HDInsightActivity.</span></span></param>
        <param name="getDebugInfo"><span data-ttu-id="5be81-121">デバッグ情報のオプションです。</span><span class="sxs-lookup"><span data-stu-id="5be81-121">Debug info option.</span></span> <span data-ttu-id="5be81-122">使用可能な値が含まれます 'None'、'Always' に 'Failure'。</span><span class="sxs-lookup"><span data-stu-id="5be81-122">Possible values include: 'None', 'Always', 'Failure'</span></span></param>
        <param name="fileLinkedService"><span data-ttu-id="5be81-123">ファイルが配置されているリンクされたサービスの参照。</span><span class="sxs-lookup"><span data-stu-id="5be81-123">Linked service reference where the files are located.</span></span></param>
        <param name="combiner"><span data-ttu-id="5be81-124">実行可能ファイル名を結合します。</span><span class="sxs-lookup"><span data-stu-id="5be81-124">Combiner executable name.</span></span> <span data-ttu-id="5be81-125">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5be81-125">Type: string (or Expression with resultType string).</span></span></param>
        <param name="commandEnvironment"><span data-ttu-id="5be81-126">コマンドライン環境の値です。</span><span class="sxs-lookup"><span data-stu-id="5be81-126">Command line environment values.</span></span></param>
        <param name="defines"><span data-ttu-id="5be81-127">ストリーミング ジョブの要求を指定するユーザーを定義します。</span><span class="sxs-lookup"><span data-stu-id="5be81-127">Allows user to specify defines for streaming job request.</span></span></param>
        <summary>
            <span data-ttu-id="5be81-128">HDInsightStreamingActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5be81-128">Initializes a new instance of the HDInsightStreamingActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Arguments">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;object&gt; Arguments { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;object&gt; Arguments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.Arguments" />
      <MemberSignature Language="VB.NET" Value="Public Property Arguments As IList(Of Object)" />
      <MemberSignature Language="F#" Value="member this.Arguments : System.Collections.Generic.IList&lt;obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.Arguments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.arguments")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5be81-129">指定されたユーザーの設定を取得または HDInsightActivity への引数。</span><span class="sxs-lookup"><span data-stu-id="5be81-129">Gets or sets user specified arguments to HDInsightActivity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Combiner">
      <MemberSignature Language="C#" Value="public object Combiner { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Combiner" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.Combiner" />
      <MemberSignature Language="VB.NET" Value="Public Property Combiner As Object" />
      <MemberSignature Language="F#" Value="member this.Combiner : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.Combiner" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.combiner")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5be81-130">取得または結合の実行可能ファイル名を設定します。</span><span class="sxs-lookup"><span data-stu-id="5be81-130">Gets or sets combiner executable name.</span></span> <span data-ttu-id="5be81-131">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5be81-131">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandEnvironment">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;object&gt; CommandEnvironment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;object&gt; CommandEnvironment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.CommandEnvironment" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandEnvironment As IList(Of Object)" />
      <MemberSignature Language="F#" Value="member this.CommandEnvironment : System.Collections.Generic.IList&lt;obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.CommandEnvironment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.commandEnvironment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5be81-132">取得またはコマンド ライン環境値を設定します。</span><span class="sxs-lookup"><span data-stu-id="5be81-132">Gets or sets command line environment values.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defines">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Defines { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Defines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.Defines" />
      <MemberSignature Language="VB.NET" Value="Public Property Defines As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Defines : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.Defines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.defines")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5be81-133">取得または設定は、ストリーミング ジョブの要求を指定するユーザーを定義します。</span><span class="sxs-lookup"><span data-stu-id="5be81-133">Gets or sets allows user to specify defines for streaming job request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileLinkedService">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference FileLinkedService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference FileLinkedService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.FileLinkedService" />
      <MemberSignature Language="VB.NET" Value="Public Property FileLinkedService As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.FileLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.FileLinkedService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.fileLinkedService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5be81-134">取得またはファイルが配置されているリンクされたサービス参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="5be81-134">Gets or sets linked service reference where the files are located.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePaths">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;object&gt; FilePaths { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;object&gt; FilePaths" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.FilePaths" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePaths As IList(Of Object)" />
      <MemberSignature Language="F#" Value="member this.FilePaths : System.Collections.Generic.IList&lt;obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.FilePaths" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.filePaths")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5be81-135">取得またはストリーミング ジョブ ファイルへのパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="5be81-135">Gets or sets paths to streaming job files.</span></span> <span data-ttu-id="5be81-136">ディレクトリを指定できます。</span><span class="sxs-lookup"><span data-stu-id="5be81-136">Can be directories.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDebugInfo">
      <MemberSignature Language="C#" Value="public string GetDebugInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GetDebugInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.GetDebugInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property GetDebugInfo As String" />
      <MemberSignature Language="F#" Value="member this.GetDebugInfo : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.GetDebugInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.getDebugInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5be81-137">取得またはデバッグ情報のオプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="5be81-137">Gets or sets debug info option.</span></span> <span data-ttu-id="5be81-138">使用可能な値が含まれます 'None'、'Always' に 'Failure'。</span><span class="sxs-lookup"><span data-stu-id="5be81-138">Possible values include: 'None', 'Always', 'Failure'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Input">
      <MemberSignature Language="C#" Value="public object Input { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Input" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.Input" />
      <MemberSignature Language="VB.NET" Value="Public Property Input As Object" />
      <MemberSignature Language="F#" Value="member this.Input : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.Input" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.input")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5be81-139">取得または入力 blob のパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="5be81-139">Gets or sets input blob path.</span></span> <span data-ttu-id="5be81-140">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5be81-140">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mapper">
      <MemberSignature Language="C#" Value="public object Mapper { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Mapper" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.Mapper" />
      <MemberSignature Language="VB.NET" Value="Public Property Mapper As Object" />
      <MemberSignature Language="F#" Value="member this.Mapper : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.Mapper" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.mapper")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5be81-141">取得またはマッパー実行可能ファイル名を設定します。</span><span class="sxs-lookup"><span data-stu-id="5be81-141">Gets or sets mapper executable name.</span></span> <span data-ttu-id="5be81-142">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5be81-142">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Output">
      <MemberSignature Language="C#" Value="public object Output { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Output" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.Output" />
      <MemberSignature Language="VB.NET" Value="Public Property Output As Object" />
      <MemberSignature Language="F#" Value="member this.Output : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.Output" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.output")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5be81-143">取得または出力 blob パスを設定します。</span><span class="sxs-lookup"><span data-stu-id="5be81-143">Gets or sets output blob path.</span></span> <span data-ttu-id="5be81-144">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5be81-144">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reducer">
      <MemberSignature Language="C#" Value="public object Reducer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Reducer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.Reducer" />
      <MemberSignature Language="VB.NET" Value="Public Property Reducer As Object" />
      <MemberSignature Language="F#" Value="member this.Reducer : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.Reducer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.reducer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5be81-145">取得または reducer 実行可能ファイル名を設定します。</span><span class="sxs-lookup"><span data-stu-id="5be81-145">Gets or sets reducer executable name.</span></span> <span data-ttu-id="5be81-146">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5be81-146">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageLinkedServices">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; StorageLinkedServices { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; StorageLinkedServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.StorageLinkedServices" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageLinkedServices As IList(Of LinkedServiceReference)" />
      <MemberSignature Language="F#" Value="member this.StorageLinkedServices : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.StorageLinkedServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.storageLinkedServices")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5be81-147">取得またはストレージのリンクされたサービスの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="5be81-147">Gets or sets storage linked service references.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightStreamingActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="hDInsightStreamingActivity.Validate " />
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
            <span data-ttu-id="5be81-148">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="5be81-148">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5be81-149">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5be81-149">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>