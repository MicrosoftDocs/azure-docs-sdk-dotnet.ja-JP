<Type Name="IWithIntervalInSeconds" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IWithIntervalInSeconds">
  <TypeSignature Language="C#" Value="public interface IWithIntervalInSeconds" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIntervalInSeconds" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IWithIntervalInSeconds" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIntervalInSeconds" />
  <TypeSignature Language="F#" Value="type IWithIntervalInSeconds = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fb0fa-101">TCP のステージでは、プローブの期間の変更を許可する更新プログラムをプローブします。</span><span class="sxs-lookup"><span data-stu-id="fb0fa-101">The stage of the TCP probe update allowing to modify the probe interval.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIntervalInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IUpdate WithIntervalInSeconds (int seconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IUpdate WithIntervalInSeconds(int32 seconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IWithIntervalInSeconds.WithIntervalInSeconds(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIntervalInSeconds (seconds As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithIntervalInSeconds : int -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IUpdate" Usage="iWithIntervalInSeconds.WithIntervalInSeconds seconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="seconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="seconds"><span data-ttu-id="fb0fa-102">秒数。</span><span class="sxs-lookup"><span data-stu-id="fb0fa-102">Number of seconds.</span></span></param>
        <summary>
            <span data-ttu-id="fb0fa-103">秒単位でのプローブの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="fb0fa-103">Specifies the interval between probes, in seconds.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="fb0fa-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="fb0fa-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>