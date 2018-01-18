<Type Name="IWithLeafDomainLabel" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithLeafDomainLabel">
  <TypeSignature Language="C#" Value="public interface IWithLeafDomainLabel" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLeafDomainLabel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithLeafDomainLabel" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLeafDomainLabel" />
  <TypeSignature Language="F#" Value="type IWithLeafDomainLabel = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f7a97-101">相対 DNS 名を指定できるように、トラフィック マネージャー プロファイル定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="f7a97-101">The stage of the traffic manager profile definition allowing to specify the relative DNS name.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithLeafDomainLabel">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod WithLeafDomainLabel (string dnsLabel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod WithLeafDomainLabel(string dnsLabel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithLeafDomainLabel.WithLeafDomainLabel(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLeafDomainLabel (dnsLabel As String) As IWithTrafficRoutingMethod" />
      <MemberSignature Language="F#" Value="abstract member WithLeafDomainLabel : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod" Usage="iWithLeafDomainLabel.WithLeafDomainLabel dnsLabel" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dnsLabel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dnsLabel"><span data-ttu-id="f7a97-102">プロファイルの相対 DNS 名。</span><span class="sxs-lookup"><span data-stu-id="f7a97-102">The relative DNS name of the profile.</span></span></param>
        <summary>
            <span data-ttu-id="f7a97-103">プロファイルの相対 DNS 名を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7a97-103">Specify the relative DNS name of the profile.</span></span>
            <span data-ttu-id="f7a97-104">完全修飾ドメイン名 (FQDN) は、このラベルに、ドメインの残りの部分を追加することによって自動的に構築されます。</span><span class="sxs-lookup"><span data-stu-id="f7a97-104">The fully qualified domain name (FQDN) will be constructed automatically by appending the rest of the domain to this label.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f7a97-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f7a97-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>