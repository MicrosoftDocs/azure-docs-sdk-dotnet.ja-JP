<Type Name="IContainerLogsOperations" FullName="Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations">
  <TypeSignature Language="C#" Value="public interface IContainerLogsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IContainerLogsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IContainerLogsOperations" />
  <TypeSignature Language="F#" Value="type IContainerLogsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ContainerLogsOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, string containerGroupName, string containerName, Nullable&lt;int&gt; tail = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, string containerGroupName, string containerName, valuetype System.Nullable`1&lt;int32&gt; tail, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations.ListWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt;&gt;" Usage="iContainerLogsOperations.ListWithHttpMessagesAsync (resourceGroupName, containerGroupName, containerName, tail, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerGroupName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="tail" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="containerGroupName">
            コンテナーのグループの名前。
            </param>
        <param name="containerName">
            コンテナーのインスタンスの名前。
            </param>
        <param name="tail">
            コンテナーのインスタンスのログの末尾が示される行の数。 指定しない場合、使用可能なすべてのログは、最大 4 mb のとおりです。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            インスタンスの指定されたコンテナーのログを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ログは、指定されたリソース グループおよびコンテナーのグループで指定されたコンテナー インスタンスを取得します。
            </remarks>
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