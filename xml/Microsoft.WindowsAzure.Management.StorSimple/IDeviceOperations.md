<Type Name="IDeviceOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations">
  <TypeSignature Language="C#" Value="public interface IDeviceOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDeviceOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDeviceOperations" />
  <TypeSignature Language="F#" Value="type IDeviceOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6ecac-101">デバイスに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="6ecac-101">All Operations related to Devices</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceListResponse&gt; ListAsync (Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceListResponse&gt; ListAsync(class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations.ListAsync(Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceListResponse&gt;" Usage="iDeviceOperations.ListAsync (customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customRequestHeaders">
            <span data-ttu-id="6ecac-102">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="6ecac-102">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ecac-103">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ecac-103">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="6ecac-104">デバイスの一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="6ecac-104">The response model for the list of devices.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>