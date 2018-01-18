<Type Name="AzureSearchIndexSink" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureSearchIndexSink">
  <TypeSignature Language="C#" Value="public class AzureSearchIndexSink : Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureSearchIndexSink extends Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureSearchIndexSink" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureSearchIndexSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type AzureSearchIndexSink = class&#xA;    inherit CopySink" />
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
            <span data-ttu-id="3b73b-101">コピー アクティビティの Azure Search インデックス シンクです。</span><span class="sxs-lookup"><span data-stu-id="3b73b-101">A copy activity Azure Search Index sink.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSearchIndexSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureSearchIndexSink.#ctor" />
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
            <span data-ttu-id="3b73b-102">AzureSearchIndexSink クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3b73b-102">Initializes a new instance of the AzureSearchIndexSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSearchIndexSink (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object writeBatchSize = null, object writeBatchTimeout = null, object sinkRetryCount = null, object sinkRetryWait = null, string writeBehavior = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object writeBatchSize, object writeBatchTimeout, object sinkRetryCount, object sinkRetryWait, string writeBehavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureSearchIndexSink.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional writeBatchSize As Object = null, Optional writeBatchTimeout As Object = null, Optional sinkRetryCount As Object = null, Optional sinkRetryWait As Object = null, Optional writeBehavior As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureSearchIndexSink : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * string -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureSearchIndexSink" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureSearchIndexSink (additionalProperties, writeBatchSize, writeBatchTimeout, sinkRetryCount, sinkRetryWait, writeBehavior)" />
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
        <Parameter Name="writeBehavior" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="3b73b-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="3b73b-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="writeBatchSize"><span data-ttu-id="3b73b-104">バッチ サイズを記述します。</span><span class="sxs-lookup"><span data-stu-id="3b73b-104">Write batch size.</span></span> <span data-ttu-id="3b73b-105">型: 整数 (または式と resultType 整数)、最小値: 0。</span><span class="sxs-lookup"><span data-stu-id="3b73b-105">Type: integer (or Expression with resultType integer), minimum: 0.</span></span></param>
        <param name="writeBatchTimeout"><span data-ttu-id="3b73b-106">バッチ タイムアウトを記述します。</span><span class="sxs-lookup"><span data-stu-id="3b73b-106">Write batch timeout.</span></span> <span data-ttu-id="3b73b-107">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="3b73b-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="sinkRetryCount"><span data-ttu-id="3b73b-108">再試行回数をシンクします。</span><span class="sxs-lookup"><span data-stu-id="3b73b-108">Sink retry count.</span></span> <span data-ttu-id="3b73b-109">型: 整数 (または式に整数の resultType)。</span><span class="sxs-lookup"><span data-stu-id="3b73b-109">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sinkRetryWait"><span data-ttu-id="3b73b-110">再試行の待機をシンクします。</span><span class="sxs-lookup"><span data-stu-id="3b73b-110">Sink retry wait.</span></span> <span data-ttu-id="3b73b-111">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="3b73b-111">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="writeBehavior"><span data-ttu-id="3b73b-112">アップサート文書の Azure Search インデックスには、書き込みの動作を指定します。</span><span class="sxs-lookup"><span data-stu-id="3b73b-112">Specify the write behavior when upserting documents into Azure Search Index.</span></span> <span data-ttu-id="3b73b-113">使用可能な値が含まれます: 'Merge'、'アップロード'</span><span class="sxs-lookup"><span data-stu-id="3b73b-113">Possible values include: 'Merge', 'Upload'</span></span></param>
        <summary>
            <span data-ttu-id="3b73b-114">AzureSearchIndexSink クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3b73b-114">Initializes a new instance of the AzureSearchIndexSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteBehavior">
      <MemberSignature Language="C#" Value="public string WriteBehavior { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WriteBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureSearchIndexSink.WriteBehavior" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteBehavior As String" />
      <MemberSignature Language="F#" Value="member this.WriteBehavior : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureSearchIndexSink.WriteBehavior" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="writeBehavior")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b73b-115">取得または設定は、Azure Search インデックスに文書のアップサート書き込みの動作を指定します。</span><span class="sxs-lookup"><span data-stu-id="3b73b-115">Gets or sets specify the write behavior when upserting documents into Azure Search Index.</span></span> <span data-ttu-id="3b73b-116">使用可能な値が含まれます: 'Merge'、'アップロード'</span><span class="sxs-lookup"><span data-stu-id="3b73b-116">Possible values include: 'Merge', 'Upload'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>