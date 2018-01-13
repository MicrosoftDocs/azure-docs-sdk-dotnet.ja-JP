<Type Name="ICapabilitiesOperations" FullName="Microsoft.Azure.Management.Sql.ICapabilitiesOperations">
  <TypeSignature Language="C#" Value="public interface ICapabilitiesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICapabilitiesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ICapabilitiesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICapabilitiesOperations" />
  <TypeSignature Language="F#" Value="type ICapabilitiesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e2420-101">CapabilitiesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="e2420-101">CapabilitiesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByLocationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.LocationCapabilities&gt;&gt; ListByLocationWithHttpMessagesAsync (string locationId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.LocationCapabilities&gt;&gt; ListByLocationWithHttpMessagesAsync(string locationId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ICapabilitiesOperations.ListByLocationWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByLocationWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.LocationCapabilities&gt;&gt;" Usage="iCapabilitiesOperations.ListByLocationWithHttpMessagesAsync (locationId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.LocationCapabilities&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="locationId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="locationId">
            <span data-ttu-id="e2420-102">場所 id 機能を持つが取得されます。</span><span class="sxs-lookup"><span data-stu-id="e2420-102">The location id whose capabilities are retrieved.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e2420-103">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e2420-103">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e2420-104">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e2420-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2420-105">指定された場所の使用可能な機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="e2420-105">Gets the capabilities available for the specified location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e2420-106">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e2420-106">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e2420-107">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e2420-107">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e2420-108">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e2420-108">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>