<Type Name="IWithoutPrimaryLoadBalancer" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancer">
  <TypeSignature Language="C#" Value="public interface IWithoutPrimaryLoadBalancer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithoutPrimaryLoadBalancer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithoutPrimaryLoadBalancer" />
  <TypeSignature Language="F#" Value="type IWithoutPrimaryLoadBalancer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4551a-101">仮想マシンのスケールのステージでは、プライマリ ネットワーク インターフェイスの構成からパブリックおよび内部ロード バランサーの削除を許可する更新プログラムを設定します。</span><span class="sxs-lookup"><span data-stu-id="4551a-101">The stage of a virtual machine scale set update allowing to remove the public and internal load balancer from the primary network interface configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutPrimaryInternalLoadBalancer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternalLoadBalancer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternalLoadBalancer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancer.WithoutPrimaryInternalLoadBalancer" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryInternalLoadBalancer () As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryInternalLoadBalancer : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithoutPrimaryLoadBalancer.WithoutPrimaryInternalLoadBalancer " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4551a-102">内部ロード バランサーとプライマリ ネットワーク インターフェイスの構成間の関連付けを削除します。</span><span class="sxs-lookup"><span data-stu-id="4551a-102">Removes the association between the internal load balancer and the primary network interface configuration.</span></span>
            <span data-ttu-id="4551a-103">これには、ロード バランサーのプライマリ ネットワーク インターフェイスの構成とすべてのバックエンドと着信 NAT プール間の関連付けを削除します。</span><span class="sxs-lookup"><span data-stu-id="4551a-103">This removes the association between primary network interface configuration and all the backends and inbound NAT pools in the load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4551a-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="4551a-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPrimaryInternetFacingLoadBalancer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternetFacingLoadBalancer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternetFacingLoadBalancer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancer.WithoutPrimaryInternetFacingLoadBalancer" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryInternetFacingLoadBalancer () As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryInternetFacingLoadBalancer : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithoutPrimaryLoadBalancer.WithoutPrimaryInternetFacingLoadBalancer " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4551a-105">インターネットに接続するロード バランサーとプライマリ ネットワーク インターフェイスの構成間の関連付けを削除します。</span><span class="sxs-lookup"><span data-stu-id="4551a-105">Removes the association between the Internet-facing load balancer and the primary network interface configuration.</span></span>
            <span data-ttu-id="4551a-106">これには、ロード バランサーのプライマリ ネットワーク インターフェイスの構成とすべてのバックエンドと着信 NAT プール間の関連付けを削除します。</span><span class="sxs-lookup"><span data-stu-id="4551a-106">This removes the association between primary network interface configuration and all the backends and inbound NAT pools in the load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4551a-107">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="4551a-107">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>