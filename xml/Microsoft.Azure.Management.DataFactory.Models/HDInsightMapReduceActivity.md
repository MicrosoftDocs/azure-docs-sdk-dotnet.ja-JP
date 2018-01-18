<Type Name="HDInsightMapReduceActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity">
  <TypeSignature Language="C#" Value="public class HDInsightMapReduceActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HDInsightMapReduceActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class HDInsightMapReduceActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type HDInsightMapReduceActivity = class&#xA;    inherit ExecutionActivity" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("HDInsightMapReduce")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="2565f-101">HDInsight MapReduce アクティビティの型。</span><span class="sxs-lookup"><span data-stu-id="2565f-101">HDInsight MapReduce activity type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightMapReduceActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.#ctor" />
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
            <span data-ttu-id="2565f-102">HDInsightMapReduceActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2565f-102">Initializes a new instance of the HDInsightMapReduceActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightMapReduceActivity (string name, object className, object jarFilePath, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; storageLinkedServices = null, System.Collections.Generic.IList&lt;object&gt; arguments = null, string getDebugInfo = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference jarLinkedService = null, System.Collections.Generic.IList&lt;object&gt; jarLibs = null, System.Collections.Generic.IDictionary&lt;string,object&gt; defines = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object className, object jarFilePath, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; storageLinkedServices, class System.Collections.Generic.IList`1&lt;object&gt; arguments, string getDebugInfo, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference jarLinkedService, class System.Collections.Generic.IList`1&lt;object&gt; jarLibs, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; defines) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.#ctor(System.String,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference},System.Collections.Generic.IList{System.Object},System.String,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Collections.Generic.IList{System.Object},System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, className As Object, jarFilePath As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional storageLinkedServices As IList(Of LinkedServiceReference) = null, Optional arguments As IList(Of Object) = null, Optional getDebugInfo As String = null, Optional jarLinkedService As LinkedServiceReference = null, Optional jarLibs As IList(Of Object) = null, Optional defines As IDictionary(Of String, Object) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity : string * obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; * System.Collections.Generic.IList&lt;obj&gt; * string * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * System.Collections.Generic.IList&lt;obj&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity (name, className, jarFilePath, additionalProperties, description, dependsOn, linkedServiceName, policy, storageLinkedServices, arguments, getDebugInfo, jarLinkedService, jarLibs, defines)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="className" Type="System.Object" />
        <Parameter Name="jarFilePath" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="storageLinkedServices" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt;" />
        <Parameter Name="arguments" Type="System.Collections.Generic.IList&lt;System.Object&gt;" />
        <Parameter Name="getDebugInfo" Type="System.String" />
        <Parameter Name="jarLinkedService" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="jarLibs" Type="System.Collections.Generic.IList&lt;System.Object&gt;" />
        <Parameter Name="defines" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="2565f-103">アクティビティ名。</span><span class="sxs-lookup"><span data-stu-id="2565f-103">Activity name.</span></span></param>
        <param name="className"><span data-ttu-id="2565f-104">クラスの名前です。</span><span class="sxs-lookup"><span data-stu-id="2565f-104">Class name.</span></span> <span data-ttu-id="2565f-105">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="2565f-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="jarFilePath"><span data-ttu-id="2565f-106">Jar のパスです。</span><span class="sxs-lookup"><span data-stu-id="2565f-106">Jar path.</span></span> <span data-ttu-id="2565f-107">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="2565f-107">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="2565f-108">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="2565f-108">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="2565f-109">アクティビティの説明です。</span><span class="sxs-lookup"><span data-stu-id="2565f-109">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="2565f-110">アクティビティは、条件によって異なります。</span><span class="sxs-lookup"><span data-stu-id="2565f-110">Activity depends on condition.</span></span></param>
        <param name="linkedServiceName"><span data-ttu-id="2565f-111">リンクされたサービスの参照。</span><span class="sxs-lookup"><span data-stu-id="2565f-111">Linked service reference.</span></span></param>
        <param name="policy"><span data-ttu-id="2565f-112">アクティビティ ポリシー。</span><span class="sxs-lookup"><span data-stu-id="2565f-112">Activity policy.</span></span></param>
        <param name="storageLinkedServices"><span data-ttu-id="2565f-113">ストレージのリンクされたサービスの参照。</span><span class="sxs-lookup"><span data-stu-id="2565f-113">Storage linked service references.</span></span></param>
        <param name="arguments"><span data-ttu-id="2565f-114">ユーザーは、HDInsightActivity への引数を指定します。</span><span class="sxs-lookup"><span data-stu-id="2565f-114">User specified arguments to HDInsightActivity.</span></span></param>
        <param name="getDebugInfo"><span data-ttu-id="2565f-115">デバッグ情報のオプションです。</span><span class="sxs-lookup"><span data-stu-id="2565f-115">Debug info option.</span></span> <span data-ttu-id="2565f-116">使用可能な値が含まれます 'None'、'Always' に 'Failure'。</span><span class="sxs-lookup"><span data-stu-id="2565f-116">Possible values include: 'None', 'Always', 'Failure'</span></span></param>
        <param name="jarLinkedService"><span data-ttu-id="2565f-117">リンクされたサービスの参照を jar します。</span><span class="sxs-lookup"><span data-stu-id="2565f-117">Jar linked service reference.</span></span></param>
        <param name="jarLibs"><span data-ttu-id="2565f-118">ライブラリを jar します。</span><span class="sxs-lookup"><span data-stu-id="2565f-118">Jar libs.</span></span></param>
        <param name="defines"><span data-ttu-id="2565f-119">により、MapReduce ジョブの要求のユーザーを指定するを定義します。</span><span class="sxs-lookup"><span data-stu-id="2565f-119">Allows user to specify defines for the MapReduce job request.</span></span></param>
        <summary>
            <span data-ttu-id="2565f-120">HDInsightMapReduceActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2565f-120">Initializes a new instance of the HDInsightMapReduceActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Arguments">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;object&gt; Arguments { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;object&gt; Arguments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.Arguments" />
      <MemberSignature Language="VB.NET" Value="Public Property Arguments As IList(Of Object)" />
      <MemberSignature Language="F#" Value="member this.Arguments : System.Collections.Generic.IList&lt;obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.Arguments" />
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
            <span data-ttu-id="2565f-121">指定されたユーザーの設定を取得または HDInsightActivity への引数。</span><span class="sxs-lookup"><span data-stu-id="2565f-121">Gets or sets user specified arguments to HDInsightActivity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClassName">
      <MemberSignature Language="C#" Value="public object ClassName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ClassName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.ClassName" />
      <MemberSignature Language="VB.NET" Value="Public Property ClassName As Object" />
      <MemberSignature Language="F#" Value="member this.ClassName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.ClassName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.className")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2565f-122">取得またはクラス名を設定します。</span><span class="sxs-lookup"><span data-stu-id="2565f-122">Gets or sets class name.</span></span> <span data-ttu-id="2565f-123">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="2565f-123">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defines">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Defines { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Defines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.Defines" />
      <MemberSignature Language="VB.NET" Value="Public Property Defines As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Defines : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.Defines" />
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
            <span data-ttu-id="2565f-124">により、取得または設定を指定するユーザーは MapReduce ジョブの要求を定義します。</span><span class="sxs-lookup"><span data-stu-id="2565f-124">Gets or sets allows user to specify defines for the MapReduce job request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDebugInfo">
      <MemberSignature Language="C#" Value="public string GetDebugInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GetDebugInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.GetDebugInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property GetDebugInfo As String" />
      <MemberSignature Language="F#" Value="member this.GetDebugInfo : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.GetDebugInfo" />
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
            <span data-ttu-id="2565f-125">取得またはデバッグ情報のオプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="2565f-125">Gets or sets debug info option.</span></span> <span data-ttu-id="2565f-126">使用可能な値が含まれます 'None'、'Always' に 'Failure'。</span><span class="sxs-lookup"><span data-stu-id="2565f-126">Possible values include: 'None', 'Always', 'Failure'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JarFilePath">
      <MemberSignature Language="C#" Value="public object JarFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object JarFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.JarFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property JarFilePath As Object" />
      <MemberSignature Language="F#" Value="member this.JarFilePath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.JarFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.jarFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2565f-127">取得または jar のパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="2565f-127">Gets or sets jar path.</span></span> <span data-ttu-id="2565f-128">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="2565f-128">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JarLibs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;object&gt; JarLibs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;object&gt; JarLibs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.JarLibs" />
      <MemberSignature Language="VB.NET" Value="Public Property JarLibs As IList(Of Object)" />
      <MemberSignature Language="F#" Value="member this.JarLibs : System.Collections.Generic.IList&lt;obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.JarLibs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.jarLibs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2565f-129">取得または jar の lib を設定します。</span><span class="sxs-lookup"><span data-stu-id="2565f-129">Gets or sets jar libs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JarLinkedService">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference JarLinkedService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference JarLinkedService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.JarLinkedService" />
      <MemberSignature Language="VB.NET" Value="Public Property JarLinkedService As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.JarLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.JarLinkedService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.jarLinkedService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2565f-130">取得または設定は、リンクされたサービスの参照を jar します。</span><span class="sxs-lookup"><span data-stu-id="2565f-130">Gets or sets jar linked service reference.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageLinkedServices">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; StorageLinkedServices { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; StorageLinkedServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.StorageLinkedServices" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageLinkedServices As IList(Of LinkedServiceReference)" />
      <MemberSignature Language="F#" Value="member this.StorageLinkedServices : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.StorageLinkedServices" />
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
            <span data-ttu-id="2565f-131">取得またはストレージのリンクされたサービスの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="2565f-131">Gets or sets storage linked service references.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightMapReduceActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="hDInsightMapReduceActivity.Validate " />
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
            <span data-ttu-id="2565f-132">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="2565f-132">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2565f-133">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2565f-133">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>