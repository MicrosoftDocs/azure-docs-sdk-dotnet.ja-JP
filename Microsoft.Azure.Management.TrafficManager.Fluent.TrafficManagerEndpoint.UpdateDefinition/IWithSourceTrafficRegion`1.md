<Type Name="IWithSourceTrafficRegion&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithSourceTrafficRegion&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSourceTrafficRegion&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSourceTrafficRegion`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithSourceTrafficRegion`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSourceTrafficRegion(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithSourceTrafficRegion&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="6628b-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="6628b-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="6628b-102">外部エンドポイントの場所を指定できるように、traffic manager エンドポイント定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="6628b-102">The stage of the traffic manager endpoint definition allowing to specify the location of the external endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromRegion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;ParentT&gt; FromRegion (Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; FromRegion(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithSourceTrafficRegion`1.FromRegion(Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region)" />
      <MemberSignature Language="F#" Value="abstract member FromRegion : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithSourceTrafficRegion.FromRegion region" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="region" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" />
      </Parameters>
      <Docs>
        <param name="region"><span data-ttu-id="6628b-103">場所。</span><span class="sxs-lookup"><span data-stu-id="6628b-103">The location.</span></span></param>
        <summary>
            <span data-ttu-id="6628b-104">パフォーマンスのルーティング メソッド TrafficRoutingMethod.PERFORMANCE を使用して、親プロファイルが構成されている場合に使用されるエンドポイントの場所を指定します。</span><span class="sxs-lookup"><span data-stu-id="6628b-104">Specifies the location of the endpoint that will be used when the parent profile is configured with Performance routing method  TrafficRoutingMethod.PERFORMANCE.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="6628b-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="6628b-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>