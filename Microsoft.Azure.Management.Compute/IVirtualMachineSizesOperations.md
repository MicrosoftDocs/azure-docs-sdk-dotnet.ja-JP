<Type Name="IVirtualMachineSizesOperations" FullName="Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineSizesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineSizesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineSizesOperations" />
  <TypeSignature Language="F#" Value="type IVirtualMachineSizesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="82466-101">VirtualMachineSizesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="82466-101">VirtualMachineSizesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt;&gt; ListWithHttpMessagesAsync (string location, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt;&gt; ListWithHttpMessagesAsync(string location, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations.ListWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt;&gt;" Usage="iVirtualMachineSizesOperations.ListWithHttpMessagesAsync (location, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="location">
            <span data-ttu-id="82466-102">どの仮想マシンのサイズと場所は、クエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="82466-102">The location upon which virtual-machine-sizes is queried.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="82466-103">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="82466-103">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="82466-104">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="82466-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="82466-105">場所でサブスクリプションのすべての利用可能な仮想マシンのサイズを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="82466-105">Lists all available virtual machine sizes for a subscription in a location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="82466-106">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="82466-106">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="82466-107">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="82466-107">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="82466-108">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="82466-108">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>