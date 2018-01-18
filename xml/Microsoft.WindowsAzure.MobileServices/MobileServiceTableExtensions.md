<Type Name="MobileServiceTableExtensions" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceTableExtensions">
  <TypeSignature Language="C#" Value="public static class MobileServiceTableExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MobileServiceTableExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceTableExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MobileServiceTableExtensions" />
  <TypeSignature Language="F#" Value="type MobileServiceTableExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e7443-101">拡張メソッドを提供します。<see cref="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" /></span><span class="sxs-lookup"><span data-stu-id="e7443-101">Provides extension methods on <see cref="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" /></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; ReadAsync (this Microsoft.WindowsAzure.MobileServices.IMobileServiceTable table, string query, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; ReadAsync(class Microsoft.WindowsAzure.MobileServices.IMobileServiceTable table, string query, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceTableExtensions.ReadAsync(Microsoft.WindowsAzure.MobileServices.IMobileServiceTable,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ReadAsync (table As IMobileServiceTable, query As String, parameters As IDictionary(Of String, String)) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="static member ReadAsync : Microsoft.WindowsAzure.MobileServices.IMobileServiceTable * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceTableExtensions.ReadAsync (table, query, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" RefType="this" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="table">
            <span data-ttu-id="e7443-102">テーブルからの読み取りのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="e7443-102">The instance of table to read from.</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="e7443-103">クエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="e7443-103">A query to execute.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e7443-104">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="e7443-104">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7443-105">テーブルに対するクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="e7443-105">Executes a query against the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e7443-106">クエリの終了時に結果と共に返すタスク。</span><span class="sxs-lookup"><span data-stu-id="e7443-106">A task that will return with results when the query finishes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>