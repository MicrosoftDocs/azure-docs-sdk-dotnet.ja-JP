<Type Name="Factory" FullName="Microsoft.Azure.Management.DataFactory.Models.Factory">
  <TypeSignature Language="C#" Value="public class Factory : Microsoft.Azure.Management.DataFactory.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Factory extends Microsoft.Azure.Management.DataFactory.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.Factory" />
  <TypeSignature Language="VB.NET" Value="Public Class Factory&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Factory = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="6328f-101">工場出荷時のリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="6328f-101">Factory resource type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Factory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.Factory.#ctor" />
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
            <span data-ttu-id="6328f-102">ファクトリ クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6328f-102">Initializes a new instance of the Factory class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Factory (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity identity = null, string provisioningState = null, Nullable&lt;DateTime&gt; createTime = null, string version = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity identity, string provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createTime, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.Factory.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity,System.String,System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional identity As FactoryIdentity = null, Optional provisioningState As String = null, Optional createTime As Nullable(Of DateTime) = null, Optional version As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.Factory : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity * string * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Management.DataFactory.Models.Factory" Usage="new Microsoft.Azure.Management.DataFactory.Models.Factory (id, name, type, location, tags, additionalProperties, identity, provisioningState, createTime, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="createTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="6328f-103">リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="6328f-103">The resource identifier.</span></span></param>
        <param name="name"><span data-ttu-id="6328f-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="6328f-104">The resource name.</span></span></param>
        <param name="type"><span data-ttu-id="6328f-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="6328f-105">The resource type.</span></span></param>
        <param name="location"><span data-ttu-id="6328f-106">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="6328f-106">The resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="6328f-107">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="6328f-107">The resource tags.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="6328f-108">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="6328f-108">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="identity"><span data-ttu-id="6328f-109">工場出荷時の管理されたサービスの id。</span><span class="sxs-lookup"><span data-stu-id="6328f-109">Managed service identity of the factory.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="6328f-110">ファクトリのプロビジョニングの状態、例が成功しました。</span><span class="sxs-lookup"><span data-stu-id="6328f-110">Factory provisioning state, example Succeeded.</span></span></param>
        <param name="createTime"><span data-ttu-id="6328f-111">ファクトリが ISO8601 の形式で作成された時刻。</span><span class="sxs-lookup"><span data-stu-id="6328f-111">Time the factory was created in ISO8601 format.</span></span></param>
        <param name="version"><span data-ttu-id="6328f-112">工場出荷時のバージョンです。</span><span class="sxs-lookup"><span data-stu-id="6328f-112">Version of the factory.</span></span></param>
        <summary>
            <span data-ttu-id="6328f-113">ファクトリ クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6328f-113">Initializes a new instance of the Factory class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.Factory.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.Factory.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6328f-114">メッセージから一致しないプロパティを取得または設定は、このコレクションを逆シリアル化</span><span class="sxs-lookup"><span data-stu-id="6328f-114">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.Factory.CreateTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreateTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreateTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.Factory.CreateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6328f-115">ファクトリが ISO8601 の形式で作成された日時を取得します。</span><span class="sxs-lookup"><span data-stu-id="6328f-115">Gets time the factory was created in ISO8601 format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.Factory.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As FactoryIdentity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.Factory.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6328f-116">取得または工場出荷時の管理されたサービス id を設定します。</span><span class="sxs-lookup"><span data-stu-id="6328f-116">Gets or sets managed service identity of the factory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.Factory.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.DataFactory.Models.Factory.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6328f-117">プロビジョニング状態成功の例ををファクトリを取得します。</span><span class="sxs-lookup"><span data-stu-id="6328f-117">Gets factory provisioning state, example Succeeded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.Factory.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string" Usage="Microsoft.Azure.Management.DataFactory.Models.Factory.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6328f-118">ファクトリのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="6328f-118">Gets version of the factory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>