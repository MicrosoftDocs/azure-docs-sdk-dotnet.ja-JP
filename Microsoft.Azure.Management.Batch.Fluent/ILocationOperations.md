<Type Name="ILocationOperations" FullName="Microsoft.Azure.Management.Batch.Fluent.ILocationOperations">
  <TypeSignature Language="C#" Value="public interface ILocationOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILocationOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.ILocationOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILocationOperations" />
  <TypeSignature Language="F#" Value="type ILocationOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="85f3e-101">LocationOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="85f3e-101">LocationOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetQuotasWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner&gt;&gt; GetQuotasWithHttpMessagesAsync (string locationName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner&gt;&gt; GetQuotasWithHttpMessagesAsync(string locationName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.ILocationOperations.GetQuotasWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetQuotasWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner&gt;&gt;" Usage="iLocationOperations.GetQuotasWithHttpMessagesAsync (locationName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="locationName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="locationName">
            <span data-ttu-id="85f3e-102">クォータの目的の地域。</span><span class="sxs-lookup"><span data-stu-id="85f3e-102">The desired region for the quotas.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="85f3e-103">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="85f3e-103">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="85f3e-104">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="85f3e-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="85f3e-105">指定された場所に、指定されたサブスクリプションのバッチ サービスのクォータを取得します。</span><span class="sxs-lookup"><span data-stu-id="85f3e-105">Gets the Batch service quotas for the specified subscription at the given location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="85f3e-106">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="85f3e-106">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="85f3e-107">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="85f3e-107">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="85f3e-108">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="85f3e-108">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>