<Type Name="ImageReferenceInner" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner">
  <TypeSignature Language="C#" Value="public class ImageReferenceInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageReferenceInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageReferenceInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ImageReferenceInner = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5789c-101">イメージの参照。</span><span class="sxs-lookup"><span data-stu-id="5789c-101">The image reference.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReferenceInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5789c-102">ImageReferenceInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5789c-102">Initializes a new instance of the ImageReferenceInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageReferenceInner (string id = null, string publisher = null, string offer = null, string sku = null, string version = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string publisher, string offer, string sku, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional publisher As String = null, Optional offer As String = null, Optional sku As String = null, Optional version As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner : string * string * string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner (id, publisher, offer, sku, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="publisher"><span data-ttu-id="5789c-103">イメージのパブリッシャーです。</span><span class="sxs-lookup"><span data-stu-id="5789c-103">The image publisher.</span></span></param>
        <param name="offer"><span data-ttu-id="5789c-104">イメージの提供。</span><span class="sxs-lookup"><span data-stu-id="5789c-104">The image offer.</span></span></param>
        <param name="sku"><span data-ttu-id="5789c-105">イメージの SKU。</span><span class="sxs-lookup"><span data-stu-id="5789c-105">The image SKU.</span></span></param>
        <param name="version"><span data-ttu-id="5789c-106">イメージのバージョン。</span><span class="sxs-lookup"><span data-stu-id="5789c-106">The image version.</span></span> <span data-ttu-id="5789c-107">許可されている形式は、Major.Minor.Build または '最新' です。</span><span class="sxs-lookup"><span data-stu-id="5789c-107">The allowed formats are Major.Minor.Build or 'latest'.</span></span> <span data-ttu-id="5789c-108">メジャー、マイナー、ビルドは 10 進数。</span><span class="sxs-lookup"><span data-stu-id="5789c-108">Major, Minor and Build are decimal numbers.</span></span> <span data-ttu-id="5789c-109">イメージの最新バージョンを使用する ' 最新' を指定します。</span><span class="sxs-lookup"><span data-stu-id="5789c-109">Specify 'latest' to use the latest version of the image.</span></span></param>
        <summary>
            <span data-ttu-id="5789c-110">ImageReferenceInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5789c-110">Initializes a new instance of the ImageReferenceInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offer">
      <MemberSignature Language="C#" Value="public string Offer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner.Offer" />
      <MemberSignature Language="VB.NET" Value="Public Property Offer As String" />
      <MemberSignature Language="F#" Value="member this.Offer : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner.Offer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="offer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5789c-111">取得またはイメージの提供を設定します。</span><span class="sxs-lookup"><span data-stu-id="5789c-111">Gets or sets the image offer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner.Publisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="publisher")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5789c-112">取得またはイメージのパブリッシャーを設定します。</span><span class="sxs-lookup"><span data-stu-id="5789c-112">Gets or sets the image publisher.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public string Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As String" />
      <MemberSignature Language="F#" Value="member this.Sku : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5789c-113">取得またはイメージの SKU を設定します。</span><span class="sxs-lookup"><span data-stu-id="5789c-113">Gets or sets the image SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageReferenceInner.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5789c-114">取得またはイメージのバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="5789c-114">Gets or sets the image version.</span></span> <span data-ttu-id="5789c-115">許可されている形式は、Major.Minor.Build または '最新' です。</span><span class="sxs-lookup"><span data-stu-id="5789c-115">The allowed formats are Major.Minor.Build or 'latest'.</span></span> <span data-ttu-id="5789c-116">メジャー、マイナー、ビルドは 10 進数。</span><span class="sxs-lookup"><span data-stu-id="5789c-116">Major, Minor and Build are decimal numbers.</span></span> <span data-ttu-id="5789c-117">イメージの最新バージョンを使用する ' 最新' を指定します。</span><span class="sxs-lookup"><span data-stu-id="5789c-117">Specify 'latest' to use the latest version of the image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>