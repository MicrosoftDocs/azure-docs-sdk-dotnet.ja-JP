<Type Name="ResourceGroupPatchable" FullName="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable">
  <TypeSignature Language="C#" Value="public class ResourceGroupPatchable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceGroupPatchable extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceGroupPatchable" />
  <TypeSignature Language="F#" Value="type ResourceGroupPatchable = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="171ff-101">リソース グループの情報です。</span><span class="sxs-lookup"><span data-stu-id="171ff-101">Resource group information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceGroupPatchable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="171ff-102">ResourceGroupPatchable クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="171ff-102">Initializes a new instance of the ResourceGroupPatchable class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceGroupPatchable (string name = null, Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties properties = null, string managedBy = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties properties, string managedBy, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable.#ctor(System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional properties As ResourceGroupProperties = null, Optional managedBy As String = null, Optional tags As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable : string * Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable (name, properties, managedBy, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties" />
        <Parameter Name="managedBy" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="171ff-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="171ff-103">The name of the resource group.</span></span></param>
        <param name="properties">To be added.</param>
        <param name="managedBy"><span data-ttu-id="171ff-104">このリソース グループを管理するリソースの ID。</span><span class="sxs-lookup"><span data-stu-id="171ff-104">The ID of the resource that manages this resource group.</span></span></param>
        <param name="tags"><span data-ttu-id="171ff-105">リソース グループに関連付けられたタグ。</span><span class="sxs-lookup"><span data-stu-id="171ff-105">The tags attached to the resource group.</span></span></param>
        <summary>
            <span data-ttu-id="171ff-106">ResourceGroupPatchable クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="171ff-106">Initializes a new instance of the ResourceGroupPatchable class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedBy">
      <MemberSignature Language="C#" Value="public string ManagedBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ManagedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable.ManagedBy" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedBy As String" />
      <MemberSignature Language="F#" Value="member this.ManagedBy : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable.ManagedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="managedBy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="171ff-107">取得またはこのリソース グループを管理するリソースの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="171ff-107">Gets or sets the ID of the resource that manages this resource group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable.Name" />
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
            <span data-ttu-id="171ff-108">取得またはリソース グループの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="171ff-108">Gets or sets the name of the resource group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As ResourceGroupProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="171ff-109">取得またはリソース グループに関連付けられたタグを設定します。</span><span class="sxs-lookup"><span data-stu-id="171ff-109">Gets or sets the tags attached to the resource group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>