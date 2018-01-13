<Type Name="ITrafficManagerProfile" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile">
  <TypeSignature Language="C#" Value="public interface ITrafficManagerProfile : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManager,Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITrafficManagerProfile implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManager, class Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITrafficManagerProfile&#xA;Implements IGroupableResource(Of ITrafficManager, ProfileInner), IHasInner(Of ProfileInner), IHasManager(Of ITrafficManager), IRefreshable(Of ITrafficManagerProfile), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type ITrafficManagerProfile = interface&#xA;    interface IGroupableResource&lt;ITrafficManager, ProfileInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;ITrafficManager&gt;&#xA;    interface IHasInner&lt;ProfileInner&gt;&#xA;    interface IRefreshable&lt;ITrafficManagerProfile&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManager,Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="17396-101">Azure traffic manager プロファイルの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="17396-101">An immutable client-side representation of an Azure traffic manager profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AzureEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerAzureEndpoint&gt; AzureEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerAzureEndpoint&gt; AzureEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.AzureEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AzureEndpoints As IReadOnlyDictionary(Of String, ITrafficManagerAzureEndpoint)" />
      <MemberSignature Language="F#" Value="member this.AzureEndpoints : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerAzureEndpoint&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.AzureEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerAzureEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17396-102">名前によってインデックス付けされた、traffic manager プロファイルでは、Azure エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="17396-102">Gets Azure endpoints in the traffic manager profile, indexed by the name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsLabel">
      <MemberSignature Language="C#" Value="public string DnsLabel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DnsLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.DnsLabel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DnsLabel As String" />
      <MemberSignature Language="F#" Value="member this.DnsLabel : string" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.DnsLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17396-103">Traffic manager プロファイルの相対 DNS 名を取得します。</span><span class="sxs-lookup"><span data-stu-id="17396-103">Gets the relative DNS name of the traffic manager profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExternalEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerExternalEndpoint&gt; ExternalEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerExternalEndpoint&gt; ExternalEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.ExternalEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExternalEndpoints As IReadOnlyDictionary(Of String, ITrafficManagerExternalEndpoint)" />
      <MemberSignature Language="F#" Value="member this.ExternalEndpoints : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerExternalEndpoint&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.ExternalEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerExternalEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17396-104">Traffic manager プロファイルを名前によってインデックス設定内の外部エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="17396-104">Gets external endpoints in the traffic manager profile, indexed by the name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fqdn">
      <MemberSignature Language="C#" Value="public string Fqdn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Fqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.Fqdn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Fqdn As String" />
      <MemberSignature Language="F#" Value="member this.Fqdn : string" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.Fqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17396-105">Traffic manager プロファイルの完全修飾ドメイン名 (FQDN) を取得します。</span><span class="sxs-lookup"><span data-stu-id="17396-105">Gets fully qualified domain name (FQDN) of the traffic manager profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsEnabled">
      <MemberSignature Language="C#" Value="public bool IsEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.IsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsEnabled : bool" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.IsEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17396-106">Traffic manager プロファイルが有効な場合は false を指定すると有効になっている場合は true を取得します。</span><span class="sxs-lookup"><span data-stu-id="17396-106">Gets true if the traffic manager profile is enabled, false if enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitoringPath">
      <MemberSignature Language="C#" Value="public string MonitoringPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MonitoringPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.MonitoringPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MonitoringPath As String" />
      <MemberSignature Language="F#" Value="member this.MonitoringPath : string" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.MonitoringPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17396-107">Traffic manager プロファイル エンドポイントの正常性を確認するのには監視があるパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="17396-107">Gets the path that is monitored to check the health of traffic manager profile endpoints.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitoringPort">
      <MemberSignature Language="C#" Value="public long MonitoringPort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MonitoringPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.MonitoringPort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MonitoringPort As Long" />
      <MemberSignature Language="F#" Value="member this.MonitoringPort : int64" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.MonitoringPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17396-108">Traffic manager プロファイル エンドポイントの正常性を確認するのには監視があるポートを取得します。</span><span class="sxs-lookup"><span data-stu-id="17396-108">Gets the port that is monitored to check the health of traffic manager profile endpoints.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitorStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.ProfileMonitorStatus MonitorStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Fluent.ProfileMonitorStatus MonitorStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.MonitorStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MonitorStatus As ProfileMonitorStatus" />
      <MemberSignature Language="F#" Value="member this.MonitorStatus : Microsoft.Azure.Management.TrafficManager.Fluent.ProfileMonitorStatus" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.MonitorStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.ProfileMonitorStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17396-109">プロファイルでは、すべてのエンドポイントのエンドポイント監視状態の値の組み合わせであるプロファイル モニターの状態と構成済みのプロファイル状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="17396-109">Gets profile monitor status which is combination of the endpoint monitor status values for all endpoints in the profile, and the configured profile status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NestedProfileEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerNestedProfileEndpoint&gt; NestedProfileEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerNestedProfileEndpoint&gt; NestedProfileEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.NestedProfileEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NestedProfileEndpoints As IReadOnlyDictionary(Of String, ITrafficManagerNestedProfileEndpoint)" />
      <MemberSignature Language="F#" Value="member this.NestedProfileEndpoints : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerNestedProfileEndpoint&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.NestedProfileEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerNestedProfileEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17396-110">この traffic manager プロファイルの名前によってインデックス設定では、入れ子になった traffic manager のプロファイル エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="17396-110">Gets nested traffic manager profile endpoints in this traffic manager profile, indexed by the name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public long TimeToLive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeToLive As Long" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : int64" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17396-111">DNS 有効期限 (TTL) を秒単位で取得します。</span><span class="sxs-lookup"><span data-stu-id="17396-111">Gets the DNS Time-To-Live (TTL), in seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficRoutingMethod">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod TrafficRoutingMethod { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod TrafficRoutingMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.TrafficRoutingMethod" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TrafficRoutingMethod As TrafficRoutingMethod" />
      <MemberSignature Language="F#" Value="member this.TrafficRoutingMethod : Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.TrafficRoutingMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17396-112">トラフィックを traffic manager プロファイル エンドポイントにルーティングするためのルーティング メソッドを取得します。</span><span class="sxs-lookup"><span data-stu-id="17396-112">Gets the routing method used to route traffic to traffic manager profile endpoints.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>