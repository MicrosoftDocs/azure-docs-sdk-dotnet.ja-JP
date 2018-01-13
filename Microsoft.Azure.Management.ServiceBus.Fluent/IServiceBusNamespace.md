<Type Name="IServiceBusNamespace" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace">
  <TypeSignature Language="C#" Value="public interface IServiceBusNamespace : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceBusNamespace implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceBusNamespace&#xA;Implements IGroupableResource(Of IServiceBusManager, NamespaceModelInner), IHasInner(Of NamespaceModelInner), IHasManager(Of IServiceBusManager), IRefreshable(Of IServiceBusNamespace), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IServiceBusNamespace = interface&#xA;    interface IGroupableResource&lt;IServiceBusManager, NamespaceModelInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IServiceBusManager&gt;&#xA;    interface IHasInner&lt;NamespaceModelInner&gt;&#xA;    interface IRefreshable&lt;IServiceBusNamespace&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="6fd17-101">Azure Service Bus 名前空間の変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="6fd17-101">An immutable client-side representation of an Azure Service Bus namespace.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="6fd17-102">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="6fd17-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthorizationRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.INamespaceAuthorizationRules AuthorizationRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Fluent.INamespaceAuthorizationRules AuthorizationRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace.AuthorizationRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthorizationRules As INamespaceAuthorizationRules" />
      <MemberSignature Language="F#" Value="member this.AuthorizationRules : Microsoft.Azure.Management.ServiceBus.Fluent.INamespaceAuthorizationRules" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace.AuthorizationRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.INamespaceAuthorizationRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fd17-103">Service Bus 名前空間の承認規則を管理するエントリ ポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="6fd17-103">Gets entry point to manage authorization rules for the Service Bus namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fd17-104">名前空間が作成された日時を取得します。</span><span class="sxs-lookup"><span data-stu-id="6fd17-104">Gets time the namespace was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsLabel">
      <MemberSignature Language="C#" Value="public string DnsLabel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DnsLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace.DnsLabel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DnsLabel As String" />
      <MemberSignature Language="F#" Value="member this.DnsLabel : string" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace.DnsLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fd17-105">Service Bus 名前空間の相対 DNS 名を取得します。</span><span class="sxs-lookup"><span data-stu-id="6fd17-105">Gets the relative DNS name of the Service Bus namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fqdn">
      <MemberSignature Language="C#" Value="public string Fqdn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Fqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace.Fqdn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Fqdn As String" />
      <MemberSignature Language="F#" Value="member this.Fqdn : string" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace.Fqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fd17-106">Service Bus 名前空間の完全修飾ドメイン名 (FQDN) を取得します。</span><span class="sxs-lookup"><span data-stu-id="6fd17-106">Gets fully qualified domain name (FQDN) of the Service Bus namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Queues">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.IQueues Queues { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Fluent.IQueues Queues" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace.Queues" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Queues As IQueues" />
      <MemberSignature Language="F#" Value="member this.Queues : Microsoft.Azure.Management.ServiceBus.Fluent.IQueues" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace.Queues" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.IQueues</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fd17-107">Service Bus 名前空間のキュー エンティティを管理するエントリ ポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="6fd17-107">Gets entry point to manage queue entities in the Service Bus namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.NamespaceSku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Fluent.NamespaceSku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As NamespaceSku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.ServiceBus.Fluent.NamespaceSku" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.NamespaceSku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fd17-108">Sku 値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6fd17-108">Gets sku value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Topics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.ITopics Topics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Fluent.ITopics Topics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace.Topics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Topics As ITopics" />
      <MemberSignature Language="F#" Value="member this.Topics : Microsoft.Azure.Management.ServiceBus.Fluent.ITopics" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace.Topics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.ITopics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fd17-109">Service Bus 名前空間にトピック エンティティの管理へのエントリ ポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="6fd17-109">Gets entry point to manage topics entities in the Service Bus namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespace.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fd17-110">名前空間が更新された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="6fd17-110">Gets time the namespace was updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>