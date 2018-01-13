<Type Name="QueryKeysOperationsExtensions" FullName="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class QueryKeysOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit QueryKeysOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module QueryKeysOperationsExtensions" />
  <TypeSignature Language="F#" Value="type QueryKeysOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            QueryKeysOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Search.Models.QueryKey Create (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string name, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Search.Models.QueryKey Create(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string name, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.Create(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; Microsoft.Azure.Management.Search.Models.QueryKey" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.Create (operations, resourceGroupName, searchServiceName, name, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.QueryKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            現在のサブスクリプション内のリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="searchServiceName">
            指定されたリソース グループに関連付けられている Azure Search サービスの名前。
            </param>
        <param name="name">
            新しいクエリ API キーの名前。
            </param>
        <param name="searchManagementRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定した Search サービスの新しいクエリ キーを生成します。 サービスごとに最大で 50 個のクエリ キーを作成できます。
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt; CreateAsync (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string name, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Search.Models.QueryKey&gt; CreateAsync(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string name, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.CreateAsync (operations, resourceGroupName, searchServiceName, name, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            現在のサブスクリプション内のリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="searchServiceName">
            指定されたリソース グループに関連付けられている Azure Search サービスの名前。
            </param>
        <param name="name">
            新しいクエリ API キーの名前。
            </param>
        <param name="searchManagementRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した Search サービスの新しいクエリ キーを生成します。 サービスごとに最大で 50 個のクエリ キーを作成できます。
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string key, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string key, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.Delete(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; unit" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.Delete (operations, resourceGroupName, searchServiceName, key, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            現在のサブスクリプション内のリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="searchServiceName">
            指定されたリソース グループに関連付けられている Azure Search サービスの名前。
            </param>
        <param name="key">
            削除するクエリのキー。 クエリ キーは、名前ではなく、値によって識別されます。
            </param>
        <param name="searchManagementRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定されたクエリ キーを削除します。 管理者キーとは異なりクエリ キーは再生成されません。 クエリ キーを再生成するには、キーを削除して再作成します。
            <see href="https://aka.ms/search-manage" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string key, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string key, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.DeleteAsync (operations, resourceGroupName, searchServiceName, key, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            現在のサブスクリプション内のリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="searchServiceName">
            指定されたリソース グループに関連付けられている Azure Search サービスの名前。
            </param>
        <param name="key">
            削除するクエリのキー。 クエリ キーは、名前ではなく、値によって識別されます。
            </param>
        <param name="searchManagementRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたクエリ キーを削除します。 管理者キーとは異なりクエリ キーは再生成されません。 クエリ キーを再生成するには、キーを削除して再作成します。
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySearchService">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt; ListBySearchService (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Search.Models.QueryKey&gt; ListBySearchService(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.ListBySearchService(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member ListBySearchService : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; seq&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.ListBySearchService (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            現在のサブスクリプション内のリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="searchServiceName">
            指定されたリソース グループに関連付けられている Azure Search サービスの名前。
            </param>
        <param name="searchManagementRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            特定の Azure Search サービスのクエリ API キーの一覧を返します。
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySearchServiceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt; ListBySearchServiceAsync (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt; ListBySearchServiceAsync(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.ListBySearchServiceAsync(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySearchServiceAsync : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.ListBySearchServiceAsync (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions/&lt;ListBySearchServiceAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            現在のサブスクリプション内のリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="searchServiceName">
            指定されたリソース グループに関連付けられている Azure Search サービスの名前。
            </param>
        <param name="searchManagementRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            特定の Azure Search サービスのクエリ API キーの一覧を返します。
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>