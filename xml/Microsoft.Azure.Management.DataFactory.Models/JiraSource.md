<Type Name="JiraSource" FullName="Microsoft.Azure.Management.DataFactory.Models.JiraSource">
  <TypeSignature Language="C#" Value="public class JiraSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JiraSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.JiraSource" />
  <TypeSignature Language="VB.NET" Value="Public Class JiraSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type JiraSource = class&#xA;    inherit CopySource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.CopySource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d11c3-101">コピー アクティビティで Jira サービスのソース。</span><span class="sxs-lookup"><span data-stu-id="d11c3-101">A copy activity Jira Serivce source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JiraSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.JiraSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d11c3-102">JiraSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d11c3-102">Initializes a new instance of the JiraSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JiraSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object query = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.JiraSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional sourceRetryCount As Object = null, Optional sourceRetryWait As Object = null, Optional query As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.JiraSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.JiraSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.JiraSource (additionalProperties, sourceRetryCount, sourceRetryWait, query)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="query" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="d11c3-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="d11c3-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="sourceRetryCount"><span data-ttu-id="d11c3-104">ソースの再試行回数です。</span><span class="sxs-lookup"><span data-stu-id="d11c3-104">Source retry count.</span></span> <span data-ttu-id="d11c3-105">型: 整数 (または式に整数の resultType)。</span><span class="sxs-lookup"><span data-stu-id="d11c3-105">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sourceRetryWait"><span data-ttu-id="d11c3-106">ソースの再試行の待機です。</span><span class="sxs-lookup"><span data-stu-id="d11c3-106">Source retry wait.</span></span> <span data-ttu-id="d11c3-107">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="d11c3-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="query"><span data-ttu-id="d11c3-108">ソースからデータを取得するクエリ。</span><span class="sxs-lookup"><span data-stu-id="d11c3-108">A query to retrieve data from source.</span></span> <span data-ttu-id="d11c3-109">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="d11c3-109">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="d11c3-110">JiraSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d11c3-110">Initializes a new instance of the JiraSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public object Query { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Query" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.JiraSource.Query" />
      <MemberSignature Language="VB.NET" Value="Public Property Query As Object" />
      <MemberSignature Language="F#" Value="member this.Query : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.JiraSource.Query" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="query")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d11c3-111">取得またはデータ ソースから取得するクエリを設定します。</span><span class="sxs-lookup"><span data-stu-id="d11c3-111">Gets or sets a query to retrieve data from source.</span></span> <span data-ttu-id="d11c3-112">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="d11c3-112">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>