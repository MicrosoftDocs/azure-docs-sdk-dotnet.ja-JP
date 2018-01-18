<Type Name="SqlSource" FullName="Microsoft.Azure.Management.DataFactories.Models.SqlSource">
  <TypeSignature Language="C#" Value="public class SqlSource : Microsoft.Azure.Management.DataFactories.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlSource extends Microsoft.Azure.Management.DataFactories.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.SqlSource" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type SqlSource = class&#xA;    inherit CopySource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.CopySource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d0344-101">コピー アクティビティ SQL ソース。</span><span class="sxs-lookup"><span data-stu-id="d0344-101">A copy activity SQL source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.SqlSource.#ctor" />
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
    <Member MemberName="SqlReaderQuery">
      <MemberSignature Language="C#" Value="public string SqlReaderQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlReaderQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SqlSource.SqlReaderQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlReaderQuery As String" />
      <MemberSignature Language="F#" Value="member this.SqlReaderQuery : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SqlSource.SqlReaderQuery" />
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
            <span data-ttu-id="d0344-102">リーダーの SQL クエリ。</span><span class="sxs-lookup"><span data-stu-id="d0344-102">SQL reader query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlReaderStoredProcedureName">
      <MemberSignature Language="C#" Value="public string SqlReaderStoredProcedureName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlReaderStoredProcedureName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SqlSource.SqlReaderStoredProcedureName" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlReaderStoredProcedureName As String" />
      <MemberSignature Language="F#" Value="member this.SqlReaderStoredProcedureName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SqlSource.SqlReaderStoredProcedureName" />
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
            <span data-ttu-id="d0344-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d0344-103">Optional.</span></span> <span data-ttu-id="d0344-104">SQL Azure のソースのストアド プロシージャの名前。</span><span class="sxs-lookup"><span data-stu-id="d0344-104">Name of the stored procedure for a SQL Azure source.</span></span> <span data-ttu-id="d0344-105">これは、SqlReaderQuery と同時に使用できません。</span><span class="sxs-lookup"><span data-stu-id="d0344-105">This cannot be used at the same time as SqlReaderQuery.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProcedureParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,System.Collections.Generic.IDictionary&lt;string,string&gt;&gt; StoredProcedureParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class System.Collections.Generic.IDictionary`2&lt;string, string&gt;&gt; StoredProcedureParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SqlSource.StoredProcedureParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property StoredProcedureParameters As IDictionary(Of String, IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="member this.StoredProcedureParameters : System.Collections.Generic.IDictionary&lt;string, System.Collections.Generic.IDictionary&lt;string, string&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SqlSource.StoredProcedureParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d0344-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d0344-106">Optional.</span></span> <span data-ttu-id="d0344-107">値および種類のストアド プロシージャのパラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="d0344-107">Value and type setting for stored procedure parameters.</span></span> <span data-ttu-id="d0344-108">例:"{Parameter1: {値:「1」、種類:"int"}}"。</span><span class="sxs-lookup"><span data-stu-id="d0344-108">Example: "{Parameter1: {value: "1", type: "int"}}".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>