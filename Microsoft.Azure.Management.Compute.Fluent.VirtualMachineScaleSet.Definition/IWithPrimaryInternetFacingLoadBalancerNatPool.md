<Type Name="IWithPrimaryInternetFacingLoadBalancerNatPool" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerNatPool">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryInternetFacingLoadBalancerNatPool : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryInternetFacingLoadBalancerNatPool implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryInternetFacingLoadBalancerNatPool&#xA;Implements IWithPrimaryInternalLoadBalancer" />
  <TypeSignature Language="F#" Value="type IWithPrimaryInternetFacingLoadBalancerNatPool = interface&#xA;    interface IWithPrimaryInternalLoadBalancer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            仮想マシンのスケールのステージでは、可能であり、仮想マシン スケール セット内のプライマリ ネットワーク インターフェイスで選択されているインターネットに接続するロード バランサーの受信の NAT プールを関連付けるに定義を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrimaryInternetFacingLoadBalancerInboundNatPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer WithPrimaryInternetFacingLoadBalancerInboundNatPools (params string[] natPoolNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer WithPrimaryInternetFacingLoadBalancerInboundNatPools(string[] natPoolNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerNatPool.WithPrimaryInternetFacingLoadBalancerInboundNatPools(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryInternetFacingLoadBalancerInboundNatPools (ParamArray natPoolNames As String()) As IWithPrimaryInternalLoadBalancer" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryInternetFacingLoadBalancerInboundNatPools : string[] -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer" Usage="iWithPrimaryInternetFacingLoadBalancerNatPool.WithPrimaryInternetFacingLoadBalancerInboundNatPools natPoolNames" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer</ReturnType>
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
        <param name="natPoolNames">着信 NAT プールの選択されているロード バランサー上の既存の名前。</param>
        <summary>
            選択されている内部ロード バランサーの指定、着信 NAT プールを仮想マシン スケール セット内のプライマリ ネットワーク インターフェイスに関連付けます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>