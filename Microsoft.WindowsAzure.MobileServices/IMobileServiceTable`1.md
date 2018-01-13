<Type Name="IMobileServiceTable&lt;T&gt;" FullName="Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IMobileServiceTable&lt;T&gt; : Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceTable`1&lt;T&gt; implements class Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceTable(Of T)&#xA;Implements IMobileServiceTable" />
  <TypeSignature Language="F#" Value="type IMobileServiceTable&lt;'T&gt; = interface&#xA;    interface IMobileServiceTable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.MobileServices.IMobileServiceTable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">
            (これは、テーブルを意味する) テーブル内のインスタンスの型。
            </typeparam>
    <summary>
            モバイル サービスのテーブルに対する操作を提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; CreateQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; CreateQuery() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.CreateQuery" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQuery () As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.CreateQuery " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在のテーブルに対してクエリを作成します。
            </summary>
        <returns>
            テーブルに対するクエリ。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.DeleteAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.DeleteAsync instance" />
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
        <Parameter Name="instance" Type="T" />
      </Parameters>
      <Docs>
        <param name="instance">
            削除するインスタンス。
            </param>
        <summary>
            テーブルからインスタンスを削除します。
            </summary>
        <returns>
            削除が完了したときに完了するタスク。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (T instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(!T instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.DeleteAsync(`0,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (instance As T, parameters As IDictionary(Of String, String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : 'T * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.DeleteAsync (instance, parameters)" />
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
        <Parameter Name="instance" Type="T" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance">削除するインスタンス。
            </param>
        <param name="parameters">
            ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。
            </param>
        <summary>
            テーブルからインスタンスを削除します。
            </summary>
        <returns>
            削除が完了したときに完了するタスク。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeDeleted">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; IncludeDeleted ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; IncludeDeleted() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.IncludeDeleted" />
      <MemberSignature Language="VB.NET" Value="Public Function IncludeDeleted () As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member IncludeDeleted : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.IncludeDeleted " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            削除されたレコードを取得するクエリを作成します。 これは、ソフト モバイル サービスで有効にする機能を削除する必要があります。 参照してください<see href="http://go.microsoft.com/fwlink/?LinkId=507647">リンク</see>詳細についてはします。
            </summary>
        <returns>
            テーブルに対するクエリ。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeTotalCount">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; IncludeTotalCount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; IncludeTotalCount() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.IncludeTotalCount" />
      <MemberSignature Language="VB.NET" Value="Public Function IncludeTotalCount () As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member IncludeTotalCount : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.IncludeTotalCount " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            無視して返されたすべてのレコードがページングを実行/クライアントまたはサーバーで指定された句を制限の合計数を取得するクエリを作成します。
            </summary>
        <returns>
            テーブルに対するクエリ。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InsertAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task InsertAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.InsertAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function InsertAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.InsertAsync instance" />
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
        <Parameter Name="instance" Type="T" />
      </Parameters>
      <Docs>
        <param name="instance">
            挿入するインスタンス。
            </param>
        <summary>
            新しいインスタンスをテーブルに挿入します。
            </summary>
        <returns>
            挿入が完了したときに完了するタスク。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InsertAsync (T instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task InsertAsync(!T instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.InsertAsync(`0,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function InsertAsync (instance As T, parameters As IDictionary(Of String, String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : 'T * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.InsertAsync (instance, parameters)" />
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
        <Parameter Name="instance" Type="T" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance">
            挿入するインスタンス。
            </param>
        <param name="parameters">
            ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。
            </param>
        <summary>
            新しいインスタンスをテーブルに挿入します。
            </summary>
        <returns>
            挿入が完了したときに完了するタスク。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; LookupAsync (object id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; LookupAsync(object id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.LookupAsync(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (id As Object) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : obj -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iMobileServiceTable.LookupAsync id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="id">
            インスタンスの id。
            </param>
        <summary>
            参照 id によってテーブルからインスタンスです。
            </summary>
        <returns>
            目的のインスタンス。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; LookupAsync (object id, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; LookupAsync(object id, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.LookupAsync(System.Object,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (id As Object, parameters As IDictionary(Of String, String)) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : obj * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iMobileServiceTable.LookupAsync (id, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id">
            インスタンスの id。
            </param>
        <param name="parameters">
            ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。
            </param>
        <summary>
            参照 id によってテーブルからインスタンスです。
            </summary>
        <returns>
            目的のインスタンス。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderBy&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; OrderBy&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; OrderBy&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.OrderBy``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function OrderBy(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member OrderBy : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.OrderBy keySelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="keySelector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,TKey&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">
            並べ替え対象のメンバーの型。
            </typeparam>
        <param name="keySelector">
            並べ替えるメンバーを選択する式。
            </param>
        <summary>
            指定した ascending order 句を適用することにより、クエリを作成します。
            </summary>
        <returns>
            テーブルに対するクエリ。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderByDescending&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; OrderByDescending&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; OrderByDescending&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.OrderByDescending``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function OrderByDescending(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member OrderByDescending : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.OrderByDescending keySelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="keySelector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,TKey&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">
            並べ替え対象のメンバーの型。
            </typeparam>
        <param name="keySelector">
            並べ替えるメンバーを選択する式。
            </param>
        <summary>
            指定した descending order 句を適用することにより、クエリを作成します。
            </summary>
        <returns>
            テーブルに対するクエリ。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt; ReadAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!T&gt;&gt; ReadAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.ReadAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync () As Task(Of IEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;'T&gt;&gt;" Usage="iMobileServiceTable.ReadAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            テーブルからインスタンスを返します。
            </summary>
        <returns>
            テーブルからのインスタンス。
            </returns>
        <remarks>
            この呼び出しがページングなどを処理しません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync&lt;U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;U&gt;&gt; ReadAsync&lt;U&gt; (Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!!U&gt;&gt; ReadAsync&lt;U&gt;(class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.ReadAsync``1(Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync(Of U) (query As IMobileServiceTableQuery(Of U)) As Task(Of IEnumerable(Of U))" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;'U&gt;&gt;" Usage="iMobileServiceTable.ReadAsync query" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;U&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="U">
            クエリによって返されるインスタンスの型。
            </typeparam>
        <param name="query">
            クエリを実行します。
            </param>
        <summary>
            クエリを使用してテーブルからインスタンスを返します。
            </summary>
        <returns>
            テーブルからのインスタンス。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync&lt;U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;U&gt;&gt; ReadAsync&lt;U&gt; (string query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!!U&gt;&gt; ReadAsync&lt;U&gt;(string query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.ReadAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync(Of U) (query As String) As Task(Of IEnumerable(Of U))" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;'U&gt;&gt;" Usage="iMobileServiceTable.ReadAsync query" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;U&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="U">To be added.</typeparam>
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
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.RefreshAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function RefreshAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.RefreshAsync instance" />
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
        <Parameter Name="instance" Type="T" />
      </Parameters>
      <Docs>
        <param name="instance">
            更新するインスタンス。
            </param>
        <summary>
            現在のインスタンスと、テーブルからの最新の値を更新します。
            </summary>
        <returns>
            更新が完了したときに完了するタスク。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (T instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(!T instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.RefreshAsync(`0,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function RefreshAsync (instance As T, parameters As IDictionary(Of String, String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : 'T * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.RefreshAsync (instance, parameters)" />
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
        <Parameter Name="instance" Type="T" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance">
            更新するインスタンス。
            </param>
        <param name="parameters">
            ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。
            </param>
        <summary>
            現在のインスタンスと、テーブルからの最新の値を更新します。
            </summary>
        <returns>
            更新が完了したときに完了するタスク。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select&lt;U&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; Select&lt;U&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,U&gt;&gt; selector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; Select&lt;U&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!U&gt;&gt; selector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.Select``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function Select(Of U) (selector As Expression(Of Func(Of T, U))) As IMobileServiceTableQuery(Of U)" />
      <MemberSignature Language="F#" Value="abstract member Select : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'U&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt;" Usage="iMobileServiceTable.Select selector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="selector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,U&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="U">
            クエリの射影された結果を表す型。
            </typeparam>
        <param name="selector">
            selector 関数。
            </param>
        <summary>
            指定した選択を適用することにより、クエリを作成します。
            </summary>
        <returns>
            テーブルに対するクエリ。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Skip">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Skip (int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Skip(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.Skip(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Skip (count As Integer) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Skip : int -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.Skip count" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="count">
            skip の数値。
            </param>
        <summary>
            指定した skip 句を適用することにより、クエリを作成します。
            </summary>
        <returns>
            テーブルに対するクエリ。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Take">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Take (int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Take(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.Take(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Take (count As Integer) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Take : int -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.Take count" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="count">
            take の数値。
            </param>
        <summary>
            指定した take 句を適用することにより、クエリを作成します。
            </summary>
        <returns>
            テーブルに対するクエリ。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThenBy&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; ThenBy&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; ThenBy&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.ThenBy``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function ThenBy(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ThenBy : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.ThenBy keySelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="keySelector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,TKey&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">
            並べ替え対象のメンバーの型。
            </typeparam>
        <param name="keySelector">
            並べ替えるメンバーを選択する式。
            </param>
        <summary>
            指定した ascending order 句を適用することにより、クエリを作成します。
            </summary>
        <returns>
            テーブルに対するクエリ。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThenByDescending&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; ThenByDescending&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; ThenByDescending&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.ThenByDescending``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function ThenByDescending(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ThenByDescending : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.ThenByDescending keySelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="keySelector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,TKey&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">
            並べ替え対象のメンバーの型。
            </typeparam>
        <param name="keySelector">
            並べ替えるメンバーを選択する式。
            </param>
        <summary>
            指定した descending order 句を適用することにより、クエリを作成します。
            </summary>
        <returns>
            テーブルに対するクエリ。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt; ToEnumerableAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!T&gt;&gt; ToEnumerableAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.ToEnumerableAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ToEnumerableAsync () As Task(Of IEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ToEnumerableAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;'T&gt;&gt;" Usage="iMobileServiceTable.ToEnumerableAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            テーブルの要素を非同期に取得します。
            </summary>
        <returns>
            テーブル要素のシーケンスとして結果。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;T&gt;&gt; ToListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.List`1&lt;!T&gt;&gt; ToListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.ToListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ToListAsync () As Task(Of List(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ToListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;'T&gt;&gt;" Usage="iMobileServiceTable.ToListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            テーブルの要素を非同期に取得し、新しい一覧で、結果を返します。
            </summary>
        <returns>
            テーブル要素の一覧として結果。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UndeleteAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UndeleteAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.UndeleteAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function UndeleteAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member UndeleteAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.UndeleteAsync instance" />
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
        <Parameter Name="instance" Type="T" />
      </Parameters>
      <Docs>
        <param name="instance">テーブルから復元するインスタンス。</param>
        <summary>
            削除を取り消します、<paramref name="instance" />テーブルからです。 これは、ソフト モバイル サービスで有効にする機能を削除する必要があります。 参照してください<see href="http://go.microsoft.com/fwlink/?LinkId=507647">リンク</see>詳細についてはします。
            </summary>
        <returns>削除の取り消しが終了するときに完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UndeleteAsync (T instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UndeleteAsync(!T instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.UndeleteAsync(`0,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function UndeleteAsync (instance As T, parameters As IDictionary(Of String, String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member UndeleteAsync : 'T * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.UndeleteAsync (instance, parameters)" />
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
        <Parameter Name="instance" Type="T" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance">テーブルから復元するインスタンス。</param>
        <param name="parameters">
            ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。
            </param>
        <summary>
            削除を取り消します、<paramref name="instance" />テーブルからです。 これは、ソフト モバイル サービスで有効にする機能を削除する必要があります。 参照してください<see href="http://go.microsoft.com/fwlink/?LinkId=507647">リンク</see>詳細についてはします。
            </summary>
        <returns>削除の取り消しが終了するときに完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.UpdateAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.UpdateAsync instance" />
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
        <Parameter Name="instance" Type="T" />
      </Parameters>
      <Docs>
        <param name="instance">
            更新するインスタンス。
            </param>
        <summary>
            テーブル内のインスタンスを更新します。
            </summary>
        <returns>
            更新プログラムが終了すると完了するタスク。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateAsync (T instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateAsync(!T instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.UpdateAsync(`0,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAsync (instance As T, parameters As IDictionary(Of String, String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : 'T * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.UpdateAsync (instance, parameters)" />
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
        <Parameter Name="instance" Type="T" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance">
            更新するインスタンス。
            </param>
        <param name="parameters">
            ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。
            </param>
        <summary>
            テーブル内のインスタンスを更新します。
            </summary>
        <returns>
            更新プログラムが終了すると完了するタスク。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Where">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Where (System.Linq.Expressions.Expression&lt;Func&lt;T,bool&gt;&gt; predicate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Where(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, bool&gt;&gt; predicate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.Where(System.Linq.Expressions.Expression{System.Func{`0,System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Function Where (predicate As Expression(Of Func(Of T, Boolean))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Where : System.Linq.Expressions.Expression&lt;Func&lt;'T, bool&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.Where predicate" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="predicate" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="predicate">
            フィルター述語。
            </param>
        <summary>
            指定したフィルター述語を適用することにより、クエリを作成します。
            </summary>
        <returns>
            テーブルに対するクエリ。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithParameters">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; WithParameters (System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; WithParameters(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.WithParameters(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithParameters (parameters As IDictionary(Of String, String)) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member WithParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.WithParameters parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="parameters">
            適用するパラメーター。
            </param>
        <summary>
            要求 URI クエリ文字列でユーザー定義のパラメーターとして使用する指定した文字列のキー/値ペアをソース クエリに適用されます。
            </summary>
        <returns>
            作成されたクエリ。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>