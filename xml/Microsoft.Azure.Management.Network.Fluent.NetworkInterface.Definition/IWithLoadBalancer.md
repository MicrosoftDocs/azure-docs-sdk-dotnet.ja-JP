<Type Name="IWithLoadBalancer" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithLoadBalancer">
  <TypeSignature Language="C#" Value="public interface IWithLoadBalancer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLoadBalancer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithLoadBalancer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLoadBalancer" />
  <TypeSignature Language="F#" Value="type IWithLoadBalancer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dadb2-101">ロード バランサーに関連付けることを許可するネットワーク インターフェイスの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="dadb2-101">The stage of the network interface definition allowing to associate it with a load balancer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingLoadBalancerBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithExistingLoadBalancerBackend (Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string backendName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithExistingLoadBalancerBackend(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string backendName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithLoadBalancer.WithExistingLoadBalancerBackend(Microsoft.Azure.Management.Network.Fluent.ILoadBalancer,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingLoadBalancerBackend (loadBalancer As ILoadBalancer, backendName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingLoadBalancerBackend : Microsoft.Azure.Management.Network.Fluent.ILoadBalancer * string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithLoadBalancer.WithExistingLoadBalancerBackend (loadBalancer, backendName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadBalancer" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
        <Parameter Name="backendName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="loadBalancer"><span data-ttu-id="dadb2-102">既存のロード バランサーです。</span><span class="sxs-lookup"><span data-stu-id="dadb2-102">An existing load balancer.</span></span></param>
        <param name="backendName"><span data-ttu-id="dadb2-103">上の既存のバックエンドの名前はロード バランサーです。</span><span class="sxs-lookup"><span data-stu-id="dadb2-103">The name of an existing backend on that load balancer.</span></span></param>
        <summary>
            <span data-ttu-id="dadb2-104">ネットワーク インターフェイスのプライマリ IP 構成を既存のロード バランサーのバックエンドに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="dadb2-104">Associates the network interface's primary IP configuration with a backend of an existing load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="dadb2-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="dadb2-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingLoadBalancerInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithExistingLoadBalancerInboundNatRule (Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string inboundNatRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithExistingLoadBalancerInboundNatRule(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string inboundNatRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithLoadBalancer.WithExistingLoadBalancerInboundNatRule(Microsoft.Azure.Management.Network.Fluent.ILoadBalancer,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingLoadBalancerInboundNatRule (loadBalancer As ILoadBalancer, inboundNatRuleName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingLoadBalancerInboundNatRule : Microsoft.Azure.Management.Network.Fluent.ILoadBalancer * string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithLoadBalancer.WithExistingLoadBalancerInboundNatRule (loadBalancer, inboundNatRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadBalancer" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
        <Parameter Name="inboundNatRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="loadBalancer"><span data-ttu-id="dadb2-106">既存のロード バランサーです。</span><span class="sxs-lookup"><span data-stu-id="dadb2-106">An existing load balancer.</span></span></param>
        <param name="inboundNatRuleName"><span data-ttu-id="dadb2-107">選択されているロード バランサーの既存の受信 NAT 規則の名前。</span><span class="sxs-lookup"><span data-stu-id="dadb2-107">The name of an existing inbound NAT rule on the selected load balancer.</span></span></param>
        <summary>
            <span data-ttu-id="dadb2-108">ネットワーク インターフェイスのプライマリ IP 構成を既存のロード バランサーの受信 NAT 規則に関連付けます。</span><span class="sxs-lookup"><span data-stu-id="dadb2-108">Associates the network interface's primary IP configuration with an inbound NAT rule of an existing load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="dadb2-109">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="dadb2-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>