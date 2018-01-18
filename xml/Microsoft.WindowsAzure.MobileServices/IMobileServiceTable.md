<Type Name="IMobileServiceTable" FullName="Microsoft.WindowsAzure.MobileServices.IMobileServiceTable">
  <TypeSignature Language="C#" Value="public interface IMobileServiceTable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceTable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceTable" />
  <TypeSignature Language="F#" Value="type IMobileServiceTable = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="99b29-101">Microsoft Azure モバイル サービス用のテーブルに対する操作を提供します。</span><span class="sxs-lookup"><span data-stu-id="99b29-101">Provides operations on a table for a Microsoft Azure Mobile Service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; DeleteAsync (Newtonsoft.Json.Linq.JObject instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; DeleteAsync(class Newtonsoft.Json.Linq.JObject instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.DeleteAsync(Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (instance As JObject) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.DeleteAsync instance" />
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
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="instance">
            <span data-ttu-id="99b29-102">テーブルから削除するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="99b29-102">The instance to delete from the table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b29-103">削除、<paramref name="instance" />テーブルからです。</span><span class="sxs-lookup"><span data-stu-id="99b29-103">Deletes an <paramref name="instance" /> from the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="99b29-104">削除の終了時に完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="99b29-104">A task that will complete when the delete finishes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; DeleteAsync (Newtonsoft.Json.Linq.JObject instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; DeleteAsync(class Newtonsoft.Json.Linq.JObject instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.DeleteAsync(Newtonsoft.Json.Linq.JObject,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (instance As JObject, parameters As IDictionary(Of String, String)) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Newtonsoft.Json.Linq.JObject * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.DeleteAsync (instance, parameters)" />
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
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance">
            <span data-ttu-id="99b29-105">テーブルから削除するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="99b29-105">The instance to delete from the table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="99b29-106">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="99b29-106">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b29-107">削除、<paramref name="instance" />テーブルからです。</span><span class="sxs-lookup"><span data-stu-id="99b29-107">Deletes an <paramref name="instance" /> from the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="99b29-108">削除の終了時に完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="99b29-108">A task that will complete when the delete finishes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; InsertAsync (Newtonsoft.Json.Linq.JObject instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; InsertAsync(class Newtonsoft.Json.Linq.JObject instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.InsertAsync(Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function InsertAsync (instance As JObject) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.InsertAsync instance" />
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
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="instance">
            <span data-ttu-id="99b29-109">テーブルに挿入するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="99b29-109">The instance to insert into the table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b29-110">挿入、<paramref name="instance" />テーブルにします。</span><span class="sxs-lookup"><span data-stu-id="99b29-110">Inserts an <paramref name="instance" /> into the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="99b29-111">挿入の終了時に完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="99b29-111">A task that will complete when the insert finishes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; InsertAsync (Newtonsoft.Json.Linq.JObject instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; InsertAsync(class Newtonsoft.Json.Linq.JObject instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.InsertAsync(Newtonsoft.Json.Linq.JObject,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function InsertAsync (instance As JObject, parameters As IDictionary(Of String, String)) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : Newtonsoft.Json.Linq.JObject * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.InsertAsync (instance, parameters)" />
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
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance">
            <span data-ttu-id="99b29-112">テーブルに挿入するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="99b29-112">The instance to insert into the table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="99b29-113">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="99b29-113">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b29-114">挿入、<paramref name="instance" />テーブルにします。</span><span class="sxs-lookup"><span data-stu-id="99b29-114">Inserts an <paramref name="instance" /> into the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="99b29-115">挿入の終了時に完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="99b29-115">A task that will complete when the insert finishes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; LookupAsync (object id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; LookupAsync(object id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.LookupAsync(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (id As Object) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : obj -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.LookupAsync id" />
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
        <Parameter Name="id" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="id">
            <span data-ttu-id="99b29-116">参照するインスタンスの id。</span><span class="sxs-lookup"><span data-stu-id="99b29-116">The id of the instance to lookup.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b29-117">テーブルに対する参照を実行します。</span><span class="sxs-lookup"><span data-stu-id="99b29-117">Executes a lookup against a table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="99b29-118">参照の終了時に結果と共に返すタスク。</span><span class="sxs-lookup"><span data-stu-id="99b29-118">A task that will return with a result when the lookup finishes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; LookupAsync (object id, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; LookupAsync(object id, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.LookupAsync(System.Object,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (id As Object, parameters As IDictionary(Of String, String)) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : obj * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.LookupAsync (id, parameters)" />
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
        <Parameter Name="id" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id">
            <span data-ttu-id="99b29-119">参照するインスタンスの id。</span><span class="sxs-lookup"><span data-stu-id="99b29-119">The id of the instance to lookup.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="99b29-120">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="99b29-120">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b29-121">テーブルに対する参照を実行します。</span><span class="sxs-lookup"><span data-stu-id="99b29-121">Executes a lookup against a table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="99b29-122">参照の終了時に結果と共に返すタスク。</span><span class="sxs-lookup"><span data-stu-id="99b29-122">A task that will return with a result when the lookup finishes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MobileServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.MobileServiceClient MobileServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.MobileServiceClient MobileServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.MobileServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MobileServiceClient As MobileServiceClient" />
      <MemberSignature Language="F#" Value="member this.MobileServiceClient : Microsoft.WindowsAzure.MobileServices.MobileServiceClient" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.MobileServiceClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.MobileServiceClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99b29-123">参照を取得、<see cref="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.MobileServiceClient" />このテーブルに関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="99b29-123">Gets a reference to the <see cref="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.MobileServiceClient" /> associated with this table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; ReadAsync (string query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; ReadAsync(string query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.ReadAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync (query As String) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : string -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.ReadAsync query" />
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
        <Parameter Name="query" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="query">
            <span data-ttu-id="99b29-124">クエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="99b29-124">A query to execute.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b29-125">テーブルに対するクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="99b29-125">Executes a query against the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="99b29-126">クエリの終了時に結果と共に返すタスク。</span><span class="sxs-lookup"><span data-stu-id="99b29-126">A task that will return with results when the query finishes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; ReadAsync (string query, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, bool wrapResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; ReadAsync(string query, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, bool wrapResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.ReadAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync (query As String, parameters As IDictionary(Of String, String), wrapResult As Boolean) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : string * System.Collections.Generic.IDictionary&lt;string, string&gt; * bool -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.ReadAsync (query, parameters, wrapResult)" />
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
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="wrapResult" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="query">
            <span data-ttu-id="99b29-127">クエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="99b29-127">A query to execute.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="99b29-128">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="99b29-128">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="wrapResult">
            <span data-ttu-id="99b29-129">かどうか応答を書式設定する例: 余分な応答の詳細を含む JObject としてリンク ヘッダーを指定します</span><span class="sxs-lookup"><span data-stu-id="99b29-129">Specifies whether response should be formatted as JObject including extra response details e.g. link header</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b29-130">テーブルに対するクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="99b29-130">Executes a query against the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="99b29-131">クエリの終了時に結果と共に返すタスク。</span><span class="sxs-lookup"><span data-stu-id="99b29-131">A task that will return with results when the query finishes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableName">
      <MemberSignature Language="C#" Value="public string TableName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TableName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.TableName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TableName As String" />
      <MemberSignature Language="F#" Value="member this.TableName : string" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.TableName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99b29-132">テーブルの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="99b29-132">Gets the name of the table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; UndeleteAsync (Newtonsoft.Json.Linq.JObject instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; UndeleteAsync(class Newtonsoft.Json.Linq.JObject instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.UndeleteAsync(Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function UndeleteAsync (instance As JObject) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member UndeleteAsync : Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.UndeleteAsync instance" />
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
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="instance"><span data-ttu-id="99b29-133">テーブルから復元するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="99b29-133">The instance to undelete from the table.</span></span></param>
        <summary>
            <span data-ttu-id="99b29-134">削除を取り消します、<paramref name="instance" />テーブルからです。</span><span class="sxs-lookup"><span data-stu-id="99b29-134">Undeletes an <paramref name="instance" /> from the table.</span></span> <span data-ttu-id="99b29-135">これは、ソフト モバイル サービスで有効にする機能を削除する必要があります。</span><span class="sxs-lookup"><span data-stu-id="99b29-135">This requires the soft delete feature to be enabled on the Mobile Service.</span></span> <span data-ttu-id="99b29-136">参照してください<see href="http://go.microsoft.com/fwlink/?LinkId=507647">リンク</see>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="99b29-136">Visit <see href="http://go.microsoft.com/fwlink/?LinkId=507647">the link</see> for details.</span></span>
            </summary>
        <returns><span data-ttu-id="99b29-137">削除の取り消しが終了するときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="99b29-137">A task that will complete when the undelete finishes.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; UndeleteAsync (Newtonsoft.Json.Linq.JObject instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; UndeleteAsync(class Newtonsoft.Json.Linq.JObject instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.UndeleteAsync(Newtonsoft.Json.Linq.JObject,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function UndeleteAsync (instance As JObject, parameters As IDictionary(Of String, String)) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member UndeleteAsync : Newtonsoft.Json.Linq.JObject * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.UndeleteAsync (instance, parameters)" />
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
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance"><span data-ttu-id="99b29-138">テーブルから復元するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="99b29-138">The instance to undelete from the table.</span></span></param>
        <param name="parameters">
            <span data-ttu-id="99b29-139">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="99b29-139">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b29-140">削除を取り消します、<paramref name="instance" />テーブルからです。</span><span class="sxs-lookup"><span data-stu-id="99b29-140">Undeletes an <paramref name="instance" /> from the table.</span></span> <span data-ttu-id="99b29-141">これは、ソフト モバイル サービスで有効にする機能を削除する必要があります。</span><span class="sxs-lookup"><span data-stu-id="99b29-141">This requires the soft delete feature to be enabled on the Mobile Service.</span></span> <span data-ttu-id="99b29-142">参照してください<see href="http://go.microsoft.com/fwlink/?LinkId=507647">リンク</see>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="99b29-142">Visit <see href="http://go.microsoft.com/fwlink/?LinkId=507647">the link</see> for details.</span></span>
            </summary>
        <returns><span data-ttu-id="99b29-143">削除の取り消しが終了するときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="99b29-143">A task that will complete when the undelete finishes.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; UpdateAsync (Newtonsoft.Json.Linq.JObject instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; UpdateAsync(class Newtonsoft.Json.Linq.JObject instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.UpdateAsync(Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAsync (instance As JObject) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.UpdateAsync instance" />
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
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="instance">
            <span data-ttu-id="99b29-144">テーブルで更新するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="99b29-144">The instance to update in the table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b29-145">更新プログラム、<paramref name="instance" />テーブルにします。</span><span class="sxs-lookup"><span data-stu-id="99b29-145">Updates an <paramref name="instance" /> in the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="99b29-146">更新プログラムが終了するときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="99b29-146">A task that will complete when the update finishes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; UpdateAsync (Newtonsoft.Json.Linq.JObject instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; UpdateAsync(class Newtonsoft.Json.Linq.JObject instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable.UpdateAsync(Newtonsoft.Json.Linq.JObject,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAsync (instance As JObject, parameters As IDictionary(Of String, String)) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : Newtonsoft.Json.Linq.JObject * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceTable.UpdateAsync (instance, parameters)" />
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
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance">
            <span data-ttu-id="99b29-147">テーブルで更新するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="99b29-147">The instance to update in the table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="99b29-148">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="99b29-148">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b29-149">更新プログラム、<paramref name="instance" />テーブルにします。</span><span class="sxs-lookup"><span data-stu-id="99b29-149">Updates an <paramref name="instance" /> in the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="99b29-150">更新プログラムが終了するときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="99b29-150">A task that will complete when the update finishes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>