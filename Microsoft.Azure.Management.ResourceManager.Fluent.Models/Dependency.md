<Type Name="Dependency" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Models.Dependency">
  <TypeSignature Language="C#" Value="public class Dependency" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Dependency extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Models.Dependency" />
  <TypeSignature Language="VB.NET" Value="Public Class Dependency" />
  <TypeSignature Language="F#" Value="type Dependency = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2ee90-101">デプロイメントの依存関係情報です。</span><span class="sxs-lookup"><span data-stu-id="2ee90-101">Deployment dependency information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Dependency ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.Dependency.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2ee90-102">依存関係クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2ee90-102">Initializes a new instance of the Dependency class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Dependency (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.BasicDependency&gt; dependsOn = null, string id = null, string resourceType = null, string resourceName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.BasicDependency&gt; dependsOn, string id, string resourceType, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.Dependency.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Fluent.Models.BasicDependency},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dependsOn As IList(Of BasicDependency) = null, Optional id As String = null, Optional resourceType As String = null, Optional resourceName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.Dependency : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.BasicDependency&gt; * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Models.Dependency" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.Dependency (dependsOn, id, resourceType, resourceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.BasicDependency&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dependsOn"><span data-ttu-id="2ee90-103">依存関係の一覧。</span><span class="sxs-lookup"><span data-stu-id="2ee90-103">The list of dependencies.</span></span></param>
        <param name="id"><span data-ttu-id="2ee90-104">依存関係の ID です。</span><span class="sxs-lookup"><span data-stu-id="2ee90-104">The ID of the dependency.</span></span></param>
        <param name="resourceType"><span data-ttu-id="2ee90-105">依存関係リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="2ee90-105">The dependency resource type.</span></span></param>
        <param name="resourceName"><span data-ttu-id="2ee90-106">依存関係リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="2ee90-106">The dependency resource name.</span></span></param>
        <summary>
            <span data-ttu-id="2ee90-107">依存関係クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2ee90-107">Initializes a new instance of the Dependency class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DependsOn">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.BasicDependency&gt; DependsOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.BasicDependency&gt; DependsOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.Dependency.DependsOn" />
      <MemberSignature Language="VB.NET" Value="Public Property DependsOn As IList(Of BasicDependency)" />
      <MemberSignature Language="F#" Value="member this.DependsOn : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.BasicDependency&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.Dependency.DependsOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dependsOn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.BasicDependency&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ee90-108">取得または依存関係の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ee90-108">Gets or sets the list of dependencies.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.Dependency.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.Dependency.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="2ee90-109">取得または依存関係の ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ee90-109">Gets or sets the ID of the dependency.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceName">
      <MemberSignature Language="C#" Value="public string ResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.Dependency.ResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceName As String" />
      <MemberSignature Language="F#" Value="member this.ResourceName : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.Dependency.ResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ee90-110">取得または依存関係のリソース名を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ee90-110">Gets or sets the dependency resource name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.Dependency.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.Dependency.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ee90-111">取得または依存関係リソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ee90-111">Gets or sets the dependency resource type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>