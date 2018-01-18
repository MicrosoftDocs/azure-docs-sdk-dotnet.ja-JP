<Type Name="DeploymentExtended" FullName="Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended">
  <TypeSignature Language="C#" Value="public class DeploymentExtended" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeploymentExtended extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended" />
  <TypeSignature Language="VB.NET" Value="Public Class DeploymentExtended" />
  <TypeSignature Language="F#" Value="type DeploymentExtended = class" />
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
            <span data-ttu-id="bdf73-101">デプロイメント情報です。</span><span class="sxs-lookup"><span data-stu-id="bdf73-101">Deployment information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentExtended ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bdf73-102">DeploymentExtended クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bdf73-102">Initializes a new instance of the DeploymentExtended class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentExtended (string name, string id = null, Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string id, class Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended.#ctor(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional id As String = null, Optional properties As DeploymentPropertiesExtended = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended : string * string * Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended -&gt; Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended" Usage="new Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended (name, id, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="bdf73-103">デプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="bdf73-103">The name of the deployment.</span></span></param>
        <param name="id"><span data-ttu-id="bdf73-104">展開の ID。</span><span class="sxs-lookup"><span data-stu-id="bdf73-104">The ID of the deployment.</span></span></param>
        <param name="properties"><span data-ttu-id="bdf73-105">配置プロパティです。</span><span class="sxs-lookup"><span data-stu-id="bdf73-105">Deployment properties.</span></span></param>
        <summary>
            <span data-ttu-id="bdf73-106">DeploymentExtended クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bdf73-106">Initializes a new instance of the DeploymentExtended class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended.Id" />
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
            <span data-ttu-id="bdf73-107">取得または展開の ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="bdf73-107">Gets or sets the ID of the deployment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended.Name" />
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
            <span data-ttu-id="bdf73-108">取得またはデプロイの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="bdf73-108">Gets or sets the name of the deployment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As DeploymentPropertiesExtended" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended.Properties" />
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
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdf73-109">取得または展開のプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="bdf73-109">Gets or sets deployment properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="deploymentExtended.Validate " />
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
            <span data-ttu-id="bdf73-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="bdf73-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bdf73-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bdf73-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>