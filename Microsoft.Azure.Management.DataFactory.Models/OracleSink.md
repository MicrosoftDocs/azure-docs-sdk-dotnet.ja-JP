<Type Name="OracleSink" FullName="Microsoft.Azure.Management.DataFactory.Models.OracleSink">
  <TypeSignature Language="C#" Value="public class OracleSink : Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OracleSink extends Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.OracleSink" />
  <TypeSignature Language="VB.NET" Value="Public Class OracleSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type OracleSink = class&#xA;    inherit CopySink" />
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
            <span data-ttu-id="26640-101">コピー アクティビティ Oracle シンクです。</span><span class="sxs-lookup"><span data-stu-id="26640-101">A copy activity Oracle sink.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OracleSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OracleSink.#ctor" />
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
            <span data-ttu-id="26640-102">OracleSink クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="26640-102">Initializes a new instance of the OracleSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OracleSink (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object writeBatchSize = null, object writeBatchTimeout = null, object sinkRetryCount = null, object sinkRetryWait = null, object preCopyScript = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object writeBatchSize, object writeBatchTimeout, object sinkRetryCount, object sinkRetryWait, object preCopyScript) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OracleSink.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional writeBatchSize As Object = null, Optional writeBatchTimeout As Object = null, Optional sinkRetryCount As Object = null, Optional sinkRetryWait As Object = null, Optional preCopyScript As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.OracleSink : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.OracleSink" Usage="new Microsoft.Azure.Management.DataFactory.Models.OracleSink (additionalProperties, writeBatchSize, writeBatchTimeout, sinkRetryCount, sinkRetryWait, preCopyScript)" />
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
        <param name="additionalProperties"><span data-ttu-id="26640-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="26640-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="writeBatchSize"><span data-ttu-id="26640-104">バッチ サイズを記述します。</span><span class="sxs-lookup"><span data-stu-id="26640-104">Write batch size.</span></span> <span data-ttu-id="26640-105">型: 整数 (または式と resultType 整数)、最小値: 0。</span><span class="sxs-lookup"><span data-stu-id="26640-105">Type: integer (or Expression with resultType integer), minimum: 0.</span></span></param>
        <param name="writeBatchTimeout"><span data-ttu-id="26640-106">バッチ タイムアウトを記述します。</span><span class="sxs-lookup"><span data-stu-id="26640-106">Write batch timeout.</span></span> <span data-ttu-id="26640-107">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="26640-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="sinkRetryCount"><span data-ttu-id="26640-108">再試行回数をシンクします。</span><span class="sxs-lookup"><span data-stu-id="26640-108">Sink retry count.</span></span> <span data-ttu-id="26640-109">型: 整数 (または式に整数の resultType)。</span><span class="sxs-lookup"><span data-stu-id="26640-109">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sinkRetryWait"><span data-ttu-id="26640-110">再試行の待機をシンクします。</span><span class="sxs-lookup"><span data-stu-id="26640-110">Sink retry wait.</span></span> <span data-ttu-id="26640-111">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="26640-111">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="preCopyScript"><span data-ttu-id="26640-112">コピー前の SQL スクリプト。</span><span class="sxs-lookup"><span data-stu-id="26640-112">SQL pre-copy script.</span></span> <span data-ttu-id="26640-113">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="26640-113">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="26640-114">OracleSink クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="26640-114">Initializes a new instance of the OracleSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreCopyScript">
      <MemberSignature Language="C#" Value="public object PreCopyScript { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object PreCopyScript" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OracleSink.PreCopyScript" />
      <MemberSignature Language="VB.NET" Value="Public Property PreCopyScript As Object" />
      <MemberSignature Language="F#" Value="member this.PreCopyScript : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OracleSink.PreCopyScript" />
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
            <span data-ttu-id="26640-115">取得または設定のコピー前の SQL スクリプト。</span><span class="sxs-lookup"><span data-stu-id="26640-115">Gets or sets SQL pre-copy script.</span></span> <span data-ttu-id="26640-116">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="26640-116">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>