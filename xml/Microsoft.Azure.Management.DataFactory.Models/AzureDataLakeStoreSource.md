<Type Name="AzureDataLakeStoreSource" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSource">
  <TypeSignature Language="C#" Value="public class AzureDataLakeStoreSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureDataLakeStoreSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSource" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureDataLakeStoreSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type AzureDataLakeStoreSource = class&#xA;    inherit CopySource" />
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
            <span data-ttu-id="16ba0-101">コピー アクティビティの Azure Data Lake ソース。</span><span class="sxs-lookup"><span data-stu-id="16ba0-101">A copy activity Azure Data Lake source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureDataLakeStoreSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSource.#ctor" />
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
            <span data-ttu-id="16ba0-102">AzureDataLakeStoreSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="16ba0-102">Initializes a new instance of the AzureDataLakeStoreSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureDataLakeStoreSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object recursive = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object recursive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional sourceRetryCount As Object = null, Optional sourceRetryWait As Object = null, Optional recursive As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSource (additionalProperties, sourceRetryCount, sourceRetryWait, recursive)" />
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
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="16ba0-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="16ba0-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="sourceRetryCount"><span data-ttu-id="16ba0-104">ソースの再試行回数です。</span><span class="sxs-lookup"><span data-stu-id="16ba0-104">Source retry count.</span></span> <span data-ttu-id="16ba0-105">型: 整数 (または式に整数の resultType)。</span><span class="sxs-lookup"><span data-stu-id="16ba0-105">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sourceRetryWait"><span data-ttu-id="16ba0-106">ソースの再試行の待機です。</span><span class="sxs-lookup"><span data-stu-id="16ba0-106">Source retry wait.</span></span> <span data-ttu-id="16ba0-107">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="16ba0-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="recursive"><span data-ttu-id="16ba0-108">True の場合、フォルダーのパスの下のファイルには、再帰的が読み取られます。</span><span class="sxs-lookup"><span data-stu-id="16ba0-108">If true, files under the folder path will be read recursively.</span></span> <span data-ttu-id="16ba0-109">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="16ba0-109">Default is true.</span></span> <span data-ttu-id="16ba0-110">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="16ba0-110">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <summary>
            <span data-ttu-id="16ba0-111">AzureDataLakeStoreSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="16ba0-111">Initializes a new instance of the AzureDataLakeStoreSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recursive">
      <MemberSignature Language="C#" Value="public object Recursive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Recursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSource.Recursive" />
      <MemberSignature Language="VB.NET" Value="Public Property Recursive As Object" />
      <MemberSignature Language="F#" Value="member this.Recursive : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSource.Recursive" />
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
            <span data-ttu-id="16ba0-112">取得または設定が true の場合、フォルダーのパスの下のファイルには、再帰的が読み取られます。</span><span class="sxs-lookup"><span data-stu-id="16ba0-112">Gets or sets if true, files under the folder path will be read recursively.</span></span> <span data-ttu-id="16ba0-113">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="16ba0-113">Default is true.</span></span> <span data-ttu-id="16ba0-114">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="16ba0-114">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>