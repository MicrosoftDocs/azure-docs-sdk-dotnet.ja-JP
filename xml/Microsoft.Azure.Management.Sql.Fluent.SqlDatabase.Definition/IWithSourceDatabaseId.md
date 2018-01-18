<Type Name="IWithSourceDatabaseId" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithSourceDatabaseId">
  <TypeSignature Language="C#" Value="public interface IWithSourceDatabaseId" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSourceDatabaseId" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithSourceDatabaseId" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSourceDatabaseId" />
  <TypeSignature Language="F#" Value="type IWithSourceDatabaseId = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cb181-101">データベースのソース データベースの id を設定する SQL データベースの定義。</span><span class="sxs-lookup"><span data-stu-id="cb181-101">The SQL Database definition to set the source database id for database.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSourceDatabase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateMode WithSourceDatabase (Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase sourceDatabase);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateMode WithSourceDatabase(class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase sourceDatabase) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithSourceDatabaseId.WithSourceDatabase(Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSourceDatabase (sourceDatabase As ISqlDatabase) As IWithCreateMode" />
      <MemberSignature Language="F#" Value="abstract member WithSourceDatabase : Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateMode" Usage="iWithSourceDatabaseId.WithSourceDatabase sourceDatabase" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateMode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceDatabase" Type="Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase" />
      </Parameters>
      <Docs>
        <param name="sourceDatabase"><span data-ttu-id="cb181-102">ソース データベースのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="cb181-102">Instance of the source database.</span></span></param>
        <summary>
            <span data-ttu-id="cb181-103">ソース データベースの場合は、SQL データベースのリソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="cb181-103">Sets the resource if of source database for the SQL Database.</span></span>
            <span data-ttu-id="cb181-104">照合順序、エディション、および MaxSizeBytes 必要がありますまま同じ、リンクはアクティブです。</span><span class="sxs-lookup"><span data-stu-id="cb181-104">Collation, Edition, and MaxSizeBytes must remain the same while the link is active.</span></span> <span data-ttu-id="cb181-105">これらのパラメーターに指定した値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="cb181-105">Values specified for these parameters will be ignored.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="cb181-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="cb181-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSourceDatabase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateMode WithSourceDatabase (string sourceDatabaseId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateMode WithSourceDatabase(string sourceDatabaseId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithSourceDatabaseId.WithSourceDatabase(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSourceDatabase (sourceDatabaseId As String) As IWithCreateMode" />
      <MemberSignature Language="F#" Value="abstract member WithSourceDatabase : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateMode" Usage="iWithSourceDatabaseId.WithSourceDatabase sourceDatabaseId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateMode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceDatabaseId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceDatabaseId"><span data-ttu-id="cb181-107">ソース データベースの id。</span><span class="sxs-lookup"><span data-stu-id="cb181-107">Id of the source database.</span></span></param>
        <summary>
            <span data-ttu-id="cb181-108">ソース データベースの場合は、SQL データベースのリソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="cb181-108">Sets the resource if of source database for the SQL Database.</span></span>
            <span data-ttu-id="cb181-109">照合順序、エディション、および MaxSizeBytes 必要がありますまま同じ、リンクはアクティブです。</span><span class="sxs-lookup"><span data-stu-id="cb181-109">Collation, Edition, and MaxSizeBytes must remain the same while the link is active.</span></span> <span data-ttu-id="cb181-110">これらのパラメーターに指定した値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="cb181-110">Values specified for these parameters will be ignored.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="cb181-111">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="cb181-111">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>