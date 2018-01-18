<Type Name="OdbcSink" FullName="Microsoft.Azure.Management.DataFactory.Models.OdbcSink">
  <TypeSignature Language="C#" Value="public class OdbcSink : Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OdbcSink extends Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.OdbcSink" />
  <TypeSignature Language="VB.NET" Value="Public Class OdbcSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type OdbcSink = class&#xA;    inherit CopySink" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.CopySink</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="16a68-101">コピー アクティビティ ODBC シンクです。</span><span class="sxs-lookup"><span data-stu-id="16a68-101">A copy activity ODBC sink.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OdbcSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OdbcSink.#ctor" />
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
            <span data-ttu-id="16a68-102">OdbcSink クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="16a68-102">Initializes a new instance of the OdbcSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OdbcSink (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object writeBatchSize = null, object writeBatchTimeout = null, object sinkRetryCount = null, object sinkRetryWait = null, object preCopyScript = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object writeBatchSize, object writeBatchTimeout, object sinkRetryCount, object sinkRetryWait, object preCopyScript) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OdbcSink.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional writeBatchSize As Object = null, Optional writeBatchTimeout As Object = null, Optional sinkRetryCount As Object = null, Optional sinkRetryWait As Object = null, Optional preCopyScript As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.OdbcSink : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.OdbcSink" Usage="new Microsoft.Azure.Management.DataFactory.Models.OdbcSink (additionalProperties, writeBatchSize, writeBatchTimeout, sinkRetryCount, sinkRetryWait, preCopyScript)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="writeBatchSize" Type="System.Object" />
        <Parameter Name="writeBatchTimeout" Type="System.Object" />
        <Parameter Name="sinkRetryCount" Type="System.Object" />
        <Parameter Name="sinkRetryWait" Type="System.Object" />
        <Parameter Name="preCopyScript" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="16a68-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="16a68-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="writeBatchSize"><span data-ttu-id="16a68-104">バッチ サイズを記述します。</span><span class="sxs-lookup"><span data-stu-id="16a68-104">Write batch size.</span></span> <span data-ttu-id="16a68-105">型: 整数 (または式と resultType 整数)、最小値: 0。</span><span class="sxs-lookup"><span data-stu-id="16a68-105">Type: integer (or Expression with resultType integer), minimum: 0.</span></span></param>
        <param name="writeBatchTimeout"><span data-ttu-id="16a68-106">バッチ タイムアウトを記述します。</span><span class="sxs-lookup"><span data-stu-id="16a68-106">Write batch timeout.</span></span> <span data-ttu-id="16a68-107">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="16a68-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="sinkRetryCount"><span data-ttu-id="16a68-108">再試行回数をシンクします。</span><span class="sxs-lookup"><span data-stu-id="16a68-108">Sink retry count.</span></span> <span data-ttu-id="16a68-109">型: 整数 (または式に整数の resultType)。</span><span class="sxs-lookup"><span data-stu-id="16a68-109">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sinkRetryWait"><span data-ttu-id="16a68-110">再試行の待機をシンクします。</span><span class="sxs-lookup"><span data-stu-id="16a68-110">Sink retry wait.</span></span> <span data-ttu-id="16a68-111">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="16a68-111">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="preCopyScript"><span data-ttu-id="16a68-112">コピーを開始する前に実行するクエリ。</span><span class="sxs-lookup"><span data-stu-id="16a68-112">A query to execute before starting the copy.</span></span> <span data-ttu-id="16a68-113">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="16a68-113">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="16a68-114">OdbcSink クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="16a68-114">Initializes a new instance of the OdbcSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreCopyScript">
      <MemberSignature Language="C#" Value="public object PreCopyScript { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object PreCopyScript" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OdbcSink.PreCopyScript" />
      <MemberSignature Language="VB.NET" Value="Public Property PreCopyScript As Object" />
      <MemberSignature Language="F#" Value="member this.PreCopyScript : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OdbcSink.PreCopyScript" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preCopyScript")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16a68-115">取得またはコピーを開始する前に実行するクエリを設定します。</span><span class="sxs-lookup"><span data-stu-id="16a68-115">Gets or sets a query to execute before starting the copy.</span></span> <span data-ttu-id="16a68-116">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="16a68-116">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>