<Type Name="IMobileServiceLocalStore" FullName="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore">
  <TypeSignature Language="C#" Value="public interface IMobileServiceLocalStore : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceLocalStore implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceLocalStore&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IMobileServiceLocalStore = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            ローカル テーブル内のデータの保存および読み取りを許可します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.DeleteAsync(Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (query As MobileServiceTableQueryDescription) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceLocalStore.DeleteAsync query" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" />
      </Parameters>
      <Docs>
        <param name="query">インスタンス<see cref="T:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" /></param>
        <summary>
            クエリに一致するローカル テーブルからすべての項目を削除します。
            </summary>
        <returns>ローカル テーブルの削除が実行されたときに完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (string tableName, System.Collections.Generic.IEnumerable&lt;string&gt; ids);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(string tableName, class System.Collections.Generic.IEnumerable`1&lt;string&gt; ids) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.DeleteAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (tableName As String, ids As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceLocalStore.DeleteAsync (tableName, ids)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="ids" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="tableName">ローカル テーブルの名前です。</param>
        <param name="ids">削除する項目の id の一覧</param>
        <summary>
            指定した id のリストを持つローカル テーブルから項目を削除します。
            </summary>
        <returns>ときに完了するタスクを削除クエリが実行されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InitializeAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task InitializeAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.InitializeAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function InitializeAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member InitializeAsync : unit -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceLocalStore.InitializeAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            使用するストアを初期化します。
            </summary>
        <returns>ストアが初期化したときに完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt; LookupAsync (string tableName, string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JObject&gt; LookupAsync(string tableName, string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.LookupAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (tableName As String, id As String) As Task(Of JObject)" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt;" Usage="iMobileServiceLocalStore.LookupAsync (tableName, id)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName">ローカル テーブルの名前です。</param>
        <param name="id">読み取るオブジェクトの id。</param>
        <summary>
            指定した id を持つローカル テーブルから 1 つの項目を読み取ります。
            </summary>
        <returns>ローカル テーブルから読み取り、項目を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; ReadAsync (Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; ReadAsync(class Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.ReadAsync(Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync (query As MobileServiceTableQueryDescription) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceLocalStore.ReadAsync query" />
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
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" />
      </Parameters>
      <Docs>
        <param name="query">インスタンス<see cref="T:Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription" />ローカル テーブルで実行するクエリを定義します。</param>
        <summary>
            クエリを実行して、ローカル テーブルからデータを読み取ります。
            </summary>
        <returns>インスタンスを返す JObject または JArray、クエリに一致する項目を含むタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpsertAsync (string tableName, System.Collections.Generic.IEnumerable&lt;Newtonsoft.Json.Linq.JObject&gt; items, bool ignoreMissingColumns);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpsertAsync(string tableName, class System.Collections.Generic.IEnumerable`1&lt;class Newtonsoft.Json.Linq.JObject&gt; items, bool ignoreMissingColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.UpsertAsync(System.String,System.Collections.Generic.IEnumerable{Newtonsoft.Json.Linq.JObject},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpsertAsync (tableName As String, items As IEnumerable(Of JObject), ignoreMissingColumns As Boolean) As Task" />
      <MemberSignature Language="F#" Value="abstract member UpsertAsync : string * seq&lt;Newtonsoft.Json.Linq.JObject&gt; * bool -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceLocalStore.UpsertAsync (tableName, items, ignoreMissingColumns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="items" Type="System.Collections.Generic.IEnumerable&lt;Newtonsoft.Json.Linq.JObject&gt;" />
        <Parameter Name="ignoreMissingColumns" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="tableName">ローカル テーブルの名前です。</param>
        <param name="items">挿入する項目の一覧。</param>
        <param name="ignoreMissingColumns">
          <code>true</code>項目の追加プロパティが無視される場合<code>false</code>それ以外の場合。</param>
        <summary>
            ローカル テーブルにデータを挿入または更新されます。
            </summary>
        <returns>項目が完了したときに、タスクは、ローカル テーブル upserted されています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>