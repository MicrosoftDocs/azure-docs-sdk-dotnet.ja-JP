<Type Name="IWithFqdn&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithFqdn&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithFqdn&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFqdn`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithFqdn`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFqdn(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithFqdn&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="34cc2-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="34cc2-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="34cc2-102">トラフィック マネージャー プロファイルの外部エンドポイント定義できるようにするという FQDN を指定する段階です。</span><span class="sxs-lookup"><span data-stu-id="34cc2-102">The stage of the traffic manager profile external endpoint definition allowing to specify the FQDN.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithSourceTrafficRegion&lt;ParentT&gt; ToFqdn (string externalFqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithSourceTrafficRegion`1&lt;!ParentT&gt; ToFqdn(string externalFqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithFqdn`1.ToFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToFqdn (externalFqdn As String) As IWithSourceTrafficRegion(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToFqdn : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithSourceTrafficRegion&lt;'ParentT&gt;" Usage="iWithFqdn.ToFqdn externalFqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithSourceTrafficRegion&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="externalFqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="externalFqdn"><span data-ttu-id="34cc2-103">外部 FQDN。</span><span class="sxs-lookup"><span data-stu-id="34cc2-103">The external FQDN.</span></span></param>
        <summary>
            <span data-ttu-id="34cc2-104">外部エンドポイントの FQDN を指定します。</span><span class="sxs-lookup"><span data-stu-id="34cc2-104">Specifies the FQDN of an external endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="34cc2-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="34cc2-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>