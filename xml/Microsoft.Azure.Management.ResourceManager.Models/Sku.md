<Type Name="Sku" FullName="Microsoft.Azure.Management.ResourceManager.Models.Sku">
  <TypeSignature Language="C#" Value="public class Sku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Sku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.Sku" />
  <TypeSignature Language="VB.NET" Value="Public Class Sku" />
  <TypeSignature Language="F#" Value="type Sku = class" />
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
            <span data-ttu-id="8c005-101">リソースの SKU。</span><span class="sxs-lookup"><span data-stu-id="8c005-101">SKU for the resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.Sku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8c005-102">Sku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8c005-102">Initializes a new instance of the Sku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku (string name = null, string tier = null, string size = null, string family = null, string model = null, Nullable&lt;int&gt; capacity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string tier, string size, string family, string model, valuetype System.Nullable`1&lt;int32&gt; capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.Sku.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional tier As String = null, Optional size As String = null, Optional family As String = null, Optional model As String = null, Optional capacity As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.Sku : string * string * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Models.Sku" Usage="new Microsoft.Azure.Management.ResourceManager.Models.Sku (name, tier, size, family, model, capacity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="tier" Type="System.String" />
        <Parameter Name="size" Type="System.String" />
        <Parameter Name="family" Type="System.String" />
        <Parameter Name="model" Type="System.String" />
        <Parameter Name="capacity" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="8c005-103">SKU の名前です。</span><span class="sxs-lookup"><span data-stu-id="8c005-103">The SKU name.</span></span></param>
        <param name="tier"><span data-ttu-id="8c005-104">SKU の層。</span><span class="sxs-lookup"><span data-stu-id="8c005-104">The SKU tier.</span></span></param>
        <param name="size"><span data-ttu-id="8c005-105">SKU のサイズ。</span><span class="sxs-lookup"><span data-stu-id="8c005-105">The SKU size.</span></span></param>
        <param name="family"><span data-ttu-id="8c005-106">SKU ファミリ。</span><span class="sxs-lookup"><span data-stu-id="8c005-106">The SKU family.</span></span></param>
        <param name="model"><span data-ttu-id="8c005-107">SKU のモデル。</span><span class="sxs-lookup"><span data-stu-id="8c005-107">The SKU model.</span></span></param>
        <param name="capacity"><span data-ttu-id="8c005-108">SKU 容量。</span><span class="sxs-lookup"><span data-stu-id="8c005-108">The SKU capacity.</span></span></param>
        <summary>
            <span data-ttu-id="8c005-109">Sku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8c005-109">Initializes a new instance of the Sku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Sku.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Capacity : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.Sku.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8c005-110">取得または SKU 容量を設定します。</span><span class="sxs-lookup"><span data-stu-id="8c005-110">Gets or sets the SKU capacity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Family">
      <MemberSignature Language="C#" Value="public string Family { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Family" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Sku.Family" />
      <MemberSignature Language="VB.NET" Value="Public Property Family As String" />
      <MemberSignature Language="F#" Value="member this.Family : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.Sku.Family" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="family")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8c005-111">取得または SKU ファミリを設定します。</span><span class="sxs-lookup"><span data-stu-id="8c005-111">Gets or sets the SKU family.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Model">
      <MemberSignature Language="C#" Value="public string Model { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Model" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Sku.Model" />
      <MemberSignature Language="VB.NET" Value="Public Property Model As String" />
      <MemberSignature Language="F#" Value="member this.Model : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.Sku.Model" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="model")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8c005-112">取得または SKU のモデルを設定します。</span><span class="sxs-lookup"><span data-stu-id="8c005-112">Gets or sets the SKU model.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Sku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.Sku.Name" />
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
            <span data-ttu-id="8c005-113">取得または SKU の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="8c005-113">Gets or sets the SKU name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public string Size { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Sku.Size" />
      <MemberSignature Language="VB.NET" Value="Public Property Size As String" />
      <MemberSignature Language="F#" Value="member this.Size : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.Sku.Size" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="size")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8c005-114">取得または SKU のサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="8c005-114">Gets or sets the SKU size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public string Tier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Sku.Tier" />
      <MemberSignature Language="VB.NET" Value="Public Property Tier As String" />
      <MemberSignature Language="F#" Value="member this.Tier : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.Sku.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="8c005-115">取得または SKU の層を設定します。</span><span class="sxs-lookup"><span data-stu-id="8c005-115">Gets or sets the SKU tier.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>