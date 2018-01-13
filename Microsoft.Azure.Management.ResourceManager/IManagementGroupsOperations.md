<Type Name="IManagementGroupsOperations" FullName="Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations">
  <TypeSignature Language="C#" Value="public interface IManagementGroupsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IManagementGroupsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IManagementGroupsOperations" />
  <TypeSignature Language="F#" Value="type IManagementGroupsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ManagementGroupsOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy&gt;&gt; GetWithHttpMessagesAsync (string expand = null, Nullable&lt;bool&gt; recurse = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy&gt;&gt; GetWithHttpMessagesAsync(string expand, valuetype System.Nullable`1&lt;bool&gt; recurse, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations.GetWithHttpMessagesAsync(System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy&gt;&gt;" Usage="iManagementGroupsOperations.GetWithHttpMessagesAsync (expand, recurse, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="recurse" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="expand">
             $展開クエリ文字列パラメーターにより、応答のペイロード内の子を含めることを要求するクライアントの子を = です。 使用可能な値が含まれます: '子'
             </param>
        <param name="recurse">
             $Recurse = true のクエリ文字列パラメーターを使用してクライアントを応答ペイロードの階層全体を含めることを要求します。
             </param>
        <param name="customHeaders">
             追加されるヘッダーを要求します。
             </param>
        <param name="cancellationToken">
             キャンセル トークン。
             </param>
        <summary>
             管理グループの詳細を取得します。
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
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
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;&gt;" Usage="iManagementGroupsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;&gt;</ReturnType>
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
             認証されたユーザーの管理グループを一覧表示します。
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
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
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;&gt; ListWithHttpMessagesAsync (string skiptoken = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;&gt; ListWithHttpMessagesAsync(string skiptoken, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations.ListWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;&gt;" Usage="iManagementGroupsOperations.ListWithHttpMessagesAsync (skiptoken, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="skiptoken">
             ページ継続トークンは、前の操作には、部分的な結果が返された場合にのみ使用します。
             前の応答には、nextLink 要素が含まれています、nextLink 要素の値により、後続の呼び出しに使用する開始位置を指定するトークンのパラメーターが含まれます。
             
             </param>
        <param name="customHeaders">
             追加されるヘッダーを要求します。
             </param>
        <param name="cancellationToken">
             キャンセル トークン。
             </param>
        <summary>
             認証されたユーザーの管理グループを一覧表示します。
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
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