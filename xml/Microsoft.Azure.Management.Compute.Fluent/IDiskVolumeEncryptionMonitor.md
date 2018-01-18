<Type Name="IDiskVolumeEncryptionMonitor" FullName="Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor">
  <TypeSignature Language="C#" Value="public interface IDiskVolumeEncryptionMonitor : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDiskVolumeEncryptionMonitor implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDiskVolumeEncryptionMonitor&#xA;Implements IRefreshable(Of IDiskVolumeEncryptionMonitor)" />
  <TypeSignature Language="F#" Value="type IDiskVolumeEncryptionMonitor = interface&#xA;    interface IRefreshable&lt;IDiskVolumeEncryptionMonitor&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="e4681-101">暗号化の監視に使用できる型では、有効にし、バーチャル マシンの状態を無効にします。</span><span class="sxs-lookup"><span data-stu-id="e4681-101">Type that can be used to monitor encryption enable and disable status of a virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DataDiskStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.EncryptionStatus DataDiskStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.EncryptionStatus DataDiskStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor.DataDiskStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataDiskStatus As EncryptionStatus" />
      <MemberSignature Language="F#" Value="member this.DataDiskStatus : Microsoft.Azure.Management.Compute.Fluent.EncryptionStatus" Usage="Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor.DataDiskStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.EncryptionStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4681-102">データ ディスクの暗号化の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="e4681-102">Gets data disks encryption status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.EncryptionStatus OSDiskStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.EncryptionStatus OSDiskStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor.OSDiskStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskStatus As EncryptionStatus" />
      <MemberSignature Language="F#" Value="member this.OSDiskStatus : Microsoft.Azure.Management.Compute.Fluent.EncryptionStatus" Usage="Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor.OSDiskStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.EncryptionStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4681-103">オペレーティング システム ディスク暗号化の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="e4681-103">Gets operating system disk encryption status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OSType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OSType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor.OSType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSType As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="member this.OSType : Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor.OSType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4681-104">仮想マシンのオペレーティング システムの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="e4681-104">Gets operating system type of the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProgressMessage">
      <MemberSignature Language="C#" Value="public string ProgressMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProgressMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor.ProgressMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProgressMessage As String" />
      <MemberSignature Language="F#" Value="member this.ProgressMessage : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor.ProgressMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e4681-105">暗号化の進行状況メッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="e4681-105">Gets the encryption progress message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt; RefreshAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt; RefreshAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor.RefreshAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt;" Usage="iDiskVolumeEncryptionMonitor.RefreshAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1.RefreshAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>