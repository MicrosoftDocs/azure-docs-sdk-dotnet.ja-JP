<Type Name="IComputeNodeOperations" FullName="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations">
  <TypeSignature Language="C#" Value="public interface IComputeNodeOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IComputeNodeOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IComputeNodeOperations" />
  <TypeSignature Language="F#" Value="type IComputeNodeOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ComputeNodeOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddUserWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;&gt; AddUserWithHttpMessagesAsync (string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser user, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions computeNodeAddUserOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;&gt; AddUserWithHttpMessagesAsync(string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser user, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions computeNodeAddUserOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.AddUserWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddUserWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;&gt;" Usage="iComputeNodeOperations.AddUserWithHttpMessagesAsync (poolId, nodeId, user, computeNodeAddUserOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="user" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser" />
        <Parameter Name="computeNodeAddUserOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            コンピューティング ノードを含むプールの ID。
            </param>
        <param name="nodeId">
            ユーザー アカウントを作成するコンピューターの ID。
            </param>
        <param name="user">
            作成するユーザー アカウント。
            </param>
        <param name="computeNodeAddUserOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された計算ノードには、ユーザー アカウントを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            アイドル状態または実行中の状態にある場合にのみ、ノードに、ユーザー アカウントを追加できます。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteUserWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders&gt;&gt; DeleteUserWithHttpMessagesAsync (string poolId, string nodeId, string userName, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions computeNodeDeleteUserOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders&gt;&gt; DeleteUserWithHttpMessagesAsync(string poolId, string nodeId, string userName, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions computeNodeDeleteUserOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.DeleteUserWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteUserWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders&gt;&gt;" Usage="iComputeNodeOperations.DeleteUserWithHttpMessagesAsync (poolId, nodeId, userName, computeNodeDeleteUserOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="computeNodeDeleteUserOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            コンピューティング ノードを含むプールの ID。
            </param>
        <param name="nodeId">
            ユーザー アカウントを削除するコンピューターの ID。
            </param>
        <param name="userName">
            削除するユーザー アカウントの名前。
            </param>
        <param name="computeNodeDeleteUserOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された計算ノードから、ユーザー アカウントを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            アイドル状態または実行中の状態にある場合にのみ、ノードへのユーザー アカウントを削除できます。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DisableSchedulingWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders&gt;&gt; DisableSchedulingWithHttpMessagesAsync (string poolId, string nodeId, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; nodeDisableSchedulingOption = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions computeNodeDisableSchedulingOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders&gt;&gt; DisableSchedulingWithHttpMessagesAsync(string poolId, string nodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; nodeDisableSchedulingOption, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions computeNodeDisableSchedulingOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.DisableSchedulingWithHttpMessagesAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableSchedulingWithHttpMessagesAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders&gt;&gt;" Usage="iComputeNodeOperations.DisableSchedulingWithHttpMessagesAsync (poolId, nodeId, nodeDisableSchedulingOption, computeNodeDisableSchedulingOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeDisableSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="computeNodeDisableSchedulingOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            コンピューティング ノードを含むプールの ID。
            </param>
        <param name="nodeId">
            タスクのスケジュールを無効にするコンピューティング ノードの ID。
            </param>
        <param name="nodeDisableSchedulingOption">
            コンピューティング ノードでタスクのスケジュール設定を無効にするときにタスクを実行中の対処方法。 既定値は requeue です。
            使用可能な値が含まれます: 'キューに再登録'、'終了'、'taskCompletion'
            </param>
        <param name="computeNodeDisableSchedulingOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したコンピューティング ノードでタスクのスケジュール設定を無効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            現在のスケジュールの状態が有効になっている場合にのみ、ノード上のスケジュール タスクを無効にすることができます。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnableSchedulingWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders&gt;&gt; EnableSchedulingWithHttpMessagesAsync (string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions computeNodeEnableSchedulingOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders&gt;&gt; EnableSchedulingWithHttpMessagesAsync(string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions computeNodeEnableSchedulingOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.EnableSchedulingWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableSchedulingWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders&gt;&gt;" Usage="iComputeNodeOperations.EnableSchedulingWithHttpMessagesAsync (poolId, nodeId, computeNodeEnableSchedulingOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeEnableSchedulingOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            コンピューティング ノードを含むプールの ID。
            </param>
        <param name="nodeId">
            タスクのスケジュール設定を有効にするコンピューティング ノードの ID。
            </param>
        <param name="computeNodeEnableSchedulingOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したコンピューティング ノードでタスクのスケジュール設定を使用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            現在のスケジュールの状態が無効になっている場合にのみ、ノード上のスケジュール タスクを有効にすることができます。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteDesktopWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopHeaders&gt;&gt; GetRemoteDesktopWithHttpMessagesAsync (string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions computeNodeGetRemoteDesktopOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class System.IO.Stream, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopHeaders&gt;&gt; GetRemoteDesktopWithHttpMessagesAsync(string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions computeNodeGetRemoteDesktopOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.GetRemoteDesktopWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetRemoteDesktopWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopHeaders&gt;&gt;" Usage="iComputeNodeOperations.GetRemoteDesktopWithHttpMessagesAsync (poolId, nodeId, computeNodeGetRemoteDesktopOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeGetRemoteDesktopOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            コンピューティング ノードを含むプールの ID。
            </param>
        <param name="nodeId">
            リモート デスクトップ プロトコル ファイルを取得するコンピューティング ノードの ID。
            </param>
        <param name="computeNodeGetRemoteDesktopOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された計算ノードのリモート デスクトップ プロトコル ファイルを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ノードにアクセスするには、RDP ファイルを使用して、前に、ノードで、ユーザー アカウントを作成する必要があります。 この API は、クラウド サービスの構成で作成されたプールでのみ呼び出すことができます。 プールの仮想マシンの構成で作成された場合は、GetRemoteLoginSettings API を参照してください。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
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
    <Member MemberName="GetRemoteLoginSettingsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsHeaders&gt;&gt; GetRemoteLoginSettingsWithHttpMessagesAsync (string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions computeNodeGetRemoteLoginSettingsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsHeaders&gt;&gt; GetRemoteLoginSettingsWithHttpMessagesAsync(string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions computeNodeGetRemoteLoginSettingsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.GetRemoteLoginSettingsWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetRemoteLoginSettingsWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsHeaders&gt;&gt;" Usage="iComputeNodeOperations.GetRemoteLoginSettingsWithHttpMessagesAsync (poolId, nodeId, computeNodeGetRemoteLoginSettingsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeGetRemoteLoginSettingsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            コンピューティング ノードを含むプールの ID。
            </param>
        <param name="nodeId">
            リモート ログインの設定を取得する対象のコンピューティング ノードの ID。
            </param>
        <param name="computeNodeGetRemoteLoginSettingsOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            コンピューティング ノードへのリモート ログイン用に必要な設定を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            前にリモートでログインにリモート ログインの設定を使用してノード、ノードでユーザー アカウントを作成する必要があります。 この API は、仮想マシンの構成プロパティを使用して作成されたプールでのみ呼び出すことができます。 クラウド サービスの構成で作成されたプール、GetRemoteDesktop API を参照してください。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions computeNodeGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNode, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions computeNodeGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.GetWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetHeaders&gt;&gt;" Usage="iComputeNodeOperations.GetWithHttpMessagesAsync (poolId, nodeId, computeNodeGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            コンピューティング ノードを含むプールの ID。
            </param>
        <param name="nodeId">
            に関する情報を取得するコンピューティング ノードの ID。
            </param>
        <param name="computeNodeGetOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された計算ノードに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions computeNodeListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions computeNodeListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt;" Usage="iComputeNodeOperations.ListNextWithHttpMessagesAsync (nextPageLink, computeNodeListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="computeNodeListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="computeNodeListNextOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したプール内の計算ノードを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt; ListWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions computeNodeListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt; ListWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions computeNodeListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.ListWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt;" Usage="iComputeNodeOperations.ListWithHttpMessagesAsync (poolId, computeNodeListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            リストのノードにプールの ID。
            </param>
        <param name="computeNodeListOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したプール内の計算ノードを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
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
    <Member MemberName="RebootWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;&gt; RebootWithHttpMessagesAsync (string poolId, string nodeId, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; nodeRebootOption = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions computeNodeRebootOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;&gt; RebootWithHttpMessagesAsync(string poolId, string nodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; nodeRebootOption, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions computeNodeRebootOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.RebootWithHttpMessagesAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RebootWithHttpMessagesAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;&gt;" Usage="iComputeNodeOperations.RebootWithHttpMessagesAsync (poolId, nodeId, nodeRebootOption, computeNodeRebootOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeRebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt;" />
        <Parameter Name="computeNodeRebootOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            コンピューティング ノードを含むプールの ID。
            </param>
        <param name="nodeId">
            再起動するコンピューティング ノードの ID。
            </param>
        <param name="nodeRebootOption">
            コンピューティング ノードを再起動するタイミングと、実行中のタスクの処理方法します。 既定値は requeue です。 使用可能な値が含まれます: 'requeue'、'終了'、'taskCompletion'、'retainedData'
            </param>
        <param name="computeNodeRebootOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された計算ノードを再起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            アイドル状態または実行中の状態である場合にのみ、ノードを再起動したことができます。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ReimageWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders&gt;&gt; ReimageWithHttpMessagesAsync (string poolId, string nodeId, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; nodeReimageOption = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions computeNodeReimageOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders&gt;&gt; ReimageWithHttpMessagesAsync(string poolId, string nodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; nodeReimageOption, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions computeNodeReimageOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.ReimageWithHttpMessagesAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReimageWithHttpMessagesAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders&gt;&gt;" Usage="iComputeNodeOperations.ReimageWithHttpMessagesAsync (poolId, nodeId, nodeReimageOption, computeNodeReimageOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeReimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt;" />
        <Parameter Name="computeNodeReimageOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            コンピューティング ノードを含むプールの ID。
            </param>
        <param name="nodeId">
            再起動するコンピューティング ノードの ID。
            </param>
        <param name="nodeReimageOption">
            コンピューティング ノードを再イメージ化する場合と実行中のタスクを行うには新機能です。 既定値は requeue です。 使用可能な値が含まれます: 'requeue'、'終了'、'taskCompletion'、'retainedData'
            </param>
        <param name="computeNodeReimageOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したコンピューティング ノードで、オペレーティング システムを再インストールします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            アイドル状態または実行中の状態である場合にのみ、ノードにオペレーティング システムを再インストールすることができます。 この API は、クラウド サービスの構成プロパティを使用して作成されたプールでのみ呼び出すことができます。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateUserWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders&gt;&gt; UpdateUserWithHttpMessagesAsync (string poolId, string nodeId, string userName, Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter nodeUpdateUserParameter, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions computeNodeUpdateUserOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders&gt;&gt; UpdateUserWithHttpMessagesAsync(string poolId, string nodeId, string userName, class Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter nodeUpdateUserParameter, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions computeNodeUpdateUserOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.UpdateUserWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateUserWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders&gt;&gt;" Usage="iComputeNodeOperations.UpdateUserWithHttpMessagesAsync (poolId, nodeId, userName, nodeUpdateUserParameter, computeNodeUpdateUserOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="nodeUpdateUserParameter" Type="Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter" />
        <Parameter Name="computeNodeUpdateUserOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            コンピューティング ノードを含むプールの ID。
            </param>
        <param name="nodeId">
            ユーザー アカウントを更新するコンピューターの ID。
            </param>
        <param name="userName">
            更新するユーザー アカウントの名前。
            </param>
        <param name="nodeUpdateUserParameter">
            要求のパラメーターです。
            </param>
        <param name="computeNodeUpdateUserOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された計算ノード上のユーザー アカウントのパスワードと有効期限の時間を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この操作は、アカウントの更新可能なすべてのプロパティの置き換えられます。 たとえば、expiryTime 要素が指定されていない場合は、現在の値がない左変更されていない、既定値に置き換えられます。 アイドル状態または実行中の状態にある場合にのみ、ノード上のユーザー アカウントを更新することができます。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>