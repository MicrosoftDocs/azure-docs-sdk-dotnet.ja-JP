<Type Name="SqlQuerySpec" FullName="Microsoft.Azure.Documents.SqlQuerySpec">
  <TypeSignature Language="C#" Value="public sealed class SqlQuerySpec" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SqlQuerySpec extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.SqlQuerySpec" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SqlQuerySpec" />
  <TypeSignature Language="F#" Value="type SqlQuerySpec = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9a7c5-101">Azure Cosmos DB サービス SQL クエリを表します。</span><span class="sxs-lookup"><span data-stu-id="9a7c5-101">Represents a SQL query in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlQuerySpec ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlQuerySpec.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9a7c5-102">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" /> Azure Cosmos DB サービスのクラスです。</span><span class="sxs-lookup"><span data-stu-id="9a7c5-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" /> class for the Azure Cosmos DB service.</span></span></summary>
        <remarks> 
            <span data-ttu-id="9a7c5-103">既定のコンストラクターは、フィールドを既定値に初期化します。</span><span class="sxs-lookup"><span data-stu-id="9a7c5-103">The default constructor initializes any fields to their default values.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlQuerySpec (string queryText);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string queryText) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlQuerySpec.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (queryText As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.SqlQuerySpec : string -&gt; Microsoft.Azure.Documents.SqlQuerySpec" Usage="new Microsoft.Azure.Documents.SqlQuerySpec queryText" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="queryText" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="queryText"><span data-ttu-id="9a7c5-104">クエリのテキスト。</span><span class="sxs-lookup"><span data-stu-id="9a7c5-104">The text of the query.</span></span></param>
        <summary>
            <span data-ttu-id="9a7c5-105">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" /> Azure Cosmos DB サービスのクラスです。</span><span class="sxs-lookup"><span data-stu-id="9a7c5-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlQuerySpec (string queryText, Microsoft.Azure.Documents.SqlParameterCollection parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string queryText, class Microsoft.Azure.Documents.SqlParameterCollection parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlQuerySpec.#ctor(System.String,Microsoft.Azure.Documents.SqlParameterCollection)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (queryText As String, parameters As SqlParameterCollection)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.SqlQuerySpec : string * Microsoft.Azure.Documents.SqlParameterCollection -&gt; Microsoft.Azure.Documents.SqlQuerySpec" Usage="new Microsoft.Azure.Documents.SqlQuerySpec (queryText, parameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="queryText" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Documents.SqlParameterCollection" />
      </Parameters>
      <Docs>
        <param name="queryText"><span data-ttu-id="9a7c5-106">データベース クエリのテキストです。</span><span class="sxs-lookup"><span data-stu-id="9a7c5-106">The text of the database query.</span></span></param>
        <param name="parameters"><span data-ttu-id="9a7c5-107"><see cref="T:Microsoft.Azure.Documents.SqlParameterCollection" />インスタンスで、クエリ パラメーターのコレクションを表します。</span><span class="sxs-lookup"><span data-stu-id="9a7c5-107">The <see cref="T:Microsoft.Azure.Documents.SqlParameterCollection" /> instance, which represents the collection of query parameters.</span></span></param>
        <summary>
            <span data-ttu-id="9a7c5-108">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" /> Azure Cosmos DB サービスのクラスです。</span><span class="sxs-lookup"><span data-stu-id="9a7c5-108">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.SqlParameterCollection Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.SqlParameterCollection Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.SqlQuerySpec.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As SqlParameterCollection" />
      <MemberSignature Language="F#" Value="member this.Parameters : Microsoft.Azure.Documents.SqlParameterCollection with get, set" Usage="Microsoft.Azure.Documents.SqlQuerySpec.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Name="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.SqlParameterCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a7c5-109">取得または設定、<see cref="T:Microsoft.Azure.Documents.SqlParameterCollection" />インスタンスで、Azure Cosmos DB クエリ パラメーターのコレクションを表します。</span><span class="sxs-lookup"><span data-stu-id="9a7c5-109">Gets or sets the <see cref="T:Microsoft.Azure.Documents.SqlParameterCollection" /> instance, which represents the collection of Azure Cosmos DB query parameters.</span></span>
            </summary>
        <value><span data-ttu-id="9a7c5-110"><see cref="T:Microsoft.Azure.Documents.SqlParameterCollection" /> インスタンス。</span><span class="sxs-lookup"><span data-stu-id="9a7c5-110">The <see cref="T:Microsoft.Azure.Documents.SqlParameterCollection" /> instance.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryText">
      <MemberSignature Language="C#" Value="public string QueryText { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QueryText" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.SqlQuerySpec.QueryText" />
      <MemberSignature Language="VB.NET" Value="Public Property QueryText As String" />
      <MemberSignature Language="F#" Value="member this.QueryText : string with get, set" Usage="Microsoft.Azure.Documents.SqlQuerySpec.QueryText" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Name="query")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a7c5-111">取得または Azure Cosmos DB データベース クエリのテキストを設定します。</span><span class="sxs-lookup"><span data-stu-id="9a7c5-111">Gets or sets the text of the Azure Cosmos DB database query.</span></span>
            </summary>
        <value><span data-ttu-id="9a7c5-112">データベース クエリのテキストです。</span><span class="sxs-lookup"><span data-stu-id="9a7c5-112">The text of the database query.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldSerializeParameters">
      <MemberSignature Language="C#" Value="public bool ShouldSerializeParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool ShouldSerializeParameters() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlQuerySpec.ShouldSerializeParameters" />
      <MemberSignature Language="VB.NET" Value="Public Function ShouldSerializeParameters () As Boolean" />
      <MemberSignature Language="F#" Value="member this.ShouldSerializeParameters : unit -&gt; bool" Usage="sqlQuerySpec.ShouldSerializeParameters " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9a7c5-113">示す値を返すかどうか、Azure Cosmos DB データベース<see cref="P:Microsoft.Azure.Documents.SqlQuerySpec.Parameters" />プロパティをシリアル化する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9a7c5-113">Returns a value that indicates whether the Azure Cosmos DB database <see cref="P:Microsoft.Azure.Documents.SqlQuerySpec.Parameters" /> property should be serialized.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>