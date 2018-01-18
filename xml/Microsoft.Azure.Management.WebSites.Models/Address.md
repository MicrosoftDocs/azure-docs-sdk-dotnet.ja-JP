<Type Name="Address" FullName="Microsoft.Azure.Management.WebSites.Models.Address">
  <TypeSignature Language="C#" Value="public class Address" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Address extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.Address" />
  <TypeSignature Language="VB.NET" Value="Public Class Address" />
  <TypeSignature Language="F#" Value="type Address = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="90623-101">ドメインの登録の情報に対応します。</span><span class="sxs-lookup"><span data-stu-id="90623-101">Address information for domain registration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Address ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Address.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="90623-102">アドレスのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="90623-102">Initializes a new instance of the Address class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Address (string address1, string city, string country, string postalCode, string state, string address2 = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address1, string city, string country, string postalCode, string state, string address2) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Address.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address1 As String, city As String, country As String, postalCode As String, state As String, Optional address2 As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.Address : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.Address" Usage="new Microsoft.Azure.Management.WebSites.Models.Address (address1, city, country, postalCode, state, address2)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address1" Type="System.String" />
        <Parameter Name="city" Type="System.String" />
        <Parameter Name="country" Type="System.String" />
        <Parameter Name="postalCode" Type="System.String" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="address2" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address1"><span data-ttu-id="90623-103">アドレスの最初の行。</span><span class="sxs-lookup"><span data-stu-id="90623-103">First line of an Address.</span></span></param>
        <param name="city"><span data-ttu-id="90623-104">住所の市区町村。</span><span class="sxs-lookup"><span data-stu-id="90623-104">The city for the address.</span></span></param>
        <param name="country"><span data-ttu-id="90623-105">住所の国。</span><span class="sxs-lookup"><span data-stu-id="90623-105">The country for the address.</span></span></param>
        <param name="postalCode"><span data-ttu-id="90623-106">住所の郵便番号。</span><span class="sxs-lookup"><span data-stu-id="90623-106">The postal code for the address.</span></span></param>
        <param name="state"><span data-ttu-id="90623-107">都道府県のアドレス。</span><span class="sxs-lookup"><span data-stu-id="90623-107">The state or province for the address.</span></span></param>
        <param name="address2"><span data-ttu-id="90623-108">アドレスの 2 行目。</span><span class="sxs-lookup"><span data-stu-id="90623-108">The second line of the Address.</span></span>
            <span data-ttu-id="90623-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="90623-109">Optional.</span></span></param>
        <summary>
            <span data-ttu-id="90623-110">アドレスのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="90623-110">Initializes a new instance of the Address class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address1">
      <MemberSignature Language="C#" Value="public string Address1 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address1" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Address.Address1" />
      <MemberSignature Language="VB.NET" Value="Public Property Address1 As String" />
      <MemberSignature Language="F#" Value="member this.Address1 : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Address.Address1" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="address1")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90623-111">取得またはアドレスの最初の行を設定します。</span><span class="sxs-lookup"><span data-stu-id="90623-111">Gets or sets first line of an Address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address2">
      <MemberSignature Language="C#" Value="public string Address2 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Address.Address2" />
      <MemberSignature Language="VB.NET" Value="Public Property Address2 As String" />
      <MemberSignature Language="F#" Value="member this.Address2 : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Address.Address2" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="address2")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90623-112">取得またはアドレスの 2 行目を設定します。</span><span class="sxs-lookup"><span data-stu-id="90623-112">Gets or sets the second line of the Address.</span></span> <span data-ttu-id="90623-113">省略可能。</span><span class="sxs-lookup"><span data-stu-id="90623-113">Optional.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="City">
      <MemberSignature Language="C#" Value="public string City { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string City" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Address.City" />
      <MemberSignature Language="VB.NET" Value="Public Property City As String" />
      <MemberSignature Language="F#" Value="member this.City : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Address.City" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="city")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90623-114">取得またはアドレスの市区町村を設定します。</span><span class="sxs-lookup"><span data-stu-id="90623-114">Gets or sets the city for the address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Country">
      <MemberSignature Language="C#" Value="public string Country { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Country" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Address.Country" />
      <MemberSignature Language="VB.NET" Value="Public Property Country As String" />
      <MemberSignature Language="F#" Value="member this.Country : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Address.Country" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="country")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90623-115">取得または国のアドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="90623-115">Gets or sets the country for the address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostalCode">
      <MemberSignature Language="C#" Value="public string PostalCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PostalCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Address.PostalCode" />
      <MemberSignature Language="VB.NET" Value="Public Property PostalCode As String" />
      <MemberSignature Language="F#" Value="member this.PostalCode : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Address.PostalCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="postalCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90623-116">取得または住所の郵便番号コードを設定します。</span><span class="sxs-lookup"><span data-stu-id="90623-116">Gets or sets the postal code for the address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Address.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Address.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90623-117">取得または住所の都道府県を設定します。</span><span class="sxs-lookup"><span data-stu-id="90623-117">Gets or sets the state or province for the address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Address.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="address.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="90623-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="90623-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="90623-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="90623-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>