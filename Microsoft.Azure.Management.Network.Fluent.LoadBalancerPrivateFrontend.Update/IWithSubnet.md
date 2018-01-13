<Type Name="IWithSubnet" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Update.IWithSubnet">
  <TypeSignature Language="C#" Value="public interface IWithSubnet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSubnet" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Update.IWithSubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSubnet" />
  <TypeSignature Language="F#" Value="type IWithSubnet = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8de27-101">選択したネットワークのサブネットを指定する許可するプライベート フロント エンドの更新の段階です。</span><span class="sxs-lookup"><span data-stu-id="8de27-101">The stage of a private frontend update allowing to specify a subnet from the selected network.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Update.IUpdate WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Update.IUpdate WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Update.IWithSubnet.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.INetwork,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (network As INetwork, subnetName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.INetwork * string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Update.IUpdate" Usage="iWithSubnet.WithExistingSubnet (network, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="network"><span data-ttu-id="8de27-102">仮想ネットワークが、サブネットに存在します。</span><span class="sxs-lookup"><span data-stu-id="8de27-102">The virtual network the subnet exists in.</span></span></param>
        <param name="subnetName"><span data-ttu-id="8de27-103">サブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="8de27-103">The name of a subnet.</span></span></param>
        <summary>
            <span data-ttu-id="8de27-104">内部ロード バランサーのこのプライベート フロント エンドに指定されたサブネットを割り当てます。</span><span class="sxs-lookup"><span data-stu-id="8de27-104">Assigns the specified subnet to this private frontend of the internal load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8de27-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="8de27-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>