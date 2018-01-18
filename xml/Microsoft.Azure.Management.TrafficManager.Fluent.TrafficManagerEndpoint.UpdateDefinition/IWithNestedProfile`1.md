<Type Name="IWithNestedProfile&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithNestedProfile&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNestedProfile&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNestedProfile`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithNestedProfile`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNestedProfile(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithNestedProfile&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="75679-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="75679-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="75679-102">Traffic manager のステージでは、プロファイルのエンドポイントの定義を許可する、プロファイルを指定する入れ子になった。</span><span class="sxs-lookup"><span data-stu-id="75679-102">The stage of the traffic manager nested profile endpoint definition allowing to specify the profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithSourceTrafficRegionThenThreshold&lt;ParentT&gt; ToProfile (Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile profile);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithSourceTrafficRegionThenThreshold`1&lt;!ParentT&gt; ToProfile(class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile profile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithNestedProfile`1.ToProfile(Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToProfile (profile As ITrafficManagerProfile) As IWithSourceTrafficRegionThenThreshold(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToProfile : Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithSourceTrafficRegionThenThreshold&lt;'ParentT&gt;" Usage="iWithNestedProfile.ToProfile profile" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithSourceTrafficRegionThenThreshold&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="profile" Type="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile" />
      </Parameters>
      <Docs>
        <param name="profile"><span data-ttu-id="75679-103">入れ子になった traffic manager プロファイルでします。</span><span class="sxs-lookup"><span data-stu-id="75679-103">The nested traffic manager profile.</span></span></param>
        <summary>
            <span data-ttu-id="75679-104">エンドポイントの入れ子になった traffic manager プロファイルを指定します。</span><span class="sxs-lookup"><span data-stu-id="75679-104">Specifies a nested traffic manager profile for the endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="75679-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="75679-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>