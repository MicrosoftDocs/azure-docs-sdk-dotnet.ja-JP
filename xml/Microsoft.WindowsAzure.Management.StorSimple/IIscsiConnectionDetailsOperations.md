<Type Name="IIscsiConnectionDetailsOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations">
  <TypeSignature Language="C#" Value="public interface IIscsiConnectionDetailsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IIscsiConnectionDetailsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IIscsiConnectionDetailsOperations" />
  <TypeSignature Language="F#" Value="type IIscsiConnectionDetailsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="68092-101">Iscsi 接続に関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="68092-101">All Operations related to iscsi connection</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse&gt; GetAsync (string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse&gt; GetAsync(string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations.GetAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse&gt;" Usage="iIscsiConnectionDetailsOperations.GetAsync (deviceId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="68092-102">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="68092-102">The device id for which the call will be made.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="68092-103">カスタム要求ヘッダーをクライアントが使用できます。</span><span class="sxs-lookup"><span data-stu-id="68092-103">The Custom Request Headers which client can use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="68092-104">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="68092-104">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="68092-105">Iscsi 接続の詳細の一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="68092-105">The response model for the list of iscsi connection details.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>