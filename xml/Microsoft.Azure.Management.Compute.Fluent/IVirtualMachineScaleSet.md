<Type Name="IVirtualMachineScaleSet" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineScaleSet : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryLoadBalancer&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineScaleSet implements class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Compute.Fluent.IComputeManager, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryLoadBalancer&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineScaleSet&#xA;Implements IBeta, IGroupableResource(Of IComputeManager, VirtualMachineScaleSetInner), IHasInner(Of VirtualMachineScaleSetInner), IHasManager(Of IComputeManager), IRefreshable(Of IVirtualMachineScaleSet), IUpdatable(Of IWithPrimaryLoadBalancer), IVirtualMachineScaleSetBeta" />
  <TypeSignature Language="F#" Value="type IVirtualMachineScaleSet = interface&#xA;    interface IGroupableResource&lt;IComputeManager, VirtualMachineScaleSetInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IComputeManager&gt;&#xA;    interface IHasInner&lt;VirtualMachineScaleSetInner&gt;&#xA;    interface IRefreshable&lt;IVirtualMachineScaleSet&gt;&#xA;    interface IUpdatable&lt;IWithPrimaryLoadBalancer&gt;&#xA;    interface IVirtualMachineScaleSetBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryLoadBalancer&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="2989f-101">Azure の仮想マシン スケールの変更できないクライアント側表現を設定します。</span><span class="sxs-lookup"><span data-stu-id="2989f-101">An immutable client-side representation of an Azure virtual machine scale set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public int Capacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Capacity As Integer" />
      <MemberSignature Language="F#" Value="member this.Capacity : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Capacity" />
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
            <span data-ttu-id="2989f-102">スケール セット内の仮想マシン インスタンスの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-102">Gets the number of virtual machine instances in the scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputerNamePrefix">
      <MemberSignature Language="C#" Value="public string ComputerNamePrefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComputerNamePrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ComputerNamePrefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputerNamePrefix As String" />
      <MemberSignature Language="F#" Value="member this.ComputerNamePrefix : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ComputerNamePrefix" />
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
            <span data-ttu-id="2989f-103">スケール セット内の仮想マシン名のプレフィックスを取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-103">Gets the name prefix of the virtual machines in the scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deallocate">
      <MemberSignature Language="C#" Value="public void Deallocate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Deallocate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Deallocate" />
      <MemberSignature Language="VB.NET" Value="Public Sub Deallocate ()" />
      <MemberSignature Language="F#" Value="abstract member Deallocate : unit -&gt; unit" Usage="iVirtualMachineScaleSet.Deallocate " />
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
            <span data-ttu-id="2989f-104">スケール セット内の仮想マシンをシャット ダウンし、コンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="2989f-104">Shuts down the virtual machines in the scale set and releases its compute resources.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeallocateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeallocateAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeallocateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.DeallocateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeallocateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSet.DeallocateAsync cancellationToken" />
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
            <span data-ttu-id="2989f-105">スケール セット内の仮想マシンをシャット ダウンし、非同期的に、コンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="2989f-105">Shuts down the virtual machines in the scale set and releases its compute resources asynchronously.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="2989f-106">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="2989f-106">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="2989f-107">この呼び出しの遅延の計算の表現。</span><span class="sxs-lookup"><span data-stu-id="2989f-107">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Extensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension&gt; Extensions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension&gt; Extensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Extensions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Extensions As IReadOnlyDictionary(Of String, IVirtualMachineScaleSetExtension)" />
      <MemberSignature Language="F#" Value="member this.Extensions : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Extensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2989f-108">スケール セット内の仮想マシンにアタッチされている拡張機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-108">Gets the extensions attached to the virtual machines in the scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNetworkInterfaceByInstanceId">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface GetNetworkInterfaceByInstanceId (string instanceId, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface GetNetworkInterfaceByInstanceId(string instanceId, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.GetNetworkInterfaceByInstanceId(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNetworkInterfaceByInstanceId (instanceId As String, name As String) As IVirtualMachineScaleSetNetworkInterface" />
      <MemberSignature Language="F#" Value="abstract member GetNetworkInterfaceByInstanceId : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface" Usage="iVirtualMachineScaleSet.GetNetworkInterfaceByInstanceId (instanceId, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="instanceId"><span data-ttu-id="2989f-109">仮想マシン スケール セット vm インスタンスの id。</span><span class="sxs-lookup"><span data-stu-id="2989f-109">The virtual machine scale set vm instance ID.</span></span></param>
        <param name="name"><span data-ttu-id="2989f-110">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="2989f-110">The network interface name.</span></span></param>
        <summary>
            <span data-ttu-id="2989f-111">仮想マシン スケール セット インスタンスに関連付けられているネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-111">Gets a network interface associated with a virtual machine scale set instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2989f-112">ネットワーク インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="2989f-112">The network interface.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetPrimaryInternalLoadBalancer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancer GetPrimaryInternalLoadBalancer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer GetPrimaryInternalLoadBalancer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.GetPrimaryInternalLoadBalancer" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPrimaryInternalLoadBalancer () As ILoadBalancer" />
      <MemberSignature Language="F#" Value="abstract member GetPrimaryInternalLoadBalancer : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" Usage="iVirtualMachineScaleSet.GetPrimaryInternalLoadBalancer " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancer</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <throws><span data-ttu-id="2989f-113">IOException IO の例外。</span><span class="sxs-lookup"><span data-stu-id="2989f-113">IOException the IO exception.</span></span></throws>
        <return>
            <span data-ttu-id="2989f-114">スケールには、仮想マシンのプライマリ ネットワーク インターフェイスに関連付けられている内部ロード バランサーを設定します。</span><span class="sxs-lookup"><span data-stu-id="2989f-114">The internal load balancer associated with the primary network interface of the virtual machines in the scale set.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetPrimaryInternetFacingLoadBalancer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancer GetPrimaryInternetFacingLoadBalancer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer GetPrimaryInternetFacingLoadBalancer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.GetPrimaryInternetFacingLoadBalancer" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPrimaryInternetFacingLoadBalancer () As ILoadBalancer" />
      <MemberSignature Language="F#" Value="abstract member GetPrimaryInternetFacingLoadBalancer : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" Usage="iVirtualMachineScaleSet.GetPrimaryInternetFacingLoadBalancer " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancer</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <throws><span data-ttu-id="2989f-115">IOException IO の例外。</span><span class="sxs-lookup"><span data-stu-id="2989f-115">IOException the IO exception.</span></span></throws>
        <return>
            <span data-ttu-id="2989f-116">スケールには、仮想マシンのプライマリ ネットワーク インターフェイスに関連付けられたインターネットに接続するロード バランサーを設定します。</span><span class="sxs-lookup"><span data-stu-id="2989f-116">The Internet-facing load balancer associated with the primary network interface of the virtual machines in the scale set.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetwork GetPrimaryNetwork ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.INetwork GetPrimaryNetwork() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.GetPrimaryNetwork" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPrimaryNetwork () As INetwork" />
      <MemberSignature Language="F#" Value="abstract member GetPrimaryNetwork : unit -&gt; Microsoft.Azure.Management.Network.Fluent.INetwork" Usage="iVirtualMachineScaleSet.GetPrimaryNetwork " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetwork</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsManagedDiskEnabled">
      <MemberSignature Language="C#" Value="public bool IsManagedDiskEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsManagedDiskEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.IsManagedDiskEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsManagedDiskEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsManagedDiskEnabled : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.IsManagedDiskEnabled" />
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
            <span data-ttu-id="2989f-117">仮想マシン スケール セットのディスク (os、データ) ため管理されているディスクが使用される場合は true を取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-117">Gets true if managed disk is used for the virtual machine scale set's disks (os, data).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSkus">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetSku&gt; ListAvailableSkus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetSku&gt; ListAvailableSkus() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ListAvailableSkus" />
      <MemberSignature Language="VB.NET" Value="Public Function ListAvailableSkus () As IEnumerable(Of IVirtualMachineScaleSetSku)" />
      <MemberSignature Language="F#" Value="abstract member ListAvailableSkus : unit -&gt; seq&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetSku&gt;" Usage="iVirtualMachineScaleSet.ListAvailableSkus " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetSku&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            <span data-ttu-id="2989f-118">特定の SKU に許可されている最小値と最大の仮想マシン インスタンスを含む、仮想マシン スケール セットの使用可能な Sku をします。</span><span class="sxs-lookup"><span data-stu-id="2989f-118">Available SKUs for the virtual machine scale set, including the minimum and maximum virtual machine instances allowed for a particular SKU.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListNetworkInterfaces">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt; ListNetworkInterfaces ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt; ListNetworkInterfaces() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ListNetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public Function ListNetworkInterfaces () As IEnumerable(Of IVirtualMachineScaleSetNetworkInterface)" />
      <MemberSignature Language="F#" Value="abstract member ListNetworkInterfaces : unit -&gt; seq&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;" Usage="iVirtualMachineScaleSet.ListNetworkInterfaces " />
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
        <return><span data-ttu-id="2989f-119">スケール セット内のすべての仮想マシン インスタンスに関連付けられているネットワーク インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="2989f-119">The network interfaces associated with all virtual machine instances in a scale set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ListNetworkInterfacesByInstanceId">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt; ListNetworkInterfacesByInstanceId (string virtualMachineInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt; ListNetworkInterfacesByInstanceId(string virtualMachineInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ListNetworkInterfacesByInstanceId(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListNetworkInterfacesByInstanceId (virtualMachineInstanceId As String) As IEnumerable(Of IVirtualMachineScaleSetNetworkInterface)" />
      <MemberSignature Language="F#" Value="abstract member ListNetworkInterfacesByInstanceId : string -&gt; seq&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;" Usage="iVirtualMachineScaleSet.ListNetworkInterfacesByInstanceId virtualMachineInstanceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="virtualMachineInstanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="virtualMachineInstanceId"><span data-ttu-id="2989f-120">インスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="2989f-120">The instance ID.</span></span></param>
        <summary>
            <span data-ttu-id="2989f-121">スケール セット内の特定の仮想マシン インスタンスに関連付けられているネットワーク インターフェイスを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="2989f-121">Lists the network interface associated with a specific virtual machine instance in the scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2989f-122">ネットワーク インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="2989f-122">The network interfaces.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ListPrimaryInternalLoadBalancerBackends">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt; ListPrimaryInternalLoadBalancerBackends ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt; ListPrimaryInternalLoadBalancerBackends() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ListPrimaryInternalLoadBalancerBackends" />
      <MemberSignature Language="VB.NET" Value="Public Function ListPrimaryInternalLoadBalancerBackends () As IReadOnlyDictionary(Of String, ILoadBalancerBackend)" />
      <MemberSignature Language="F#" Value="abstract member ListPrimaryInternalLoadBalancerBackends : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt;" Usage="iVirtualMachineScaleSet.ListPrimaryInternalLoadBalancerBackends " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <throws><span data-ttu-id="2989f-123">IOException IO の例外。</span><span class="sxs-lookup"><span data-stu-id="2989f-123">IOException the IO exception.</span></span></throws>
        <return>
            <span data-ttu-id="2989f-124">仮想マシン スケール セット内のプライマリ ネットワーク インターフェイスに関連付けられている内部ロード バランサーのバックエンドです。</span><span class="sxs-lookup"><span data-stu-id="2989f-124">The internal load balancer's backends associated with the primary network interface of the virtual machines in the scale set.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListPrimaryInternalLoadBalancerInboundNatPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt; ListPrimaryInternalLoadBalancerInboundNatPools ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt; ListPrimaryInternalLoadBalancerInboundNatPools() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ListPrimaryInternalLoadBalancerInboundNatPools" />
      <MemberSignature Language="VB.NET" Value="Public Function ListPrimaryInternalLoadBalancerInboundNatPools () As IReadOnlyDictionary(Of String, ILoadBalancerInboundNatPool)" />
      <MemberSignature Language="F#" Value="abstract member ListPrimaryInternalLoadBalancerInboundNatPools : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt;" Usage="iVirtualMachineScaleSet.ListPrimaryInternalLoadBalancerInboundNatPools " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <throws><span data-ttu-id="2989f-125">IOException IO の例外。</span><span class="sxs-lookup"><span data-stu-id="2989f-125">IOException the IO exception.</span></span></throws>
        <return>
            <span data-ttu-id="2989f-126">存在する場合は、仮想マシン スケール セット内のプライマリ ネットワーク インターフェイスに関連付けられている内部ロード バランサーの着信 NAT プールします。</span><span class="sxs-lookup"><span data-stu-id="2989f-126">The inbound NAT pools of the internal load balancer associated with the primary network interface of the virtual machines in the scale set, if any.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListPrimaryInternetFacingLoadBalancerBackends">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt; ListPrimaryInternetFacingLoadBalancerBackends ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt; ListPrimaryInternetFacingLoadBalancerBackends() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ListPrimaryInternetFacingLoadBalancerBackends" />
      <MemberSignature Language="VB.NET" Value="Public Function ListPrimaryInternetFacingLoadBalancerBackends () As IReadOnlyDictionary(Of String, ILoadBalancerBackend)" />
      <MemberSignature Language="F#" Value="abstract member ListPrimaryInternetFacingLoadBalancerBackends : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt;" Usage="iVirtualMachineScaleSet.ListPrimaryInternetFacingLoadBalancerBackends " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <throws><span data-ttu-id="2989f-127">IOException IO の例外。</span><span class="sxs-lookup"><span data-stu-id="2989f-127">IOException the IO exception.</span></span></throws>
        <return>
            <span data-ttu-id="2989f-128">スケールには、仮想マシンのプライマリ ネットワーク インターフェイスに関連付けられたインターネットに接続するロード バランサーのバックエンドを設定します。</span><span class="sxs-lookup"><span data-stu-id="2989f-128">The Internet-facing load balancer's backends associated with the primary network interface of the virtual machines in the scale set.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListPrimaryInternetFacingLoadBalancerInboundNatPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt; ListPrimaryInternetFacingLoadBalancerInboundNatPools ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt; ListPrimaryInternetFacingLoadBalancerInboundNatPools() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ListPrimaryInternetFacingLoadBalancerInboundNatPools" />
      <MemberSignature Language="VB.NET" Value="Public Function ListPrimaryInternetFacingLoadBalancerInboundNatPools () As IReadOnlyDictionary(Of String, ILoadBalancerInboundNatPool)" />
      <MemberSignature Language="F#" Value="abstract member ListPrimaryInternetFacingLoadBalancerInboundNatPools : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt;" Usage="iVirtualMachineScaleSet.ListPrimaryInternetFacingLoadBalancerInboundNatPools " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <throws><span data-ttu-id="2989f-129">IOException IO の例外。</span><span class="sxs-lookup"><span data-stu-id="2989f-129">IOException the IO exception.</span></span></throws>
        <return>
            <span data-ttu-id="2989f-130">インターネットに接続されたはロード バランサーの着信 NAT プールが仮想マシン スケール セット内のプライマリ ネットワーク インターフェイスに関連付けられたです。</span><span class="sxs-lookup"><span data-stu-id="2989f-130">The Internet-facing load balancer's inbound NAT pool associated with the primary network interface of the virtual machines in the scale set.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="NetworkProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetNetworkProfile NetworkProfile { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetNetworkProfile NetworkProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.NetworkProfile" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkProfile As VirtualMachineScaleSetNetworkProfile" />
      <MemberSignature Language="F#" Value="member this.NetworkProfile : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetNetworkProfile" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.NetworkProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetNetworkProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2989f-131">ネットワーク プロファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-131">Gets the network profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskCachingType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes OSDiskCachingType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes OSDiskCachingType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.OSDiskCachingType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskCachingType As CachingTypes" />
      <MemberSignature Language="F#" Value="member this.OSDiskCachingType : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.OSDiskCachingType" />
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
            <span data-ttu-id="2989f-132">キャッシュの種類をオペレーティング システム ディスクを取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-132">Gets the operating system disk caching type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskName">
      <MemberSignature Language="C#" Value="public string OSDiskName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OSDiskName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.OSDiskName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskName As String" />
      <MemberSignature Language="F#" Value="member this.OSDiskName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.OSDiskName" />
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
            <span data-ttu-id="2989f-133">スケール セット内の仮想マシンの OS ディスクの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-133">Gets the name of the OS disk of virtual machines in the scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OSType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OSType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.OSType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSType As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="member this.OSType : Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.OSType" />
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
            <span data-ttu-id="2989f-134">スケール セット内の仮想マシンのオペレーティング システムを取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-134">Gets the operating system of the virtual machines in the scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OverProvisionEnabled">
      <MemberSignature Language="C#" Value="public bool OverProvisionEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool OverProvisionEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.OverProvisionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OverProvisionEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.OverProvisionEnabled : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.OverProvisionEnabled" />
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
            <span data-ttu-id="2989f-135">経由でのプロビジョニングが有効な場合、仮想マシンは、false のそれ以外の場合は true。 を取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-135">Gets true if over provision is enabled for the virtual machines, false otherwise.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOff">
      <MemberSignature Language="C#" Value="public void PowerOff ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void PowerOff() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.PowerOff" />
      <MemberSignature Language="VB.NET" Value="Public Sub PowerOff ()" />
      <MemberSignature Language="F#" Value="abstract member PowerOff : unit -&gt; unit" Usage="iVirtualMachineScaleSet.PowerOff " />
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
            <span data-ttu-id="2989f-136">電源が切れる (停止) の仮想マシンのスケールを設定します。</span><span class="sxs-lookup"><span data-stu-id="2989f-136">Powers off (stops) the virtual machines in the scale set.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOffAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PowerOffAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PowerOffAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.PowerOffAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PowerOffAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSet.PowerOffAsync cancellationToken" />
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
            <span data-ttu-id="2989f-137">電源オフ (停止) スケールには、仮想マシンを非同期的に設定します。</span><span class="sxs-lookup"><span data-stu-id="2989f-137">Powers off (stops) the virtual machines in the scale set asynchronously.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="2989f-138">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="2989f-138">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="2989f-139">この呼び出しの遅延の計算の表現。</span><span class="sxs-lookup"><span data-stu-id="2989f-139">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="PrimaryPublicIPAddressIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; PrimaryPublicIPAddressIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; PrimaryPublicIPAddressIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.PrimaryPublicIPAddressIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryPublicIPAddressIds As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PrimaryPublicIPAddressIds : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.PrimaryPublicIPAddressIds" />
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
            <span data-ttu-id="2989f-140">IOException IO の例外を取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-140">Gets IOException the IO exception.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <return>
            <span data-ttu-id="2989f-141">スケール セットの主要なインターネットに接続するロード バランサーに関連付けられているパブリック IP アドレスの Id の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-141">Gets the list of IDs of the public IP addresses associated with the primary Internet-facing load balancer of the scale set.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="Reimage">
      <MemberSignature Language="C#" Value="public void Reimage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Reimage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Reimage" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reimage ()" />
      <MemberSignature Language="F#" Value="abstract member Reimage : unit -&gt; unit" Usage="iVirtualMachineScaleSet.Reimage " />
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
            <span data-ttu-id="2989f-142">再イメージ (インストールされているオペレーティング システムのバージョンを更新する) スケール セット内の仮想マシン。</span><span class="sxs-lookup"><span data-stu-id="2989f-142">Re-images (updates the version of the installed operating system) the virtual machines in the scale set.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReimageAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ReimageAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ReimageAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReimageAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSet.ReimageAsync cancellationToken" />
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
            <span data-ttu-id="2989f-143">再イメージ (インストールされているオペレーティング システムのバージョンを更新する) スケールには、仮想マシンを非同期的に設定します。</span><span class="sxs-lookup"><span data-stu-id="2989f-143">Re-images (updates the version of the installed operating system) the virtual machines in the scale set asynchronously.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="2989f-144">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="2989f-144">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="2989f-145">この呼び出しの遅延の計算の表現。</span><span class="sxs-lookup"><span data-stu-id="2989f-145">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Restart">
      <MemberSignature Language="C#" Value="public void Restart ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Restart() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Restart" />
      <MemberSignature Language="VB.NET" Value="Public Sub Restart ()" />
      <MemberSignature Language="F#" Value="abstract member Restart : unit -&gt; unit" Usage="iVirtualMachineScaleSet.Restart " />
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
            <span data-ttu-id="2989f-146">スケール セット内の仮想マシンを再起動します。</span><span class="sxs-lookup"><span data-stu-id="2989f-146">Restarts the virtual machines in the scale set.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.RestartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSet.RestartAsync cancellationToken" />
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
            <span data-ttu-id="2989f-147">スケール セットが非同期的に仮想マシンを再起動します。</span><span class="sxs-lookup"><span data-stu-id="2989f-147">Restarts the virtual machines in the scale set asynchronously.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="2989f-148">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="2989f-148">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="2989f-149">この呼び出しの遅延の計算の表現。</span><span class="sxs-lookup"><span data-stu-id="2989f-149">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetSkuTypes Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetSkuTypes Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As VirtualMachineScaleSetSkuTypes" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetSkuTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetSkuTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2989f-150">スケール セット内の仮想マシンの SKU を取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-150">Gets the SKU of the virtual machines in the scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public void Start ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Start() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Start" />
      <MemberSignature Language="VB.NET" Value="Public Sub Start ()" />
      <MemberSignature Language="F#" Value="abstract member Start : unit -&gt; unit" Usage="iVirtualMachineScaleSet.Start " />
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
            <span data-ttu-id="2989f-151">スケール セット内の仮想マシンを起動します。</span><span class="sxs-lookup"><span data-stu-id="2989f-151">Starts the virtual machines in the scale set.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.StartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSet.StartAsync cancellationToken" />
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
            <span data-ttu-id="2989f-152">スケールには、設定を非同期的に仮想マシンを起動します。</span><span class="sxs-lookup"><span data-stu-id="2989f-152">Starts the virtual machines in the scale set asynchronously.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="2989f-153">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="2989f-153">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="2989f-154">この呼び出しの遅延の計算の表現。</span><span class="sxs-lookup"><span data-stu-id="2989f-154">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="StorageProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile StorageProfile { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile StorageProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.StorageProfile" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageProfile As VirtualMachineScaleSetStorageProfile" />
      <MemberSignature Language="F#" Value="member this.StorageProfile : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.StorageProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2989f-155">ストレージ プロファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-155">Gets the storage profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeModel">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode UpgradeModel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode UpgradeModel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.UpgradeModel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeModel As UpgradeMode" />
      <MemberSignature Language="F#" Value="member this.UpgradeModel : Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.UpgradeModel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2989f-156">アップグレードのモデルを取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-156">Gets the upgrade model.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VhdContainers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; VhdContainers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; VhdContainers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.VhdContainers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VhdContainers As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.VhdContainers : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.VhdContainers" />
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
            <span data-ttu-id="2989f-157">スケール セット内の仮想マシンの Vhd を格納するストレージ コンテナーへの URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-157">Gets the URL to storage containers that store the VHDs of the virtual machines in the scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachines">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMs VirtualMachines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMs VirtualMachines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.VirtualMachines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachines As IVirtualMachineScaleSetVMs" />
      <MemberSignature Language="F#" Value="member this.VirtualMachines : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMs" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.VirtualMachines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMs</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2989f-158">仮想マシン スケール セット内のインスタンスを管理するエントリ ポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="2989f-158">Gets entry point to manage virtual machine instances in the scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>