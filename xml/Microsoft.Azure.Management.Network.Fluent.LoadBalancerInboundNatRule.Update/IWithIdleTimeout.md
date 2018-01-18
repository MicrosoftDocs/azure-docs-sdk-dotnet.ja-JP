<Type Name="IWithIdleTimeout" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IWithIdleTimeout">
  <TypeSignature Language="C#" Value="public interface IWithIdleTimeout" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIdleTimeout" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IWithIdleTimeout" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIdleTimeout" />
  <TypeSignature Language="F#" Value="type IWithIdleTimeout = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8eeed-101">受信 NAT 規則のステージでは、この受信 NAT 規則のアイドル状態の接続タイムアウトを指定できるようにを更新します。</span><span class="sxs-lookup"><span data-stu-id="8eeed-101">The stage of an inbound NAT rule update allowing to specify the idle connection timeout for this inbound NAT rule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IUpdate WithIdleTimeoutInMinutes (int minutes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IUpdate WithIdleTimeoutInMinutes(int32 minutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IWithIdleTimeout.WithIdleTimeoutInMinutes(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIdleTimeoutInMinutes (minutes As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithIdleTimeoutInMinutes : int -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IUpdate" Usage="iWithIdleTimeout.WithIdleTimeoutInMinutes minutes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="minutes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minutes"><span data-ttu-id="8eeed-102">分数。</span><span class="sxs-lookup"><span data-stu-id="8eeed-102">A number of minutes.</span></span></param>
        <summary>
            <span data-ttu-id="8eeed-103">アイドル接続のタイムアウト時間を分単位で指定します。</span><span class="sxs-lookup"><span data-stu-id="8eeed-103">Specifies the idle connection timeout in minutes.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8eeed-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="8eeed-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>