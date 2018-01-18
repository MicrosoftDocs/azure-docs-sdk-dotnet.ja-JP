<Type Name="PolicyAssignment" FullName="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment">
  <TypeSignature Language="C#" Value="public class PolicyAssignment : Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PolicyAssignment extends System.Object implements class Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" />
  <TypeSignature Language="VB.NET" Value="Public Class PolicyAssignment&#xA;Implements IResource" />
  <TypeSignature Language="F#" Value="type PolicyAssignment = class&#xA;    interface IResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IResource</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="083bb-101">ポリシーの割り当て。</span><span class="sxs-lookup"><span data-stu-id="083bb-101">The policy assignment.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolicyAssignment ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="083bb-102">PolicyAssignment クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="083bb-102">Initializes a new instance of the PolicyAssignment class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolicyAssignment (string displayName = null, string policyDefinitionId = null, string scope = null, System.Collections.Generic.IList&lt;string&gt; notScopes = null, object parameters = null, string description = null, object metadata = null, string id = null, string type = null, string name = null, Microsoft.Azure.Management.ResourceManager.Models.PolicySku sku = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string displayName, string policyDefinitionId, string scope, class System.Collections.Generic.IList`1&lt;string&gt; notScopes, object parameters, string description, object metadata, string id, string type, string name, class Microsoft.Azure.Management.ResourceManager.Models.PolicySku sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Object,System.String,System.Object,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicySku)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional displayName As String = null, Optional policyDefinitionId As String = null, Optional scope As String = null, Optional notScopes As IList(Of String) = null, Optional parameters As Object = null, Optional description As String = null, Optional metadata As Object = null, Optional id As String = null, Optional type As String = null, Optional name As String = null, Optional sku As PolicySku = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment : string * string * string * System.Collections.Generic.IList&lt;string&gt; * obj * string * obj * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.PolicySku -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" Usage="new Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment (displayName, policyDefinitionId, scope, notScopes, parameters, description, metadata, id, type, name, sku)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="policyDefinitionId" Type="System.String" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="notScopes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="parameters" Type="System.Object" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="metadata" Type="System.Object" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicySku" />
      </Parameters>
      <Docs>
        <param name="displayName"><span data-ttu-id="083bb-103">ポリシー割り当ての表示名。</span><span class="sxs-lookup"><span data-stu-id="083bb-103">The display name of the policy assignment.</span></span></param>
        <param name="policyDefinitionId"><span data-ttu-id="083bb-104">ポリシー定義の ID。</span><span class="sxs-lookup"><span data-stu-id="083bb-104">The ID of the policy definition.</span></span></param>
        <param name="scope"><span data-ttu-id="083bb-105">ポリシー割り当てのスコープです。</span><span class="sxs-lookup"><span data-stu-id="083bb-105">The scope for the policy assignment.</span></span></param>
        <param name="notScopes"><span data-ttu-id="083bb-106">ポリシーのスコープを除外します。</span><span class="sxs-lookup"><span data-stu-id="083bb-106">The policy's excluded scopes.</span></span></param>
        <param name="parameters"><span data-ttu-id="083bb-107">ポリシーのルールでパラメーターを使用するかどうかに必要です。</span><span class="sxs-lookup"><span data-stu-id="083bb-107">Required if a parameter is used in policy rule.</span></span></param>
        <param name="description"><span data-ttu-id="083bb-108">このメッセージは、ポリシー違反が発生した場合の応答の一部になります。</span><span class="sxs-lookup"><span data-stu-id="083bb-108">This message will be part of response in case of policy violation.</span></span></param>
        <param name="metadata"><span data-ttu-id="083bb-109">ポリシー割り当てのメタデータ。</span><span class="sxs-lookup"><span data-stu-id="083bb-109">The policy assignment metadata.</span></span></param>
        <param name="id"><span data-ttu-id="083bb-110">ポリシー割り当ての ID。</span><span class="sxs-lookup"><span data-stu-id="083bb-110">The ID of the policy assignment.</span></span></param>
        <param name="type"><span data-ttu-id="083bb-111">ポリシー割り当ての種類。</span><span class="sxs-lookup"><span data-stu-id="083bb-111">The type of the policy assignment.</span></span></param>
        <param name="name"><span data-ttu-id="083bb-112">ポリシー割り当ての名前。</span><span class="sxs-lookup"><span data-stu-id="083bb-112">The name of the policy assignment.</span></span></param>
        <param name="sku"><span data-ttu-id="083bb-113">ポリシーの sku。</span><span class="sxs-lookup"><span data-stu-id="083bb-113">The policy sku.</span></span></param>
        <summary>
            <span data-ttu-id="083bb-114">PolicyAssignment クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="083bb-114">Initializes a new instance of the PolicyAssignment class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="083bb-115">この設定を取得またはエラー メッセージがポリシーの違反が発生した場合の応答の一部になります。</span><span class="sxs-lookup"><span data-stu-id="083bb-115">Gets or sets this message will be part of response in case of policy violation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="083bb-116">取得または設定ポリシー割り当ての表示名。</span><span class="sxs-lookup"><span data-stu-id="083bb-116">Gets or sets the display name of the policy assignment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="083bb-117">ポリシー割り当ての ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="083bb-117">Gets the ID of the policy assignment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public object Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As Object" />
      <MemberSignature Language="F#" Value="member this.Metadata : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="083bb-118">取得またはポリシーの割り当てのメタデータを設定します。</span><span class="sxs-lookup"><span data-stu-id="083bb-118">Gets or sets the policy assignment metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="083bb-119">ポリシー割り当ての名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="083bb-119">Gets the name of the policy assignment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotScopes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; NotScopes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; NotScopes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.NotScopes" />
      <MemberSignature Language="VB.NET" Value="Public Property NotScopes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NotScopes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.NotScopes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.notScopes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="083bb-120">取得またはポリシーの除外範囲を設定します。</span><span class="sxs-lookup"><span data-stu-id="083bb-120">Gets or sets the policy's excluded scopes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public object Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As Object" />
      <MemberSignature Language="F#" Value="member this.Parameters : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="083bb-121">取得または設定ポリシーのルールのパラメーターを使用する場合に必要です。</span><span class="sxs-lookup"><span data-stu-id="083bb-121">Gets or sets required if a parameter is used in policy rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyDefinitionId">
      <MemberSignature Language="C#" Value="public string PolicyDefinitionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyDefinitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.PolicyDefinitionId" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyDefinitionId As String" />
      <MemberSignature Language="F#" Value="member this.PolicyDefinitionId : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.PolicyDefinitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.policyDefinitionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="083bb-122">取得またはポリシーの定義の ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="083bb-122">Gets or sets the ID of the policy definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public string Scope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Scope" />
      <MemberSignature Language="VB.NET" Value="Public Property Scope As String" />
      <MemberSignature Language="F#" Value="member this.Scope : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scope")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="083bb-123">取得またはポリシーの割り当てのスコープを設定します。</span><span class="sxs-lookup"><span data-stu-id="083bb-123">Gets or sets the scope for the policy assignment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.PolicySku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.PolicySku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As PolicySku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.ResourceManager.Models.PolicySku with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicySku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="083bb-124">取得またはポリシーの sku を設定します。</span><span class="sxs-lookup"><span data-stu-id="083bb-124">Gets or sets the policy sku.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="083bb-125">ポリシーの割り当ての種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="083bb-125">Gets the type of the policy assignment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="policyAssignment.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="083bb-126">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="083bb-126">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="083bb-127">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="083bb-127">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>