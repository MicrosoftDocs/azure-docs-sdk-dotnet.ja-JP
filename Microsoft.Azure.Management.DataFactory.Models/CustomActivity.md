<Type Name="CustomActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.CustomActivity">
  <TypeSignature Language="C#" Value="public class CustomActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CustomActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.CustomActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class CustomActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type CustomActivity = class&#xA;    inherit ExecutionActivity" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Custom")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="d46b4-101">カスタム アクティビティの型。</span><span class="sxs-lookup"><span data-stu-id="d46b4-101">Custom activity type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CustomActivity.#ctor" />
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
            <span data-ttu-id="d46b4-102">[Customactivity] クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d46b4-102">Initializes a new instance of the CustomActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomActivity (string name, object command, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference resourceLinkedService = null, object folderPath = null, Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject referenceObjects = null, System.Collections.Generic.IDictionary&lt;string,object&gt; extendedProperties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object command, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference resourceLinkedService, object folderPath, class Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject referenceObjects, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; extendedProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CustomActivity.#ctor(System.String,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object,Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, command As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional resourceLinkedService As LinkedServiceReference = null, Optional folderPath As Object = null, Optional referenceObjects As CustomActivityReferenceObject = null, Optional extendedProperties As IDictionary(Of String, Object) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.CustomActivity : string * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj * Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.CustomActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.CustomActivity (name, command, additionalProperties, description, dependsOn, linkedServiceName, policy, resourceLinkedService, folderPath, referenceObjects, extendedProperties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="command" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="resourceLinkedService" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="folderPath" Type="System.Object" />
        <Parameter Name="referenceObjects" Type="Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject" />
        <Parameter Name="extendedProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d46b4-103">アクティビティ名。</span><span class="sxs-lookup"><span data-stu-id="d46b4-103">Activity name.</span></span></param>
        <param name="command"><span data-ttu-id="d46b4-104">カスタム アクティビティの種類のコマンド: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="d46b4-104">Command for custom activity Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="d46b4-105">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="d46b4-105">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="d46b4-106">アクティビティの説明です。</span><span class="sxs-lookup"><span data-stu-id="d46b4-106">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="d46b4-107">アクティビティは、条件によって異なります。</span><span class="sxs-lookup"><span data-stu-id="d46b4-107">Activity depends on condition.</span></span></param>
        <param name="linkedServiceName"><span data-ttu-id="d46b4-108">リンクされたサービスの参照。</span><span class="sxs-lookup"><span data-stu-id="d46b4-108">Linked service reference.</span></span></param>
        <param name="policy"><span data-ttu-id="d46b4-109">アクティビティ ポリシー。</span><span class="sxs-lookup"><span data-stu-id="d46b4-109">Activity policy.</span></span></param>
        <param name="resourceLinkedService"><span data-ttu-id="d46b4-110">リソースには、サービス参照の追加がリンクされています。</span><span class="sxs-lookup"><span data-stu-id="d46b4-110">Resource linked service reference.</span></span></param>
        <param name="folderPath"><span data-ttu-id="d46b4-111">ファイルの種類のリソースのフォルダーのパス: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="d46b4-111">Folder path for resource files Type: string (or Expression with resultType string).</span></span></param>
        <param name="referenceObjects"><span data-ttu-id="d46b4-112">オブジェクトを参照</span><span class="sxs-lookup"><span data-stu-id="d46b4-112">Reference objects</span></span></param>
        <param name="extendedProperties"><span data-ttu-id="d46b4-113">ユーザーは、プロパティ バッグを定義します。</span><span class="sxs-lookup"><span data-stu-id="d46b4-113">User defined property bag.</span></span> <span data-ttu-id="d46b4-114">キーまたは使用できる値に制限はありません。</span><span class="sxs-lookup"><span data-stu-id="d46b4-114">There is no restriction on the keys or values that can be used.</span></span> <span data-ttu-id="d46b4-115">ユーザーは、カスタム アクティビティが使用して、定義されているコンテンツを解釈する全責任を指定します。</span><span class="sxs-lookup"><span data-stu-id="d46b4-115">The user specified custom activity has the full responsibility to consume and interpret the content defined.</span></span></param>
        <summary>
            <span data-ttu-id="d46b4-116">[Customactivity] クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d46b4-116">Initializes a new instance of the CustomActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Command">
      <MemberSignature Language="C#" Value="public object Command { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Command" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CustomActivity.Command" />
      <MemberSignature Language="VB.NET" Value="Public Property Command As Object" />
      <MemberSignature Language="F#" Value="member this.Command : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CustomActivity.Command" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.command")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d46b4-117">取得またはカスタム アクティビティの種類のコマンドを設定します。 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="d46b4-117">Gets or sets command for custom activity Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; ExtendedProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; ExtendedProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CustomActivity.ExtendedProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.ExtendedProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CustomActivity.ExtendedProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.extendedProperties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d46b4-118">取得またはユーザー定義されたプロパティ バッグを設定します。</span><span class="sxs-lookup"><span data-stu-id="d46b4-118">Gets or sets user defined property bag.</span></span> <span data-ttu-id="d46b4-119">キーまたは使用できる値に制限はありません。</span><span class="sxs-lookup"><span data-stu-id="d46b4-119">There is no restriction on the keys or values that can be used.</span></span> <span data-ttu-id="d46b4-120">ユーザーは、カスタム アクティビティが使用して、定義されているコンテンツを解釈する全責任を指定します。</span><span class="sxs-lookup"><span data-stu-id="d46b4-120">The user specified custom activity has the full responsibility to consume and interpret the content defined.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FolderPath">
      <MemberSignature Language="C#" Value="public object FolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object FolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CustomActivity.FolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property FolderPath As Object" />
      <MemberSignature Language="F#" Value="member this.FolderPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CustomActivity.FolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.folderPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d46b4-121">フォルダー パス リソース ファイルの種類を取得または設定します。 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="d46b4-121">Gets or sets folder path for resource files Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReferenceObjects">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject ReferenceObjects { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject ReferenceObjects" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CustomActivity.ReferenceObjects" />
      <MemberSignature Language="VB.NET" Value="Public Property ReferenceObjects As CustomActivityReferenceObject" />
      <MemberSignature Language="F#" Value="member this.ReferenceObjects : Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CustomActivity.ReferenceObjects" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.referenceObjects")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d46b4-122">取得または設定オブジェクトを参照</span><span class="sxs-lookup"><span data-stu-id="d46b4-122">Gets or sets reference objects</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceLinkedService">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference ResourceLinkedService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference ResourceLinkedService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CustomActivity.ResourceLinkedService" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceLinkedService As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.ResourceLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CustomActivity.ResourceLinkedService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.resourceLinkedService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d46b4-123">取得またはリンクされているリソース サービス参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="d46b4-123">Gets or sets resource linked service reference.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CustomActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="customActivity.Validate " />
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
            <span data-ttu-id="d46b4-124">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="d46b4-124">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d46b4-125">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d46b4-125">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>