<Type Name="IWithInternalInternalLoadBalancerNatPool" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalInternalLoadBalancerNatPool">
  <TypeSignature Language="C#" Value="public interface IWithInternalInternalLoadBalancerNatPool : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInternalInternalLoadBalancerNatPool implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalInternalLoadBalancerNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInternalInternalLoadBalancerNatPool&#xA;Implements IWithOS" />
  <TypeSignature Language="F#" Value="type IWithInternalInternalLoadBalancerNatPool = interface&#xA;    interface IWithOS" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="e4c1c-101">仮想マシンのスケールのステージでは、可能であり、仮想マシン スケール セット内のプライマリ ネットワーク インターフェイスで選択されている内部ロード バランサーの着信 NAT プールを関連付けるに定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="e4c1c-101">The stage of the virtual machine scale set definition allowing to associate inbound NAT pools of the selected internal load balancer with the primary network interface of the virtual machines in the scale set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrimaryInternalLoadBalancerInboundNatPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS WithPrimaryInternalLoadBalancerInboundNatPools (params string[] natPoolNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS WithPrimaryInternalLoadBalancerInboundNatPools(string[] natPoolNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalInternalLoadBalancerNatPool.WithPrimaryInternalLoadBalancerInboundNatPools(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryInternalLoadBalancerInboundNatPools (ParamArray natPoolNames As String()) As IWithOS" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryInternalLoadBalancerInboundNatPools : string[] -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS" Usage="iWithInternalInternalLoadBalancerNatPool.WithPrimaryInternalLoadBalancerInboundNatPools natPoolNames" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="natPoolNames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="natPoolNames"><span data-ttu-id="e4c1c-102">着信 NAT プールの名前。</span><span class="sxs-lookup"><span data-stu-id="e4c1c-102">Inbound NAT pool names.</span></span></param>
        <summary>
            <span data-ttu-id="e4c1c-103">内部ロード バランサーに関連付ける着信 NAT プールをスケールのプライマリ ネットワーク インターフェイスが仮想マシンを設定します。</span><span class="sxs-lookup"><span data-stu-id="e4c1c-103">Associate internal load balancer inbound NAT pools with the the primary network interface of the scale set virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e4c1c-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e4c1c-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>