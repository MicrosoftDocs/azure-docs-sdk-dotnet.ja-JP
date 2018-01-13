<Type Name="RenewCertificateOrderRequest" FullName="Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest">
  <TypeSignature Language="C#" Value="public class RenewCertificateOrderRequest : Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RenewCertificateOrderRequest extends Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class RenewCertificateOrderRequest&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type RenewCertificateOrderRequest = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="6e2db-101">クラスを表す証明書は、要求を更新します。</span><span class="sxs-lookup"><span data-stu-id="6e2db-101">Class representing certificate renew request.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RenewCertificateOrderRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6e2db-102">RenewCertificateOrderRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6e2db-102">Initializes a new instance of the RenewCertificateOrderRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RenewCertificateOrderRequest (string location, string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;int&gt; keySize = null, string csr = null, Nullable&lt;bool&gt; isPrivateKeyExternal = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string kind, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;int32&gt; keySize, string csr, valuetype System.Nullable`1&lt;bool&gt; isPrivateKeyExternal) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Int32},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional keySize As Nullable(Of Integer) = null, Optional csr As String = null, Optional isPrivateKeyExternal As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest : string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;int&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest" Usage="new Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest (location, id, name, kind, type, tags, keySize, csr, isPrivateKeyExternal)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="keySize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="csr" Type="System.String" />
        <Parameter Name="isPrivateKeyExternal" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="6e2db-103">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="6e2db-103">Resource Location.</span></span></param>
        <param name="id"><span data-ttu-id="6e2db-104">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="6e2db-104">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="6e2db-105">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="6e2db-105">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="6e2db-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="6e2db-106">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="6e2db-107">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="6e2db-107">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="6e2db-108">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="6e2db-108">Resource tags.</span></span></param>
        <param name="keySize"><span data-ttu-id="6e2db-109">証明書のキー サイズ。</span><span class="sxs-lookup"><span data-stu-id="6e2db-109">Certificate Key Size.</span></span></param>
        <param name="csr"><span data-ttu-id="6e2db-110">Csr のキーの再処理に使用します。</span><span class="sxs-lookup"><span data-stu-id="6e2db-110">Csr to be used for re-key operation.</span></span></param>
        <param name="isPrivateKeyExternal"><span data-ttu-id="6e2db-111">(管理されている秘密キーの外部の秘密キーにその逆) から ASC 型変更する必要があります。</span><span class="sxs-lookup"><span data-stu-id="6e2db-111">Should we change the ASC type (from managed private key to external private key and vice versa).</span></span></param>
        <summary>
            <span data-ttu-id="6e2db-112">RenewCertificateOrderRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6e2db-112">Initializes a new instance of the RenewCertificateOrderRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Csr">
      <MemberSignature Language="C#" Value="public string Csr { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Csr" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest.Csr" />
      <MemberSignature Language="VB.NET" Value="Public Property Csr As String" />
      <MemberSignature Language="F#" Value="member this.Csr : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest.Csr" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.csr")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e2db-113">取得または設定 csr のキーの再処理に使用します。</span><span class="sxs-lookup"><span data-stu-id="6e2db-113">Gets or sets csr to be used for re-key operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPrivateKeyExternal">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsPrivateKeyExternal { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsPrivateKeyExternal" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest.IsPrivateKeyExternal" />
      <MemberSignature Language="VB.NET" Value="Public Property IsPrivateKeyExternal As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsPrivateKeyExternal : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest.IsPrivateKeyExternal" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isPrivateKeyExternal")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e2db-114">取得または設定 (管理されている秘密キーの外部の秘密キーにその逆) から ASC 型を変更します。</span><span class="sxs-lookup"><span data-stu-id="6e2db-114">Gets or sets should we change the ASC type (from managed private key to external private key and vice versa).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; KeySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; KeySize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest.KeySize" />
      <MemberSignature Language="VB.NET" Value="Public Property KeySize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.KeySize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest.KeySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keySize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e2db-115">取得または証明書キーのサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="6e2db-115">Gets or sets certificate Key Size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="renewCertificateOrderRequest.Validate " />
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
            <span data-ttu-id="6e2db-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="6e2db-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6e2db-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6e2db-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>