<Type Name="IWithNetwork&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithNetwork&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNetwork&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNetwork`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithNetwork`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNetwork(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithNetwork&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="42e86-101">最終的な Attachable.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="42e86-101">The return type of the final  Attachable.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="42e86-102">仮想ネットワークを指定を許可するネットワーク インターフェイス IP 構成定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="42e86-102">The stage of the network interface IP configuration definition allowing to specify the virtual network.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithSubnet&lt;ParentT&gt; WithExistingNetwork (Microsoft.Azure.Management.Network.Fluent.INetwork network);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithSubnet`1&lt;!ParentT&gt; WithExistingNetwork(class Microsoft.Azure.Management.Network.Fluent.INetwork network) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithNetwork`1.WithExistingNetwork(Microsoft.Azure.Management.Network.Fluent.INetwork)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingNetwork (network As INetwork) As IWithSubnet(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingNetwork : Microsoft.Azure.Management.Network.Fluent.INetwork -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithSubnet&lt;'ParentT&gt;" Usage="iWithNetwork.WithExistingNetwork network" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithSubnet&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
      </Parameters>
      <Docs>
        <param name="network"><span data-ttu-id="42e86-103">既存の仮想ネットワークです。</span><span class="sxs-lookup"><span data-stu-id="42e86-103">An existing virtual network.</span></span></param>
        <summary>
            <span data-ttu-id="42e86-104">既存の仮想ネットワークをネットワーク インターフェイス IP 構成に関連付けます。</span><span class="sxs-lookup"><span data-stu-id="42e86-104">Associate an existing virtual network with the network interface IP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="42e86-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="42e86-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP&lt;ParentT&gt; WithNewNetwork (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP`1&lt;!ParentT&gt; WithNewNetwork(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetwork&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithNetwork`1.WithNewNetwork(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetwork})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewNetwork (creatable As ICreatable(Of INetwork)) As IWithPrivateIP(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNewNetwork : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP&lt;'ParentT&gt;" Usage="iWithNetwork.WithNewNetwork creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable"><span data-ttu-id="42e86-106">新しい仮想ネットワークの作成可能な定義です。</span><span class="sxs-lookup"><span data-stu-id="42e86-106">A creatable definition for a new virtual network.</span></span></param>
        <summary>
            <span data-ttu-id="42e86-107">指定された定義に基づく、ネットワーク インターフェイス IP 構成に関連付ける場合は、新しい仮想ネットワークを作成します。</span><span class="sxs-lookup"><span data-stu-id="42e86-107">Create a new virtual network to associate with the  network interface IP configuration, based on the provided definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="42e86-108">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="42e86-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP&lt;ParentT&gt; WithNewNetwork (string addressSpace);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP`1&lt;!ParentT&gt; WithNewNetwork(string addressSpace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithNetwork`1.WithNewNetwork(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewNetwork (addressSpace As String) As IWithPrivateIP(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNewNetwork : string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP&lt;'ParentT&gt;" Usage="iWithNetwork.WithNewNetwork addressSpace" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addressSpace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="addressSpace"><span data-ttu-id="42e86-109">仮想ネットワークのアドレス空間です。</span><span class="sxs-lookup"><span data-stu-id="42e86-109">The address space for the virtual network.</span></span></param>
        <summary>
            <span data-ttu-id="42e86-110">ネットワーク インターフェイス IP 構成に関連付ける場合は、新しい仮想ネットワークを作成します。</span><span class="sxs-lookup"><span data-stu-id="42e86-110">Creates a new virtual network to associate with the network interface IP configuration.</span></span>
            <span data-ttu-id="42e86-111">仮想ネットワークは、同じリソース グループと親のネットワーク インターフェイスの時点でのリージョンに作成されますが、指定されたアドレス空間と、ネットワークの IP アドレス空間の全体をカバーする既定のサブネットが作成されます。</span><span class="sxs-lookup"><span data-stu-id="42e86-111">the virtual network will be created in the same resource group and region as of parent network interface, it will be created with the specified address space and a default subnet covering the entirety of the network IP address space.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="42e86-112">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="42e86-112">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP&lt;ParentT&gt; WithNewNetwork (string name, string addressSpace);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP`1&lt;!ParentT&gt; WithNewNetwork(string name, string addressSpace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithNetwork`1.WithNewNetwork(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewNetwork (name As String, addressSpace As String) As IWithPrivateIP(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNewNetwork : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP&lt;'ParentT&gt;" Usage="iWithNetwork.WithNewNetwork (name, addressSpace)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="addressSpace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="42e86-113">新しい仮想ネットワークの名前。</span><span class="sxs-lookup"><span data-stu-id="42e86-113">The name of the new virtual network.</span></span></param>
        <param name="addressSpace"><span data-ttu-id="42e86-114">された仮想ネットワークのアドレス空間です。</span><span class="sxs-lookup"><span data-stu-id="42e86-114">The address space for rhe virtual network.</span></span></param>
        <summary>
            <span data-ttu-id="42e86-115">ネットワーク インターフェイス IP 構成に関連付ける場合は、新しい仮想ネットワークを作成します。</span><span class="sxs-lookup"><span data-stu-id="42e86-115">Creates a new virtual network to associate with the network interface IP configuration.</span></span>
            <span data-ttu-id="42e86-116">仮想ネットワークは、同じリソース グループと親のネットワーク インターフェイスの時点でのリージョンに作成されますが、指定されたアドレス空間と、ネットワークの IP アドレス空間の全体をカバーする既定のサブネットが作成されます。</span><span class="sxs-lookup"><span data-stu-id="42e86-116">the virtual network will be created in the same resource group and region as of parent network interface, it will be created with the specified address space and a default subnet covering the entirety of the network IP address space.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="42e86-117">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="42e86-117">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>