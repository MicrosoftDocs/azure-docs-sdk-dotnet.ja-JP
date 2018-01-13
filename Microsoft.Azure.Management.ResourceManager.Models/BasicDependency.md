<Type Name="BasicDependency" FullName="Microsoft.Azure.Management.ResourceManager.Models.BasicDependency">
  <TypeSignature Language="C#" Value="public class BasicDependency" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BasicDependency extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.BasicDependency" />
  <TypeSignature Language="VB.NET" Value="Public Class BasicDependency" />
  <TypeSignature Language="F#" Value="type BasicDependency = class" />
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
            <span data-ttu-id="0bf6c-101">デプロイメントの依存関係情報です。</span><span class="sxs-lookup"><span data-stu-id="0bf6c-101">Deployment dependency information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BasicDependency ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.BasicDependency.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0bf6c-102">BasicDependency クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0bf6c-102">Initializes a new instance of the BasicDependency class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BasicDependency (string id = null, string resourceType = null, string resourceName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string resourceType, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.BasicDependency.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional resourceType As String = null, Optional resourceName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.BasicDependency : string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.BasicDependency" Usage="new Microsoft.Azure.Management.ResourceManager.Models.BasicDependency (id, resourceType, resourceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="0bf6c-103">依存関係の ID です。</span><span class="sxs-lookup"><span data-stu-id="0bf6c-103">The ID of the dependency.</span></span></param>
        <param name="resourceType"><span data-ttu-id="0bf6c-104">依存関係リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="0bf6c-104">The dependency resource type.</span></span></param>
        <param name="resourceName"><span data-ttu-id="0bf6c-105">依存関係リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="0bf6c-105">The dependency resource name.</span></span></param>
        <summary>
            <span data-ttu-id="0bf6c-106">BasicDependency クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0bf6c-106">Initializes a new instance of the BasicDependency class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.BasicDependency.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.BasicDependency.Id" />
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
            <span data-ttu-id="0bf6c-107">取得または依存関係の ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="0bf6c-107">Gets or sets the ID of the dependency.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceName">
      <MemberSignature Language="C#" Value="public string ResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.BasicDependency.ResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceName As String" />
      <MemberSignature Language="F#" Value="member this.ResourceName : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.BasicDependency.ResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="0bf6c-108">取得または依存関係のリソース名を設定します。</span><span class="sxs-lookup"><span data-stu-id="0bf6c-108">Gets or sets the dependency resource name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.BasicDependency.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.BasicDependency.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="0bf6c-109">取得または依存関係リソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="0bf6c-109">Gets or sets the dependency resource type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>