<Type Name="IWithPrimaryInternetFacingLoadBalancer" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancer">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryInternetFacingLoadBalancer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryInternetFacingLoadBalancer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryInternetFacingLoadBalancer" />
  <TypeSignature Language="F#" Value="type IWithPrimaryInternetFacingLoadBalancer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            仮想マシンのスケールのステージでは、スケール セット内の仮想マシンのプライマリ ネットワーク インターフェイス用のインターネットに接続するロード バランサーの指定を許可する定義を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryInternetFacingLoadBalancer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool WithExistingPrimaryInternetFacingLoadBalancer (Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool WithExistingPrimaryInternetFacingLoadBalancer(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancer.WithExistingPrimaryInternetFacingLoadBalancer(Microsoft.Azure.Management.Network.Fluent.ILoadBalancer)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryInternetFacingLoadBalancer (loadBalancer As ILoadBalancer) As IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryInternetFacingLoadBalancer : Microsoft.Azure.Management.Network.Fluent.ILoadBalancer -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool" Usage="iWithPrimaryInternetFacingLoadBalancer.WithExistingPrimaryInternetFacingLoadBalancer loadBalancer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadBalancer" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
      </Parameters>
      <Docs>
        <param name="loadBalancer">既存のインターネット対応のロード バランサーです。</param>
        <summary>
            仮想マシン スケール セット内のプライマリ ネットワーク インターフェイスを持つバックエンドや NAT プールを割り当てることがインターネットに接続するロード バランサーを指定します。
            既定では、すべてのバックエンドと、ロード バランサーの着信 NAT プールに関連付けられるスケール セットの仮想マシンのプライマリ ネットワーク インターフェイス。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPrimaryInternetFacingLoadBalancer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer WithoutPrimaryInternetFacingLoadBalancer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer WithoutPrimaryInternetFacingLoadBalancer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancer.WithoutPrimaryInternetFacingLoadBalancer" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryInternetFacingLoadBalancer () As IWithPrimaryInternalLoadBalancer" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryInternetFacingLoadBalancer : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer" Usage="iWithPrimaryInternetFacingLoadBalancer.WithoutPrimaryInternetFacingLoadBalancer " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            パブリック ロード バランサーなしに関連付けることは、仮想マシン スケール セットを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>