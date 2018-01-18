<Type Name="IWithNetworkSecurityGroup" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithNetworkSecurityGroup">
  <TypeSignature Language="C#" Value="public interface IWithNetworkSecurityGroup" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNetworkSecurityGroup" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithNetworkSecurityGroup" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNetworkSecurityGroup" />
  <TypeSignature Language="F#" Value="type IWithNetworkSecurityGroup = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="abdfb-101">ネットワーク セキュリティ グループを関連付けるを許可するネットワーク インターフェイスの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="abdfb-101">The stage of the network interface definition allowing to associate a network security group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingNetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithExistingNetworkSecurityGroup (Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup networkSecurityGroup);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithExistingNetworkSecurityGroup(class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup networkSecurityGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithNetworkSecurityGroup.WithExistingNetworkSecurityGroup(Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingNetworkSecurityGroup (networkSecurityGroup As INetworkSecurityGroup) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingNetworkSecurityGroup : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithNetworkSecurityGroup.WithExistingNetworkSecurityGroup networkSecurityGroup" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="networkSecurityGroup" Type="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup" />
      </Parameters>
      <Docs>
        <param name="networkSecurityGroup"><span data-ttu-id="abdfb-102">既存のネットワーク セキュリティ グループです。</span><span class="sxs-lookup"><span data-stu-id="abdfb-102">An existing network security group.</span></span></param>
        <summary>
            <span data-ttu-id="abdfb-103">既存のネットワーク セキュリティ グループをネットワーク インターフェイスに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="abdfb-103">Associates an existing network security group with the network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="abdfb-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="abdfb-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewNetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithNewNetworkSecurityGroup (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithNewNetworkSecurityGroup(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithNetworkSecurityGroup.WithNewNetworkSecurityGroup(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewNetworkSecurityGroup (creatable As ICreatable(Of INetworkSecurityGroup)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewNetworkSecurityGroup : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithNetworkSecurityGroup.WithNewNetworkSecurityGroup creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable"><span data-ttu-id="abdfb-105">新しいネットワーク セキュリティ グループに対して作成可能な定義です。</span><span class="sxs-lookup"><span data-stu-id="abdfb-105">A creatable definition for a new network security group.</span></span></param>
        <summary>
            <span data-ttu-id="abdfb-106">指定された定義に基づくネットワーク インターフェイスに関連付ける新しいネットワーク セキュリティ グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="abdfb-106">Create a new network security group to associate with network interface, based on the provided definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="abdfb-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="abdfb-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>