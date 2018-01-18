<Type Name="ITrafficManagerAzureEndpoint" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerAzureEndpoint">
  <TypeSignature Language="C#" Value="public interface ITrafficManagerAzureEndpoint : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint&gt;, Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITrafficManagerAzureEndpoint implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource`2&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint, class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint&gt;, class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerAzureEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITrafficManagerAzureEndpoint&#xA;Implements IChildResource(Of ITrafficManagerProfile), IExternalChildResource(Of ITrafficManagerEndpoint, ITrafficManagerProfile), IHasInner(Of EndpointInner), IHasParent(Of ITrafficManagerProfile), IRefreshable(Of ITrafficManagerEndpoint), ITrafficManagerEndpoint" />
  <TypeSignature Language="F#" Value="type ITrafficManagerAzureEndpoint = interface&#xA;    interface ITrafficManagerEndpoint&#xA;    interface IExternalChildResource&lt;ITrafficManagerEndpoint, ITrafficManagerProfile&gt;&#xA;    interface IChildResource&lt;ITrafficManagerProfile&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;ITrafficManagerProfile&gt;&#xA;    interface IRefreshable&lt;ITrafficManagerEndpoint&gt;&#xA;    interface IHasInner&lt;EndpointInner&gt;" />
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
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="94a5f-101">Azure traffic manager プロファイルの Azure エンドポイントの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="94a5f-101">An immutable client-side representation of an Azure traffic manager profile Azure endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="TargetAzureResourceId">
      <MemberSignature Language="C#" Value="public string TargetAzureResourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetAzureResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerAzureEndpoint.TargetAzureResourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetAzureResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetAzureResourceId : string" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerAzureEndpoint.TargetAzureResourceId" />
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
            <span data-ttu-id="94a5f-102">ターゲットの Azure リソースのリソース id を取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5f-102">Gets the resource id of the target Azure resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TargetAzureResourceType TargetResourceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Fluent.TargetAzureResourceType TargetResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerAzureEndpoint.TargetResourceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetResourceType As TargetAzureResourceType" />
      <MemberSignature Language="F#" Value="member this.TargetResourceType : Microsoft.Azure.Management.TrafficManager.Fluent.TargetAzureResourceType" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerAzureEndpoint.TargetResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TargetAzureResourceType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94a5f-103">ターゲットの Azure リソースの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5f-103">Gets the type of the target Azure resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>