<Type Name="TextFormat" FullName="Microsoft.Azure.Management.DataFactories.Models.TextFormat">
  <TypeSignature Language="C#" Value="public class TextFormat : Microsoft.Azure.Management.DataFactories.Models.StorageFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TextFormat extends Microsoft.Azure.Management.DataFactories.Models.StorageFormat" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.TextFormat" />
  <TypeSignature Language="VB.NET" Value="Public Class TextFormat&#xA;Inherits StorageFormat" />
  <TypeSignature Language="F#" Value="type TextFormat = class&#xA;    inherit StorageFormat" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.StorageFormat</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f1820-101">テキスト形式です。</span><span class="sxs-lookup"><span data-stu-id="f1820-101">Text format.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TextFormat ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.TextFormat.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ColumnDelimiter">
      <MemberSignature Language="C#" Value="public string ColumnDelimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ColumnDelimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.TextFormat.ColumnDelimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property ColumnDelimiter As String" />
      <MemberSignature Language="F#" Value="member this.ColumnDelimiter : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.TextFormat.ColumnDelimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f1820-102">列の区切り記号。</span><span class="sxs-lookup"><span data-stu-id="f1820-102">The column delimiter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncodingName">
      <MemberSignature Language="C#" Value="public string EncodingName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncodingName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.TextFormat.EncodingName" />
      <MemberSignature Language="VB.NET" Value="Public Property EncodingName As String" />
      <MemberSignature Language="F#" Value="member this.EncodingName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.TextFormat.EncodingName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f1820-103">使用するエンコーディングのコード ページ名。</span><span class="sxs-lookup"><span data-stu-id="f1820-103">The code page name of the preferred encoding.</span></span> <span data-ttu-id="f1820-104">かどうかミス、既定値は"utf-8"限り BOM は、Unicode、別のエンコードを表します。</span><span class="sxs-lookup"><span data-stu-id="f1820-104">If miss, the default value is “utf-8”, unless BOM denotes another Unicode encoding.</span></span> <span data-ttu-id="f1820-105">サポートされている値を設定する次のリンクの表の"Name"列を参照してください: https://msdn.microsoft.com/library/system.text.encoding.aspx です。</span><span class="sxs-lookup"><span data-stu-id="f1820-105">Refer to the “Name” column of the table in the following link to set supported values: https://msdn.microsoft.com/library/system.text.encoding.aspx.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EscapeChar">
      <MemberSignature Language="C#" Value="public string EscapeChar { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EscapeChar" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.TextFormat.EscapeChar" />
      <MemberSignature Language="VB.NET" Value="Public Property EscapeChar As String" />
      <MemberSignature Language="F#" Value="member this.EscapeChar : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.TextFormat.EscapeChar" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f1820-106">エスケープ文字。</span><span class="sxs-lookup"><span data-stu-id="f1820-106">The escape character.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirstRowAsHeader">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; FirstRowAsHeader { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; FirstRowAsHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.TextFormat.FirstRowAsHeader" />
      <MemberSignature Language="VB.NET" Value="Public Property FirstRowAsHeader As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.FirstRowAsHeader : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.TextFormat.FirstRowAsHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f1820-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f1820-107">Optional.</span></span> <span data-ttu-id="f1820-108">このオブジェクトの書式設定を定義しているデータセットは入力として使用する場合は、データの最初の行として出力にヘッダーを書き込む出力として使用されているときに、データの最初の行をヘッダーとして扱うです。</span><span class="sxs-lookup"><span data-stu-id="f1820-108">When the dataset that this format object is defining is used as input, treat the first row of data as headers, when it's used as output, write the headers into the output as the first row of data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NullValue">
      <MemberSignature Language="C#" Value="public string NullValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NullValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.TextFormat.NullValue" />
      <MemberSignature Language="VB.NET" Value="Public Property NullValue As String" />
      <MemberSignature Language="F#" Value="member this.NullValue : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.TextFormat.NullValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f1820-109">Null 値の文字列。</span><span class="sxs-lookup"><span data-stu-id="f1820-109">The null value string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QuoteChar">
      <MemberSignature Language="C#" Value="public string QuoteChar { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QuoteChar" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.TextFormat.QuoteChar" />
      <MemberSignature Language="VB.NET" Value="Public Property QuoteChar As String" />
      <MemberSignature Language="F#" Value="member this.QuoteChar : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.TextFormat.QuoteChar" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f1820-110">引用符文字。</span><span class="sxs-lookup"><span data-stu-id="f1820-110">The quote character.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowDelimiter">
      <MemberSignature Language="C#" Value="public string RowDelimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowDelimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.TextFormat.RowDelimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property RowDelimiter As String" />
      <MemberSignature Language="F#" Value="member this.RowDelimiter : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.TextFormat.RowDelimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f1820-111">行区切り記号。</span><span class="sxs-lookup"><span data-stu-id="f1820-111">The row delimeter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkipLineCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SkipLineCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SkipLineCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.TextFormat.SkipLineCount" />
      <MemberSignature Language="VB.NET" Value="Public Property SkipLineCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SkipLineCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.TextFormat.SkipLineCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f1820-112">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f1820-112">Optional.</span></span> <span data-ttu-id="f1820-113">テキスト ファイルの解析中にスキップするには、行/行の数。</span><span class="sxs-lookup"><span data-stu-id="f1820-113">The count of lines/rows to be skipped when parsing text files.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TreatEmptyAsNull">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; TreatEmptyAsNull { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; TreatEmptyAsNull" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.TextFormat.TreatEmptyAsNull" />
      <MemberSignature Language="VB.NET" Value="Public Property TreatEmptyAsNull As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.TreatEmptyAsNull : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.TextFormat.TreatEmptyAsNull" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f1820-114">省略可能。</span><span class="sxs-lookup"><span data-stu-id="f1820-114">Optional.</span></span> <span data-ttu-id="f1820-115">テキスト ファイル内の空の列の値を null として扱います。</span><span class="sxs-lookup"><span data-stu-id="f1820-115">Treat empty column values in the text files as null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>