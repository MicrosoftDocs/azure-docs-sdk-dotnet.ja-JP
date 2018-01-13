<Type Name="Plan" FullName="Microsoft.Azure.Management.Compute.Models.Plan">
  <TypeSignature Language="C#" Value="public class Plan" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Plan extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.Plan" />
  <TypeSignature Language="VB.NET" Value="Public Class Plan" />
  <TypeSignature Language="F#" Value="type Plan = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="28e00-101">仮想マシンの作成に使用する marketplace イメージに関する情報を指定します。</span><span class="sxs-lookup"><span data-stu-id="28e00-101">Specifies information about the marketplace image used to create the virtual machine.</span></span> <span data-ttu-id="28e00-102">この要素は marketplace イメージのみ使用されます。</span><span class="sxs-lookup"><span data-stu-id="28e00-102">This element is only used for marketplace images.</span></span>
            <span data-ttu-id="28e00-103">API から marketplace イメージを使用することができます、前に、画像がプログラムでの使用を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="28e00-103">Before you can use a marketplace image from an API, you must enable the image for programmatic use.</span></span>  <span data-ttu-id="28e00-104">Azure ポータルで、検索、marketplace イメージを使用して、をクリックする**はじめに - をプログラムでは、展開する&gt;**です。</span><span class="sxs-lookup"><span data-stu-id="28e00-104">In the Azure portal, find the marketplace image that you want to use and then click **Want to deploy programmatically, Get Started -&gt;**.</span></span> <span data-ttu-id="28e00-105">必要な情報を入力し、クリックして**保存**です。</span><span class="sxs-lookup"><span data-stu-id="28e00-105">Enter any required information and then click **Save**.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Plan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Plan.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="28e00-106">Plan クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="28e00-106">Initializes a new instance of the Plan class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Plan (string name = null, string publisher = null, string product = null, string promotionCode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string publisher, string product, string promotionCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Plan.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional publisher As String = null, Optional product As String = null, Optional promotionCode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.Plan : string * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.Plan" Usage="new Microsoft.Azure.Management.Compute.Models.Plan (name, publisher, product, promotionCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="product" Type="System.String" />
        <Parameter Name="promotionCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="28e00-107">プランの ID</span><span class="sxs-lookup"><span data-stu-id="28e00-107">The plan ID.</span></span></param>
        <param name="publisher"><span data-ttu-id="28e00-108">パブリッシャーの id。</span><span class="sxs-lookup"><span data-stu-id="28e00-108">The publisher ID.</span></span></param>
        <param name="product"><span data-ttu-id="28e00-109">Marketplace からのイメージの製品を指定します。</span><span class="sxs-lookup"><span data-stu-id="28e00-109">Specifies the product of the image from the marketplace.</span></span> <span data-ttu-id="28e00-110">これは、imageReference 要素の下のプランと同じ値です。</span><span class="sxs-lookup"><span data-stu-id="28e00-110">This is the same value as Offer under the imageReference element.</span></span></param>
        <param name="promotionCode"><span data-ttu-id="28e00-111">販売促進コード。</span><span class="sxs-lookup"><span data-stu-id="28e00-111">The promotion code.</span></span></param>
        <summary>
            <span data-ttu-id="28e00-112">Plan クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="28e00-112">Initializes a new instance of the Plan class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Plan.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Plan.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="28e00-113">取得または設定、プランの id です。</span><span class="sxs-lookup"><span data-stu-id="28e00-113">Gets or sets the plan ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Product">
      <MemberSignature Language="C#" Value="public string Product { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Product" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Plan.Product" />
      <MemberSignature Language="VB.NET" Value="Public Property Product As String" />
      <MemberSignature Language="F#" Value="member this.Product : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Plan.Product" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="product")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="28e00-114">取得または設定は、marketplace からのイメージの製品を指定します。</span><span class="sxs-lookup"><span data-stu-id="28e00-114">Gets or sets specifies the product of the image from the marketplace.</span></span> <span data-ttu-id="28e00-115">これは、imageReference 要素の下のプランと同じ値です。</span><span class="sxs-lookup"><span data-stu-id="28e00-115">This is the same value as Offer under the imageReference element.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PromotionCode">
      <MemberSignature Language="C#" Value="public string PromotionCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PromotionCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Plan.PromotionCode" />
      <MemberSignature Language="VB.NET" Value="Public Property PromotionCode As String" />
      <MemberSignature Language="F#" Value="member this.PromotionCode : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Plan.PromotionCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="promotionCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="28e00-116">取得またはプロモーション コードを設定します。</span><span class="sxs-lookup"><span data-stu-id="28e00-116">Gets or sets the promotion code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Plan.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Plan.Publisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="28e00-117">取得または設定、パブリッシャーの id です。</span><span class="sxs-lookup"><span data-stu-id="28e00-117">Gets or sets the publisher ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>