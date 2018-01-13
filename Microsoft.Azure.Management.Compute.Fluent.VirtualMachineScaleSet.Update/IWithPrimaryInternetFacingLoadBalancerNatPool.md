<Type Name="IWithPrimaryInternetFacingLoadBalancerNatPool" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerNatPool">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryInternetFacingLoadBalancerNatPool : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternalLoadBalancer, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryInternetFacingLoadBalancerNatPool implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithAvailabilityZone, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithBootDiagnostics, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithCapacity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithExtension, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithManagedDataDisk, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithManagedServiceIdentity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancer, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerBackend, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerNatPool, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternalLoadBalancer, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithSku, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithUnmanagedDataDisk, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryInternetFacingLoadBalancerNatPool&#xA;Implements IAppliable(Of IVirtualMachineScaleSet), IBeta, IUpdateWithTags(Of IWithApply), IWithPrimaryInternalLoadBalancer" />
  <TypeSignature Language="F#" Value="type IWithPrimaryInternetFacingLoadBalancerNatPool = interface&#xA;    interface IWithPrimaryInternalLoadBalancer&#xA;    interface IWithApply&#xA;    interface IAppliable&lt;IVirtualMachineScaleSet&gt;&#xA;    interface IIndexable&#xA;    interface IUpdateWithTags&lt;IWithApply&gt;&#xA;    interface IWithManagedDataDisk&#xA;    interface IWithUnmanagedDataDisk&#xA;    interface IWithSku&#xA;    interface IWithCapacity&#xA;    interface IWithExtension&#xA;    interface IWithoutPrimaryLoadBalancer&#xA;    interface IWithoutPrimaryLoadBalancerBackend&#xA;    interface IWithoutPrimaryLoadBalancerNatPool&#xA;    interface IWithManagedServiceIdentity&#xA;    interface IBeta&#xA;    interface IWithBootDiagnostics&#xA;    interface IWithAvailabilityZone" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternalLoadBalancer</InterfaceName>
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
            仮想マシン スケール セットの更新を許可するスケールには、仮想マシンのプライマリ ネットワーク インターフェイスに選択されているインターネットに接続するロード バランサーの受信の NAT プールを関連付けるのステージを設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrimaryInternetFacingLoadBalancerInboundNatPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternalLoadBalancer WithPrimaryInternetFacingLoadBalancerInboundNatPools (params string[] natPoolNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternalLoadBalancer WithPrimaryInternetFacingLoadBalancerInboundNatPools(string[] natPoolNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerNatPool.WithPrimaryInternetFacingLoadBalancerInboundNatPools(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryInternetFacingLoadBalancerInboundNatPools (ParamArray natPoolNames As String()) As IWithPrimaryInternalLoadBalancer" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryInternetFacingLoadBalancerInboundNatPools : string[] -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternalLoadBalancer" Usage="iWithPrimaryInternetFacingLoadBalancerNatPool.WithPrimaryInternetFacingLoadBalancerInboundNatPools natPoolNames" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternalLoadBalancer</ReturnType>
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
        <param name="natPoolNames">選択されているロード バランサーの着信 NAT プールを既存の名前。</param>
        <summary>
            関連付けは、仮想マシン スケール セット内のプライマリ ネットワーク インターフェイスで選択されているインターネットに接続するロード バランサーの NAT プールを受信します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>