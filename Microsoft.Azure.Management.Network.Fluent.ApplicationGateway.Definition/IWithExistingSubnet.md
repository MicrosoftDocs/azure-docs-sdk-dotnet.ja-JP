<Type Name="IWithExistingSubnet" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithExistingSubnet">
  <TypeSignature Language="C#" Value="public interface IWithExistingSubnet : Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Definition.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExistingSubnet implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Definition.IWithSubnet`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithExistingSubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExistingSubnet&#xA;Implements IWithSubnet(Of IWithCreate)" />
  <TypeSignature Language="F#" Value="type IWithExistingSubnet = interface&#xA;    interface IWithSubnet&lt;IWithCreate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Definition.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="9499c-101">アプリケーション ゲートウェイ サブネットを指定するようにアプリケーション ゲートウェイ定義のステージからプライベート IP アドレスの取得です。</span><span class="sxs-lookup"><span data-stu-id="9499c-101">The stage of an application gateway definition allowing to specify the subnet the app gateway is getting its private IP address from.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.ISubnet subnet);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.ISubnet subnet) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithExistingSubnet.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.ISubnet)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (subnet As ISubnet) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.ISubnet -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate" Usage="iWithExistingSubnet.WithExistingSubnet subnet" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.Network.Fluent.ISubnet" />
      </Parameters>
      <Docs>
        <param name="subnet"><span data-ttu-id="9499c-102">既存のサブネットです。</span><span class="sxs-lookup"><span data-stu-id="9499c-102">An existing subnet.</span></span></param>
        <summary>
            <span data-ttu-id="9499c-103">アプリケーション ゲートウェイのサブネットからプライベート IP アドレスの取得を指定します。</span><span class="sxs-lookup"><span data-stu-id="9499c-103">Specifies the subnet the application gateway gets its private IP address from.</span></span>
            <span data-ttu-id="9499c-104">既に存在しない場合は、新しい IP 構成が作成します。</span><span class="sxs-lookup"><span data-stu-id="9499c-104">This will create a new IP configuration, if it does not already exist.</span></span>
            <span data-ttu-id="9499c-105">プライベート (内部) フロント エンド、いずれかが有効になっている場合は、構成もこのサブネットを使用します。</span><span class="sxs-lookup"><span data-stu-id="9499c-105">Private (internal) frontends, if any have been enabled, will be configured to use this subnet as well.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9499c-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="9499c-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithExistingSubnet.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.INetwork,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (network As INetwork, subnetName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.INetwork * string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate" Usage="iWithExistingSubnet.WithExistingSubnet (network, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="network"><span data-ttu-id="9499c-107">仮想ネットワーク サブネットでは、一部です。</span><span class="sxs-lookup"><span data-stu-id="9499c-107">The virtual network the subnet is part of.</span></span></param>
        <param name="subnetName"><span data-ttu-id="9499c-108">選択したネットワーク内のサブネットの名前。</span><span class="sxs-lookup"><span data-stu-id="9499c-108">The name of a subnet within the selected network.</span></span></param>
        <summary>
            <span data-ttu-id="9499c-109">アプリケーション ゲートウェイのサブネットからプライベート IP アドレスの取得を指定します。</span><span class="sxs-lookup"><span data-stu-id="9499c-109">Specifies the subnet the application gateway gets its private IP address from.</span></span>
            <span data-ttu-id="9499c-110">既に存在しない場合は、新しい IP 構成が作成します。</span><span class="sxs-lookup"><span data-stu-id="9499c-110">This will create a new IP configuration, if it does not already exist.</span></span>
            <span data-ttu-id="9499c-111">プライベート (内部) フロント エンド、いずれかが有効になっている場合は、構成もこのサブネットを使用します。</span><span class="sxs-lookup"><span data-stu-id="9499c-111">Private (internal) frontends, if any have been enabled, will be configured to use this subnet as well.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9499c-112">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="9499c-112">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>