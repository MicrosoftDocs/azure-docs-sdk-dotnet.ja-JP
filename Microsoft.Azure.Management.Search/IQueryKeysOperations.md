<Type Name="IQueryKeysOperations" FullName="Microsoft.Azure.Management.Search.IQueryKeysOperations">
  <TypeSignature Language="C#" Value="public interface IQueryKeysOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IQueryKeysOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.IQueryKeysOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IQueryKeysOperations" />
  <TypeSignature Language="F#" Value="type IQueryKeysOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            QueryKeysOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string searchServiceName, string name, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string searchServiceName, string name, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.IQueryKeysOperations.CreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;" Usage="iQueryKeysOperations.CreateWithHttpMessagesAsync (resourceGroupName, searchServiceName, name, searchManagementRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            現在のサブスクリプション内のリソース グループの名前。
            この値は、Azure リソース マネージャー API またはポータルから取得できます。
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
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した Search サービスの新しいクエリ キーを生成します。 サービスごとに最大で 50 個のクエリ キーを作成できます。
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string searchServiceName, string key, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string searchServiceName, string key, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.IQueryKeysOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iQueryKeysOperations.DeleteWithHttpMessagesAsync (resourceGroupName, searchServiceName, key, searchManagementRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            現在のサブスクリプション内のリソース グループの名前。
            この値は、Azure リソース マネージャー API またはポータルから取得できます。
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
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたクエリ キーを削除します。 管理者キーとは異なりクエリ キーは再生成されません。 クエリ キーを再生成するには、キーを削除して再作成します。
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListBySearchServiceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;&gt; ListBySearchServiceWithHttpMessagesAsync (string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;&gt; ListBySearchServiceWithHttpMessagesAsync(string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.IQueryKeysOperations.ListBySearchServiceWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBySearchServiceWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;&gt;" Usage="iQueryKeysOperations.ListBySearchServiceWithHttpMessagesAsync (resourceGroupName, searchServiceName, searchManagementRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            現在のサブスクリプション内のリソース グループの名前。
            この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="searchServiceName">
            指定されたリソース グループに関連付けられている Azure Search サービスの名前。
            </param>
        <param name="searchManagementRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            特定の Azure Search サービスのクエリ API キーの一覧を返します。
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>