<Type Name="Replication" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.Replication">
  <TypeSignature Language="C#" Value="public class Replication : Microsoft.Azure.Management.ContainerRegistry.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Replication extends Microsoft.Azure.Management.ContainerRegistry.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.Replication" />
  <TypeSignature Language="VB.NET" Value="Public Class Replication&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Replication = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ContainerRegistry.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ec259-101">コンテナー レジストリにレプリケーションを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ec259-101">An object that represents a replication for a container registry.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Replication ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Replication.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ec259-102">レプリケーション クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ec259-102">Initializes a new instance of the Replication class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Replication (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string provisioningState = null, Microsoft.Azure.Management.ContainerRegistry.Models.Status status = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string provisioningState, class Microsoft.Azure.Management.ContainerRegistry.Models.Status status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Replication.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.ContainerRegistry.Models.Status)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.Replication : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.ContainerRegistry.Models.Status -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Replication" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.Replication (location, id, name, type, tags, provisioningState, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Status" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="ec259-103">リソースの場所です。</span><span class="sxs-lookup"><span data-stu-id="ec259-103">The location of the resource.</span></span> <span data-ttu-id="ec259-104">これは、リソースを作成した後に変更できません。</span><span class="sxs-lookup"><span data-stu-id="ec259-104">This cannot be changed after the resource is created.</span></span></param>
        <param name="id"><span data-ttu-id="ec259-105">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="ec259-105">The resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="ec259-106">リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="ec259-106">The name of the resource.</span></span></param>
        <param name="type"><span data-ttu-id="ec259-107">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="ec259-107">The type of the resource.</span></span></param>
        <param name="tags"><span data-ttu-id="ec259-108">リソースのタグ。</span><span class="sxs-lookup"><span data-stu-id="ec259-108">The tags of the resource.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="ec259-109">操作が呼び出された時点でレプリケーションのプロビジョニングの状態。</span><span class="sxs-lookup"><span data-stu-id="ec259-109">The provisioning state of the replication at the time the operation was called.</span></span> <span data-ttu-id="ec259-110">使用可能な値が含まれます: '作成中'、'更新'、'削除'、'成功'、'失敗'、'キャンセル'</span><span class="sxs-lookup"><span data-stu-id="ec259-110">Possible values include: 'Creating', 'Updating', 'Deleting', 'Succeeded', 'Failed', 'Canceled'</span></span></param>
        <param name="status"><span data-ttu-id="ec259-111">操作が呼び出された時点で、レプリケーションのステータス。</span><span class="sxs-lookup"><span data-stu-id="ec259-111">The status of the replication at the time the operation was called.</span></span></param>
        <summary>
            <span data-ttu-id="ec259-112">レプリケーション クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ec259-112">Initializes a new instance of the Replication class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Replication.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Replication.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="ec259-113">操作が呼び出された時点でレプリケーションのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="ec259-113">Gets the provisioning state of the replication at the time the operation was called.</span></span> <span data-ttu-id="ec259-114">使用可能な値が含まれます: '作成中'、'更新'、'削除'、'成功'、'失敗'、'キャンセル'</span><span class="sxs-lookup"><span data-stu-id="ec259-114">Possible values include: 'Creating', 'Updating', 'Deleting', 'Succeeded', 'Failed', 'Canceled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.Status Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.Status Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Replication.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Status" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.ContainerRegistry.Models.Status" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Replication.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Status</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec259-115">操作が呼び出された時点でレプリケーションの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="ec259-115">Gets the status of the replication at the time the operation was called.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Replication.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="replication.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ec259-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="ec259-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ec259-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec259-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>