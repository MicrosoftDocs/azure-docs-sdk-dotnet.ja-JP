<Type Name="CsvSerialization" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization">
  <TypeSignature Language="C#" Value="public class CsvSerialization : Microsoft.Azure.Management.StreamAnalytics.Models.Serialization" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CsvSerialization extends Microsoft.Azure.Management.StreamAnalytics.Models.Serialization" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization" />
  <TypeSignature Language="VB.NET" Value="Public Class CsvSerialization&#xA;Inherits Serialization" />
  <TypeSignature Language="F#" Value="type CsvSerialization = class&#xA;    inherit Serialization" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.Serialization</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Csv")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="bd946-101">入力からのデータをシリアル化する方法または CSV 形式で出力に書き込まれるときにデータをシリアル化する方法について説明します。</span><span class="sxs-lookup"><span data-stu-id="bd946-101">Describes how data from an input is serialized or how data is serialized when written to an output in CSV format.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CsvSerialization ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bd946-102">CsvSerialization クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bd946-102">Initializes a new instance of the CsvSerialization class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CsvSerialization (string fieldDelimiter = null, string encoding = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string fieldDelimiter, string encoding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional fieldDelimiter As String = null, Optional encoding As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization : string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization (fieldDelimiter, encoding)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fieldDelimiter" Type="System.String" />
        <Parameter Name="encoding" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fieldDelimiter"><span data-ttu-id="bd946-103">コンマ区切り値 (CSV) レコードを区切るために使用される区切り記号を指定します。</span><span class="sxs-lookup"><span data-stu-id="bd946-103">Specifies the delimiter that will be used to separate comma-separated value (CSV) records.</span></span> <span data-ttu-id="bd946-104">Https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input またはサポートされている値の一覧については https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output を参照してください。</span><span class="sxs-lookup"><span data-stu-id="bd946-104">See https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input or https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output for a list of supported values.</span></span> <span data-ttu-id="bd946-105">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="bd946-105">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="encoding"><span data-ttu-id="bd946-106">入力の場合、受信データのエンコードと出力の場合、送信データのエンコードを指定します。</span><span class="sxs-lookup"><span data-stu-id="bd946-106">Specifies the encoding of the incoming data in the case of input and the encoding of outgoing data in the case of output.</span></span> <span data-ttu-id="bd946-107">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="bd946-107">Required on PUT (CreateOrReplace) requests.</span></span> <span data-ttu-id="bd946-108">使用可能な値が含まれます: 'UTF8'</span><span class="sxs-lookup"><span data-stu-id="bd946-108">Possible values include: 'UTF8'</span></span></param>
        <summary>
            <span data-ttu-id="bd946-109">CsvSerialization クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bd946-109">Initializes a new instance of the CsvSerialization class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encoding">
      <MemberSignature Language="C#" Value="public string Encoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Encoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization.Encoding" />
      <MemberSignature Language="VB.NET" Value="Public Property Encoding As String" />
      <MemberSignature Language="F#" Value="member this.Encoding : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization.Encoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encoding")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd946-110">取得または設定は、入力の場合、受信データのエンコードと出力の場合、送信データのエンコードを指定します。</span><span class="sxs-lookup"><span data-stu-id="bd946-110">Gets or sets specifies the encoding of the incoming data in the case of input and the encoding of outgoing data in the case of output.</span></span> <span data-ttu-id="bd946-111">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="bd946-111">Required on PUT (CreateOrReplace) requests.</span></span> <span data-ttu-id="bd946-112">使用可能な値が含まれます: 'UTF8'</span><span class="sxs-lookup"><span data-stu-id="bd946-112">Possible values include: 'UTF8'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FieldDelimiter">
      <MemberSignature Language="C#" Value="public string FieldDelimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FieldDelimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization.FieldDelimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property FieldDelimiter As String" />
      <MemberSignature Language="F#" Value="member this.FieldDelimiter : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.CsvSerialization.FieldDelimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.fieldDelimiter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd946-113">取得または設定は、コンマ区切り値 (CSV) レコードを区切るために使用される区切り記号を指定します。</span><span class="sxs-lookup"><span data-stu-id="bd946-113">Gets or sets specifies the delimiter that will be used to separate comma-separated value (CSV) records.</span></span> <span data-ttu-id="bd946-114">Https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input またはサポートされている値の一覧については https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output を参照してください。</span><span class="sxs-lookup"><span data-stu-id="bd946-114">See https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input or https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output for a list of supported values.</span></span> <span data-ttu-id="bd946-115">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="bd946-115">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>