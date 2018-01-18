<Type Name="Sku" FullName="Microsoft.Azure.Management.Storage.Fluent.Models.Sku">
  <TypeSignature Language="C#" Value="public class Sku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Sku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.Models.Sku" />
  <TypeSignature Language="VB.NET" Value="Public Class Sku" />
  <TypeSignature Language="F#" Value="type Sku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="420e1-101">ストレージ アカウントの SKU。</span><span class="sxs-lookup"><span data-stu-id="420e1-101">The SKU of the storage account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.Sku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="420e1-102">Sku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="420e1-102">Initializes a new instance of the Sku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku (Microsoft.Azure.Management.Storage.Fluent.Models.SkuName name, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.SkuTier&gt; tier = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Storage.Fluent.Models.SkuName name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.SkuTier&gt; tier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.Sku.#ctor(Microsoft.Azure.Management.Storage.Fluent.Models.SkuName,System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.SkuTier})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As SkuName, Optional tier As Nullable(Of SkuTier) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Fluent.Models.Sku : Microsoft.Azure.Management.Storage.Fluent.Models.SkuName * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.SkuTier&gt; -&gt; Microsoft.Azure.Management.Storage.Fluent.Models.Sku" Usage="new Microsoft.Azure.Management.Storage.Fluent.Models.Sku (name, tier)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="Microsoft.Azure.Management.Storage.Fluent.Models.SkuName" />
        <Parameter Name="tier" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.SkuTier&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="420e1-103">取得または sku の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="420e1-103">Gets or sets the sku name.</span></span> <span data-ttu-id="420e1-104">アカウントの作成に必要な更新プログラムの省略可能です。</span><span class="sxs-lookup"><span data-stu-id="420e1-104">Required for account creation; optional for update.</span></span> <span data-ttu-id="420e1-105">以前のバージョンで sku 名が呼び出されたこと accountType に注意してください。</span><span class="sxs-lookup"><span data-stu-id="420e1-105">Note that in older versions, sku name was called accountType.</span></span> <span data-ttu-id="420e1-106">使用可能な値が含まれます: 'Standard_LRS'、'Standard_GRS'、'Standard_RAGRS'、'が ' standard_zrs の場合、'Premium_LRS'</span><span class="sxs-lookup"><span data-stu-id="420e1-106">Possible values include: 'Standard_LRS', 'Standard_GRS', 'Standard_RAGRS', 'Standard_ZRS', 'Premium_LRS'</span></span></param>
        <param name="tier"><span data-ttu-id="420e1-107">Sku レベルを取得します。</span><span class="sxs-lookup"><span data-stu-id="420e1-107">Gets the sku tier.</span></span> <span data-ttu-id="420e1-108">これは、SKU 名に基づきます。</span><span class="sxs-lookup"><span data-stu-id="420e1-108">This is based on the SKU name.</span></span> <span data-ttu-id="420e1-109">使用可能な値が含まれます: 'Standard'、'Premium'</span><span class="sxs-lookup"><span data-stu-id="420e1-109">Possible values include: 'Standard', 'Premium'</span></span></param>
        <summary>
            <span data-ttu-id="420e1-110">Sku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="420e1-110">Initializes a new instance of the Sku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.SkuName Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Fluent.Models.SkuName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.Sku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As SkuName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Storage.Fluent.Models.SkuName with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.Sku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.SkuName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="420e1-111">取得または sku の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="420e1-111">Gets or sets the sku name.</span></span> <span data-ttu-id="420e1-112">アカウントの作成に必要な更新プログラムの省略可能です。</span><span class="sxs-lookup"><span data-stu-id="420e1-112">Required for account creation; optional for update.</span></span> <span data-ttu-id="420e1-113">以前のバージョンで sku 名が呼び出されたこと accountType に注意してください。</span><span class="sxs-lookup"><span data-stu-id="420e1-113">Note that in older versions, sku name was called accountType.</span></span> <span data-ttu-id="420e1-114">使用可能な値が含まれます: 'Standard_LRS'、'Standard_GRS'、'Standard_RAGRS'、'が ' standard_zrs の場合、'Premium_LRS'</span><span class="sxs-lookup"><span data-stu-id="420e1-114">Possible values include: 'Standard_LRS', 'Standard_GRS', 'Standard_RAGRS', 'Standard_ZRS', 'Premium_LRS'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.SkuTier&gt; Tier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.SkuTier&gt; Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.Sku.Tier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tier As Nullable(Of SkuTier)" />
      <MemberSignature Language="F#" Value="member this.Tier : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.SkuTier&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.Sku.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.SkuTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="420e1-115">Sku レベルを取得します。</span><span class="sxs-lookup"><span data-stu-id="420e1-115">Gets the sku tier.</span></span> <span data-ttu-id="420e1-116">これは、SKU 名に基づきます。</span><span class="sxs-lookup"><span data-stu-id="420e1-116">This is based on the SKU name.</span></span> <span data-ttu-id="420e1-117">使用可能な値が含まれます: 'Standard'、'Premium'</span><span class="sxs-lookup"><span data-stu-id="420e1-117">Possible values include: 'Standard', 'Premium'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.Sku.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sku.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="420e1-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="420e1-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="420e1-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="420e1-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>