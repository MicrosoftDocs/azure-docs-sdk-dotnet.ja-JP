<Type Name="IMobileServiceSyncTable" FullName="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable">
  <TypeSignature Language="C#" Value="public interface IMobileServiceSyncTable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceSyncTable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceSyncTable" />
  <TypeSignature Language="F#" Value="type IMobileServiceSyncTable = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ローカル テーブルでの操作を提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (Newtonsoft.Json.Linq.JObject instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Newtonsoft.Json.Linq.JObject instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.DeleteAsync(Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (instance As JObject) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.DeleteAsync instance" />
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
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="instance">
            テーブルから削除するインスタンス。
            </param>
        <summary>
            削除、<paramref name="instance" />テーブルからです。
            </summary>
        <returns>
            削除の終了時に完了するタスク。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt; InsertAsync (Newtonsoft.Json.Linq.JObject instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JObject&gt; InsertAsync(class Newtonsoft.Json.Linq.JObject instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.InsertAsync(Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function InsertAsync (instance As JObject) As Task(Of JObject)" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt;" Usage="iMobileServiceSyncTable.InsertAsync instance" />
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
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="instance">
            テーブルに挿入するインスタンス。
            </param>
        <summary>
            挿入、<paramref name="instance" />テーブルにします。
            </summary>
        <returns>
            挿入の終了時に完了するタスク。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt; LookupAsync (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JObject&gt; LookupAsync(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.LookupAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (id As String) As Task(Of JObject)" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : string -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt;" Usage="iMobileServiceSyncTable.LookupAsync id" />
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
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">
            参照するインスタンスの id。
            </param>
        <summary>
            テーブルに対する参照を実行します。
            </summary>
        <returns>
            参照の終了時に結果と共に返すタスク。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MobileServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.MobileServiceClient MobileServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.MobileServiceClient MobileServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.MobileServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MobileServiceClient As MobileServiceClient" />
      <MemberSignature Language="F#" Value="member this.MobileServiceClient : Microsoft.WindowsAzure.MobileServices.MobileServiceClient" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.MobileServiceClient" />
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
            参照を取得、<see cref="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.MobileServiceClient" />このテーブルに関連付けられています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PullAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PullAsync (string queryId, string query, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, bool pushOtherTables, System.Threading.CancellationToken cancellationToken, Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PullAsync(string queryId, string query, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, bool pushOtherTables, valuetype System.Threading.CancellationToken cancellationToken, class Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.PullAsync(System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Boolean,System.Threading.CancellationToken,Microsoft.WindowsAzure.MobileServices.Sync.PullOptions)" />
      <MemberSignature Language="F#" Value="abstract member PullAsync : string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * bool * System.Threading.CancellationToken * Microsoft.WindowsAzure.MobileServices.Sync.PullOptions -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.PullAsync (queryId, query, parameters, pushOtherTables, cancellationToken, pullOptions)" />
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
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="pushOtherTables" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="pullOptions" Type="Microsoft.WindowsAzure.MobileServices.Sync.PullOptions" />
      </Parameters>
      <Docs>
        <param name="queryId">
            一意にこのクエリを識別し、同期状態を追跡するために使用する文字列。 このパラメーターを指定すること、同じキーを再度使用されるたびに増分同期を有効にします。
            </param>
        <param name="query">
            リモート テーブルからプルする項目を決定する OData クエリ。
            </param>
        <param name="parameters">
            ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。
            </param>
        <param name="pushOtherTables">
            このテーブルがダーティの場合は、他のテーブルをプッシュします。
            </param>
        <param name="cancellationToken"><see cref="T:System.Threading.CancellationToken" />観察するトークン
            </param>
        <param name="pullOptions">
            リモート テーブルからデータをプルする方法を決定する PullOptions
            </param>
        <summary>
            関連付けられているリモート テーブルから特定のクエリに一致するすべての項目を取得します。 増分同期をサポートしています。
            </summary>
        <returns>
            完了するタスクをプル操作が完了するとします。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PurgeAsync (string queryId, string query, bool force, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PurgeAsync(string queryId, string query, bool force, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.PurgeAsync(System.String,System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeAsync : string * string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.PurgeAsync (queryId, query, force, cancellationToken)" />
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
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="force" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryId">
            一意にこのクエリを識別し、同期状態を追跡するために使用する文字列。 このパラメーターを指定すると、クエリの差分同期状態がリセットされます。
            </param>
        <param name="query">削除する項目を決定する OData クエリ。</param>
        <param name="force">保留中の操作を破棄することによって、消去を強制します。</param>
        <param name="cancellationToken"><see cref="T:System.Threading.CancellationToken" />観察するトークン
            </param>
        <summary>
            クエリに一致するローカル テーブル内のすべての項目を削除します。
            </summary>
        <returns>ときに完了するタスクをパージ操作が完了します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; ReadAsync (string query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; ReadAsync(string query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.ReadAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync (query As String) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : string -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="iMobileServiceSyncTable.ReadAsync query" />
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
            クエリを実行します。
            </param>
        <summary>
            テーブルに対するクエリを実行します。
            </summary>
        <returns>
            クエリの終了時に結果と共に返すタスク。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedOptions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.MobileServiceRemoteTableOptions SupportedOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.MobileServiceRemoteTableOptions SupportedOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.SupportedOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportedOptions As MobileServiceRemoteTableOptions" />
      <MemberSignature Language="F#" Value="member this.SupportedOptions : Microsoft.WindowsAzure.MobileServices.MobileServiceRemoteTableOptions with get, set" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.SupportedOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.MobileServiceRemoteTableOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            リモート テーブルでサポートされる odata オプション
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableName">
      <MemberSignature Language="C#" Value="public string TableName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TableName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.TableName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TableName As String" />
      <MemberSignature Language="F#" Value="member this.TableName : string" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.TableName" />
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
            テーブルの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateAsync (Newtonsoft.Json.Linq.JObject instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateAsync(class Newtonsoft.Json.Linq.JObject instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable.UpdateAsync(Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAsync (instance As JObject) As Task" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.UpdateAsync instance" />
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
        <Parameter Name="instance" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="instance">
            テーブルで更新するインスタンス。
            </param>
        <summary>
            更新プログラム、<paramref name="instance" />テーブルにします。
            </summary>
        <returns>
            更新プログラムが終了するときに完了するタスク。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>