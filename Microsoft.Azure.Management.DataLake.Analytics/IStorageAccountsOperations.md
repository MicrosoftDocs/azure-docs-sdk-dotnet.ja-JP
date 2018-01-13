<Type Name="IStorageAccountsOperations" FullName="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations">
  <TypeSignature Language="C#" Value="public interface IStorageAccountsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStorageAccountsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStorageAccountsOperations" />
  <TypeSignature Language="F#" Value="type IStorageAccountsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            StorageAccountsOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; AddWithHttpMessagesAsync (string resourceGroupName, string accountName, string storageAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; AddWithHttpMessagesAsync(string resourceGroupName, string accountName, string storageAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.AddWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iStorageAccountsOperations.AddWithHttpMessagesAsync (resourceGroupName, accountName, storageAccountName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Azure ストレージ アカウントを追加する、Data Lake Analytics アカウントの名前。
            </param>
        <param name="storageAccountName">
            追加する Azure ストレージ アカウントの名前
            </param>
        <param name="parameters">
            Azure ストレージ アカウントのアクセス キーと省略可能なサフィックスを含むパラメーター。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure ストレージ アカウントを追加する指定された Data Lake Analytics アカウントを更新します。
            </summary>
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
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, string storageAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, string storageAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iStorageAccountsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, accountName, storageAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Azure ストレージ アカウントを削除する Data Lake Analytics アカウントの名前。
            </param>
        <param name="storageAccountName">
            削除する Azure ストレージ アカウントの名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure ストレージ アカウントを削除する指定された Data Lake Analytics アカウントを更新します。
            </summary>
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
    <Member MemberName="GetStorageContainerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt; GetStorageContainerWithHttpMessagesAsync (string resourceGroupName, string accountName, string storageAccountName, string containerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt; GetStorageContainerWithHttpMessagesAsync(string resourceGroupName, string accountName, string storageAccountName, string containerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.GetStorageContainerWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageContainerWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;" Usage="iStorageAccountsOperations.GetStorageContainerWithHttpMessagesAsync (resourceGroupName, accountName, storageAccountName, containerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Blob コンテナーを取得する対象の Data Lake Analytics アカウントの名前。
            </param>
        <param name="storageAccountName">
            Blob コンテナーを取得する対象の Azure ストレージ アカウントの名前。
            </param>
        <param name="containerName">
            取得する Azure ストレージ コンテナーの名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Analytics と Azure ストレージ アカウントに関連付けられている指定された Azure ストレージ コンテナーを取得します。
            </summary>
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
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string accountName, string storageAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string accountName, string storageAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;" Usage="iStorageAccountsOperations.GetWithHttpMessagesAsync (resourceGroupName, accountName, storageAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Azure ストレージ アカウントの詳細を取得する対象の Data Lake Analytics アカウントの名前。
            </param>
        <param name="storageAccountName">
            詳細を取得する対象の Azure ストレージ アカウントの名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Azure ストレージ アカウントが指定された Data Lake Analytics アカウントへのリンクを取得します。
            </summary>
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
    <Member MemberName="ListByAccountNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;&gt; ListByAccountNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;&gt; ListByAccountNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.ListByAccountNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByAccountNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListByAccountNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Analytics アカウントに、リンクされている場合は、Azure ストレージ アカウントの最初のページを取得します。 応答には、存在する場合、次のページへのリンクが含まれています。
            </summary>
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
    <Member MemberName="ListByAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;&gt; ListByAccountWithHttpMessagesAsync (string resourceGroupName, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;&gt; ListByAccountWithHttpMessagesAsync(string resourceGroupName, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.ListByAccountWithHttpMessagesAsync(System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByAccountWithHttpMessagesAsync : string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListByAccountWithHttpMessagesAsync (resourceGroupName, accountName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            名前、Data Lake Analytics アカウントを Azure ストレージ アカウントを一覧表示します。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="select">
            OData の Select ステートメント。 各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。
            省略可能。
            </param>
        <param name="count">
            応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。 省略可能。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Analytics アカウントに、リンクされている場合は、Azure ストレージ アカウントの最初のページを取得します。 応答には、存在する場合、次のページへのリンクが含まれています。
            </summary>
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
    <Member MemberName="ListSasTokensNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;&gt; ListSasTokensNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;&gt; ListSasTokensNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.ListSasTokensNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSasTokensNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListSasTokensNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            組み合わせに関連付けられた、指定された Data Lake Analytics と Azure ストレージ アカウントとコンテナーの SAS トークンを取得します。
            </summary>
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
    <Member MemberName="ListSasTokensWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;&gt; ListSasTokensWithHttpMessagesAsync (string resourceGroupName, string accountName, string storageAccountName, string containerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;&gt; ListSasTokensWithHttpMessagesAsync(string resourceGroupName, string accountName, string storageAccountName, string containerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.ListSasTokensWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSasTokensWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListSasTokensWithHttpMessagesAsync (resourceGroupName, accountName, storageAccountName, containerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Azure ストレージ アカウントの SAS トークンの要求された Data Lake Analytics アカウントの名前。
            </param>
        <param name="storageAccountName">
            SAS トークンを要求する Azure のストレージ アカウントの名前。
            </param>
        <param name="containerName">
            SAS トークンを要求する対象の Azure ストレージ コンテナーの名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            組み合わせに関連付けられた、指定された Data Lake Analytics と Azure ストレージ アカウントとコンテナーの SAS トークンを取得します。
            </summary>
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
    <Member MemberName="ListStorageContainersNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;&gt; ListStorageContainersNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;&gt; ListStorageContainersNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.ListStorageContainersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListStorageContainersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListStorageContainersNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Analytics と Azure ストレージ アカウントの組み合わせに関連付けられている場合は、Azure ストレージ コンテナーを一覧表示します。 応答には、存在する場合、結果の次のページへのリンクが含まれています。
            </summary>
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
    <Member MemberName="ListStorageContainersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;&gt; ListStorageContainersWithHttpMessagesAsync (string resourceGroupName, string accountName, string storageAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;&gt; ListStorageContainersWithHttpMessagesAsync(string resourceGroupName, string accountName, string storageAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.ListStorageContainersWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListStorageContainersWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListStorageContainersWithHttpMessagesAsync (resourceGroupName, accountName, storageAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            名前 Data Lake Analytics アカウントを Azure Storage blob コンテナーの一覧にします。
            </param>
        <param name="storageAccountName">
            Blob コンテナーの一覧を表示する Azure のストレージ アカウントの名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Analytics と Azure ストレージ アカウントの組み合わせに関連付けられている場合は、Azure ストレージ コンテナーを一覧表示します。 応答には、存在する場合、結果の次のページへのリンクが含まれています。
            </summary>
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
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string accountName, string storageAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters parameters = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string accountName, string storageAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iStorageAccountsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, accountName, storageAccountName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            内のストレージ アカウントを変更する Data Lake Analytics アカウントの名前
            </param>
        <param name="storageAccountName">
            Azure ストレージ アカウントを変更するには
            </param>
        <param name="parameters">
            存在する場合に、アクセス キーと、ストレージ アカウントを更新するサフィックスを含むパラメーター。 何も渡すことは、変更なしになります。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アクセス キーまたはサフィックスなど、Azure ストレージ blob アカウントの詳細を交換できる Data Lake Analytics アカウントを更新します。
            </summary>
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
  </Members>
</Type>