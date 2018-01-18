<Type Name="AzureTableSource" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureTableSource">
  <TypeSignature Language="C#" Value="public class AzureTableSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureTableSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureTableSource" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureTableSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type AzureTableSource = class&#xA;    inherit CopySource" />
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
            <span data-ttu-id="30449-101">コピー アクティビティの Azure テーブル ソースです。</span><span class="sxs-lookup"><span data-stu-id="30449-101">A copy activity Azure Table source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureTableSource.#ctor" />
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
            <span data-ttu-id="30449-102">AzureTableSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="30449-102">Initializes a new instance of the AzureTableSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object azureTableSourceQuery = null, object azureTableSourceIgnoreTableNotFound = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object azureTableSourceQuery, object azureTableSourceIgnoreTableNotFound) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureTableSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional sourceRetryCount As Object = null, Optional sourceRetryWait As Object = null, Optional azureTableSourceQuery As Object = null, Optional azureTableSourceIgnoreTableNotFound As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureTableSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureTableSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureTableSource (additionalProperties, sourceRetryCount, sourceRetryWait, azureTableSourceQuery, azureTableSourceIgnoreTableNotFound)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="azureTableSourceQuery" Type="System.Object" />
        <Parameter Name="azureTableSourceIgnoreTableNotFound" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="30449-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="30449-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="sourceRetryCount"><span data-ttu-id="30449-104">ソースの再試行回数です。</span><span class="sxs-lookup"><span data-stu-id="30449-104">Source retry count.</span></span> <span data-ttu-id="30449-105">型: 整数 (または式に整数の resultType)。</span><span class="sxs-lookup"><span data-stu-id="30449-105">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sourceRetryWait"><span data-ttu-id="30449-106">ソースの再試行の待機です。</span><span class="sxs-lookup"><span data-stu-id="30449-106">Source retry wait.</span></span> <span data-ttu-id="30449-107">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="30449-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="azureTableSourceQuery"><span data-ttu-id="30449-108">Azure のテーブル ソース クエリです。</span><span class="sxs-lookup"><span data-stu-id="30449-108">Azure Table source query.</span></span> <span data-ttu-id="30449-109">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="30449-109">Type: string (or Expression with resultType string).</span></span></param>
        <param name="azureTableSourceIgnoreTableNotFound"><span data-ttu-id="30449-110">Azure のテーブル ソースは、テーブルが見つかりません。 を無視します。</span><span class="sxs-lookup"><span data-stu-id="30449-110">Azure Table source ignore table not found.</span></span> <span data-ttu-id="30449-111">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="30449-111">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <summary>
            <span data-ttu-id="30449-112">AzureTableSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="30449-112">Initializes a new instance of the AzureTableSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableSourceIgnoreTableNotFound">
      <MemberSignature Language="C#" Value="public object AzureTableSourceIgnoreTableNotFound { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AzureTableSourceIgnoreTableNotFound" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableSource.AzureTableSourceIgnoreTableNotFound" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableSourceIgnoreTableNotFound As Object" />
      <MemberSignature Language="F#" Value="member this.AzureTableSourceIgnoreTableNotFound : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableSource.AzureTableSourceIgnoreTableNotFound" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTableSourceIgnoreTableNotFound")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30449-113">取得またはソース テーブルが見つかりません。 を無視する azure のテーブルを設定します。</span><span class="sxs-lookup"><span data-stu-id="30449-113">Gets or sets azure Table source ignore table not found.</span></span> <span data-ttu-id="30449-114">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="30449-114">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableSourceQuery">
      <MemberSignature Language="C#" Value="public object AzureTableSourceQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AzureTableSourceQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableSource.AzureTableSourceQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableSourceQuery As Object" />
      <MemberSignature Language="F#" Value="member this.AzureTableSourceQuery : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableSource.AzureTableSourceQuery" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTableSourceQuery")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30449-115">取得または azure のテーブル ソース クエリを設定します。</span><span class="sxs-lookup"><span data-stu-id="30449-115">Gets or sets azure Table source query.</span></span> <span data-ttu-id="30449-116">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="30449-116">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>