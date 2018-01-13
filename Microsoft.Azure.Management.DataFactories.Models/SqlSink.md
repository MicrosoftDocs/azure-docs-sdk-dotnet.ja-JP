<Type Name="SqlSink" FullName="Microsoft.Azure.Management.DataFactories.Models.SqlSink">
  <TypeSignature Language="C#" Value="public class SqlSink : Microsoft.Azure.Management.DataFactories.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlSink extends Microsoft.Azure.Management.DataFactories.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.SqlSink" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type SqlSink = class&#xA;    inherit CopySink" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.CopySink</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4520b-101">コピー アクティビティ SQL シンクです。</span><span class="sxs-lookup"><span data-stu-id="4520b-101">A copy activity SQL sink.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.SqlSink.#ctor" />
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
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlSink (int writeBatchSize, TimeSpan writeBatchTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 writeBatchSize, valuetype System.TimeSpan writeBatchTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.SqlSink.#ctor(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (writeBatchSize As Integer, writeBatchTimeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.SqlSink : int * TimeSpan -&gt; Microsoft.Azure.Management.DataFactories.Models.SqlSink" Usage="new Microsoft.Azure.Management.DataFactories.Models.SqlSink (writeBatchSize, writeBatchTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="writeBatchSize" Type="System.Int32" />
        <Parameter Name="writeBatchTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="writeBatchSize">To be added.</param>
        <param name="writeBatchTimeout">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SliceIdentifierColumnName">
      <MemberSignature Language="C#" Value="public string SliceIdentifierColumnName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SliceIdentifierColumnName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SqlSink.SliceIdentifierColumnName" />
      <MemberSignature Language="VB.NET" Value="Public Property SliceIdentifierColumnName As String" />
      <MemberSignature Language="F#" Value="member this.SliceIdentifierColumnName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SqlSink.SliceIdentifierColumnName" />
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
            <span data-ttu-id="4520b-102">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4520b-102">Optional.</span></span> <span data-ttu-id="4520b-103">べき等なのでコピーをサポートするために、スライスの識別子情報の保存に使用される SQL 列の名前。</span><span class="sxs-lookup"><span data-stu-id="4520b-103">Name of the SQL column which is used to save slice identifier information, to support idempotent copy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlWriterCleanupScript">
      <MemberSignature Language="C#" Value="public string SqlWriterCleanupScript { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlWriterCleanupScript" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SqlSink.SqlWriterCleanupScript" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlWriterCleanupScript As String" />
      <MemberSignature Language="F#" Value="member this.SqlWriterCleanupScript : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SqlSink.SqlWriterCleanupScript" />
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
            <span data-ttu-id="4520b-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4520b-104">Optional.</span></span> <span data-ttu-id="4520b-105">SQL ライター クリーンアップ スクリプトです。</span><span class="sxs-lookup"><span data-stu-id="4520b-105">SQL writer cleanup script.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlWriterStoredProcedureName">
      <MemberSignature Language="C#" Value="public string SqlWriterStoredProcedureName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlWriterStoredProcedureName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SqlSink.SqlWriterStoredProcedureName" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlWriterStoredProcedureName As String" />
      <MemberSignature Language="F#" Value="member this.SqlWriterStoredProcedureName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SqlSink.SqlWriterStoredProcedureName" />
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
            <span data-ttu-id="4520b-106">SQL ライター ストアド プロシージャの名前。</span><span class="sxs-lookup"><span data-stu-id="4520b-106">SQL writer stored procedure name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlWriterTableType">
      <MemberSignature Language="C#" Value="public string SqlWriterTableType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlWriterTableType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SqlSink.SqlWriterTableType" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlWriterTableType As String" />
      <MemberSignature Language="F#" Value="member this.SqlWriterTableType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SqlSink.SqlWriterTableType" />
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
            <span data-ttu-id="4520b-107">SQL ライターのテーブル型です。</span><span class="sxs-lookup"><span data-stu-id="4520b-107">SQL writer table type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProcedureParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactories.Models.StoredProcedureParameter&gt; StoredProcedureParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactories.Models.StoredProcedureParameter&gt; StoredProcedureParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SqlSink.StoredProcedureParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property StoredProcedureParameters As IDictionary(Of String, StoredProcedureParameter)" />
      <MemberSignature Language="F#" Value="member this.StoredProcedureParameters : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactories.Models.StoredProcedureParameter&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SqlSink.StoredProcedureParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactories.Models.StoredProcedureParameter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4520b-108">SQL ストアド プロシージャのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4520b-108">SQL stored procedure parameters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>