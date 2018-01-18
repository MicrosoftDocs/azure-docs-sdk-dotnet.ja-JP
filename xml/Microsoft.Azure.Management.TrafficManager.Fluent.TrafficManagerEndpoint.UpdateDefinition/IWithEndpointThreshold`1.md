<Type Name="IWithEndpointThreshold&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithEndpointThreshold&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithEndpointThreshold&lt;ParentT&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;ParentT&gt;, Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;ParentT&gt;, Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithGeographicLocation&lt;ParentT&gt;, Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithRoutingPriority&lt;ParentT&gt;, Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithRoutingWeight&lt;ParentT&gt;, Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithTrafficDisabled&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithEndpointThreshold`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithGeographicLocation`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithRoutingPriority`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithRoutingWeight`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithTrafficDisabled`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithEndpointThreshold`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithEndpointThreshold(Of ParentT)&#xA;Implements IInUpdate(Of ParentT), IWithAttach(Of ParentT), IWithGeographicLocation(Of ParentT), IWithRoutingPriority(Of ParentT), IWithRoutingWeight(Of ParentT), IWithTrafficDisabled(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithEndpointThreshold&lt;'ParentT&gt; = interface&#xA;    interface IWithAttach&lt;'ParentT&gt;&#xA;    interface IInUpdate&lt;'ParentT&gt;&#xA;    interface IWithRoutingWeight&lt;'ParentT&gt;&#xA;    interface IWithRoutingPriority&lt;'ParentT&gt;&#xA;    interface IWithGeographicLocation&lt;'ParentT&gt;&#xA;    interface IWithTrafficDisabled&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithGeographicLocation&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithRoutingPriority&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithRoutingWeight&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithTrafficDisabled&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="0bd15-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="0bd15-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="0bd15-102">オンラインされませんが低下として考慮する、入れ子になったプロファイルである最小のエンドポイントを指定を許可する入れ子になった traffic manager プロファイル エンドポイント定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="0bd15-102">The stage of the nested traffic manager profile endpoint definition allowing to specify the minimum endpoints to be online in the nested profile to consider it as not degraded.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMinimumEndpointsToEnableTraffic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithMinimumEndpointsToEnableTraffic (int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithMinimumEndpointsToEnableTraffic(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithEndpointThreshold`1.WithMinimumEndpointsToEnableTraffic(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMinimumEndpointsToEnableTraffic (count As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithMinimumEndpointsToEnableTraffic : int -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithEndpointThreshold.WithMinimumEndpointsToEnableTraffic count" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="count"><span data-ttu-id="0bd15-103">エンドポイントの数。</span><span class="sxs-lookup"><span data-stu-id="0bd15-103">The number of endpoints.</span></span></param>
        <summary>
            <span data-ttu-id="0bd15-104">正常と見なされるには、入れ子になったプロファイルをオンラインにするエンドポイントの最小数を指定します。</span><span class="sxs-lookup"><span data-stu-id="0bd15-104">Specifies the minimum number of endpoints to be online for the nested profile to be considered healthy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0bd15-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0bd15-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>