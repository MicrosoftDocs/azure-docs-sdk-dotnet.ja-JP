<Type Name="IWithNetwork" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork">
  <TypeSignature Language="C#" Value="public interface IWithNetwork : Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrimaryNetworkInterface" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNetwork implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrimaryNetworkInterface" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNetwork&#xA;Implements IWithPrimaryNetworkInterface" />
  <TypeSignature Language="F#" Value="type IWithNetwork = interface&#xA;    interface IWithPrimaryNetworkInterface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrimaryNetworkInterface</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="0e516-101">新しいプライマリ ネットワーク インターフェイスを持つ仮想ネットワークを指定するように仮想マシンの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="0e516-101">The stage of a virtual machine definition allowing to specify a virtual network with the new primary network interface.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSubnet WithExistingPrimaryNetwork (Microsoft.Azure.Management.Network.Fluent.INetwork network);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSubnet WithExistingPrimaryNetwork(class Microsoft.Azure.Management.Network.Fluent.INetwork network) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork.WithExistingPrimaryNetwork(Microsoft.Azure.Management.Network.Fluent.INetwork)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryNetwork (network As INetwork) As IWithSubnet" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryNetwork : Microsoft.Azure.Management.Network.Fluent.INetwork -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSubnet" Usage="iWithNetwork.WithExistingPrimaryNetwork network" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSubnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
      </Parameters>
      <Docs>
        <param name="network"><span data-ttu-id="0e516-102">既存の仮想ネットワークです。</span><span class="sxs-lookup"><span data-stu-id="0e516-102">An existing virtual network.</span></span></param>
        <summary>
            <span data-ttu-id="0e516-103">既存の仮想ネットワークをバーチャル マシンのプライマリ ネットワーク インターフェイスに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="0e516-103">Associates an existing virtual network with the virtual machine's primary network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0e516-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0e516-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP WithNewPrimaryNetwork (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP WithNewPrimaryNetwork(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetwork&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork.WithNewPrimaryNetwork(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetwork})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryNetwork (creatable As ICreatable(Of INetwork)) As IWithPrivateIP" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryNetwork : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP" Usage="iWithNetwork.WithNewPrimaryNetwork creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable"><span data-ttu-id="0e516-105">新しい仮想ネットワークの作成可能な定義です。</span><span class="sxs-lookup"><span data-stu-id="0e516-105">A creatable definition for a new virtual network.</span></span></param>
        <summary>
            <span data-ttu-id="0e516-106">指定された定義に基づくバーチャル マシンのプライマリ ネットワーク インターフェイスに関連付ける場合は、新しい仮想ネットワークを作成します。</span><span class="sxs-lookup"><span data-stu-id="0e516-106">Creates a new virtual network to associate with the virtual machine's primary network interface, based on the provided definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0e516-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0e516-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP WithNewPrimaryNetwork (string addressSpace);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP WithNewPrimaryNetwork(string addressSpace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork.WithNewPrimaryNetwork(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryNetwork (addressSpace As String) As IWithPrivateIP" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryNetwork : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP" Usage="iWithNetwork.WithNewPrimaryNetwork addressSpace" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addressSpace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="addressSpace"><span data-ttu-id="0e516-108">仮想ネットワークのアドレス空間です。</span><span class="sxs-lookup"><span data-stu-id="0e516-108">The address space for the virtual network.</span></span></param>
        <summary>
            <span data-ttu-id="0e516-109">バーチャル マシンのプライマリ ネットワーク インターフェイスに関連付ける場合は、新しい仮想ネットワークを作成します。</span><span class="sxs-lookup"><span data-stu-id="0e516-109">Creates a new virtual network to associate with the virtual machine's primary network interface.</span></span>
            <span data-ttu-id="0e516-110">仮想ネットワークは、同じリソース グループと仮想マシンの時点でのリージョンに作成されますが、指定されたアドレス空間と、ネットワークの IP アドレス空間の全体をカバーする既定のサブネットが作成されます。</span><span class="sxs-lookup"><span data-stu-id="0e516-110">The virtual network will be created in the same resource group and region as of virtual machine, it will be created with the specified address space and a default subnet covering the entirety of the network IP address space.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0e516-111">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0e516-111">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>