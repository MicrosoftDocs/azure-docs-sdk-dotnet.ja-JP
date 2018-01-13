<Type Name="PolicyDefinition" FullName="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition">
  <TypeSignature Language="C#" Value="public class PolicyDefinition : Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PolicyDefinition extends System.Object implements class Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Class PolicyDefinition&#xA;Implements IResource" />
  <TypeSignature Language="F#" Value="type PolicyDefinition = class&#xA;    interface IResource" />
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
            <span data-ttu-id="296a0-101">ポリシー定義します。</span><span class="sxs-lookup"><span data-stu-id="296a0-101">The policy definition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolicyDefinition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="296a0-102">PolicyDefinition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="296a0-102">Initializes a new instance of the PolicyDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolicyDefinition (string policyType = null, string mode = null, string displayName = null, string description = null, object policyRule = null, object metadata = null, object parameters = null, string id = null, string name = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string policyType, string mode, string displayName, string description, object policyRule, object metadata, object parameters, string id, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.#ctor(System.String,System.String,System.String,System.String,System.Object,System.Object,System.Object,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional policyType As String = null, Optional mode As String = null, Optional displayName As String = null, Optional description As String = null, Optional policyRule As Object = null, Optional metadata As Object = null, Optional parameters As Object = null, Optional id As String = null, Optional name As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition : string * string * string * string * obj * obj * obj * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition" Usage="new Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition (policyType, mode, displayName, description, policyRule, metadata, parameters, id, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="policyType" Type="System.String" />
        <Parameter Name="mode" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="policyRule" Type="System.Object" />
        <Parameter Name="metadata" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Object" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policyType"><span data-ttu-id="296a0-103">ポリシー定義の型。</span><span class="sxs-lookup"><span data-stu-id="296a0-103">The type of policy definition.</span></span> <span data-ttu-id="296a0-104">使用可能な値は NotSpecified、ビルトイン、およびカスタムです。</span><span class="sxs-lookup"><span data-stu-id="296a0-104">Possible values are NotSpecified, BuiltIn, and Custom.</span></span> <span data-ttu-id="296a0-105">使用可能な値が含まれます: 'NotSpecified'、'BuiltIn'、'Custom'</span><span class="sxs-lookup"><span data-stu-id="296a0-105">Possible values include: 'NotSpecified', 'BuiltIn', 'Custom'</span></span></param>
        <param name="mode"><span data-ttu-id="296a0-106">ポリシー定義モードです。</span><span class="sxs-lookup"><span data-stu-id="296a0-106">The policy definition mode.</span></span> <span data-ttu-id="296a0-107">指定できる値は NotSpecified、インデックス、およびそのすべてです。</span><span class="sxs-lookup"><span data-stu-id="296a0-107">Possible values are NotSpecified, Indexed, and All.</span></span> <span data-ttu-id="296a0-108">使用可能な値が含まれます: 'NotSpecified'、'Indexed'、'All'</span><span class="sxs-lookup"><span data-stu-id="296a0-108">Possible values include: 'NotSpecified', 'Indexed', 'All'</span></span></param>
        <param name="displayName"><span data-ttu-id="296a0-109">ポリシー定義の表示名。</span><span class="sxs-lookup"><span data-stu-id="296a0-109">The display name of the policy definition.</span></span></param>
        <param name="description"><span data-ttu-id="296a0-110">ポリシー定義の説明。</span><span class="sxs-lookup"><span data-stu-id="296a0-110">The policy definition description.</span></span></param>
        <param name="policyRule"><span data-ttu-id="296a0-111">ポリシーのルール。</span><span class="sxs-lookup"><span data-stu-id="296a0-111">The policy rule.</span></span></param>
        <param name="metadata"><span data-ttu-id="296a0-112">ポリシー定義のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="296a0-112">The policy definition metadata.</span></span></param>
        <param name="parameters"><span data-ttu-id="296a0-113">ポリシーのルールでパラメーターを使用するかどうかに必要です。</span><span class="sxs-lookup"><span data-stu-id="296a0-113">Required if a parameter is used in policy rule.</span></span></param>
        <param name="id"><span data-ttu-id="296a0-114">ポリシー定義の ID。</span><span class="sxs-lookup"><span data-stu-id="296a0-114">The ID of the policy definition.</span></span></param>
        <param name="name"><span data-ttu-id="296a0-115">ポリシー定義の名前。</span><span class="sxs-lookup"><span data-stu-id="296a0-115">The name of the policy definition.</span></span></param>
        <summary>
            <span data-ttu-id="296a0-116">PolicyDefinition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="296a0-116">Initializes a new instance of the PolicyDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Description" />
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
            <span data-ttu-id="296a0-117">取得またはポリシーの定義の説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="296a0-117">Gets or sets the policy definition description.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.DisplayName" />
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
            <span data-ttu-id="296a0-118">取得またはポリシーの定義の表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="296a0-118">Gets or sets the display name of the policy definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Id" />
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
            <span data-ttu-id="296a0-119">ポリシー定義の ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="296a0-119">Gets the ID of the policy definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public object Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As Object" />
      <MemberSignature Language="F#" Value="member this.Metadata : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Metadata" />
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
            <span data-ttu-id="296a0-120">取得またはポリシーの定義のメタデータを設定します。</span><span class="sxs-lookup"><span data-stu-id="296a0-120">Gets or sets the policy definition metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public string Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As String" />
      <MemberSignature Language="F#" Value="member this.Mode : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.mode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="296a0-121">取得またはポリシーの定義のモードを設定します。</span><span class="sxs-lookup"><span data-stu-id="296a0-121">Gets or sets the policy definition mode.</span></span> <span data-ttu-id="296a0-122">指定できる値は NotSpecified、インデックス、およびそのすべてです。</span><span class="sxs-lookup"><span data-stu-id="296a0-122">Possible values are NotSpecified, Indexed, and All.</span></span> <span data-ttu-id="296a0-123">使用可能な値が含まれます: 'NotSpecified'、'Indexed'、'All'</span><span class="sxs-lookup"><span data-stu-id="296a0-123">Possible values include: 'NotSpecified', 'Indexed', 'All'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Name" />
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
            <span data-ttu-id="296a0-124">ポリシー定義の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="296a0-124">Gets the name of the policy definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public object Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As Object" />
      <MemberSignature Language="F#" Value="member this.Parameters : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.Parameters" />
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
            <span data-ttu-id="296a0-125">取得または設定ポリシーのルールのパラメーターを使用する場合に必要です。</span><span class="sxs-lookup"><span data-stu-id="296a0-125">Gets or sets required if a parameter is used in policy rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyRule">
      <MemberSignature Language="C#" Value="public object PolicyRule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object PolicyRule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.PolicyRule" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyRule As Object" />
      <MemberSignature Language="F#" Value="member this.PolicyRule : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.PolicyRule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.policyRule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="296a0-126">取得またはポリシーのルールを設定します。</span><span class="sxs-lookup"><span data-stu-id="296a0-126">Gets or sets the policy rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyType">
      <MemberSignature Language="C#" Value="public string PolicyType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.PolicyType" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyType As String" />
      <MemberSignature Language="F#" Value="member this.PolicyType : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition.PolicyType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.policyType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="296a0-127">取得またはポリシーの定義の型を設定します。</span><span class="sxs-lookup"><span data-stu-id="296a0-127">Gets or sets the type of policy definition.</span></span> <span data-ttu-id="296a0-128">使用可能な値は NotSpecified、ビルトイン、およびカスタムです。</span><span class="sxs-lookup"><span data-stu-id="296a0-128">Possible values are NotSpecified, BuiltIn, and Custom.</span></span> <span data-ttu-id="296a0-129">使用可能な値が含まれます: 'NotSpecified'、'BuiltIn'、'Custom'</span><span class="sxs-lookup"><span data-stu-id="296a0-129">Possible values include: 'NotSpecified', 'BuiltIn', 'Custom'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>