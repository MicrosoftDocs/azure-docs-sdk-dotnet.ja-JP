<Type Name="IWithPrimaryInternalLoadBalancer" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryInternalLoadBalancer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryInternalLoadBalancer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryInternalLoadBalancer" />
  <TypeSignature Language="F#" Value="type IWithPrimaryInternalLoadBalancer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            仮想マシンのスケールのステージでは、スケール セット内の仮想マシンのプライマリ ネットワーク インターフェイスの内部ロード バランサーの指定を許可する定義を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryInternalLoadBalancer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalLoadBalancerBackendOrNatPool WithExistingPrimaryInternalLoadBalancer (Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalLoadBalancerBackendOrNatPool WithExistingPrimaryInternalLoadBalancer(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer.WithExistingPrimaryInternalLoadBalancer(Microsoft.Azure.Management.Network.Fluent.ILoadBalancer)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryInternalLoadBalancer (loadBalancer As ILoadBalancer) As IWithInternalLoadBalancerBackendOrNatPool" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryInternalLoadBalancer : Microsoft.Azure.Management.Network.Fluent.ILoadBalancer -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalLoadBalancerBackendOrNatPool" Usage="iWithPrimaryInternalLoadBalancer.WithExistingPrimaryInternalLoadBalancer loadBalancer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalLoadBalancerBackendOrNatPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadBalancer" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
      </Parameters>
      <Docs>
        <param name="loadBalancer">既存の内部ロード バランサーです。</param>
        <summary>
            内部ロード バランサーのバックエンドや NAT プールは、仮想マシン スケール セット内のプライマリ ネットワーク インターフェイスに割り当てることができますを指定します。
            既定では、すべてのバックエンドと、ロード バランサーの着信 NAT プールに関連付けられる仮想マシン スケール セット内のプライマリ ネットワーク インターフェイス、次の段階でそれらのサブセットが選択されていません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPrimaryInternalLoadBalancer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS WithoutPrimaryInternalLoadBalancer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS WithoutPrimaryInternalLoadBalancer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer.WithoutPrimaryInternalLoadBalancer" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryInternalLoadBalancer () As IWithOS" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryInternalLoadBalancer : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS" Usage="iWithPrimaryInternalLoadBalancer.WithoutPrimaryInternalLoadBalancer " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ある内部ロード バランサーなしに関連付けることは、仮想マシン スケール セット内のプライマリ ネットワーク インターフェイスを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>