<Type Name="IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerNatPool, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithAvailabilityZone, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithBootDiagnostics, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithCapacity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithExtension, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithManagedDataDisk, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithManagedServiceIdentity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancer, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerBackend, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerNatPool, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternalLoadBalancer, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerNatPool, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithSku, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithUnmanagedDataDisk, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool&#xA;Implements IAppliable(Of IVirtualMachineScaleSet), IBeta, IUpdateWithTags(Of IWithApply), IWithPrimaryInternetFacingLoadBalancerNatPool" />
  <TypeSignature Language="F#" Value="type IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool = interface&#xA;    interface IWithPrimaryInternetFacingLoadBalancerNatPool&#xA;    interface IWithPrimaryInternalLoadBalancer&#xA;    interface IWithApply&#xA;    interface IAppliable&lt;IVirtualMachineScaleSet&gt;&#xA;    interface IIndexable&#xA;    interface IUpdateWithTags&lt;IWithApply&gt;&#xA;    interface IWithManagedDataDisk&#xA;    interface IWithUnmanagedDataDisk&#xA;    interface IWithSku&#xA;    interface IWithCapacity&#xA;    interface IWithExtension&#xA;    interface IWithoutPrimaryLoadBalancer&#xA;    interface IWithoutPrimaryLoadBalancerBackend&#xA;    interface IWithoutPrimaryLoadBalancerNatPool&#xA;    interface IWithManagedServiceIdentity&#xA;    interface IBeta&#xA;    interface IWithBootDiagnostics&#xA;    interface IWithAvailabilityZone" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerNatPool</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="b1bd7-101">仮想マシンのスケールのステージの設定に、バックエンドを関連付けるには更新を許可するプールや、選択したインターネットからの着信 NAT プールのロード バランサー仮想マシン スケール セット内のプライマリ ネットワーク インターフェイスを使用します。</span><span class="sxs-lookup"><span data-stu-id="b1bd7-101">The stage of a virtual machine scale set update allowing to associate a backend pool and/or inbound NAT pool of the selected Internet-facing load balancer with the primary network interface of the virtual machines in the scale set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrimaryInternetFacingLoadBalancerBackends">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerNatPool WithPrimaryInternetFacingLoadBalancerBackends (params string[] backendNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerNatPool WithPrimaryInternetFacingLoadBalancerBackends(string[] backendNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool.WithPrimaryInternetFacingLoadBalancerBackends(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryInternetFacingLoadBalancerBackends (ParamArray backendNames As String()) As IWithPrimaryInternetFacingLoadBalancerNatPool" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryInternetFacingLoadBalancerBackends : string[] -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerNatPool" Usage="iWithPrimaryInternetFacingLoadBalancerBackendOrNatPool.WithPrimaryInternetFacingLoadBalancerBackends backendNames" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerNatPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backendNames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="backendNames"><span data-ttu-id="b1bd7-102">バックエンドの名前。</span><span class="sxs-lookup"><span data-stu-id="b1bd7-102">The backend names.</span></span></param>
        <summary>
            <span data-ttu-id="b1bd7-103">関連付けられた、指定されたインターネットに接続されたは、仮想マシン スケール セット内のプライマリ ネットワーク インターフェイスを持つバランサー バックエンドを読み込みます。</span><span class="sxs-lookup"><span data-stu-id="b1bd7-103">Associates the specified Internet-facing load balancer backends with the primary network interface of the virtual machines in the scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b1bd7-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b1bd7-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>