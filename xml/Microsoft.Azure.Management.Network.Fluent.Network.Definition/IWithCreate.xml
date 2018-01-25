<Type Name="IWithCreate" FullName="Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate">
  <TypeSignature Language="C#" Value="public interface IWithCreate : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCreate implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetwork&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCreate&#xA;Implements ICreatable(Of INetwork), IDefinitionWithTags(Of IWithCreate)" />
  <TypeSignature Language="F#" Value="type IWithCreate = interface&#xA;    interface ICreatable&lt;INetwork&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="ca1df-101">含むすべての最低限必要な入力を作成するリソースの仮想ネットワーク定義のステージ (WithCreate.create()) を使用してサブネットを追加することを除き、指定する省略可能なその他の設定も可能ですが。</span><span class="sxs-lookup"><span data-stu-id="ca1df-101">The stage of the virtual network definition which contains all the minimum required inputs for the resource to be created (via  WithCreate.create()), but also allows for any other optional settings to be specified, except for adding subnets.</span></span>
            <span data-ttu-id="ca1df-102">サブネットに追加できるだけ右後、アドレス空間が明示的に指定された (WithCreate.withAddressSpace(String)) 参照します。</span><span class="sxs-lookup"><span data-stu-id="ca1df-102">Subnets can be added only right after the address space is explicitly specified (see  WithCreate.withAddressSpace(String)).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAddressSpace">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet WithAddressSpace (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet WithAddressSpace(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate.WithAddressSpace(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAddressSpace (cidr As String) As IWithCreateAndSubnet" />
      <MemberSignature Language="F#" Value="abstract member WithAddressSpace : string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet" Usage="iWithCreate.WithAddressSpace cidr" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cidr"><span data-ttu-id="ca1df-103">アドレス空間の CIDR 表記します。</span><span class="sxs-lookup"><span data-stu-id="ca1df-103">The CIDR representation of the address space.</span></span></param>
        <summary>
            <span data-ttu-id="ca1df-104">仮想ネットワークにアドレス空間が明示的に追加します。</span><span class="sxs-lookup"><span data-stu-id="ca1df-104">Explicitly adds an address space to the virtual network.</span></span>
            <span data-ttu-id="ca1df-105">アドレス空間を明示的に指定していない場合、既定ではアドレス空間 CIDR「10.0.0.0/16」は、仮想ネットワークに割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="ca1df-105">If no address spaces are explicitly specified, a default address space with the CIDR "10.0.0.0/16" will be assigned to the virtual network.</span></span>
            <span data-ttu-id="ca1df-106">このメソッドの効果は加法、つまりそれを使用するたび、新しいアドレス空間がネットワークに追加します。</span><span class="sxs-lookup"><span data-stu-id="ca1df-106">Note that this method's effect is additive, i.e. each time it is used, a new address space is added to the network.</span></span>
            <span data-ttu-id="ca1df-107">このメソッドは、競合をチェックしませんまたはその他のアドレス空間と重複しています。</span><span class="sxs-lookup"><span data-stu-id="ca1df-107">This method does not check for conflicts or overlaps with other address spaces.</span></span> <span data-ttu-id="ca1df-108">競合がある場合は、ネットワークの作成時にクラウド例外がスローされる可能性がします。</span><span class="sxs-lookup"><span data-stu-id="ca1df-108">If there is a conflict, a cloud exception may be thrown at the time the network is created.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ca1df-109">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ca1df-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithDnsServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate WithDnsServer (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate WithDnsServer(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate.WithDnsServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDnsServer (ipAddress As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDnsServer : string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate" Usage="iWithCreate.WithDnsServer ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="ca1df-110">DNS サーバーの IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="ca1df-110">The IP address of the DNS server.</span></span></param>
        <summary>
            <span data-ttu-id="ca1df-111">仮想ネットワークに関連付ける既存の DNS サーバーの IP アドレスを指定します。</span><span class="sxs-lookup"><span data-stu-id="ca1df-111">Specifies the IP address of an existing DNS server to associate with the virtual network.</span></span>
            <span data-ttu-id="ca1df-112">このメソッドの効果は加法、つまりそれを使用するたび、新しい dns サーバーがネットワークに追加します。</span><span class="sxs-lookup"><span data-stu-id="ca1df-112">Note this method's effect is additive, i.e. each time it is used, a new dns server is added to the network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ca1df-113">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ca1df-113">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>