<Type Name="SyncFullSchemaTable" FullName="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable">
  <TypeSignature Language="C#" Value="public class SyncFullSchemaTable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncFullSchemaTable extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncFullSchemaTable" />
  <TypeSignature Language="F#" Value="type SyncFullSchemaTable = class" />
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
            <span data-ttu-id="733fc-101">データベースの完全スキーマ内のテーブルのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="733fc-101">Properties of the table in the database full schema.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncFullSchemaTable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="733fc-102">SyncFullSchemaTable クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="733fc-102">Initializes a new instance of the SyncFullSchemaTable class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncFullSchemaTable (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn&gt; columns = null, string errorId = null, Nullable&lt;bool&gt; hasError = null, string name = null, string quotedName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn&gt; columns, string errorId, valuetype System.Nullable`1&lt;bool&gt; hasError, string name, string quotedName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn},System.String,System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional columns As IList(Of SyncFullSchemaTableColumn) = null, Optional errorId As String = null, Optional hasError As Nullable(Of Boolean) = null, Optional name As String = null, Optional quotedName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn&gt; * string * Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable" Usage="new Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable (columns, errorId, hasError, name, quotedName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="columns" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn&gt;" />
        <Parameter Name="errorId" Type="System.String" />
        <Parameter Name="hasError" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="quotedName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="columns"><span data-ttu-id="733fc-103">データベースの完全スキーマのテーブル内の列の一覧です。</span><span class="sxs-lookup"><span data-stu-id="733fc-103">List of columns in the table of database full schema.</span></span></param>
        <param name="errorId"><span data-ttu-id="733fc-104">テーブルのエラーの id。</span><span class="sxs-lookup"><span data-stu-id="733fc-104">Error id of the table.</span></span></param>
        <param name="hasError"><span data-ttu-id="733fc-105">テーブルにエラーがある場合は。</span><span class="sxs-lookup"><span data-stu-id="733fc-105">If there is error in the table.</span></span></param>
        <param name="name"><span data-ttu-id="733fc-106">テーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="733fc-106">Name of the table.</span></span></param>
        <param name="quotedName"><span data-ttu-id="733fc-107">テーブルの名前を引用符で囲まれました。</span><span class="sxs-lookup"><span data-stu-id="733fc-107">Quoted name of the table.</span></span></param>
        <summary>
            <span data-ttu-id="733fc-108">SyncFullSchemaTable クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="733fc-108">Initializes a new instance of the SyncFullSchemaTable class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Columns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn&gt; Columns { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn&gt; Columns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.Columns" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Columns As IList(Of SyncFullSchemaTableColumn)" />
      <MemberSignature Language="F#" Value="member this.Columns : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.Columns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="columns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="733fc-109">データベースの完全スキーマのテーブルで列の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="733fc-109">Gets list of columns in the table of database full schema.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorId">
      <MemberSignature Language="C#" Value="public string ErrorId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.ErrorId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorId As String" />
      <MemberSignature Language="F#" Value="member this.ErrorId : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.ErrorId" />
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
            <span data-ttu-id="733fc-110">テーブルのエラーの id を取得します。</span><span class="sxs-lookup"><span data-stu-id="733fc-110">Gets error id of the table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasError">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HasError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HasError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.HasError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasError As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HasError : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.HasError" />
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
            <span data-ttu-id="733fc-111">テーブルにエラーがある場合を取得します。</span><span class="sxs-lookup"><span data-stu-id="733fc-111">Gets if there is error in the table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.Name" />
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
            <span data-ttu-id="733fc-112">テーブルの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="733fc-112">Gets name of the table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QuotedName">
      <MemberSignature Language="C#" Value="public string QuotedName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QuotedName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.QuotedName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QuotedName As String" />
      <MemberSignature Language="F#" Value="member this.QuotedName : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.QuotedName" />
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
            <span data-ttu-id="733fc-113">取得するには、テーブルの名前を引用符で囲まれています。</span><span class="sxs-lookup"><span data-stu-id="733fc-113">Gets quoted name of the table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>