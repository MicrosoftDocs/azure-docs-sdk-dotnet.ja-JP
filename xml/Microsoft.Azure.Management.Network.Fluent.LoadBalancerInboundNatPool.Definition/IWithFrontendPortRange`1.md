<Type Name="IWithFrontendPortRange&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Definition.IWithFrontendPortRange&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithFrontendPortRange&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontendPortRange`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Definition.IWithFrontendPortRange`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontendPortRange(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithFrontendPortRange&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="06d95-101">親のロード バランサーの種類。</span><span class="sxs-lookup"><span data-stu-id="06d95-101">The parent load balancer type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="06d95-102">フロント エンド ポート範囲を指定するを許可する受信の NAT プール定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="06d95-102">The stage of an inbound NAT pool definition allowing to specify the frontend port range.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromFrontendPortRange">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Definition.IWithBackendPort&lt;ParentT&gt; FromFrontendPortRange (int from, int to);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Definition.IWithBackendPort`1&lt;!ParentT&gt; FromFrontendPortRange(int32 from, int32 to) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Definition.IWithFrontendPortRange`1.FromFrontendPortRange(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromFrontendPortRange (from As Integer, to As Integer) As IWithBackendPort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromFrontendPortRange : int * int -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Definition.IWithBackendPort&lt;'ParentT&gt;" Usage="iWithFrontendPortRange.FromFrontendPortRange (from, to)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Definition.IWithBackendPort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.Int32" />
        <Parameter Name="to" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="from">To be added.</param>
        <param name="to">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>