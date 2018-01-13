<Type Name="IResourceEncryptionKeyOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations">
  <TypeSignature Language="C#" Value="public interface IResourceEncryptionKeyOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IResourceEncryptionKeyOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IResourceEncryptionKeyOperations" />
  <TypeSignature Language="F#" Value="type IResourceEncryptionKeyOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d98ad-101">暗号化キーに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="d98ad-101">All Operations related to Crypto keys</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse&gt; GetAsync (Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse&gt;" Usage="iResourceEncryptionKeyOperations.GetAsync (customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customRequestHeaders">
            <span data-ttu-id="d98ad-102">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d98ad-102">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d98ad-103">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d98ad-103">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="d98ad-104">リソースの暗号化キーの応答モデル。</span><span class="sxs-lookup"><span data-stu-id="d98ad-104">The response model for Resource Encryption Key.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>