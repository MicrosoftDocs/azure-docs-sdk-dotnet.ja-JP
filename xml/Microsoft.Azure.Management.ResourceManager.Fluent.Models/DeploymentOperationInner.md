<Type Name="DeploymentOperationInner" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner">
  <TypeSignature Language="C#" Value="public class DeploymentOperationInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeploymentOperationInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner" />
  <TypeSignature Language="VB.NET" Value="Public Class DeploymentOperationInner" />
  <TypeSignature Language="F#" Value="type DeploymentOperationInner = class" />
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
            <span data-ttu-id="fdd6b-101">デプロイ操作の情報です。</span><span class="sxs-lookup"><span data-stu-id="fdd6b-101">Deployment operation information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentOperationInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fdd6b-102">DeploymentOperationInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fdd6b-102">Initializes a new instance of the DeploymentOperationInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentOperationInner (string id = null, string operationId = null, Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string operationId, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner.#ctor(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional operationId As String = null, Optional properties As DeploymentOperationProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner : string * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner (id, operationId, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="fdd6b-103">完全な展開操作の id。</span><span class="sxs-lookup"><span data-stu-id="fdd6b-103">Full deployment operation id.</span></span></param>
        <param name="operationId"><span data-ttu-id="fdd6b-104">デプロイ操作の id。</span><span class="sxs-lookup"><span data-stu-id="fdd6b-104">Deployment operation id.</span></span></param>
        <param name="properties"><span data-ttu-id="fdd6b-105">配置プロパティです。</span><span class="sxs-lookup"><span data-stu-id="fdd6b-105">Deployment properties.</span></span></param>
        <summary>
            <span data-ttu-id="fdd6b-106">DeploymentOperationInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fdd6b-106">Initializes a new instance of the DeploymentOperationInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner.Id" />
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
            <span data-ttu-id="fdd6b-107">取得または完全な展開操作の id を設定します。</span><span class="sxs-lookup"><span data-stu-id="fdd6b-107">Gets or sets full deployment operation id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public string OperationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationId As String" />
      <MemberSignature Language="F#" Value="member this.OperationId : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner.OperationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdd6b-108">取得またはデプロイ操作の id を設定します。</span><span class="sxs-lookup"><span data-stu-id="fdd6b-108">Gets or sets deployment operation id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As DeploymentOperationProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdd6b-109">取得または展開のプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="fdd6b-109">Gets or sets deployment properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>