<Type Name="OracleSource" FullName="Microsoft.Azure.Management.DataFactory.Models.OracleSource">
  <TypeSignature Language="C#" Value="public class OracleSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OracleSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.OracleSource" />
  <TypeSignature Language="VB.NET" Value="Public Class OracleSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type OracleSource = class&#xA;    inherit CopySource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.CopySource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9acba-101">コピー アクティビティの Oracle ソース。</span><span class="sxs-lookup"><span data-stu-id="9acba-101">A copy activity Oracle source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OracleSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OracleSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9acba-102">OracleSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9acba-102">Initializes a new instance of the OracleSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OracleSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object oracleReaderQuery = null, object queryTimeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object oracleReaderQuery, object queryTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OracleSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional sourceRetryCount As Object = null, Optional sourceRetryWait As Object = null, Optional oracleReaderQuery As Object = null, Optional queryTimeout As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.OracleSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.OracleSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.OracleSource (additionalProperties, sourceRetryCount, sourceRetryWait, oracleReaderQuery, queryTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="oracleReaderQuery" Type="System.Object" />
        <Parameter Name="queryTimeout" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="9acba-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="9acba-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="sourceRetryCount"><span data-ttu-id="9acba-104">ソースの再試行回数です。</span><span class="sxs-lookup"><span data-stu-id="9acba-104">Source retry count.</span></span> <span data-ttu-id="9acba-105">型: 整数 (または式に整数の resultType)。</span><span class="sxs-lookup"><span data-stu-id="9acba-105">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sourceRetryWait"><span data-ttu-id="9acba-106">ソースの再試行の待機です。</span><span class="sxs-lookup"><span data-stu-id="9acba-106">Source retry wait.</span></span> <span data-ttu-id="9acba-107">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="9acba-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="oracleReaderQuery"><span data-ttu-id="9acba-108">Oracle リーダー クエリです。</span><span class="sxs-lookup"><span data-stu-id="9acba-108">Oracle reader query.</span></span> <span data-ttu-id="9acba-109">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="9acba-109">Type: string (or Expression with resultType string).</span></span></param>
        <param name="queryTimeout"><span data-ttu-id="9acba-110">クエリのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="9acba-110">Query timeout.</span></span> <span data-ttu-id="9acba-111">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="9acba-111">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <summary>
            <span data-ttu-id="9acba-112">OracleSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9acba-112">Initializes a new instance of the OracleSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OracleReaderQuery">
      <MemberSignature Language="C#" Value="public object OracleReaderQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object OracleReaderQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OracleSource.OracleReaderQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property OracleReaderQuery As Object" />
      <MemberSignature Language="F#" Value="member this.OracleReaderQuery : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OracleSource.OracleReaderQuery" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="oracleReaderQuery")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9acba-113">取得または oracle リーダーのクエリを設定します。</span><span class="sxs-lookup"><span data-stu-id="9acba-113">Gets or sets oracle reader query.</span></span> <span data-ttu-id="9acba-114">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="9acba-114">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryTimeout">
      <MemberSignature Language="C#" Value="public object QueryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object QueryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OracleSource.QueryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property QueryTimeout As Object" />
      <MemberSignature Language="F#" Value="member this.QueryTimeout : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OracleSource.QueryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="queryTimeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9acba-115">取得またはクエリのタイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="9acba-115">Gets or sets query timeout.</span></span> <span data-ttu-id="9acba-116">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="9acba-116">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>