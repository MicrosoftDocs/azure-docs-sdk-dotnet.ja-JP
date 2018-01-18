<Type Name="IVirtualMachineScaleSetVM" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineScaleSetVM : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineScaleSetVM implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineScaleSetVM&#xA;Implements IChildResource(Of IVirtualMachineScaleSet), IHasInner(Of VirtualMachineScaleSetVMInner), IHasParent(Of IVirtualMachineScaleSet), IRefreshable(Of IVirtualMachineScaleSetVM), IResource" />
  <TypeSignature Language="F#" Value="type IVirtualMachineScaleSetVM = interface&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IChildResource&lt;IVirtualMachineScaleSet&gt;&#xA;    interface IHasParent&lt;IVirtualMachineScaleSet&gt;&#xA;    interface IRefreshable&lt;IVirtualMachineScaleSetVM&gt;&#xA;    interface IHasInner&lt;VirtualMachineScaleSetVMInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="41c8d-101">Azure の仮想マシン スケールで仮想マシン インスタンスの変更できないクライアント側の表現を設定します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-101">An immutable client-side representation of a virtual machine instance in an Azure virtual machine scale set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AdministratorUserName">
      <MemberSignature Language="C#" Value="public string AdministratorUserName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdministratorUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.AdministratorUserName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AdministratorUserName As String" />
      <MemberSignature Language="F#" Value="member this.AdministratorUserName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.AdministratorUserName" />
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
            <span data-ttu-id="41c8d-102">管理ユーザーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-102">Gets the name of the admin user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilitySetId">
      <MemberSignature Language="C#" Value="public string AvailabilitySetId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AvailabilitySetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.AvailabilitySetId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilitySetId As String" />
      <MemberSignature Language="F#" Value="member this.AvailabilitySetId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.AvailabilitySetId" />
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
            <span data-ttu-id="41c8d-103">リソースのセットにこのバーチャル マシン インスタンスが属する可用性の ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-103">Gets the resource ID of the availability set that this virtual machine instance belongs to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BootDiagnosticEnabled">
      <MemberSignature Language="C#" Value="public bool BootDiagnosticEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool BootDiagnosticEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.BootDiagnosticEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BootDiagnosticEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.BootDiagnosticEnabled : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.BootDiagnosticEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-104">True の場合、有効な場合は false がそれ以外の場合は、ブート診断を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-104">Gets true if the boot diagnostic is enabled, false otherwise.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BootDiagnosticStorageAccountUri">
      <MemberSignature Language="C#" Value="public string BootDiagnosticStorageAccountUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BootDiagnosticStorageAccountUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.BootDiagnosticStorageAccountUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BootDiagnosticStorageAccountUri As String" />
      <MemberSignature Language="F#" Value="member this.BootDiagnosticStorageAccountUri : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.BootDiagnosticStorageAccountUri" />
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
            <span data-ttu-id="41c8d-105">ブート診断ログを格納するストレージ アカウントへの URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-105">Gets the URI to the storage account storing boot diagnostics log.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputerName">
      <MemberSignature Language="C#" Value="public string ComputerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComputerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.ComputerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputerName As String" />
      <MemberSignature Language="F#" Value="member this.ComputerName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.ComputerName" />
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
            <span data-ttu-id="41c8d-106">VM スケール セットのプレフィックスを持つ仮想マシン インスタンスのコンピューター名を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-106">Gets the virtual machine instance computer name with the VM scale set prefix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;int,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk&gt; DataDisks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;int32, class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataDisks As IReadOnlyDictionary(Of Integer, IVirtualMachineDataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IReadOnlyDictionary&lt;int, Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.Int32,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-107">LUN でインデックス付けされた、この仮想マシン インスタンスに関連付けられている管理対象のデータ ディスクを取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-107">Gets the managed data disks associated with this virtual machine instance, indexed by LUN.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deallocate">
      <MemberSignature Language="C#" Value="public void Deallocate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Deallocate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Deallocate" />
      <MemberSignature Language="VB.NET" Value="Public Sub Deallocate ()" />
      <MemberSignature Language="F#" Value="abstract member Deallocate : unit -&gt; unit" Usage="iVirtualMachineScaleSetVM.Deallocate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-108">シャット ダウン、仮想マシン インスタンスと関連付けられているコンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-108">Shuts down the virtual machine instance and releases the associated compute resources.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeallocateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeallocateAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeallocateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.DeallocateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeallocateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSetVM.DeallocateAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="41c8d-109">シャット ダウン、仮想マシン インスタンスと関連付けられているコンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-109">Shuts down the virtual machine instance and releases the associated compute resources.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="41c8d-110">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="41c8d-110">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="41c8d-111">Deallocate アクションに観測可能なオブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="41c8d-111">The observable to the deallocate action.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Delete" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete ()" />
      <MemberSignature Language="F#" Value="abstract member Delete : unit -&gt; unit" Usage="iVirtualMachineScaleSetVM.Delete " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-112">仮想マシン インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-112">Deletes the virtual machine instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSetVM.DeleteAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="41c8d-113">仮想マシン インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-113">Deletes the virtual machine instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="41c8d-114">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="41c8d-114">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="41c8d-115">削除アクションを監視します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-115">The observable to the delete action.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile DiagnosticsProfile { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile DiagnosticsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.DiagnosticsProfile" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiagnosticsProfile As DiagnosticsProfile" />
      <MemberSignature Language="F#" Value="member this.DiagnosticsProfile : Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.DiagnosticsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-116">仮想マシン インスタンスの診断プロファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-116">Gets the diagnostics profile of the virtual machine instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Extensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMInstanceExtension&gt; Extensions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMInstanceExtension&gt; Extensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Extensions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Extensions As IReadOnlyDictionary(Of String, IVirtualMachineScaleSetVMInstanceExtension)" />
      <MemberSignature Language="F#" Value="member this.Extensions : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMInstanceExtension&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Extensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMInstanceExtension&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-117">名前によってインデックス付けされた、仮想マシン インスタンスに関連付けられている拡張機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-117">Gets the extensions associated with the virtual machine instance, indexed by name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface GetNetworkInterface (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface GetNetworkInterface(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.GetNetworkInterface(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNetworkInterface (name As String) As IVirtualMachineScaleSetNetworkInterface" />
      <MemberSignature Language="F#" Value="abstract member GetNetworkInterface : string -&gt; Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface" Usage="iVirtualMachineScaleSetVM.GetNetworkInterface name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="41c8d-118">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="41c8d-118">The name of the network interface.</span></span></param>
        <summary>
            <span data-ttu-id="41c8d-119">この仮想マシン インスタンスに関連付けられているネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-119">Gets a network interface associated with this virtual machine instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="41c8d-120">ネットワーク インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="41c8d-120">The network interface.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetOSCustomImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage GetOSCustomImage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage GetOSCustomImage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.GetOSCustomImage" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOSCustomImage () As IVirtualMachineCustomImage" />
      <MemberSignature Language="F#" Value="abstract member GetOSCustomImage : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage" Usage="iVirtualMachineScaleSetVM.GetOSCustomImage " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            <span data-ttu-id="41c8d-121">仮想マシン インスタンスのオペレーティング システムの基になっているカスタム イメージ、null がそれ以外の場合返されます。</span><span class="sxs-lookup"><span data-stu-id="41c8d-121">The custom image that the virtual machine instance operating system is based on, null be returned otherwise.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetOSPlatformImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage GetOSPlatformImage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage GetOSPlatformImage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.GetOSPlatformImage" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOSPlatformImage () As IVirtualMachineImage" />
      <MemberSignature Language="F#" Value="abstract member GetOSPlatformImage : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage" Usage="iVirtualMachineScaleSetVM.GetOSPlatformImage " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            <span data-ttu-id="41c8d-122">仮想マシン インスタンスのオペレーティング システムの基になっているプラットフォーム イメージ、null がそれ以外の場合返されます。</span><span class="sxs-lookup"><span data-stu-id="41c8d-122">The platform image that the virtual machine instance operating system is based on, null be returned otherwise.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="InstanceId">
      <MemberSignature Language="C#" Value="public string InstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.InstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceId As String" />
      <MemberSignature Language="F#" Value="member this.InstanceId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.InstanceId" />
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
            <span data-ttu-id="41c8d-123">この仮想マシン インスタンスに割り当てられているインスタンス ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-123">Gets the instance ID assigned to this virtual machine instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceView">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView InstanceView { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView InstanceView" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.InstanceView" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceView As VirtualMachineInstanceView" />
      <MemberSignature Language="F#" Value="member this.InstanceView : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.InstanceView" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-124">仮想マシン インスタンスのインスタンス ビューを取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-124">Gets the instance view of the virtual machine instance.</span></span>
            <span data-ttu-id="41c8d-125">最新のインスタンス ビューの使用を取得する<code>refreshInstanceView()</code>です。</span><span class="sxs-lookup"><span data-stu-id="41c8d-125">To get the latest instance view use <code>refreshInstanceView()</code>.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsLatestScaleSetUpdateApplied">
      <MemberSignature Language="C#" Value="public bool IsLatestScaleSetUpdateApplied { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsLatestScaleSetUpdateApplied" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsLatestScaleSetUpdateApplied" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsLatestScaleSetUpdateApplied As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsLatestScaleSetUpdateApplied : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsLatestScaleSetUpdateApplied" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-126">True の場合、最新のスケール セットの仮想マシン インスタンスに変更が適用されるモデルを取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-126">Gets true if the latest scale set model changes are applied to the virtual machine instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsLinuxPasswordAuthenticationEnabled">
      <MemberSignature Language="C#" Value="public bool IsLinuxPasswordAuthenticationEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsLinuxPasswordAuthenticationEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsLinuxPasswordAuthenticationEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsLinuxPasswordAuthenticationEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsLinuxPasswordAuthenticationEnabled : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsLinuxPasswordAuthenticationEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-127">Linux 仮想マシンが、パスワード ベースのログインが有効になっている場合は false それ以外の場合は true を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-127">Gets true if this is a Linux virtual machine and password based login is enabled, false otherwise.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsManagedDiskEnabled">
      <MemberSignature Language="C#" Value="public bool IsManagedDiskEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsManagedDiskEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsManagedDiskEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsManagedDiskEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsManagedDiskEnabled : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsManagedDiskEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-128">管理対象ディスクをバーチャル マシンのディスク (os、データ) を使用する場合は true を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-128">Gets true if managed disk is used for the virtual machine's disks (os, data).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOSBasedOnCustomImage">
      <MemberSignature Language="C#" Value="public bool IsOSBasedOnCustomImage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsOSBasedOnCustomImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsOSBasedOnCustomImage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsOSBasedOnCustomImage As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOSBasedOnCustomImage : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsOSBasedOnCustomImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-129">仮想マシン インスタンスのオペレーティング システムは、カスタム イメージに基づいている場合は true を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-129">Gets true if the operating system of the virtual machine instance is based on custom image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOSBasedOnPlatformImage">
      <MemberSignature Language="C#" Value="public bool IsOSBasedOnPlatformImage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsOSBasedOnPlatformImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsOSBasedOnPlatformImage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsOSBasedOnPlatformImage As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOSBasedOnPlatformImage : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsOSBasedOnPlatformImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-130">仮想マシン インスタンスのオペレーティング システムがプラットフォーム イメージに基づいている場合は true を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-130">Gets true if the operating system of the virtual machine instance is based on platform image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOSBasedOnStoredImage">
      <MemberSignature Language="C#" Value="public bool IsOSBasedOnStoredImage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsOSBasedOnStoredImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsOSBasedOnStoredImage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsOSBasedOnStoredImage As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOSBasedOnStoredImage : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsOSBasedOnStoredImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-131">仮想マシン インスタンスのオペレーティング システムは、保存されたイメージに基づいている場合は true を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-131">Gets true if the operating system of the virtual machine instance is based on stored image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsWindowsAutoUpdateEnabled">
      <MemberSignature Language="C#" Value="public bool IsWindowsAutoUpdateEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsWindowsAutoUpdateEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsWindowsAutoUpdateEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsWindowsAutoUpdateEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsWindowsAutoUpdateEnabled : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsWindowsAutoUpdateEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-132">これは、Windows 仮想マシンと、自動更新が false で、それ以外の場合になっている場合は true を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-132">Gets true if this is a Windows virtual machine and automatic update is turned on, false otherwise.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsWindowsVMAgentProvisioned">
      <MemberSignature Language="C#" Value="public bool IsWindowsVMAgentProvisioned { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsWindowsVMAgentProvisioned" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsWindowsVMAgentProvisioned" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsWindowsVMAgentProvisioned As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsWindowsVMAgentProvisioned : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsWindowsVMAgentProvisioned" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-133">Windows 仮想マシンが、VM エージェントはプロビジョニング済みの場合は false をそれ以外の場合は true を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-133">Gets true if this is a Windows virtual machine and VM agent is provisioned, false otherwise.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNetworkInterfaces">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt; ListNetworkInterfaces ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt; ListNetworkInterfaces() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.ListNetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public Function ListNetworkInterfaces () As IEnumerable(Of IVirtualMachineScaleSetNetworkInterface)" />
      <MemberSignature Language="F#" Value="abstract member ListNetworkInterfaces : unit -&gt; seq&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;" Usage="iVirtualMachineScaleSetVM.ListNetworkInterfaces " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="41c8d-134">この仮想マシン インスタンスに関連付けられているネットワーク インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="41c8d-134">The network interfaces associated with this virtual machine instance.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaceIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; NetworkInterfaceIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; NetworkInterfaceIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.NetworkInterfaceIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkInterfaceIds As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceIds : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.NetworkInterfaceIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-135">仮想マシン インスタンスに関連付けられているネットワーク インターフェイスのリソース ID の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-135">Gets the list of resource ID of network interface associated with the virtual machine instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskCachingType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes OSDiskCachingType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes OSDiskCachingType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSDiskCachingType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskCachingType As CachingTypes" />
      <MemberSignature Language="F#" Value="member this.OSDiskCachingType : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSDiskCachingType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-136">オペレーティング システム ディスクのキャッシュの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-136">Gets the caching type of the operating system disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskId">
      <MemberSignature Language="C#" Value="public string OSDiskId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OSDiskId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSDiskId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskId As String" />
      <MemberSignature Language="F#" Value="member this.OSDiskId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSDiskId" />
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
            <span data-ttu-id="41c8d-137">OS ディスクのバックアップを作成、管理対象ディスクのリソース ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-137">Gets resource ID of the managed disk backing OS disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskName">
      <MemberSignature Language="C#" Value="public string OSDiskName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OSDiskName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSDiskName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskName As String" />
      <MemberSignature Language="F#" Value="member this.OSDiskName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSDiskName" />
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
            <span data-ttu-id="41c8d-138">オペレーティング システム ディスクの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-138">Gets the name of the operating system disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskSizeInGB">
      <MemberSignature Language="C#" Value="public int OSDiskSizeInGB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 OSDiskSizeInGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSDiskSizeInGB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskSizeInGB As Integer" />
      <MemberSignature Language="F#" Value="member this.OSDiskSizeInGB : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSDiskSizeInGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-139">オペレーティング システム ディスクのサイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-139">Gets the size of the operating system disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile OSProfile { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile OSProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSProfile" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSProfile As OSProfile" />
      <MemberSignature Language="F#" Value="member this.OSProfile : Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-140">仮想マシン インスタンスのオペレーティング システム プロファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-140">Gets the operating system profile of an virtual machine instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OSType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OSType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSType As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="member this.OSType : Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSType" />
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
            <span data-ttu-id="41c8d-141">オペレーティング システムの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-141">Gets the operating system type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSUnmanagedDiskVhdUri">
      <MemberSignature Language="C#" Value="public string OSUnmanagedDiskVhdUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OSUnmanagedDiskVhdUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSUnmanagedDiskVhdUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSUnmanagedDiskVhdUri As String" />
      <MemberSignature Language="F#" Value="member this.OSUnmanagedDiskVhdUri : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSUnmanagedDiskVhdUri" />
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
            <span data-ttu-id="41c8d-142">オペレーティング システム ディスクへの VHD URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-142">Gets VHD URI to the operating system disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference PlatformImageReference { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference PlatformImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.PlatformImageReference" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PlatformImageReference As ImageReference" />
      <MemberSignature Language="F#" Value="member this.PlatformImageReference : Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.PlatformImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-143">プラットフォーム イメージへの参照を取得する仮想マシン インスタンスのオペレーティング システムがに基づいて、オペレーティング システムは、カスタム イメージに基づいている場合、null が返されます。</span><span class="sxs-lookup"><span data-stu-id="41c8d-143">Gets reference to the platform image that the virtual machine instance operating system is based on, null will be returned if the operating system is based on custom image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOff">
      <MemberSignature Language="C#" Value="public void PowerOff ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void PowerOff() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.PowerOff" />
      <MemberSignature Language="VB.NET" Value="Public Sub PowerOff ()" />
      <MemberSignature Language="F#" Value="abstract member PowerOff : unit -&gt; unit" Usage="iVirtualMachineScaleSetVM.PowerOff " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-144">仮想マシン インスタンスを停止します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-144">Stops the virtual machine instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOffAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PowerOffAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PowerOffAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.PowerOffAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PowerOffAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSetVM.PowerOffAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="41c8d-145">仮想マシン インスタンスを停止します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-145">Stops the virtual machine instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="41c8d-146">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="41c8d-146">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="41c8d-147">電源オフ操作を監視します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-147">The observable to the poweroff action.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="PowerState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.PowerState PowerState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.PowerState PowerState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.PowerState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PowerState As PowerState" />
      <MemberSignature Language="F#" Value="member this.PowerState : Microsoft.Azure.Management.Compute.Fluent.PowerState" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.PowerState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.PowerState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-148">仮想マシン インスタンスの電源状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-148">Gets the power state of the virtual machine instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryNetworkInterfaceId">
      <MemberSignature Language="C#" Value="public string PrimaryNetworkInterfaceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryNetworkInterfaceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.PrimaryNetworkInterfaceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryNetworkInterfaceId As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryNetworkInterfaceId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.PrimaryNetworkInterfaceId" />
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
            <span data-ttu-id="41c8d-149">仮想マシン インスタンスに関連付けられているプライマリ ネットワーク インターフェイスのリソース ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-149">Gets resource ID of primary network interface associated with virtual machine instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshInstanceView">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView RefreshInstanceView ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView RefreshInstanceView() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.RefreshInstanceView" />
      <MemberSignature Language="VB.NET" Value="Public Function RefreshInstanceView () As VirtualMachineInstanceView" />
      <MemberSignature Language="F#" Value="abstract member RefreshInstanceView : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView" Usage="iVirtualMachineScaleSetVM.RefreshInstanceView " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-150">インスタンス ビューを更新します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-150">Refreshes the instance view.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="41c8d-151">インスタンス ビューです。</span><span class="sxs-lookup"><span data-stu-id="41c8d-151">The instance view.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Reimage">
      <MemberSignature Language="C#" Value="public void Reimage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Reimage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Reimage" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reimage ()" />
      <MemberSignature Language="F#" Value="abstract member Reimage : unit -&gt; unit" Usage="iVirtualMachineScaleSetVM.Reimage " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-152">仮想マシン インスタンスでインストールされたオペレーティング システムのバージョンを更新します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-152">Updates the version of the installed operating system in the virtual machine instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReimageAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ReimageAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.ReimageAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReimageAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSetVM.ReimageAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="41c8d-153">仮想マシン インスタンスでインストールされたオペレーティング システムのバージョンを更新します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-153">Updates the version of the installed operating system in the virtual machine instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="41c8d-154">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="41c8d-154">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="41c8d-155">再イメージ化アクションに観測可能なオブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="41c8d-155">The observable to the reimage action.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Restart">
      <MemberSignature Language="C#" Value="public void Restart ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Restart() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Restart" />
      <MemberSignature Language="VB.NET" Value="Public Sub Restart ()" />
      <MemberSignature Language="F#" Value="abstract member Restart : unit -&gt; unit" Usage="iVirtualMachineScaleSetVM.Restart " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-156">仮想マシン インスタンスを再起動します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-156">Restarts the virtual machine instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.RestartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSetVM.RestartAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="41c8d-157">仮想マシン インスタンスを再起動します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-157">Restarts the virtual machine instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="41c8d-158">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="41c8d-158">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="41c8d-159">再起動の動作を観察可能なオブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="41c8d-159">The observable to the restart action.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes Size { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Size" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Size As VirtualMachineSizeTypes" />
      <MemberSignature Language="F#" Value="member this.Size : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Size" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-160">仮想マシン インスタンスのサイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-160">Gets virtual machine instance size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.Sku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Fluent.Models.Sku" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-161">SKU を取得する仮想マシン インスタンスの親の仮想マシン スケール セットの作成中に使用される SKU になります。</span><span class="sxs-lookup"><span data-stu-id="41c8d-161">Gets the SKU of the virtual machine instance, this will be SKU used while creating the parent virtual machine scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public void Start ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Start() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Start" />
      <MemberSignature Language="VB.NET" Value="Public Sub Start ()" />
      <MemberSignature Language="F#" Value="abstract member Start : unit -&gt; unit" Usage="iVirtualMachineScaleSetVM.Start " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-162">仮想マシン インスタンスを開始します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-162">Starts the virtual machine instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.StartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSetVM.StartAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="41c8d-163">仮想マシン インスタンスを開始します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-163">Starts the virtual machine instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="41c8d-164">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="41c8d-164">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="41c8d-165">開始アクションを監視します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-165">The observable to the start action.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="StorageProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile StorageProfile { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile StorageProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.StorageProfile" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageProfile As StorageProfile" />
      <MemberSignature Language="F#" Value="member this.StorageProfile : Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.StorageProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-166">仮想マシン インスタンスのストレージ プロファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-166">Gets the storage profile of the virtual machine instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredImageUnmanagedVhdUri">
      <MemberSignature Language="C#" Value="public string StoredImageUnmanagedVhdUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoredImageUnmanagedVhdUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.StoredImageUnmanagedVhdUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredImageUnmanagedVhdUri As String" />
      <MemberSignature Language="F#" Value="member this.StoredImageUnmanagedVhdUri : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.StoredImageUnmanagedVhdUri" />
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
            <span data-ttu-id="41c8d-167">仮想マシン インスタンスのオペレーティング システムがに基づいて、オペレーティング システムがプラットフォーム イメージに基づいている場合、null が返されますことは、カスタム イメージの VHD URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-167">Gets VHD URI of the custom image that the virtual machine instance operating system is based on, null will be returned if the operating system is based on platform image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnmanagedDataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;int,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk&gt; UnmanagedDataDisks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;int32, class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk&gt; UnmanagedDataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.UnmanagedDataDisks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnmanagedDataDisks As IReadOnlyDictionary(Of Integer, IVirtualMachineUnmanagedDataDisk)" />
      <MemberSignature Language="F#" Value="member this.UnmanagedDataDisks : System.Collections.Generic.IReadOnlyDictionary&lt;int, Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.UnmanagedDataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.Int32,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41c8d-168">LUN でインデックス付けされた、この仮想マシン インスタンスに関連付けられたアンマネージ データ ディスクを取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-168">Gets the unmanaged data disks associated with this virtual machine instance, indexed by LUN.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsTimeZone">
      <MemberSignature Language="C#" Value="public string WindowsTimeZone { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WindowsTimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.WindowsTimeZone" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WindowsTimeZone As String" />
      <MemberSignature Language="F#" Value="member this.WindowsTimeZone : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.WindowsTimeZone" />
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
            <span data-ttu-id="41c8d-169">Windows 仮想マシンのタイム ゾーンを取得します。</span><span class="sxs-lookup"><span data-stu-id="41c8d-169">Gets the time zone of the Windows virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>