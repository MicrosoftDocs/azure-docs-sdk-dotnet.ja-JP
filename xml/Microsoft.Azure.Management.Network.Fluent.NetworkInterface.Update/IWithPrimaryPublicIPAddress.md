<Type Name="IWithPrimaryPublicIPAddress" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryPublicIPAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryPublicIPAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryPublicIPAddress" />
  <TypeSignature Language="F#" Value="type IWithPrimaryPublicIPAddress = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dc626-101">ネットワーク インターフェイスのステージでは、パブリック IP アドレスを関連付けることのプライマリ IP 構成を許可するを更新します。</span><span class="sxs-lookup"><span data-stu-id="dc626-101">The stage of the network interface update allowing to associate public IP address with it's primary IP configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithExistingPrimaryPublicIPAddress (Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress publicIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithExistingPrimaryPublicIPAddress(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress publicIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress.WithExistingPrimaryPublicIPAddress(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryPublicIPAddress (publicIPAddress As IPublicIPAddress) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryPublicIPAddress : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPublicIPAddress.WithExistingPrimaryPublicIPAddress publicIPAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publicIPAddress" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress" />
      </Parameters>
      <Docs>
        <param name="publicIPAddress"><span data-ttu-id="dc626-102">既存のパブリック IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="dc626-102">An existing public IP address.</span></span></param>
        <summary>
            <span data-ttu-id="dc626-103">ネットワーク インターフェイスのプライマリ IP 構成を既存のパブリック IP アドレスを関連付けます。</span><span class="sxs-lookup"><span data-stu-id="dc626-103">Associates an existing public IP address with the network interface's primary IP configuration.</span></span>
            <span data-ttu-id="dc626-104">既存がある場合は、パブリック IP の関連付けをしは、このいる削除されます。</span><span class="sxs-lookup"><span data-stu-id="dc626-104">if there is an existing public IP association then that will be removed in favour of this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="dc626-105">ネットワーク インターフェイスの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="dc626-105">The next stage of the network interface update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryPublicIPAddress () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryPublicIPAddress : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc626-106">同じリージョンと、リソースとグループに新しいパブリック IP アドレスを作成し、ネットワーク インターフェイスのプライマリ IP 構成に関連付けます。</span><span class="sxs-lookup"><span data-stu-id="dc626-106">Creates a new public IP address in the same region and group as the resource and associate it with the network interface's primary IP configuration.</span></span>
            <span data-ttu-id="dc626-107">ブックをこのいる削除される、既存のパブリック IP の関連付けがある場合、内部名とパブリック IP アドレスの DNS ラベルをネットワーク インターフェイスの名前から導き出されます。</span><span class="sxs-lookup"><span data-stu-id="dc626-107">the internal name and DNS label for the public IP address will be derived from the network interface name, if there is an existing public IP association then that will be removed in favour of this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="dc626-108">ネットワーク インターフェイスの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="dc626-108">The next stage of the network interface update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryPublicIPAddress (creatable As ICreatable(Of IPublicIPAddress)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryPublicIPAddress : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable"><span data-ttu-id="dc626-109">新しいパブリック IP の作成可能な定義です。</span><span class="sxs-lookup"><span data-stu-id="dc626-109">A creatable definition for a new public IP.</span></span></param>
        <summary>
            <span data-ttu-id="dc626-110">指定された定義に基づくネットワーク インターフェイスのプライマリ IP 構成を関連付けるには新しいパブリック IP アドレスを作成します。</span><span class="sxs-lookup"><span data-stu-id="dc626-110">Create a new public IP address to associate the network interface's primary IP configuration, based on the provided definition.</span></span>
            <span data-ttu-id="dc626-111">パブリックがある場合は、プライマリ IP 構成に関連付けられている IP、このいる削除されます。</span><span class="sxs-lookup"><span data-stu-id="dc626-111">if there is public IP associated with the primary IP configuration then that will be removed in favour of this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="dc626-112">ネットワーク インターフェイスの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="dc626-112">The next stage of the network interface update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress (string leafDnsLabel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress(string leafDnsLabel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryPublicIPAddress (leafDnsLabel As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryPublicIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress leafDnsLabel" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leafDnsLabel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="leafDnsLabel"><span data-ttu-id="dc626-113">リーフ ドメイン ラベルです。</span><span class="sxs-lookup"><span data-stu-id="dc626-113">The leaf domain label.</span></span></param>
        <summary>
            <span data-ttu-id="dc626-114">指定した DNS ラベルで、リソースと同じリージョンとグループに新しいパブリック IP アドレスを作成し、ネットワーク インターフェイスのプライマリ IP 構成に関連付けます。</span><span class="sxs-lookup"><span data-stu-id="dc626-114">Creates a new public IP address in the same region and group as the resource, with the specified DNS label and associate it with the network interface's primary IP configuration.</span></span>
            <span data-ttu-id="dc626-115">パブリック IP アドレスの内部名は、このいる削除される、既存のパブリック IP の関連付けがある場合、DNS ラベルから導き出されます。</span><span class="sxs-lookup"><span data-stu-id="dc626-115">the internal name for the public IP address will be derived from the DNS label, if there is an existing public IP association then that will be removed in favour of this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="dc626-116">ネットワーク インターフェイスの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="dc626-116">The next stage of the network interface update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithoutPrimaryPublicIPAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithoutPrimaryPublicIPAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress.WithoutPrimaryPublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryPublicIPAddress () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryPublicIPAddress : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPublicIPAddress.WithoutPrimaryPublicIPAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc626-117">ネットワーク インターフェイスのプライマリ IP 構成に関連付けられているすべてのパブリック IP を削除することを指定します。</span><span class="sxs-lookup"><span data-stu-id="dc626-117">Specifies that remove any public IP associated with the network interface's primary IP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="dc626-118">ネットワーク インターフェイスの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="dc626-118">The next stage of the network interface update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>