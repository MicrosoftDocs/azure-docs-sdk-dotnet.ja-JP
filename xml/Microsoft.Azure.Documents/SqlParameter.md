<Type Name="SqlParameter" FullName="Microsoft.Azure.Documents.SqlParameter">
  <TypeSignature Language="C#" Value="public sealed class SqlParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SqlParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.SqlParameter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SqlParameter" />
  <TypeSignature Language="F#" Value="type SqlParameter = class" />
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
            <span data-ttu-id="bf76e-101">関連付けられているパラメーターを表す<see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />Cosmos DB の Azure サービスにします。</span><span class="sxs-lookup"><span data-stu-id="bf76e-101">Represents a parameter associated with <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" /> in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="bf76e-102">Azure Cosmos DB SQL パラメーターは、パラメーター化クエリで参照されている名前と値のペアです。</span><span class="sxs-lookup"><span data-stu-id="bf76e-102">Azure Cosmos DB SQL parameters are name-value pairs referenced in parameterized queries.</span></span> <span data-ttu-id="bf76e-103">異なり関係 SQL データベースで必要はありませんそれらに関連付けられている型。</span><span class="sxs-lookup"><span data-stu-id="bf76e-103">Unlike in relation SQL databases, they don't have types associated with them.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameter.#ctor" />
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
            <span data-ttu-id="bf76e-104">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.SqlParameter" /> Azure Cosmos DB サービスのクラスです。</span><span class="sxs-lookup"><span data-stu-id="bf76e-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.SqlParameter" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlParameter (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.SqlParameter : string -&gt; Microsoft.Azure.Documents.SqlParameter" Usage="new Microsoft.Azure.Documents.SqlParameter name" />
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
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="bf76e-105">パラメーターの名前。</span><span class="sxs-lookup"><span data-stu-id="bf76e-105">The name of the parameter.</span></span></param>
        <summary>
            <span data-ttu-id="bf76e-106">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.SqlParameter" /> Azure Cosmos DB サービスのパラメーターの名前を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="bf76e-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.SqlParameter" /> class with the name of the parameter for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks><span data-ttu-id="bf76e-107">パラメーターの名前が始まる必要があります ' @' 有効な SQL 識別子であるとします。</span><span class="sxs-lookup"><span data-stu-id="bf76e-107">Names of parameters must begin with '@' and be a valid SQL identifier.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlParameter (string name, object value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameter.#ctor(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, value As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.SqlParameter : string * obj -&gt; Microsoft.Azure.Documents.SqlParameter" Usage="new Microsoft.Azure.Documents.SqlParameter (name, value)" />
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
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="bf76e-108">パラメーターの名前。</span><span class="sxs-lookup"><span data-stu-id="bf76e-108">The name of the parameter.</span></span></param>
        <param name="value"><span data-ttu-id="bf76e-109">パラメーターの値。</span><span class="sxs-lookup"><span data-stu-id="bf76e-109">The value of the parameter.</span></span></param>
        <summary>
            <span data-ttu-id="bf76e-110">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.SqlParameter" /> Azure Cosmos DB サービスのパラメーターの値と名前を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="bf76e-110">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.SqlParameter" /> class with the name and value of the parameter for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks><span data-ttu-id="bf76e-111">パラメーターの名前が始まる必要があります ' @' 有効な SQL 識別子であるとします。</span><span class="sxs-lookup"><span data-stu-id="bf76e-111">Names of parameters must begin with '@' and be a valid SQL identifier.</span></span> <span data-ttu-id="bf76e-112">値は、シリアル化およびとして渡される JSON ドキュメントのクエリを取得します。</span><span class="sxs-lookup"><span data-stu-id="bf76e-112">The value gets serialized and passed in as JSON to the document query.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.SqlParameter.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Documents.SqlParameter.Name" />
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
          <AttributeName>System.Runtime.Serialization.DataMember(Name="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf76e-113">取得または Azure Cosmos DB サービスのパラメーターの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="bf76e-113">Gets or sets the name of the parameter for the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="bf76e-114">パラメーターの名前。</span><span class="sxs-lookup"><span data-stu-id="bf76e-114">The name of the parameter.</span></span></value>
        <remarks><span data-ttu-id="bf76e-115">パラメーターの名前が始まる必要があります ' @' 有効な SQL 識別子であるとします。</span><span class="sxs-lookup"><span data-stu-id="bf76e-115">Names of parameters must begin with '@' and be a valid SQL identifier.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public object Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.SqlParameter.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As Object" />
      <MemberSignature Language="F#" Value="member this.Value : obj with get, set" Usage="Microsoft.Azure.Documents.SqlParameter.Value" />
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
          <AttributeName>System.Runtime.Serialization.DataMember(Name="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf76e-116">取得または Azure Cosmos DB サービスのパラメーターの値を設定します。</span><span class="sxs-lookup"><span data-stu-id="bf76e-116">Gets or sets the value of the parameter for the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="bf76e-117">パラメーターの値。</span><span class="sxs-lookup"><span data-stu-id="bf76e-117">The value of the parameter.</span></span></value>
        <remarks><span data-ttu-id="bf76e-118">値は、シリアル化およびとして渡される JSON ドキュメントのクエリを取得します。</span><span class="sxs-lookup"><span data-stu-id="bf76e-118">The value gets serialized and passed in as JSON to the document query.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>