<Type Name="FileProperties" FullName="Microsoft.Azure.Batch.Protocol.Models.FileProperties">
  <TypeSignature Language="C#" Value="public class FileProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.FileProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class FileProperties" />
  <TypeSignature Language="F#" Value="type FileProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4d729-101">コンピューティング ノード上のファイルのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="4d729-101">The properties of a file on a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4d729-102">FileProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4d729-102">Initializes a new instance of the FileProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileProperties (DateTime lastModified, long contentLength, Nullable&lt;DateTime&gt; creationTime = null, string contentType = null, string fileMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime lastModified, int64 contentLength, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, string contentType, string fileMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileProperties.#ctor(System.DateTime,System.Int64,System.Nullable{System.DateTime},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (lastModified As DateTime, contentLength As Long, Optional creationTime As Nullable(Of DateTime) = null, Optional contentType As String = null, Optional fileMode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.FileProperties : DateTime * int64 * Nullable&lt;DateTime&gt; * string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.FileProperties" Usage="new Microsoft.Azure.Batch.Protocol.Models.FileProperties (lastModified, contentLength, creationTime, contentType, fileMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lastModified" Type="System.DateTime" />
        <Parameter Name="contentLength" Type="System.Int64" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="fileMode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lastModified"><span data-ttu-id="4d729-103">ファイルが最後に変更された時刻。</span><span class="sxs-lookup"><span data-stu-id="4d729-103">The time at which the file was last modified.</span></span></param>
        <param name="contentLength"><span data-ttu-id="4d729-104">ファイルの長さ。</span><span class="sxs-lookup"><span data-stu-id="4d729-104">The length of the file.</span></span></param>
        <param name="creationTime"><span data-ttu-id="4d729-105">ファイルの作成時刻。</span><span class="sxs-lookup"><span data-stu-id="4d729-105">The file creation time.</span></span></param>
        <param name="contentType"><span data-ttu-id="4d729-106">ファイルのコンテンツの種類。</span><span class="sxs-lookup"><span data-stu-id="4d729-106">The content type of the file.</span></span></param>
        <param name="fileMode"><span data-ttu-id="4d729-107">8 進数形式でファイル モード属性です。</span><span class="sxs-lookup"><span data-stu-id="4d729-107">The file mode attribute in octal format.</span></span></param>
        <summary>
            <span data-ttu-id="4d729-108">FileProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4d729-108">Initializes a new instance of the FileProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLength">
      <MemberSignature Language="C#" Value="public long ContentLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ContentLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileProperties.ContentLength" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentLength As Long" />
      <MemberSignature Language="F#" Value="member this.ContentLength : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileProperties.ContentLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="contentLength")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d729-109">取得またはファイルの長さを設定します。</span><span class="sxs-lookup"><span data-stu-id="4d729-109">Gets or sets the length of the file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileProperties.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileProperties.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="contentType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d729-110">取得またはファイルのコンテンツの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="4d729-110">Gets or sets the content type of the file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileProperties.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileProperties.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d729-111">取得またはファイル作成時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="4d729-111">Gets or sets the file creation time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="4d729-112">Linux 計算ノード上のファイルの作成時は返されません。</span><span class="sxs-lookup"><span data-stu-id="4d729-112">The creation time is not returned for files on Linux compute nodes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FileMode">
      <MemberSignature Language="C#" Value="public string FileMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileProperties.FileMode" />
      <MemberSignature Language="VB.NET" Value="Public Property FileMode As String" />
      <MemberSignature Language="F#" Value="member this.FileMode : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileProperties.FileMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d729-113">取得または 8 進数形式でファイル モード属性を設定します。</span><span class="sxs-lookup"><span data-stu-id="4d729-113">Gets or sets the file mode attribute in octal format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="4d729-114">ファイル モードが Linux 計算ノード上のファイルに対してのみ返されます。</span><span class="sxs-lookup"><span data-stu-id="4d729-114">The file mode is returned only for files on Linux compute nodes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public DateTime LastModified { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileProperties.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModified As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastModified : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileProperties.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastModified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d729-115">取得またはファイルが最後に変更された日時を設定します。</span><span class="sxs-lookup"><span data-stu-id="4d729-115">Gets or sets the time at which the file was last modified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="fileProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4d729-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="4d729-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4d729-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4d729-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>