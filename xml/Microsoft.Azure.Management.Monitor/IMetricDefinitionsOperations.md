<Type Name="IMetricDefinitionsOperations" FullName="Microsoft.Azure.Management.Monitor.IMetricDefinitionsOperations">
  <TypeSignature Language="C#" Value="public interface IMetricDefinitionsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMetricDefinitionsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.IMetricDefinitionsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMetricDefinitionsOperations" />
  <TypeSignature Language="F#" Value="type IMetricDefinitionsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c4c04-101">MetricDefinitionsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="c4c04-101">MetricDefinitionsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.MetricDefinition&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceUri, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Models.MetricDefinition&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceUri, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.IMetricDefinitionsOperations.ListWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Monitor.Models.MetricDefinition&gt;&gt;&gt;" Usage="iMetricDefinitionsOperations.ListWithHttpMessagesAsync (resourceUri, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.MetricDefinition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceUri">
            <span data-ttu-id="c4c04-102">リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="c4c04-102">The identifier of the resource.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c4c04-103">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c4c04-103">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c4c04-104">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c4c04-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c4c04-105">リソースのメトリックの定義を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c4c04-105">Lists the metric definitions for the resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Models.ErrorResponseException">
            <span data-ttu-id="c4c04-106">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c4c04-106">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c4c04-107">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c4c04-107">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c4c04-108">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c4c04-108">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>