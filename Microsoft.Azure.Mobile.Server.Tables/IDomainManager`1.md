<Type Name="IDomainManager&lt;TData&gt;" FullName="Microsoft.Azure.Mobile.Server.Tables.IDomainManager&lt;TData&gt;">
  <TypeSignature Language="C#" Value="public interface IDomainManager&lt;TData&gt; where TData : class, ITableData" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDomainManager`1&lt;class (class Microsoft.Azure.Mobile.Server.Tables.ITableData) TData&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDomainManager(Of TData)" />
  <TypeSignature Language="F#" Value="type IDomainManager&lt;'Data (requires 'Data : null and 'Data :&gt; ITableData)&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TData">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
        <InterfaceName>Microsoft.Azure.Mobile.Server.Tables.ITableData</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="TData"></typeparam>
    <summary>
            提供のバックエンド ストアにアクセスするための抽象、<see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />です。
            抽象型は、バックエンド ストアの能力に応じて、2 つの方法のいずれかで実装できます。 格納をサポートする、 <see cref="T:System.Linq.IQueryable`1" />-ベースのモデルを実装できます、<see cref="M:Query" />と<see cref="M:Lookup" />メソッドをサポートしていないストア<see cref="T:System.Linq.IQueryable" />直接またはここではそれらにアクセスする方法として推奨を実装できます、<see cref="M:QueryAsync" />と<see cref="M:LookupAsync" />メソッドです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; DeleteAsync (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteAsync(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.DeleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (id As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iDomainManager.DeleteAsync id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">削除する項目の id。</param>
        <summary>
            既存の項目を削除します
            </summary>
        <returns>
          <c>true</c>項目が削除されたそれ以外の場合<c>false</c></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TData&gt; InsertAsync (TData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; InsertAsync(!TData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.InsertAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function InsertAsync (data As TData) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : 'Data -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="iDomainManager.InsertAsync data" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="TData" />
      </Parameters>
      <Docs>
        <param name="data">データを挿入します。</param>
        <summary>
            バックエンド ストアに項目を挿入します。
            </summary>
        <returns>挿入されたアイテムです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lookup">
      <MemberSignature Language="C#" Value="public System.Web.Http.SingleResult&lt;TData&gt; Lookup (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Web.Http.SingleResult`1&lt;!TData&gt; Lookup(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.Lookup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Lookup (id As String) As SingleResult(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member Lookup : string -&gt; System.Web.Http.SingleResult&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="iDomainManager.Lookup id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Web.Http.SingleResult&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">項目を表す id です。 一部として、id が指定される、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" />され、クライアントに表示されます。 ただし、によっては、バックエンド ストアとドメイン モデルでは、特定の実装では、可能性があります id にマップの他の何らかの一意識別子。</param>
        <summary>
            ビルド、<see cref="T:System.Linq.IQueryable`1" />サポートするストアに対して実行される<see cref="T:System.Linq.IQueryable`1" />1 つの項目を検索するためです。
            </summary>
        <returns>A<see cref="T:System.Web.Http.SingleResult`1" />を含む、<see cref="T:System.Linq.IQueryable`1" />がまだ実行されていません。</returns>
        <remarks>
            関連項目<see cref="M:Query" />コンパニオン メソッドを作成するためである、<see cref="T:System.Linq.IQueryable`1" />複数の項目を表すです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;TData&gt;&gt; LookupAsync (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Web.Http.SingleResult`1&lt;!TData&gt;&gt; LookupAsync(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.LookupAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (id As String) As Task(Of SingleResult(Of TData))" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;'Data&gt;&gt;" Usage="iDomainManager.LookupAsync id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;TData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">項目を表す id です。 一部として、id が指定される、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" />され、クライアントに表示されます。 ただし、によっては、バックエンド ストアとドメイン モデルでは、特定の実装では、可能性があります id にマップの他の何らかの一意識別子。</param>
        <summary>
            バックエンド ストアの 1 つの項目を検索します。 
            </summary>
        <returns>A<see cref="T:System.Web.Http.SingleResult`1" />検索の結果を表すです。 A<see cref="T:System.Web.Http.SingleResult`1" />を表す、 <see cref="T:System.Linq.IQueryable" /> 0 個または 1 つのエンティティを含むです。 これにより、さらにクエリなどを実行するとで構成される<c>$select</c>です。</returns>
        <remarks>
            関連項目<see cref="M:QueryAsync" />複数の項目のクエリを実行するコンパニオン メソッドであります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;TData&gt; Query ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!TData&gt; Query() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.Query" />
      <MemberSignature Language="VB.NET" Value="Public Function Query () As IQueryable(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member Query : unit -&gt; System.Linq.IQueryable&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="iDomainManager.Query " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ビルド、<see cref="T:System.Linq.IQueryable`1" />サポートするストアに対して実行される<see cref="T:System.Linq.IQueryable`1" />データを照会するためです。 
            </summary>
        <returns><see cref="T:System.Linq.IQueryable`1" />がまだ実行されていません。</returns>
        <remarks>
            参照<see cref="M:Lookup" />コンパニオン メソッドを作成するためである、<see cref="T:System.Linq.IQueryable`1" />を表す 1 つの項目。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;TData&gt;&gt; QueryAsync (System.Web.Http.OData.Query.ODataQueryOptions query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!TData&gt;&gt; QueryAsync(class System.Web.Http.OData.Query.ODataQueryOptions query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.QueryAsync(System.Web.Http.OData.Query.ODataQueryOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function QueryAsync (query As ODataQueryOptions) As Task(Of IEnumerable(Of TData))" />
      <MemberSignature Language="F#" Value="abstract member QueryAsync : System.Web.Http.OData.Query.ODataQueryOptions -&gt; System.Threading.Tasks.Task&lt;seq&lt;'Data&gt;&gt;" Usage="iDomainManager.QueryAsync query" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;TData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="System.Web.Http.OData.Query.ODataQueryOptions" />
      </Parameters>
      <Docs>
        <param name="query"><see cref="T:System.Web.Http.OData.Query.ODataQueryOptions" />クエリを実行します。</param>
        <summary>
            指定された実行<paramref name="query" />ストアに対してです。
            </summary>
        <returns><see cref="T:System.Collections.Generic.IEnumerable`1" />クエリの結果を表すです。</returns>
        <remarks>
            関連項目<see cref="M:LookupAsync" />1 つの項目の参照を実行するためのコンパニオン メソッドであります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TData&gt; ReplaceAsync (string id, TData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; ReplaceAsync(string id, !TData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.ReplaceAsync(System.String,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReplaceAsync (id As String, data As TData) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceAsync : string * 'Data -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="iDomainManager.ReplaceAsync (id, data)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="data" Type="TData" />
      </Parameters>
      <Docs>
        <param name="id">置換する項目の id。</param>
        <param name="data">置換</param>
        <summary>
            既存の項目を完全に置き換えます。
            </summary>
        <returns>置き換えられる項目</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TData&gt; UpdateAsync (string id, System.Web.Http.OData.Delta&lt;TData&gt; patch);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; UpdateAsync(string id, class System.Web.Http.OData.Delta`1&lt;!TData&gt; patch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.UpdateAsync(System.String,System.Web.Http.OData.Delta{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAsync (id As String, patch As Delta(Of TData)) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : string * System.Web.Http.OData.Delta&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="iDomainManager.UpdateAsync (id, patch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="patch" Type="System.Web.Http.OData.Delta&lt;TData&gt;" />
      </Parameters>
      <Docs>
        <param name="id">修正プログラムを項目の id。</param>
        <param name="patch">適用する修正プログラム。</param>
        <summary>
            適用することで既存の項目を更新、<see cref="T:System.Web.Http.OData.Delta`1" />に修正プログラム。 <see cref="T:System.Web.Http.OData.Delta`1" />抽象化を追跡するプロパティが変更された既定値と、同様の問題を回避できます。
            </summary>
        <returns>パッチが適用された項目。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>