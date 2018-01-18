<Type Name="IDevicePublicKeyOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations">
  <TypeSignature Language="C#" Value="public interface IDevicePublicKeyOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDevicePublicKeyOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDevicePublicKeyOperations" />
  <TypeSignature Language="F#" Value="type IDevicePublicKeyOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="739f4-101">デバイスの公開キーに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="739f4-101">All Operations related to Device Public keys</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse&gt; GetAsync (string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse&gt; GetAsync(string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations.GetAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse&gt;" Usage="iDevicePublicKeyOperations.GetAsync (deviceId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDevicePublicKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="739f4-102">デバイスの公開キーをフェッチお必要があります、デバイス Id</span><span class="sxs-lookup"><span data-stu-id="739f4-102">The Device Id for which we need to Fetch the Device Public Key</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="739f4-103">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="739f4-103">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="739f4-104">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="739f4-104">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="739f4-105">デバイスの公開キーの応答モデル。</span><span class="sxs-lookup"><span data-stu-id="739f4-105">The response model for Device PublicKey.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>