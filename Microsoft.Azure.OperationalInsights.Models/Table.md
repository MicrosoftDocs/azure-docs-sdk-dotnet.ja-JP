<Type Name="Table" FullName="Microsoft.Azure.OperationalInsights.Models.Table">
  <TypeSignature Language="C#" Value="public class Table" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Table extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.OperationalInsights.Models.Table" />
  <TypeSignature Language="VB.NET" Value="Public Class Table" />
  <TypeSignature Language="F#" Value="type Table = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>0.9.0.1</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7fbc2-101">クエリ応答テーブルです。</span><span class="sxs-lookup"><span data-stu-id="7fbc2-101">A query response table.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="7fbc2-102">クエリの応答に 1 つのテーブルの行と列が含まれています。</span><span class="sxs-lookup"><span data-stu-id="7fbc2-102">Contains the columns and rows for one table in a query response.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Table ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.Models.Table.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7fbc2-103">テーブル クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7fbc2-103">Initializes a new instance of the Table class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Table (string name, System.Collections.Generic.IList&lt;Microsoft.Azure.OperationalInsights.Models.Column&gt; columns, System.Collections.Generic.IList&lt;System.Collections.Generic.IList&lt;string&gt;&gt; rows);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.OperationalInsights.Models.Column&gt; columns, class System.Collections.Generic.IList`1&lt;class System.Collections.Generic.IList`1&lt;string&gt;&gt; rows) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.Models.Table.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.OperationalInsights.Models.Column},System.Collections.Generic.IList{System.Collections.Generic.IList{System.String}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, columns As IList(Of Column), rows As IList(Of IList(Of String)))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.Models.Table : string * System.Collections.Generic.IList&lt;Microsoft.Azure.OperationalInsights.Models.Column&gt; * System.Collections.Generic.IList&lt;System.Collections.Generic.IList&lt;string&gt;&gt; -&gt; Microsoft.Azure.OperationalInsights.Models.Table" Usage="new Microsoft.Azure.OperationalInsights.Models.Table (name, columns, rows)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="columns" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.OperationalInsights.Models.Column&gt;" />
        <Parameter Name="rows" Type="System.Collections.Generic.IList&lt;System.Collections.Generic.IList&lt;System.String&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7fbc2-104">テーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbc2-104">The name of the table.</span></span></param>
        <param name="columns"><span data-ttu-id="7fbc2-105">このテーブルの列の一覧。</span><span class="sxs-lookup"><span data-stu-id="7fbc2-105">The list of columns in this table.</span></span></param>
        <param name="rows"><span data-ttu-id="7fbc2-106">このクエリの結果として得られる行です。</span><span class="sxs-lookup"><span data-stu-id="7fbc2-106">The resulting rows from this query.</span></span></param>
        <summary>
            <span data-ttu-id="7fbc2-107">テーブル クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7fbc2-107">Initializes a new instance of the Table class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Columns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.OperationalInsights.Models.Column&gt; Columns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.OperationalInsights.Models.Column&gt; Columns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.Table.Columns" />
      <MemberSignature Language="VB.NET" Value="Public Property Columns As IList(Of Column)" />
      <MemberSignature Language="F#" Value="member this.Columns : System.Collections.Generic.IList&lt;Microsoft.Azure.OperationalInsights.Models.Column&gt; with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.Table.Columns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="columns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.OperationalInsights.Models.Column&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7fbc2-108">取得またはこのテーブルの列の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="7fbc2-108">Gets or sets the list of columns in this table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.Table.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.Table.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            <span data-ttu-id="7fbc2-109">取得またはテーブルの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="7fbc2-109">Gets or sets the name of the table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rows">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Collections.Generic.IList&lt;string&gt;&gt; Rows { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Collections.Generic.IList`1&lt;string&gt;&gt; Rows" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.Table.Rows" />
      <MemberSignature Language="VB.NET" Value="Public Property Rows As IList(Of IList(Of String))" />
      <MemberSignature Language="F#" Value="member this.Rows : System.Collections.Generic.IList&lt;System.Collections.Generic.IList&lt;string&gt;&gt; with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.Table.Rows" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rows")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Collections.Generic.IList&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7fbc2-110">取得またはこのクエリの結果得られた行を設定します。</span><span class="sxs-lookup"><span data-stu-id="7fbc2-110">Gets or sets the resulting rows from this query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.Models.Table.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="table.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7fbc2-111">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="7fbc2-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7fbc2-112">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7fbc2-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>