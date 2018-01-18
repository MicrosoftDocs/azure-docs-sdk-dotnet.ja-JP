<Type Name="IWithSubnet" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IWithSubnet">
  <TypeSignature Language="C#" Value="public interface IWithSubnet : Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Update.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSubnet implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Update.IWithSubnet`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IWithSubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSubnet&#xA;Implements IWithSubnet(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IWithSubnet = interface&#xA;    interface IWithSubnet&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Update.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="1eec3-101">アプリケーション ゲートウェイの IP 構成の段階では、アプリケーション ゲートウェイの一部であるサブネットを変更する許可を更新します。</span><span class="sxs-lookup"><span data-stu-id="1eec3-101">The stage of an application gateway IP configuration update allowing to modify the subnet the application gateway is part of.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.ISubnet subnet);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.ISubnet subnet) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IWithSubnet.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.ISubnet)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (subnet As ISubnet) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.ISubnet -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate" Usage="iWithSubnet.WithExistingSubnet subnet" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.Network.Fluent.ISubnet" />
      </Parameters>
      <Docs>
        <param name="subnet"><span data-ttu-id="1eec3-102">既存のサブネットです。</span><span class="sxs-lookup"><span data-stu-id="1eec3-102">An existing subnet.</span></span></param>
        <summary>
            <span data-ttu-id="1eec3-103">既存のサブネット アプリケーション ゲートウェイがの一部にしてからプライベート IP アドレスを取得する必要がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="1eec3-103">Specifies an existing subnet the application gateway should be part of and get its private IP address from.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1eec3-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="1eec3-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IWithSubnet.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.INetwork,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (network As INetwork, subnetName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.INetwork * string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate" Usage="iWithSubnet.WithExistingSubnet (network, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="network"><span data-ttu-id="1eec3-105">既存の仮想ネットワークです。</span><span class="sxs-lookup"><span data-stu-id="1eec3-105">An existing virtual network.</span></span></param>
        <param name="subnetName"><span data-ttu-id="1eec3-106">選択したネットワーク内のサブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="1eec3-106">The name of a subnet within the selected network.</span></span></param>
        <summary>
            <span data-ttu-id="1eec3-107">既存のサブネット アプリケーション ゲートウェイがの一部にしてからプライベート IP アドレスを取得する必要がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="1eec3-107">Specifies an existing subnet the application gateway should be part of and get its private IP address from.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1eec3-108">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="1eec3-108">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>