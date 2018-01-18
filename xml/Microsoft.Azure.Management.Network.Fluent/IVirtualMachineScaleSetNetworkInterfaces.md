<Type Name="IVirtualMachineScaleSetNetworkInterfaces" FullName="Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterfaces">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineScaleSetNetworkInterfaces : Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineScaleSetNetworkInterfaces implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing`1&lt;class Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterfaces" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineScaleSetNetworkInterfaces&#xA;Implements IHasInner(Of INetworkInterfacesOperations), IHasManager(Of INetworkManager), ISupportsListing(Of IVirtualMachineScaleSetNetworkInterface)" />
  <TypeSignature Language="F#" Value="type IVirtualMachineScaleSetNetworkInterfaces = interface&#xA;    interface ISupportsListing&lt;IVirtualMachineScaleSetNetworkInterface&gt;&#xA;    interface IHasInner&lt;INetworkInterfacesOperations&gt;&#xA;    interface IHasManager&lt;INetworkManager&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="0c9b9-101">仮想マシン スケール セットのネットワーク インターフェイス管理 API へのエントリ ポイントです。</span><span class="sxs-lookup"><span data-stu-id="0c9b9-101">Entry point to virtual machine scale set network interface management API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetByVirtualMachineInstanceId">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface GetByVirtualMachineInstanceId (string instanceId, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface GetByVirtualMachineInstanceId(string instanceId, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterfaces.GetByVirtualMachineInstanceId(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetByVirtualMachineInstanceId (instanceId As String, name As String) As IVirtualMachineScaleSetNetworkInterface" />
      <MemberSignature Language="F#" Value="abstract member GetByVirtualMachineInstanceId : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface" Usage="iVirtualMachineScaleSetNetworkInterfaces.GetByVirtualMachineInstanceId (instanceId, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
        <param name="instanceId"><span data-ttu-id="0c9b9-102">仮想マシン スケール セットの vm インスタンスの id。</span><span class="sxs-lookup"><span data-stu-id="0c9b9-102">The virtual machine scale set vm instance id.</span></span></param>
        <param name="name"><span data-ttu-id="0c9b9-103">ネットワーク インターフェイスの名前。</span><span class="sxs-lookup"><span data-stu-id="0c9b9-103">The network interface name.</span></span></param>
        <summary>
            <span data-ttu-id="0c9b9-104">仮想マシン スケール セット インスタンスに関連付けられているネットワーク インターフェイスを取得します。</span><span class="sxs-lookup"><span data-stu-id="0c9b9-104">Gets a network interface associated with a virtual machine scale set instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0c9b9-105">ネットワーク インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="0c9b9-105">The network interface.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ListByVirtualMachineInstanceId">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt; ListByVirtualMachineInstanceId (string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt; ListByVirtualMachineInstanceId(string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterfaces.ListByVirtualMachineInstanceId(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListByVirtualMachineInstanceId (instanceId As String) As IEnumerable(Of IVirtualMachineScaleSetNetworkInterface)" />
      <MemberSignature Language="F#" Value="abstract member ListByVirtualMachineInstanceId : string -&gt; seq&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;" Usage="iVirtualMachineScaleSetNetworkInterfaces.ListByVirtualMachineInstanceId instanceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="instanceId"><span data-ttu-id="0c9b9-106">仮想マシン スケール セットの vm インスタンスの id。</span><span class="sxs-lookup"><span data-stu-id="0c9b9-106">Virtual machine scale set vm instance id.</span></span></param>
        <summary>
            <span data-ttu-id="0c9b9-107">スケール セット内の仮想マシン インスタンスに関連付けられているすべてのネットワーク インターフェイスを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0c9b9-107">Lists all the network interfaces associated with a virtual machine instance in the scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0c9b9-108">ネットワーク インターフェイスの一覧です。</span><span class="sxs-lookup"><span data-stu-id="0c9b9-108">List of network interfaces.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>