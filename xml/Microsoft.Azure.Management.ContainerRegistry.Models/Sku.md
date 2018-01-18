<Type Name="Sku" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.Sku">
  <TypeSignature Language="C#" Value="public class Sku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Sku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.Sku" />
  <TypeSignature Language="VB.NET" Value="Public Class Sku" />
  <TypeSignature Language="F#" Value="type Sku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="24cd8-101">コンテナー レジストリの SKU。</span><span class="sxs-lookup"><span data-stu-id="24cd8-101">The SKU of a container registry.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Sku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="24cd8-102">Sku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="24cd8-102">Initializes a new instance of the Sku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku (string name, string tier = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string tier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Sku.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional tier As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.Sku : string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Sku" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.Sku (name, tier)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="tier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="24cd8-103">コンテナー レジストリの SKU の名前。</span><span class="sxs-lookup"><span data-stu-id="24cd8-103">The SKU name of the container registry.</span></span> <span data-ttu-id="24cd8-104">レジストリの作成に必要です。</span><span class="sxs-lookup"><span data-stu-id="24cd8-104">Required for registry creation.</span></span> <span data-ttu-id="24cd8-105">使用可能な値が含まれます: 'クラシック'、'Basic'、'Standard'、'Premium'</span><span class="sxs-lookup"><span data-stu-id="24cd8-105">Possible values include: 'Classic', 'Basic', 'Standard', 'Premium'</span></span></param>
        <param name="tier"><span data-ttu-id="24cd8-106">SKU 名に基づいて SKU 層です。</span><span class="sxs-lookup"><span data-stu-id="24cd8-106">The SKU tier based on the SKU name.</span></span> <span data-ttu-id="24cd8-107">使用可能な値が含まれます: 'クラシック'、'Basic'、'Standard'、'Premium'</span><span class="sxs-lookup"><span data-stu-id="24cd8-107">Possible values include: 'Classic', 'Basic', 'Standard', 'Premium'</span></span></param>
        <summary>
            <span data-ttu-id="24cd8-108">Sku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="24cd8-108">Initializes a new instance of the Sku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Sku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Sku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="24cd8-109">取得またはコンテナー レジストリの SKU の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="24cd8-109">Gets or sets the SKU name of the container registry.</span></span> <span data-ttu-id="24cd8-110">レジストリの作成に必要です。</span><span class="sxs-lookup"><span data-stu-id="24cd8-110">Required for registry creation.</span></span> <span data-ttu-id="24cd8-111">使用可能な値が含まれます: 'クラシック'、'Basic'、'Standard'、'Premium'</span><span class="sxs-lookup"><span data-stu-id="24cd8-111">Possible values include: 'Classic', 'Basic', 'Standard', 'Premium'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public string Tier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Sku.Tier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tier As String" />
      <MemberSignature Language="F#" Value="member this.Tier : string" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Sku.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24cd8-112">SKU 名に基づいて SKU 層を取得します。</span><span class="sxs-lookup"><span data-stu-id="24cd8-112">Gets the SKU tier based on the SKU name.</span></span> <span data-ttu-id="24cd8-113">使用可能な値が含まれます: 'クラシック'、'Basic'、'Standard'、'Premium'</span><span class="sxs-lookup"><span data-stu-id="24cd8-113">Possible values include: 'Classic', 'Basic', 'Standard', 'Premium'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Sku.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sku.Validate " />
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
            <span data-ttu-id="24cd8-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="24cd8-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="24cd8-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="24cd8-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>