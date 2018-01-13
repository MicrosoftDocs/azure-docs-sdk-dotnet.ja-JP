<Type Name="File" FullName="Microsoft.Azure.Management.BatchAI.Models.File">
  <TypeSignature Language="C#" Value="public class File" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit File extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.File" />
  <TypeSignature Language="VB.NET" Value="Public Class File" />
  <TypeSignature Language="F#" Value="type File = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="01991-101">ファイルのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="01991-101">Properties of the file.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public File ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.File.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="01991-102">ファイルのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="01991-102">Initializes a new instance of the File class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public File (string name, string downloadUrl, Nullable&lt;DateTime&gt; lastModified = null, Nullable&lt;long&gt; contentLength = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string downloadUrl, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, valuetype System.Nullable`1&lt;int64&gt; contentLength) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.File.#ctor(System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, downloadUrl As String, Optional lastModified As Nullable(Of DateTime) = null, Optional contentLength As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.File : string * string * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.File" Usage="new Microsoft.Azure.Management.BatchAI.Models.File (name, downloadUrl, lastModified, contentLength)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="downloadUrl" Type="System.String" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="contentLength" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="01991-103">file name</span><span class="sxs-lookup"><span data-stu-id="01991-103">file name</span></span></param>
        <param name="downloadUrl"><span data-ttu-id="01991-104">ファイル downloand url、例: https://mystg.blob.core.windows.net/mycontainer/myModel_1.dnn</span><span class="sxs-lookup"><span data-stu-id="01991-104">file downloand url, example: https://mystg.blob.core.windows.net/mycontainer/myModel_1.dnn</span></span></param>
        <param name="lastModified"><span data-ttu-id="01991-105">ファイルが最後に変更された時刻。</span><span class="sxs-lookup"><span data-stu-id="01991-105">The time at which the file was last modified.</span></span></param>
        <param name="contentLength"><span data-ttu-id="01991-106">ファイル サイズ。</span><span class="sxs-lookup"><span data-stu-id="01991-106">The file size.</span></span></param>
        <summary>
            <span data-ttu-id="01991-107">ファイルのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="01991-107">Initializes a new instance of the File class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLength">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ContentLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ContentLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.File.ContentLength" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentLength As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ContentLength : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.File.ContentLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.contentLength")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="01991-108">取得またはファイルのサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="01991-108">Gets or sets the file size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="01991-109">ファイル サイズ。</span><span class="sxs-lookup"><span data-stu-id="01991-109">The file size.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadUrl">
      <MemberSignature Language="C#" Value="public string DownloadUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DownloadUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.File.DownloadUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property DownloadUrl As String" />
      <MemberSignature Language="F#" Value="member this.DownloadUrl : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.File.DownloadUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="downloadUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="01991-110">取得または設定ファイル downloand url の例: https://mystg.blob.core.windows.net/mycontainer/myModel_1.dnn</span><span class="sxs-lookup"><span data-stu-id="01991-110">Gets or sets file downloand url, example: https://mystg.blob.core.windows.net/mycontainer/myModel_1.dnn</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="01991-111">これは、モデルはアーカイブされた場合にのみ返されます。</span><span class="sxs-lookup"><span data-stu-id="01991-111">This will be returned only if the model has been archived.</span></span> <span data-ttu-id="01991-112">ジョブの実行時にこれが返されされません、お客様は、トンネリングをダウンロードする SSH を使用できます。</span><span class="sxs-lookup"><span data-stu-id="01991-112">During job run, this won't be returned and customers can use SSH tunneling to download.</span></span> <span data-ttu-id="01991-113">ユーザーは、リモート ログイン情報の取得 API を使用して、ジョブを実行しているすべてのコンピューティング ノードの IP アドレスとポート情報を取得することができます。</span><span class="sxs-lookup"><span data-stu-id="01991-113">Users can use Get Remote Login Information API to get the IP address and port information of all the compute nodes running the job.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.File.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.File.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="01991-114">取得またはファイルが最後に変更された日時を設定します。</span><span class="sxs-lookup"><span data-stu-id="01991-114">Gets or sets the time at which the file was last modified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="01991-115">ファイルが最後に変更された時刻。</span><span class="sxs-lookup"><span data-stu-id="01991-115">The time at which the file was last modified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.File.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.File.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="01991-116">取得またはファイル名を設定</span><span class="sxs-lookup"><span data-stu-id="01991-116">Gets or sets file name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.File.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="file.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="01991-117">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="01991-117">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01991-118">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01991-118">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>