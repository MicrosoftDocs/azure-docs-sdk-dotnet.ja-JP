<Type Name="DataContainer" FullName="Microsoft.Azure.Search.Models.DataContainer">
  <TypeSignature Language="C#" Value="public class DataContainer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataContainer extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DataContainer" />
  <TypeSignature Language="VB.NET" Value="Public Class DataContainer" />
  <TypeSignature Language="F#" Value="type DataContainer = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="74f9f-101">インデックスが作成されるエンティティ (Azure SQL テーブルや DocumentDb コレクションなど) に関する情報を表します。</span><span class="sxs-lookup"><span data-stu-id="74f9f-101">Represents information about the entity (such as Azure SQL table or DocumentDb collection) that will be indexed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataContainer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataContainer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="74f9f-102">DataContainer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="74f9f-102">Initializes a new instance of the DataContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataContainer (string name, string query = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataContainer.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional query As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.DataContainer : string * string -&gt; Microsoft.Azure.Search.Models.DataContainer" Usage="new Microsoft.Azure.Search.Models.DataContainer (name, query)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="74f9f-103">(Azure SQL データ ソース) のテーブルまたはビューの名前またはインデックスが作成される (DocumentDB データ ソース) のコレクション。</span><span class="sxs-lookup"><span data-stu-id="74f9f-103">The name of the table or view (for Azure SQL data source) or collection (for DocumentDB data source) that will be indexed.</span></span></param>
        <param name="query"><span data-ttu-id="74f9f-104">このデータ コンテナーに適用されるクエリ。</span><span class="sxs-lookup"><span data-stu-id="74f9f-104">A query that is applied to this data container.</span></span>
            <span data-ttu-id="74f9f-105">このパラメーターの意味と構文は、データ ソース固有です。</span><span class="sxs-lookup"><span data-stu-id="74f9f-105">The syntax and meaning of this parameter is datasource-specific.</span></span>
            <span data-ttu-id="74f9f-106">Azure SQL データ ソースによってサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="74f9f-106">Not supported by Azure SQL datasources.</span></span></param>
        <summary>
            <span data-ttu-id="74f9f-107">DataContainer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="74f9f-107">Initializes a new instance of the DataContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataContainer.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Search.Models.DataContainer.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="74f9f-108">取得または設定 (Azure SQL データ ソース) のテーブルまたはビューの名前またはインデックスが作成される (DocumentDB データ ソース) のコレクション。</span><span class="sxs-lookup"><span data-stu-id="74f9f-108">Gets or sets the name of the table or view (for Azure SQL data source) or collection (for DocumentDB data source) that will be indexed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public string Query { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Query" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataContainer.Query" />
      <MemberSignature Language="VB.NET" Value="Public Property Query As String" />
      <MemberSignature Language="F#" Value="member this.Query : string with get, set" Usage="Microsoft.Azure.Search.Models.DataContainer.Query" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="query")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74f9f-109">取得またはこのデータ コンテナーに適用されるクエリを設定します。</span><span class="sxs-lookup"><span data-stu-id="74f9f-109">Gets or sets a query that is applied to this data container.</span></span> <span data-ttu-id="74f9f-110">このパラメーターの意味と構文は、データ ソース固有です。</span><span class="sxs-lookup"><span data-stu-id="74f9f-110">The syntax and meaning of this parameter is datasource-specific.</span></span> <span data-ttu-id="74f9f-111">Azure SQL データ ソースによってサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="74f9f-111">Not supported by Azure SQL datasources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataContainer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataContainer.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="74f9f-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="74f9f-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="74f9f-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="74f9f-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>