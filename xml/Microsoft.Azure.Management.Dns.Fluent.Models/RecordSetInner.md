<Type Name="RecordSetInner" FullName="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner">
  <TypeSignature Language="C#" Value="public class RecordSetInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecordSetInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner" />
  <TypeSignature Language="VB.NET" Value="Public Class RecordSetInner" />
  <TypeSignature Language="F#" Value="type RecordSetInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5fe0c-101">DNS レコード セット (同じ名前と種類の DNS レコードのコレクション) について説明します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-101">Describes a DNS record set (a collection of DNS records with the same name and type).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecordSetInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5fe0c-102">RecordSetInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-102">Initializes a new instance of the RecordSetInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecordSetInner (string id = null, string name = null, string type = null, string etag = null, System.Collections.Generic.IDictionary&lt;string,string&gt; metadata = null, Nullable&lt;long&gt; tTL = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ARecord&gt; aRecords = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord&gt; aaaaRecords = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord&gt; mxRecords = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord&gt; nsRecords = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord&gt; ptrRecords = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt; srvRecords = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord&gt; txtRecords = null, Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord cnameRecord = null, Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord soaRecord = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string etag, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, valuetype System.Nullable`1&lt;int64&gt; tTL, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ARecord&gt; aRecords, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord&gt; aaaaRecords, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord&gt; mxRecords, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord&gt; nsRecords, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord&gt; ptrRecords, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt; srvRecords, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord&gt; txtRecords, class Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord cnameRecord, class Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord soaRecord) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Int64},System.Collections.Generic.IList{Microsoft.Azure.Management.Dns.Fluent.Models.ARecord},System.Collections.Generic.IList{Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord},System.Collections.Generic.IList{Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord},System.Collections.Generic.IList{Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord},System.Collections.Generic.IList{Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord},System.Collections.Generic.IList{Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord},System.Collections.Generic.IList{Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord},Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord,Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;int64&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ARecord&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord&gt; * Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord * Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord -&gt; Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner" Usage="new Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner (id, name, type, etag, metadata, tTL, aRecords, aaaaRecords, mxRecords, nsRecords, ptrRecords, srvRecords, txtRecords, cnameRecord, soaRecord)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="tTL" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="aRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ARecord&gt;" />
        <Parameter Name="aaaaRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord&gt;" />
        <Parameter Name="mxRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord&gt;" />
        <Parameter Name="nsRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord&gt;" />
        <Parameter Name="ptrRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord&gt;" />
        <Parameter Name="srvRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt;" />
        <Parameter Name="txtRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord&gt;" />
        <Parameter Name="cnameRecord" Type="Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord" />
        <Parameter Name="soaRecord" Type="Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="5fe0c-103">レコード セットの ID です。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-103">The ID of the record set.</span></span></param>
        <param name="name"><span data-ttu-id="5fe0c-104">レコード セットの名前。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-104">The name of the record set.</span></span></param>
        <param name="type"><span data-ttu-id="5fe0c-105">レコード セットの種類。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-105">The type of the record set.</span></span></param>
        <param name="etag"><span data-ttu-id="5fe0c-106">レコード セットの etag です。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-106">The etag of the record set.</span></span></param>
        <param name="metadata"><span data-ttu-id="5fe0c-107">レコードに関連付けられているメタデータを設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-107">The metadata attached to the record set.</span></span></param>
        <param name="tTL"><span data-ttu-id="5fe0c-108">レコード内のレコードの TTL (time に live) を設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-108">The TTL (time-to-live) of the records in the record set.</span></span></param>
        <param name="aRecords"><span data-ttu-id="5fe0c-109">レコード セット内のレコードのリスト。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-109">The list of A records in the record set.</span></span></param>
        <param name="aaaaRecords"><span data-ttu-id="5fe0c-110">レコード セットの AAAA レコードの一覧。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-110">The list of AAAA records in the record set.</span></span></param>
        <param name="mxRecords"><span data-ttu-id="5fe0c-111">レコード セットの MX レコードの一覧。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-111">The list of MX records in the record set.</span></span></param>
        <param name="nsRecords"><span data-ttu-id="5fe0c-112">レコード セットの NS レコードの一覧。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-112">The list of NS records in the record set.</span></span></param>
        <param name="ptrRecords"><span data-ttu-id="5fe0c-113">レコード セットでの PTR レコードの一覧。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-113">The list of PTR records in the record set.</span></span></param>
        <param name="srvRecords"><span data-ttu-id="5fe0c-114">レコード セット内の SRV レコードのリスト。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-114">The list of SRV records in the record set.</span></span></param>
        <param name="txtRecords"><span data-ttu-id="5fe0c-115">レコード セットの TXT レコードの一覧。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-115">The list of TXT records in the record set.</span></span></param>
        <param name="cnameRecord"><span data-ttu-id="5fe0c-116">レコードで CNAME レコードを設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-116">The CNAME record in the  record set.</span></span></param>
        <param name="soaRecord"><span data-ttu-id="5fe0c-117">レコードの SOA レコードを設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-117">The SOA record in the record set.</span></span></param>
        <summary>
            <span data-ttu-id="5fe0c-118">RecordSetInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-118">Initializes a new instance of the RecordSetInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AaaaRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord&gt; AaaaRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord&gt; AaaaRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.AaaaRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property AaaaRecords As IList(Of AaaaRecord)" />
      <MemberSignature Language="F#" Value="member this.AaaaRecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.AaaaRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.AAAARecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.AaaaRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fe0c-119">取得または AAAA レコードの一覧をレコード セットに設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-119">Gets or sets the list of AAAA records in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ARecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ARecord&gt; ARecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ARecord&gt; ARecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.ARecords" />
      <MemberSignature Language="VB.NET" Value="Public Property ARecords As IList(Of ARecord)" />
      <MemberSignature Language="F#" Value="member this.ARecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ARecord&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.ARecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ARecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ARecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fe0c-120">取得またはレコード セット内のレコードの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-120">Gets or sets the list of A records in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CnameRecord">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord CnameRecord { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord CnameRecord" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.CnameRecord" />
      <MemberSignature Language="VB.NET" Value="Public Property CnameRecord As CnameRecord" />
      <MemberSignature Language="F#" Value="member this.CnameRecord : Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.CnameRecord" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.CNAMERecord")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.Models.CnameRecord</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fe0c-121">取得または CNAME レコードをレコード セットに設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-121">Gets or sets the CNAME record in the  record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fe0c-122">取得またはレコード セットの etag を設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-122">Gets or sets the etag of the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
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
            <span data-ttu-id="5fe0c-123">取得またはレコード セットの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-123">Gets or sets the ID of the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fe0c-124">取得またはレコード セットに関連付けられているメタデータを設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-124">Gets or sets the metadata attached to the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MxRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord&gt; MxRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord&gt; MxRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.MxRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property MxRecords As IList(Of MxRecord)" />
      <MemberSignature Language="F#" Value="member this.MxRecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.MxRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.MXRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.MxRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fe0c-125">取得または MX レコードの一覧をレコード セットに設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-125">Gets or sets the list of MX records in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="5fe0c-126">取得またはレコード セットの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-126">Gets or sets the name of the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NsRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord&gt; NsRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord&gt; NsRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.NsRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property NsRecords As IList(Of NsRecord)" />
      <MemberSignature Language="F#" Value="member this.NsRecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.NsRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.NSRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.NsRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fe0c-127">取得またはレコード セット内の NS レコードの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-127">Gets or sets the list of NS records in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PtrRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord&gt; PtrRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord&gt; PtrRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.PtrRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property PtrRecords As IList(Of PtrRecord)" />
      <MemberSignature Language="F#" Value="member this.PtrRecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.PtrRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.PTRRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.PtrRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fe0c-128">取得またはレコード セットの PTR レコードの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-128">Gets or sets the list of PTR records in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SoaRecord">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord SoaRecord { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord SoaRecord" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.SoaRecord" />
      <MemberSignature Language="VB.NET" Value="Public Property SoaRecord As SoaRecord" />
      <MemberSignature Language="F#" Value="member this.SoaRecord : Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.SoaRecord" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.SOARecord")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.Models.SoaRecord</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fe0c-129">取得または SOA レコードをレコード セットに設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-129">Gets or sets the SOA record in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SrvRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt; SrvRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt; SrvRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.SrvRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property SrvRecords As IList(Of SrvRecord)" />
      <MemberSignature Language="F#" Value="member this.SrvRecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.SrvRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.SRVRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fe0c-130">取得またはレコード セット内の SRV レコードの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-130">Gets or sets the list of SRV records in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TTL">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; TTL { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; TTL" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.TTL" />
      <MemberSignature Language="VB.NET" Value="Public Property TTL As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.TTL : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.TTL" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.TTL")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fe0c-131">取得または設定、TTL (time に live)、レコード セット内のレコードです。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-131">Gets or sets the TTL (time-to-live) of the records in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TxtRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord&gt; TxtRecords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord&gt; TxtRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.TxtRecords" />
      <MemberSignature Language="VB.NET" Value="Public Property TxtRecords As IList(Of TxtRecord)" />
      <MemberSignature Language="F#" Value="member this.TxtRecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.TxtRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.TXTRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.TxtRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fe0c-132">取得またはレコード セット内の TXT レコードの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-132">Gets or sets the list of TXT records in the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5fe0c-133">取得またはレコード セットの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="5fe0c-133">Gets or sets the type of the record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>