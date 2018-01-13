<Type Name="IDeviceFailoverOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations">
  <TypeSignature Language="C#" Value="public interface IDeviceFailoverOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDeviceFailoverOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDeviceFailoverOperations" />
  <TypeSignature Language="F#" Value="type IDeviceFailoverOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="25cb8-101">デバイスのフェールオーバーに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="25cb8-101">All Operations related to Device Failover</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListDCGroupsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse&gt; ListDCGroupsAsync (string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse&gt; ListDCGroupsAsync(string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations.ListDCGroupsAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListDCGroupsAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse&gt;" Usage="iDeviceFailoverOperations.ListDCGroupsAsync (deviceId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">To be added.</param>
        <param name="customRequestHeaders">To be added.</param>
        <param name="cancellationToken">
            <span data-ttu-id="25cb8-102">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="25cb8-102">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="25cb8-103">DataContainerGroups Get 呼び出しの応答のモデルを表します</span><span class="sxs-lookup"><span data-stu-id="25cb8-103">Represents the response model for DataContainerGroups Get call</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; TriggerAsync (string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest drRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; TriggerAsync(string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest drRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations.TriggerAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TriggerAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;" Usage="iDeviceFailoverOperations.TriggerAsync (deviceId, drRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="drRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="25cb8-104">デバイス識別子</span><span class="sxs-lookup"><span data-stu-id="25cb8-104">The device identifier</span></span>
            </param>
        <param name="drRequest">
            <span data-ttu-id="25cb8-105">デバイスのフェールオーバーの要求の詳細。</span><span class="sxs-lookup"><span data-stu-id="25cb8-105">The details of the device failover request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="25cb8-106">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="25cb8-106">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="25cb8-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="25cb8-107">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="25cb8-108">デバイスのフェールオーバーをトリガーします。</span><span class="sxs-lookup"><span data-stu-id="25cb8-108">Trigger device failover.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="25cb8-109">これは、デバイス ジョブの関連するすべての呼び出しのジョブ応答</span><span class="sxs-lookup"><span data-stu-id="25cb8-109">This is the Job Response for all Device Job Related Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>