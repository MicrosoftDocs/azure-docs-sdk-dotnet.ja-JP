<Type Name="INetworkSecurityGroup" FullName="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup">
  <TypeSignature Language="C#" Value="public interface INetworkSecurityGroup : Microsoft.Azure.Management.Network.Fluent.IHasAssociatedSubnets, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager,Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract INetworkSecurityGroup implements class Microsoft.Azure.Management.Network.Fluent.IHasAssociatedSubnets, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManager, class Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup" />
  <TypeSignature Language="VB.NET" Value="Public Interface INetworkSecurityGroup&#xA;Implements IGroupableResource(Of INetworkManager, NetworkSecurityGroupInner), IHasAssociatedSubnets, IHasInner(Of NetworkSecurityGroupInner), IHasManager(Of INetworkManager), IRefreshable(Of INetworkSecurityGroup), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type INetworkSecurityGroup = interface&#xA;    interface IGroupableResource&lt;INetworkManager, NetworkSecurityGroupInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;INetworkManager&gt;&#xA;    interface IHasInner&lt;NetworkSecurityGroupInner&gt;&#xA;    interface IRefreshable&lt;INetworkSecurityGroup&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;&#xA;    interface IHasAssociatedSubnets" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasAssociatedSubnets</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager,Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroup.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="37e5a-101">ネットワーク セキュリティ グループです。</span><span class="sxs-lookup"><span data-stu-id="37e5a-101">Network security group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefaultSecurityRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule&gt; DefaultSecurityRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule&gt; DefaultSecurityRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup.DefaultSecurityRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultSecurityRules As IReadOnlyDictionary(Of String, INetworkSecurityRule)" />
      <MemberSignature Language="F#" Value="member this.DefaultSecurityRules : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup.DefaultSecurityRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37e5a-102">このネットワーク セキュリティ グループの名前を指定してインデックスに関連付けられている既定のセキュリティ規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="37e5a-102">Gets default security rules associated with this network security group, indexed by their name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaceIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;string&gt; NetworkInterfaceIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ISet`1&lt;string&gt; NetworkInterfaceIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup.NetworkInterfaceIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkInterfaceIds As ISet(Of String)" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceIds : System.Collections.Generic.ISet&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup.NetworkInterfaceIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37e5a-103">このネットワーク セキュリティ グループに関連付けられているネットワーク インターフェイスの Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="37e5a-103">Gets the IDs of the network interfaces associated with this network security group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule&gt; SecurityRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule&gt; SecurityRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup.SecurityRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecurityRules As IReadOnlyDictionary(Of String, INetworkSecurityRule)" />
      <MemberSignature Language="F#" Value="member this.SecurityRules : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup.SecurityRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37e5a-104">このネットワーク セキュリティ グループの名前のインデックスに関連付けられているセキュリティの規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="37e5a-104">Gets security rules associated with this network security group, indexed by their names.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>