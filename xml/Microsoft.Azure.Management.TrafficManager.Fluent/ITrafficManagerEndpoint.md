<Type Name="ITrafficManagerEndpoint" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint">
  <TypeSignature Language="C#" Value="public interface ITrafficManagerEndpoint : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITrafficManagerEndpoint implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource`2&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint, class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITrafficManagerEndpoint&#xA;Implements IChildResource(Of ITrafficManagerProfile), IExternalChildResource(Of ITrafficManagerEndpoint, ITrafficManagerProfile), IHasInner(Of EndpointInner), IHasParent(Of ITrafficManagerProfile), IRefreshable(Of ITrafficManagerEndpoint)" />
  <TypeSignature Language="F#" Value="type ITrafficManagerEndpoint = interface&#xA;    interface IExternalChildResource&lt;ITrafficManagerEndpoint, ITrafficManagerProfile&gt;&#xA;    interface IChildResource&lt;ITrafficManagerProfile&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;ITrafficManagerProfile&gt;&#xA;    interface IRefreshable&lt;ITrafficManagerEndpoint&gt;&#xA;    interface IHasInner&lt;EndpointInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="05490-101">Azure traffic manager プロファイル エンドポイントの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="05490-101">An immutable client-side representation of an Azure traffic manager profile endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EndpointType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.EndpointType EndpointType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Fluent.EndpointType EndpointType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint.EndpointType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndpointType As EndpointType" />
      <MemberSignature Language="F#" Value="member this.EndpointType : Microsoft.Azure.Management.TrafficManager.Fluent.EndpointType" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint.EndpointType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.EndpointType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="05490-102">エンドポイントの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="05490-102">Gets the endpoint type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeographicLocationCodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; GeographicLocationCodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; GeographicLocationCodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint.GeographicLocationCodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GeographicLocationCodes As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.GeographicLocationCodes : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint.GeographicLocationCodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsEnabled">
      <MemberSignature Language="C#" Value="public bool IsEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint.IsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsEnabled : bool" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint.IsEnabled" />
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
            <span data-ttu-id="05490-103">True の場合、有効な場合は false がそれ以外の場合は、エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="05490-103">Gets true if the endpoint is enabled, false otherwise.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitorStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.EndpointMonitorStatus MonitorStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Fluent.EndpointMonitorStatus MonitorStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint.MonitorStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MonitorStatus As EndpointMonitorStatus" />
      <MemberSignature Language="F#" Value="member this.MonitorStatus : Microsoft.Azure.Management.TrafficManager.Fluent.EndpointMonitorStatus" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint.MonitorStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.EndpointMonitorStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="05490-104">エンドポイントの監視の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="05490-104">Gets the monitor status of the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RoutingPriority">
      <MemberSignature Language="C#" Value="public long RoutingPriority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 RoutingPriority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint.RoutingPriority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RoutingPriority As Long" />
      <MemberSignature Language="F#" Value="member this.RoutingPriority : int64" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint.RoutingPriority" />
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
            <span data-ttu-id="05490-105">優先度のトラフィック ルーティング メソッドを使用して traffic manager プロファイルが構成されているときに使用されるエンドポイントの優先度を取得します。</span><span class="sxs-lookup"><span data-stu-id="05490-105">Gets the priority of the endpoint which is used when traffic manager profile is configured with Priority traffic-routing method.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RoutingWeight">
      <MemberSignature Language="C#" Value="public long RoutingWeight { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 RoutingWeight" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint.RoutingWeight" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RoutingWeight As Long" />
      <MemberSignature Language="F#" Value="member this.RoutingWeight : int64" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint.RoutingWeight" />
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
            <span data-ttu-id="05490-106">加重のトラフィックをルーティング メソッドを使用して traffic manager プロファイルが構成されているときに使用されるエンドポイントの重みを取得します。</span><span class="sxs-lookup"><span data-stu-id="05490-106">Gets the weight of the endpoint which is used when traffic manager profile is configured with Weighted traffic-routing method.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>