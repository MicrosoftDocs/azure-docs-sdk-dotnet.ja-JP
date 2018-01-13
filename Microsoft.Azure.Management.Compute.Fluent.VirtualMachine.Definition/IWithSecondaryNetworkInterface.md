<Type Name="IWithSecondaryNetworkInterface" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface">
  <TypeSignature Language="C#" Value="public interface IWithSecondaryNetworkInterface" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSecondaryNetworkInterface" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSecondaryNetworkInterface" />
  <TypeSignature Language="F#" Value="type IWithSecondaryNetworkInterface = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0a5c0-101">追加のネットワーク インターフェイスの指定を許可する仮想マシンの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="0a5c0-101">The stage of a virtual machine definition allowing to specify additional network interfaces.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingSecondaryNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithExistingSecondaryNetworkInterface (Microsoft.Azure.Management.Network.Fluent.INetworkInterface networkInterface);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithExistingSecondaryNetworkInterface(class Microsoft.Azure.Management.Network.Fluent.INetworkInterface networkInterface) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface.WithExistingSecondaryNetworkInterface(Microsoft.Azure.Management.Network.Fluent.INetworkInterface)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSecondaryNetworkInterface (networkInterface As INetworkInterface) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSecondaryNetworkInterface : Microsoft.Azure.Management.Network.Fluent.INetworkInterface -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithSecondaryNetworkInterface.WithExistingSecondaryNetworkInterface networkInterface" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="networkInterface" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterface" />
      </Parameters>
      <Docs>
        <param name="networkInterface"><span data-ttu-id="0a5c0-102">既存のネットワーク インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="0a5c0-102">An existing network interface.</span></span></param>
        <summary>
            <span data-ttu-id="0a5c0-103">既存のネットワーク インターフェイスを仮想マシンに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="0a5c0-103">Associates an existing network interface with the virtual machine.</span></span>
            <span data-ttu-id="0a5c0-104">このメソッドの効果は加法、つまりそれを使用するたび、新しいセカンダリ ネットワーク インターフェイス、仮想マシンに追加します。</span><span class="sxs-lookup"><span data-stu-id="0a5c0-104">Note this method's effect is additive, i.e. each time it is used, the new secondary network interface added to the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0a5c0-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0a5c0-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewSecondaryNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewSecondaryNetworkInterface (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewSecondaryNetworkInterface(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface.WithNewSecondaryNetworkInterface(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetworkInterface})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewSecondaryNetworkInterface (creatable As ICreatable(Of INetworkInterface)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewSecondaryNetworkInterface : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithSecondaryNetworkInterface.WithNewSecondaryNetworkInterface creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable"><span data-ttu-id="0a5c0-106">新しいネットワーク インターフェイスの定義を作成可能です。</span><span class="sxs-lookup"><span data-stu-id="0a5c0-106">A creatable definition for a new network interface.</span></span></param>
        <summary>
            <span data-ttu-id="0a5c0-107">指定された定義に基づいて、仮想マシンに関連付ける新しいネットワーク インターフェイスを作成します。</span><span class="sxs-lookup"><span data-stu-id="0a5c0-107">Creates a new network interface to associate with the virtual machine, based on the provided definition.</span></span>
            <span data-ttu-id="0a5c0-108">このメソッドの効果は加法、つまりそれを使用するたび、新しいセカンダリ ネットワーク インターフェイス、仮想マシンに追加します。</span><span class="sxs-lookup"><span data-stu-id="0a5c0-108">Note this method's effect is additive, i.e. each time it is used, a new secondary network interface added to the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0a5c0-109">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0a5c0-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>