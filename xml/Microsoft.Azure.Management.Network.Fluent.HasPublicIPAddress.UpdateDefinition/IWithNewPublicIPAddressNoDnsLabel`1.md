<Type Name="IWithNewPublicIPAddressNoDnsLabel&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.UpdateDefinition.IWithNewPublicIPAddressNoDnsLabel&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNewPublicIPAddressNoDnsLabel&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNewPublicIPAddressNoDnsLabel`1&lt;ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.UpdateDefinition.IWithNewPublicIPAddressNoDnsLabel`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNewPublicIPAddressNoDnsLabel(Of ReturnT)" />
  <TypeSignature Language="F#" Value="type IWithNewPublicIPAddressNoDnsLabel&lt;'ReturnT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ReturnT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ReturnT"><span data-ttu-id="101e3-101">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="101e3-101">The next stage of the definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="101e3-102">関連付ける新しいパブリック IP アドレス リソースを許可する、定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="101e3-102">The stage of the definition allowing to associate the resource with a new public IP address.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewPublicIPAddress">
      <MemberSignature Language="C#" Value="public ReturnT WithNewPublicIPAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithNewPublicIPAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.UpdateDefinition.IWithNewPublicIPAddressNoDnsLabel`1.WithNewPublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPublicIPAddress () As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithNewPublicIPAddress : unit -&gt; 'ReturnT" Usage="iWithNewPublicIPAddressNoDnsLabel.WithNewPublicIPAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="101e3-103">同じリージョンと、リソースとグループに新しいパブリック IP アドレスを作成し、リソースに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="101e3-103">Creates a new public IP address in the same region and group as the resource and associates it with the resource.</span></span>
            <span data-ttu-id="101e3-104">内部名とパブリック IP アドレスの DNS ラベルは、リソース名から派生します。</span><span class="sxs-lookup"><span data-stu-id="101e3-104">The internal name and DNS label for the public IP address will be derived from the resource's name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="101e3-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="101e3-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPublicIPAddress">
      <MemberSignature Language="C#" Value="public ReturnT WithNewPublicIPAddress (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithNewPublicIPAddress(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.UpdateDefinition.IWithNewPublicIPAddressNoDnsLabel`1.WithNewPublicIPAddress(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPublicIPAddress (creatable As ICreatable(Of IPublicIPAddress)) As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithNewPublicIPAddress : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; -&gt; 'ReturnT" Usage="iWithNewPublicIPAddressNoDnsLabel.WithNewPublicIPAddress creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable"><span data-ttu-id="101e3-106">新しいパブリック IP の作成可能な定義です。</span><span class="sxs-lookup"><span data-stu-id="101e3-106">A creatable definition for a new public IP.</span></span></param>
        <summary>
            <span data-ttu-id="101e3-107">リソースに関連付ける新しいパブリック IP アドレスを作成します。</span><span class="sxs-lookup"><span data-stu-id="101e3-107">Creates a new public IP address to associate with the resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="101e3-108">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="101e3-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>