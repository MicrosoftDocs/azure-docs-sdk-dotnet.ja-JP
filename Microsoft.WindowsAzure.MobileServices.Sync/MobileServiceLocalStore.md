<Type Name="MobileServiceLocalStore" FullName="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore">
  <TypeSignature Language="C#" Value="public abstract class MobileServiceLocalStore : IDisposable, Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MobileServiceLocalStore extends System.Object implements class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MobileServiceLocalStore&#xA;Implements IDisposable, IMobileServiceLocalStore" />
  <TypeSignature Language="F#" Value="type MobileServiceLocalStore = class&#xA;    interface IMobileServiceLocalStore&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            基本の実装<see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MobileServiceLocalStore ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefineTable">
      <MemberSignature Language="C#" Value="public virtual void DefineTable (string tableName, Newtonsoft.Json.Linq.JObject item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DefineTable(string tableName, class Newtonsoft.Json.Linq.JObject item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.DefineTable(System.String,Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub DefineTable (tableName As String, item As JObject)" />
      <MemberSignature Language="F#" Value="abstract member DefineTable : string * Newtonsoft.Json.Linq.JObject -&gt; unit&#xA;override this.DefineTable : string * Newtonsoft.Json.Linq.JObject -&gt; unit" Usage="mobileServiceLocalStore.DefineTable (tableName, item)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="item" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="tableName">ローカル テーブルの名前です。</param>
        <param name="item">テーブルの構造を表すオブジェクト。</param>
        <summary>
            ストアで、ローカル テーブルを定義します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.DeleteAsync(Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function DeleteAsync (query As MobileServiceTableQueryDescription) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription -&gt; System.Threading.Tasks.Task" Usage="mobileServiceLocalStore.DeleteAsync query" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.DeleteAsync(Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription)</InterfaceMember>
      </Implements>
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
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task DeleteAsync (string tableName, System.Collections.Generic.IEnumerable&lt;string&gt; ids);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(string tableName, class System.Collections.Generic.IEnumerable`1&lt;string&gt; ids) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.DeleteAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function DeleteAsync (tableName As String, ids As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="mobileServiceLocalStore.DeleteAsync (tableName, ids)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.DeleteAsync(System.String,System.Collections.Generic.IEnumerable{System.String})</InterfaceMember>
      </Implements>
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
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="mobileServiceLocalStore.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            インスタンスを破棄します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="mobileServiceLocalStore.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing"></param>
        <summary>
            リソースをクリーンアップするために実行
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnsureInitialized">
      <MemberSignature Language="C#" Value="protected void EnsureInitialized ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void EnsureInitialized() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.EnsureInitialized" />
      <MemberSignature Language="VB.NET" Value="Protected Sub EnsureInitialized ()" />
      <MemberSignature Language="F#" Value="member this.EnsureInitialized : unit -&gt; unit" Usage="mobileServiceLocalStore.EnsureInitialized " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ストアが初期化されていない場合は、例外をスローします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task InitializeAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task InitializeAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.InitializeAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function InitializeAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member InitializeAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.InitializeAsync : unit -&gt; System.Threading.Tasks.Task" Usage="mobileServiceLocalStore.InitializeAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.InitializeAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore/&lt;InitializeAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
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
    <Member MemberName="Initialized">
      <MemberSignature Language="C#" Value="protected bool Initialized { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Initialized" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.Initialized" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property Initialized As Boolean" />
      <MemberSignature Language="F#" Value="member this.Initialized : bool" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.Initialized" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストアが初期化されているかどうかを示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt; LookupAsync (string tableName, string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JObject&gt; LookupAsync(string tableName, string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.LookupAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function LookupAsync (tableName As String, id As String) As Task(Of JObject)" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt;" Usage="mobileServiceLocalStore.LookupAsync (tableName, id)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.LookupAsync(System.String,System.String)</InterfaceMember>
      </Implements>
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
    <Member MemberName="OnInitialize">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnInitialize ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnInitialize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.OnInitialize" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnInitialize () As Task" />
      <MemberSignature Language="F#" Value="abstract member OnInitialize : unit -&gt; System.Threading.Tasks.Task&#xA;override this.OnInitialize : unit -&gt; System.Threading.Tasks.Task" Usage="mobileServiceLocalStore.OnInitialize " />
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
            Initilize はストアのインスタンスで呼び出されるときに実行します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; ReadAsync (Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; ReadAsync(class Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.ReadAsync(Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ReadAsync (query As MobileServiceTableQueryDescription) As Task(Of JToken)" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="mobileServiceLocalStore.ReadAsync query" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.ReadAsync(Microsoft.WindowsAzure.MobileServices.Query.MobileServiceTableQueryDescription)</InterfaceMember>
      </Implements>
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
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task UpsertAsync (string tableName, System.Collections.Generic.IEnumerable&lt;Newtonsoft.Json.Linq.JObject&gt; items, bool ignoreMissingColumns);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpsertAsync(string tableName, class System.Collections.Generic.IEnumerable`1&lt;class Newtonsoft.Json.Linq.JObject&gt; items, bool ignoreMissingColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceLocalStore.UpsertAsync(System.String,System.Collections.Generic.IEnumerable{Newtonsoft.Json.Linq.JObject},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpsertAsync (tableName As String, items As IEnumerable(Of JObject), ignoreMissingColumns As Boolean) As Task" />
      <MemberSignature Language="F#" Value="abstract member UpsertAsync : string * seq&lt;Newtonsoft.Json.Linq.JObject&gt; * bool -&gt; System.Threading.Tasks.Task" Usage="mobileServiceLocalStore.UpsertAsync (tableName, items, ignoreMissingColumns)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore.UpsertAsync(System.String,System.Collections.Generic.IEnumerable{Newtonsoft.Json.Linq.JObject},System.Boolean)</InterfaceMember>
      </Implements>
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