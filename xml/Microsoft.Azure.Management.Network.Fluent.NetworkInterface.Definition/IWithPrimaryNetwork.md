<Type Name="IWithPrimaryNetwork" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryNetwork" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryNetwork" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryNetwork" />
  <TypeSignature Language="F#" Value="type IWithPrimaryNetwork = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="24fd7-101">プライマリ IP 構成の仮想ネットワークを指定を許可するネットワーク インターフェイスの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="24fd7-101">The stage of the network interface definition allowing to specify the virtual network for primary IP configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetworkSubnet WithExistingPrimaryNetwork (Microsoft.Azure.Management.Network.Fluent.INetwork network);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetworkSubnet WithExistingPrimaryNetwork(class Microsoft.Azure.Management.Network.Fluent.INetwork network) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork.WithExistingPrimaryNetwork(Microsoft.Azure.Management.Network.Fluent.INetwork)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryNetwork (network As INetwork) As IWithPrimaryNetworkSubnet" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryNetwork : Microsoft.Azure.Management.Network.Fluent.INetwork -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetworkSubnet" Usage="iWithPrimaryNetwork.WithExistingPrimaryNetwork network" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetworkSubnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
      </Parameters>
      <Docs>
        <param name="network"><span data-ttu-id="24fd7-102">既存の仮想ネットワークです。</span><span class="sxs-lookup"><span data-stu-id="24fd7-102">An existing virtual network.</span></span></param>
        <summary>
            <span data-ttu-id="24fd7-103">既存の仮想ネットワークをネットワーク インターフェイスのプライマリ IP 構成に関連付けます。</span><span class="sxs-lookup"><span data-stu-id="24fd7-103">Associate an existing virtual network with the network interface's primary IP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="24fd7-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="24fd7-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetwork&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork.WithNewPrimaryNetwork(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetwork})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryNetwork (creatable As ICreatable(Of INetwork)) As IWithPrimaryPrivateIP" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryNetwork : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP" Usage="iWithPrimaryNetwork.WithNewPrimaryNetwork creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable"><span data-ttu-id="24fd7-105">新しい仮想ネットワークの作成可能な定義です。</span><span class="sxs-lookup"><span data-stu-id="24fd7-105">A creatable definition for a new virtual network.</span></span></param>
        <summary>
            <span data-ttu-id="24fd7-106">指定された定義に基づくネットワーク インターフェイスのプライマリ IP 構成に関連付ける場合は、新しい仮想ネットワークを作成します。</span><span class="sxs-lookup"><span data-stu-id="24fd7-106">Create a new virtual network to associate with the network interface's primary IP configuration, based on the provided definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="24fd7-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="24fd7-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork (string addressSpace);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork(string addressSpace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork.WithNewPrimaryNetwork(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryNetwork (addressSpace As String) As IWithPrimaryPrivateIP" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryNetwork : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP" Usage="iWithPrimaryNetwork.WithNewPrimaryNetwork addressSpace" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addressSpace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="addressSpace"><span data-ttu-id="24fd7-108">仮想ネットワークのアドレス空間です。</span><span class="sxs-lookup"><span data-stu-id="24fd7-108">The address space for the virtual network.</span></span></param>
        <summary>
            <span data-ttu-id="24fd7-109">ネットワーク インターフェイスのプライマリ IP 構成に関連付ける場合は、新しい仮想ネットワークを作成します。</span><span class="sxs-lookup"><span data-stu-id="24fd7-109">Creates a new virtual network to associate with the network interface's primary IP configuration.</span></span>
            <span data-ttu-id="24fd7-110">仮想ネットワークは、同じリソース グループとネットワーク インターフェイスの時点でのリージョンに作成されますが、指定されたアドレス空間と、ネットワークの IP アドレス空間の全体をカバーする既定のサブネットが作成されます。</span><span class="sxs-lookup"><span data-stu-id="24fd7-110">The virtual network will be created in the same resource group and region as of network interface, it will be created with the specified address space and a default subnet covering the entirety of the network IP address space.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="24fd7-111">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="24fd7-111">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork (string name, string addressSpace);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork(string name, string addressSpace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork.WithNewPrimaryNetwork(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryNetwork (name As String, addressSpace As String) As IWithPrimaryPrivateIP" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryNetwork : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP" Usage="iWithPrimaryNetwork.WithNewPrimaryNetwork (name, addressSpace)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="addressSpace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="24fd7-112">新しい仮想ネットワークの名前。</span><span class="sxs-lookup"><span data-stu-id="24fd7-112">The name of the new virtual network.</span></span></param>
        <param name="addressSpace"><span data-ttu-id="24fd7-113">された仮想ネットワークのアドレス空間です。</span><span class="sxs-lookup"><span data-stu-id="24fd7-113">The address space for rhe virtual network.</span></span></param>
        <summary>
            <span data-ttu-id="24fd7-114">ネットワーク インターフェイスのプライマリ IP 構成に関連付ける場合は、新しい仮想ネットワークを作成します。</span><span class="sxs-lookup"><span data-stu-id="24fd7-114">Creates a new virtual network to associate with the network interface's primary IP configuration.</span></span>
            <span data-ttu-id="24fd7-115">仮想ネットワークは、同じリソース グループとネットワーク インターフェイスの時点でのリージョンに作成されますが、指定されたアドレス空間と、ネットワークの IP アドレス空間の全体をカバーする既定のサブネットが作成されます。</span><span class="sxs-lookup"><span data-stu-id="24fd7-115">The virtual network will be created in the same resource group and region as of network interface, it will be created with the specified address space and a default subnet covering the entirety of the network IP address space.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="24fd7-116">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="24fd7-116">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>