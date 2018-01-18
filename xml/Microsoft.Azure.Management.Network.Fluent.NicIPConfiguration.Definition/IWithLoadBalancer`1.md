<Type Name="IWithLoadBalancer&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithLoadBalancer&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithLoadBalancer&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLoadBalancer`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithLoadBalancer`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLoadBalancer(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithLoadBalancer&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="b4586-101">最終的な Attachable.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="b4586-101">The return type of the final  Attachable.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="b4586-102">ロード バランサーに関連付けるには、この IP 構成の指定を許可するネットワーク インターフェイス IP 構成定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="b4586-102">The stage of the network interface IP configuration definition allowing to specify the load balancer to associate this IP configuration with.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingLoadBalancerBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;ParentT&gt; WithExistingLoadBalancerBackend (Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string backendName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach`1&lt;!ParentT&gt; WithExistingLoadBalancerBackend(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string backendName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithLoadBalancer`1.WithExistingLoadBalancerBackend(Microsoft.Azure.Management.Network.Fluent.ILoadBalancer,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingLoadBalancerBackend (loadBalancer As ILoadBalancer, backendName As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingLoadBalancerBackend : Microsoft.Azure.Management.Network.Fluent.ILoadBalancer * string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithLoadBalancer.WithExistingLoadBalancerBackend (loadBalancer, backendName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadBalancer" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
        <Parameter Name="backendName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="loadBalancer"><span data-ttu-id="b4586-103">既存のロード バランサーです。</span><span class="sxs-lookup"><span data-stu-id="b4586-103">An existing load balancer.</span></span></param>
        <param name="backendName"><span data-ttu-id="b4586-104">上の既存のバックエンドの名前はロード バランサーです。</span><span class="sxs-lookup"><span data-stu-id="b4586-104">The name of an existing backend on that load balancer.</span></span></param>
        <summary>
            <span data-ttu-id="b4586-105">関連付けるには、この IP 構成に、ロード バランサーのバックエンドを指定します。</span><span class="sxs-lookup"><span data-stu-id="b4586-105">Specifies the load balancer backend to associate this IP configuration with.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b4586-106">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b4586-106">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingLoadBalancerInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;ParentT&gt; WithExistingLoadBalancerInboundNatRule (Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string inboundNatRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach`1&lt;!ParentT&gt; WithExistingLoadBalancerInboundNatRule(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string inboundNatRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithLoadBalancer`1.WithExistingLoadBalancerInboundNatRule(Microsoft.Azure.Management.Network.Fluent.ILoadBalancer,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingLoadBalancerInboundNatRule (loadBalancer As ILoadBalancer, inboundNatRuleName As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingLoadBalancerInboundNatRule : Microsoft.Azure.Management.Network.Fluent.ILoadBalancer * string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithLoadBalancer.WithExistingLoadBalancerInboundNatRule (loadBalancer, inboundNatRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadBalancer" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
        <Parameter Name="inboundNatRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="loadBalancer"><span data-ttu-id="b4586-107">既存のロード バランサーです。</span><span class="sxs-lookup"><span data-stu-id="b4586-107">An existing load balancer.</span></span></param>
        <param name="inboundNatRuleName"><span data-ttu-id="b4586-108">選択されているロード バランサーの既存の受信 NAT 規則の名前。</span><span class="sxs-lookup"><span data-stu-id="b4586-108">The name of an existing inbound NAT rule on the selected load balancer.</span></span></param>
        <summary>
            <span data-ttu-id="b4586-109">ロード バランサーの指定に関連付けるには、この IP 構成の着信 NAT ルール。</span><span class="sxs-lookup"><span data-stu-id="b4586-109">Specifies the load balancer inbound NAT rule to associate this IP configuration with.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b4586-110">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b4586-110">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>