<Type Name="IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerNatPool" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerNatPool" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool&#xA;Implements IWithPrimaryInternetFacingLoadBalancerNatPool" />
  <TypeSignature Language="F#" Value="type IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool = interface&#xA;    interface IWithPrimaryInternetFacingLoadBalancerNatPool&#xA;    interface IWithPrimaryInternalLoadBalancer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerNatPool</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="ad344-101">仮想マシン スケール セットの定義を許可するスケールには、仮想マシンのプライマリ ネットワーク インターフェイスにバックエンド プールと、選択したインターネットに接続するロード バランサーの受信の NAT プールを関連付けるのステージを設定します。</span><span class="sxs-lookup"><span data-stu-id="ad344-101">The stage of a virtual machine scale set definition allowing to associate a backend pool and/or an inbound NAT pool of the selected Internet-facing load balancer with the primary network interface of the virtual machines in the scale set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrimaryInternetFacingLoadBalancerBackends">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerNatPool WithPrimaryInternetFacingLoadBalancerBackends (params string[] backendNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerNatPool WithPrimaryInternetFacingLoadBalancerBackends(string[] backendNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool.WithPrimaryInternetFacingLoadBalancerBackends(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryInternetFacingLoadBalancerBackends (ParamArray backendNames As String()) As IWithPrimaryInternetFacingLoadBalancerNatPool" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryInternetFacingLoadBalancerBackends : string[] -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerNatPool" Usage="iWithPrimaryInternetFacingLoadBalancerBackendOrNatPool.WithPrimaryInternetFacingLoadBalancerBackends backendNames" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerNatPool</ReturnType>
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
        <param name="backendNames"><span data-ttu-id="ad344-102">選択されているロード バランサーのバックエンドを既存の名前。</span><span class="sxs-lookup"><span data-stu-id="ad344-102">The names of existing backends in the selected load balancer.</span></span></param>
        <summary>
            <span data-ttu-id="ad344-103">選択されているロード バランサーの指定されたバックエンドを仮想マシン スケール セット内のプライマリ ネットワーク インターフェイスに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="ad344-103">Associates the specified backends of the selected load balancer with the primary network interface of the virtual machines in the scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ad344-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ad344-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>