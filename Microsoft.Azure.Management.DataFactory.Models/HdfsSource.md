<Type Name="HdfsSource" FullName="Microsoft.Azure.Management.DataFactory.Models.HdfsSource">
  <TypeSignature Language="C#" Value="public class HdfsSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HdfsSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HdfsSource" />
  <TypeSignature Language="VB.NET" Value="Public Class HdfsSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type HdfsSource = class&#xA;    inherit CopySource" />
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
            <span data-ttu-id="5163e-101">コピー アクティビティの HDFS ソース。</span><span class="sxs-lookup"><span data-stu-id="5163e-101">A copy activity HDFS source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HdfsSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HdfsSource.#ctor" />
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
            <span data-ttu-id="5163e-102">HdfsSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5163e-102">Initializes a new instance of the HdfsSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HdfsSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object recursive = null, Microsoft.Azure.Management.DataFactory.Models.DistcpSettings distcpSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object recursive, class Microsoft.Azure.Management.DataFactory.Models.DistcpSettings distcpSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HdfsSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.DistcpSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HdfsSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.DistcpSettings -&gt; Microsoft.Azure.Management.DataFactory.Models.HdfsSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.HdfsSource (additionalProperties, sourceRetryCount, sourceRetryWait, recursive, distcpSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="recursive" Type="System.Object" />
        <Parameter Name="distcpSettings" Type="Microsoft.Azure.Management.DataFactory.Models.DistcpSettings" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="5163e-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="5163e-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="sourceRetryCount"><span data-ttu-id="5163e-104">ソースの再試行回数です。</span><span class="sxs-lookup"><span data-stu-id="5163e-104">Source retry count.</span></span> <span data-ttu-id="5163e-105">型: 整数 (または式に整数の resultType)。</span><span class="sxs-lookup"><span data-stu-id="5163e-105">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sourceRetryWait"><span data-ttu-id="5163e-106">ソースの再試行の待機です。</span><span class="sxs-lookup"><span data-stu-id="5163e-106">Source retry wait.</span></span> <span data-ttu-id="5163e-107">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="5163e-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="recursive"><span data-ttu-id="5163e-108">True の場合、フォルダーのパスの下のファイルには、再帰的が読み取られます。</span><span class="sxs-lookup"><span data-stu-id="5163e-108">If true, files under the folder path will be read recursively.</span></span> <span data-ttu-id="5163e-109">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="5163e-109">Default is true.</span></span> <span data-ttu-id="5163e-110">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="5163e-110">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <param name="distcpSettings"><span data-ttu-id="5163e-111">Distcp 関連の設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="5163e-111">Specifies Distcp-related settings.</span></span></param>
        <summary>
            <span data-ttu-id="5163e-112">HdfsSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5163e-112">Initializes a new instance of the HdfsSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DistcpSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.DistcpSettings DistcpSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.DistcpSettings DistcpSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HdfsSource.DistcpSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property DistcpSettings As DistcpSettings" />
      <MemberSignature Language="F#" Value="member this.DistcpSettings : Microsoft.Azure.Management.DataFactory.Models.DistcpSettings with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HdfsSource.DistcpSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="distcpSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.DistcpSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5163e-113">取得または設定 Distcp 関連の設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="5163e-113">Gets or sets specifies Distcp-related settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recursive">
      <MemberSignature Language="C#" Value="public object Recursive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Recursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HdfsSource.Recursive" />
      <MemberSignature Language="VB.NET" Value="Public Property Recursive As Object" />
      <MemberSignature Language="F#" Value="member this.Recursive : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HdfsSource.Recursive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recursive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5163e-114">取得または設定が true の場合、フォルダーのパスの下のファイルには、再帰的が読み取られます。</span><span class="sxs-lookup"><span data-stu-id="5163e-114">Gets or sets if true, files under the folder path will be read recursively.</span></span> <span data-ttu-id="5163e-115">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="5163e-115">Default is true.</span></span> <span data-ttu-id="5163e-116">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="5163e-116">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HdfsSource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="hdfsSource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5163e-117">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="5163e-117">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5163e-118">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5163e-118">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>