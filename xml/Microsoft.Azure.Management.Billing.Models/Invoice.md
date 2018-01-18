<Type Name="Invoice" FullName="Microsoft.Azure.Management.Billing.Models.Invoice">
  <TypeSignature Language="C#" Value="public class Invoice : Microsoft.Azure.Management.Billing.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Invoice extends Microsoft.Azure.Management.Billing.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Billing.Models.Invoice" />
  <TypeSignature Language="VB.NET" Value="Public Class Invoice&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Invoice = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Billing.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="1cab0-101">請求書リソースを使用できる、請求書の PDF バージョンをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="1cab0-101">An invoice resource can be used download a PDF version of an invoice.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Invoice ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.Models.Invoice.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1cab0-102">請求書クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1cab0-102">Initializes a new instance of the Invoice class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Invoice (string id = null, string name = null, string type = null, Microsoft.Azure.Management.Billing.Models.DownloadUrl downloadUrl = null, Nullable&lt;DateTime&gt; invoicePeriodStartDate = null, Nullable&lt;DateTime&gt; invoicePeriodEndDate = null, System.Collections.Generic.IList&lt;string&gt; billingPeriodIds = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class Microsoft.Azure.Management.Billing.Models.DownloadUrl downloadUrl, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; invoicePeriodStartDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; invoicePeriodEndDate, class System.Collections.Generic.IList`1&lt;string&gt; billingPeriodIds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.Models.Invoice.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.Billing.Models.DownloadUrl,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Billing.Models.Invoice : string * string * string * Microsoft.Azure.Management.Billing.Models.DownloadUrl * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Billing.Models.Invoice" Usage="new Microsoft.Azure.Management.Billing.Models.Invoice (id, name, type, downloadUrl, invoicePeriodStartDate, invoicePeriodEndDate, billingPeriodIds)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="downloadUrl" Type="Microsoft.Azure.Management.Billing.Models.DownloadUrl" />
        <Parameter Name="invoicePeriodStartDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="invoicePeriodEndDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="billingPeriodIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="1cab0-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="1cab0-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="1cab0-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="1cab0-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="1cab0-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="1cab0-105">Resource type.</span></span></param>
        <param name="downloadUrl"><span data-ttu-id="1cab0-106">請求書の PDF バージョンをダウンロードするセキュリティで保護されたリンク。</span><span class="sxs-lookup"><span data-stu-id="1cab0-106">A secure link to download the PDF version of an invoice.</span></span> <span data-ttu-id="1cab0-107">リンクは、その期限に達した後に機能しなくなります。</span><span class="sxs-lookup"><span data-stu-id="1cab0-107">The link will cease to work after its expiry time is reached.</span></span></param>
        <param name="invoicePeriodStartDate"><span data-ttu-id="1cab0-108">請求書の日付範囲の開始。</span><span class="sxs-lookup"><span data-stu-id="1cab0-108">The start of the date range covered by the invoice.</span></span></param>
        <param name="invoicePeriodEndDate"><span data-ttu-id="1cab0-109">請求書の日付範囲の終了。</span><span class="sxs-lookup"><span data-stu-id="1cab0-109">The end of the date range covered by the invoice.</span></span></param>
        <param name="billingPeriodIds"><span data-ttu-id="1cab0-110">請求、請求書に起因する perdiod id の配列です。</span><span class="sxs-lookup"><span data-stu-id="1cab0-110">Array of billing perdiod ids that the invoice is attributed to.</span></span></param>
        <summary>
            <span data-ttu-id="1cab0-111">請求書クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1cab0-111">Initializes a new instance of the Invoice class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BillingPeriodIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; BillingPeriodIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; BillingPeriodIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Billing.Models.Invoice.BillingPeriodIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BillingPeriodIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.BillingPeriodIds : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Billing.Models.Invoice.BillingPeriodIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.billingPeriodIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cab0-112">請求、請求書に起因する perdiod id の配列を取得します。</span><span class="sxs-lookup"><span data-stu-id="1cab0-112">Gets array of billing perdiod ids that the invoice is attributed to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadUrl">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Billing.Models.DownloadUrl DownloadUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Billing.Models.DownloadUrl DownloadUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Billing.Models.Invoice.DownloadUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property DownloadUrl As DownloadUrl" />
      <MemberSignature Language="F#" Value="member this.DownloadUrl : Microsoft.Azure.Management.Billing.Models.DownloadUrl with get, set" Usage="Microsoft.Azure.Management.Billing.Models.Invoice.DownloadUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.downloadUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Billing.Models.DownloadUrl</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cab0-113">取得または請求書の PDF バージョンをダウンロードするセキュリティで保護されたリンクを設定します。</span><span class="sxs-lookup"><span data-stu-id="1cab0-113">Gets or sets a secure link to download the PDF version of an invoice.</span></span> <span data-ttu-id="1cab0-114">リンクは、その期限に達した後に機能しなくなります。</span><span class="sxs-lookup"><span data-stu-id="1cab0-114">The link will cease to work after its expiry time is reached.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvoicePeriodEndDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; InvoicePeriodEndDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; InvoicePeriodEndDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Billing.Models.Invoice.InvoicePeriodEndDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InvoicePeriodEndDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.InvoicePeriodEndDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Billing.Models.Invoice.InvoicePeriodEndDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.invoicePeriodEndDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cab0-115">請求書の日付範囲の末尾を取得します。</span><span class="sxs-lookup"><span data-stu-id="1cab0-115">Gets the end of the date range covered by the invoice.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvoicePeriodStartDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; InvoicePeriodStartDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; InvoicePeriodStartDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Billing.Models.Invoice.InvoicePeriodStartDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InvoicePeriodStartDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.InvoicePeriodStartDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Billing.Models.Invoice.InvoicePeriodStartDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.invoicePeriodStartDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cab0-116">請求書の日付範囲の開始を取得します。</span><span class="sxs-lookup"><span data-stu-id="1cab0-116">Gets the start of the date range covered by the invoice.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>