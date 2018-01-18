<Type Name="IWithSubnet&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IWithSubnet&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSubnet&lt;ParentT&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.UpdateDefinition.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSubnet`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.UpdateDefinition.IWithSubnet`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IWithSubnet`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSubnet(Of ParentT)&#xA;Implements IWithSubnet(Of IWithAttach(Of ParentT))" />
  <TypeSignature Language="F#" Value="type IWithSubnet&lt;'ParentT&gt; = interface&#xA;    interface IWithSubnet&lt;IWithAttach&lt;'ParentT&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.UpdateDefinition.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="66801-101">親の型。</span><span class="sxs-lookup"><span data-stu-id="66801-101">The parent type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="66801-102">アプリケーション ゲートウェイ サブネットを指定するようにアプリケーション ゲートウェイ IP 構成定義のステージは、上します。</span><span class="sxs-lookup"><span data-stu-id="66801-102">The stage of an application gateway IP configuration definition allowing to specify the subnet the application gateway is on.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.ISubnet subnet);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.ISubnet subnet) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IWithSubnet`1.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.ISubnet)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (subnet As ISubnet) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.ISubnet -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithSubnet.WithExistingSubnet subnet" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.Network.Fluent.ISubnet" />
      </Parameters>
      <Docs>
        <param name="subnet"><span data-ttu-id="66801-103">既存のサブネットです。</span><span class="sxs-lookup"><span data-stu-id="66801-103">An existing subnet.</span></span></param>
        <summary>
            <span data-ttu-id="66801-104">既存のサブネット アプリケーション ゲートウェイがの一部にしてからプライベート IP アドレスを取得する必要がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="66801-104">Specifies an existing subnet the application gateway should be part of and get its private IP address from.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="66801-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="66801-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IWithSubnet`1.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.INetwork,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (network As INetwork, subnetName As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.INetwork * string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithSubnet.WithExistingSubnet (network, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="network"><span data-ttu-id="66801-106">既存の仮想ネットワークです。</span><span class="sxs-lookup"><span data-stu-id="66801-106">An existing virtual network.</span></span></param>
        <param name="subnetName"><span data-ttu-id="66801-107">選択したネットワーク内のサブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="66801-107">The name of a subnet within the selected network.</span></span></param>
        <summary>
            <span data-ttu-id="66801-108">既存のサブネット アプリケーション ゲートウェイがの一部にしてからプライベート IP アドレスを取得する必要がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="66801-108">Specifies an existing subnet the application gateway should be part of and get its private IP address from.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="66801-109">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="66801-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>