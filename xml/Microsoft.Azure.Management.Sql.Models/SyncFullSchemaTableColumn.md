<Type Name="SyncFullSchemaTableColumn" FullName="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn">
  <TypeSignature Language="C#" Value="public class SyncFullSchemaTableColumn" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncFullSchemaTableColumn extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncFullSchemaTableColumn" />
  <TypeSignature Language="F#" Value="type SyncFullSchemaTableColumn = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="22848-101">データベースの完全スキーマのテーブル内の列のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="22848-101">Properties of the column in the table of database full schema.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncFullSchemaTableColumn ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="22848-102">SyncFullSchemaTableColumn クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="22848-102">Initializes a new instance of the SyncFullSchemaTableColumn class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncFullSchemaTableColumn (string dataSize = null, string dataType = null, string errorId = null, Nullable&lt;bool&gt; hasError = null, Nullable&lt;bool&gt; isPrimaryKey = null, string name = null, string quotedName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string dataSize, string dataType, string errorId, valuetype System.Nullable`1&lt;bool&gt; hasError, valuetype System.Nullable`1&lt;bool&gt; isPrimaryKey, string name, string quotedName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.#ctor(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dataSize As String = null, Optional dataType As String = null, Optional errorId As String = null, Optional hasError As Nullable(Of Boolean) = null, Optional isPrimaryKey As Nullable(Of Boolean) = null, Optional name As String = null, Optional quotedName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn : string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn" Usage="new Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn (dataSize, dataType, errorId, hasError, isPrimaryKey, name, quotedName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataSize" Type="System.String" />
        <Parameter Name="dataType" Type="System.String" />
        <Parameter Name="errorId" Type="System.String" />
        <Parameter Name="hasError" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isPrimaryKey" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="quotedName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dataSize"><span data-ttu-id="22848-103">列のデータのサイズ。</span><span class="sxs-lookup"><span data-stu-id="22848-103">Data size of the column.</span></span></param>
        <param name="dataType"><span data-ttu-id="22848-104">列のデータ型です。</span><span class="sxs-lookup"><span data-stu-id="22848-104">Data type of the column.</span></span></param>
        <param name="errorId"><span data-ttu-id="22848-105">エラー列の id。</span><span class="sxs-lookup"><span data-stu-id="22848-105">Error id of the column.</span></span></param>
        <param name="hasError"><span data-ttu-id="22848-106">テーブルにエラーがある場合は。</span><span class="sxs-lookup"><span data-stu-id="22848-106">If there is error in the table.</span></span></param>
        <param name="isPrimaryKey"><span data-ttu-id="22848-107">テーブルの主キーの場合。</span><span class="sxs-lookup"><span data-stu-id="22848-107">If it is the primary key of the table.</span></span></param>
        <param name="name"><span data-ttu-id="22848-108">列の名前です。</span><span class="sxs-lookup"><span data-stu-id="22848-108">Name of the column.</span></span></param>
        <param name="quotedName"><span data-ttu-id="22848-109">列の名前を引用符で囲まれました。</span><span class="sxs-lookup"><span data-stu-id="22848-109">Quoted name of the column.</span></span></param>
        <summary>
            <span data-ttu-id="22848-110">SyncFullSchemaTableColumn クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="22848-110">Initializes a new instance of the SyncFullSchemaTableColumn class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSize">
      <MemberSignature Language="C#" Value="public string DataSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.DataSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataSize As String" />
      <MemberSignature Language="F#" Value="member this.DataSize : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.DataSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22848-111">列のデータ サイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="22848-111">Gets data size of the column.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataType">
      <MemberSignature Language="C#" Value="public string DataType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.DataType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataType As String" />
      <MemberSignature Language="F#" Value="member this.DataType : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.DataType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22848-112">列のデータ型を取得します。</span><span class="sxs-lookup"><span data-stu-id="22848-112">Gets data type of the column.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorId">
      <MemberSignature Language="C#" Value="public string ErrorId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.ErrorId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorId As String" />
      <MemberSignature Language="F#" Value="member this.ErrorId : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.ErrorId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22848-113">列のエラーの id を取得します。</span><span class="sxs-lookup"><span data-stu-id="22848-113">Gets error id of the column.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasError">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HasError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HasError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.HasError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasError As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HasError : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.HasError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hasError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22848-114">テーブルにエラーがある場合を取得します。</span><span class="sxs-lookup"><span data-stu-id="22848-114">Gets if there is error in the table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPrimaryKey">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsPrimaryKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsPrimaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.IsPrimaryKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPrimaryKey As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsPrimaryKey : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.IsPrimaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isPrimaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22848-115">場合は、テーブルの主キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="22848-115">Gets if it is the primary key of the table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
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
            <span data-ttu-id="22848-116">列の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="22848-116">Gets name of the column.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QuotedName">
      <MemberSignature Language="C#" Value="public string QuotedName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QuotedName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.QuotedName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QuotedName As String" />
      <MemberSignature Language="F#" Value="member this.QuotedName : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.QuotedName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="quotedName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22848-117">取得するには、列の名前を引用符で囲まれています。</span><span class="sxs-lookup"><span data-stu-id="22848-117">Gets quoted name of the column.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>