<Type Name="IWithIntervalInSeconds&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithIntervalInSeconds&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithIntervalInSeconds&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIntervalInSeconds`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithIntervalInSeconds`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIntervalInSeconds(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithIntervalInSeconds&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="e8f71-101">親リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="e8f71-101">The parent resource type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="e8f71-102">HTTP プローブ定義できるようにするプローブの期間を指定の段階です。</span><span class="sxs-lookup"><span data-stu-id="e8f71-102">The stage of the HTTP probe definition allowing to specify the probe interval.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIntervalInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithAttach&lt;ParentT&gt; WithIntervalInSeconds (int seconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithAttach`1&lt;!ParentT&gt; WithIntervalInSeconds(int32 seconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithIntervalInSeconds`1.WithIntervalInSeconds(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIntervalInSeconds (seconds As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithIntervalInSeconds : int -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithIntervalInSeconds.WithIntervalInSeconds seconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="seconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="seconds"><span data-ttu-id="e8f71-103">秒数。</span><span class="sxs-lookup"><span data-stu-id="e8f71-103">Number of seconds.</span></span></param>
        <summary>
            <span data-ttu-id="e8f71-104">秒単位でのプローブの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="e8f71-104">Specifies the interval between probes, in seconds.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e8f71-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e8f71-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>