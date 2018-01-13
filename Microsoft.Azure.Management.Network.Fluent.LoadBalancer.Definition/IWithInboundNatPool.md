<Type Name="IWithInboundNatPool" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithInboundNatPool">
  <TypeSignature Language="C#" Value="public interface IWithInboundNatPool" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInboundNatPool" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithInboundNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInboundNatPool" />
  <TypeSignature Language="F#" Value="type IWithInboundNatPool = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="79fa5-101">仮想マシンのスケールの新しい着信 NAT プールの作成を許可するロード バランサーの定義のステージを設定します。</span><span class="sxs-lookup"><span data-stu-id="79fa5-101">The stage of a load balancer definition allowing to create a new inbound NAT pool for a virtual machine scale set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineInboundNatPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatPool&gt; DefineInboundNatPool (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatPool&gt; DefineInboundNatPool(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithInboundNatPool.DefineInboundNatPool(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineInboundNatPool (name As String) As IBlank(Of IWithCreateAndInboundNatPool)" />
      <MemberSignature Language="F#" Value="abstract member DefineInboundNatPool : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatPool&gt;" Usage="iWithInboundNatPool.DefineInboundNatPool name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="79fa5-102">着信 NAT プールの名前。</span><span class="sxs-lookup"><span data-stu-id="79fa5-102">The name of the inbound NAT pool.</span></span></param>
        <summary>
            <span data-ttu-id="79fa5-103">ロード バランサーに追加する新しい inbount NAT プールの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="79fa5-103">Begins the definition of a new inbount NAT pool to add to the load balancer.</span></span>
            <span data-ttu-id="79fa5-104">定義は、LoadBalancerInboundNatPool.DefinitionStages.WithAttach.attach() への呼び出しで完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="79fa5-104">The definition must be completed with a call to  LoadBalancerInboundNatPool.DefinitionStages.WithAttach.attach().</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="79fa5-105">新しいの着信 NAT プール定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="79fa5-105">The first stage of the new inbound NAT pool definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>