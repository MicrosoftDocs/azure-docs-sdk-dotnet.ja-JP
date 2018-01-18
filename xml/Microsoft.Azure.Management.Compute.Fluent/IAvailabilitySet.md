<Type Name="IAvailabilitySet" FullName="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet">
  <TypeSignature Language="C#" Value="public interface IAvailabilitySet : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager,Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Compute.Fluent.AvailabilitySet.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAvailabilitySet implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Compute.Fluent.IComputeManager, class Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.AvailabilitySet.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAvailabilitySet&#xA;Implements IGroupableResource(Of IComputeManager, AvailabilitySetInner), IHasInner(Of AvailabilitySetInner), IHasManager(Of IComputeManager), IRefreshable(Of IAvailabilitySet), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IAvailabilitySet = interface&#xA;    interface IGroupableResource&lt;IComputeManager, AvailabilitySetInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IComputeManager&gt;&#xA;    interface IHasInner&lt;AvailabilitySetInner&gt;&#xA;    interface IRefreshable&lt;IAvailabilitySet&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager,Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Compute.Fluent.AvailabilitySet.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="5d73d-101">Azure 可用性セットの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="5d73d-101">An immutable client-side representation of an Azure availability set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FaultDomainCount">
      <MemberSignature Language="C#" Value="public int FaultDomainCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FaultDomainCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet.FaultDomainCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FaultDomainCount As Integer" />
      <MemberSignature Language="F#" Value="member this.FaultDomainCount : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet.FaultDomainCount" />
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
            <span data-ttu-id="5d73d-102">この可用性セットのフォールト ドメイン数を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d73d-102">Gets the fault domain count of this availability set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineSizes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize&gt; ListVirtualMachineSizes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize&gt; ListVirtualMachineSizes() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet.ListVirtualMachineSizes" />
      <MemberSignature Language="VB.NET" Value="Public Function ListVirtualMachineSizes () As IEnumerable(Of IVirtualMachineSize)" />
      <MemberSignature Language="F#" Value="abstract member ListVirtualMachineSizes : unit -&gt; seq&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize&gt;" Usage="iAvailabilitySet.ListVirtualMachineSizes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5d73d-103">可用性セットでサポートされている仮想マシンのサイズ。</span><span class="sxs-lookup"><span data-stu-id="5d73d-103">The virtual machine sizes supported in the availability set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetSkuTypes Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetSkuTypes Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As AvailabilitySetSkuTypes" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetSkuTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.AvailabilitySetSkuTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d73d-104">可用性セットの SKU を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d73d-104">Gets the availability set SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statuses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; Statuses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; Statuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet.Statuses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Statuses As IReadOnlyList(Of InstanceViewStatus)" />
      <MemberSignature Language="F#" Value="member this.Statuses : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet.Statuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d73d-105">可用性セット内の既存の仮想マシンの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d73d-105">Gets the statuses of the existing virtual machines in the availability set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDomainCount">
      <MemberSignature Language="C#" Value="public int UpdateDomainCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 UpdateDomainCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet.UpdateDomainCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdateDomainCount As Integer" />
      <MemberSignature Language="F#" Value="member this.UpdateDomainCount : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet.UpdateDomainCount" />
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
            <span data-ttu-id="5d73d-106">この可用性セットの更新ドメイン数を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d73d-106">Gets the update domain count of this availability set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;string&gt; VirtualMachineIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ISet`1&lt;string&gt; VirtualMachineIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet.VirtualMachineIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineIds As ISet(Of String)" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineIds : System.Collections.Generic.ISet&lt;string&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet.VirtualMachineIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d73d-107">可用性セット内の仮想マシンのリソース Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d73d-107">Gets the resource IDs of the virtual machines in the availability set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>