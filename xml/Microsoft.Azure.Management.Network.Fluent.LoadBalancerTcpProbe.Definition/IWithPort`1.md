<Type Name="IWithPort&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Definition.IWithPort&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPort&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPort`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Definition.IWithPort`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPort(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithPort&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="b7230-101">親リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="b7230-101">The parent resource type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="b7230-102">TCP のステージでは、定義できるように監視するポート番号を指定するをプローブします。</span><span class="sxs-lookup"><span data-stu-id="b7230-102">The stage of the TCP probe definition allowing to specify the port number to monitor.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Definition.IWithAttach&lt;ParentT&gt; WithPort (int port);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Definition.IWithAttach`1&lt;!ParentT&gt; WithPort(int32 port) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Definition.IWithPort`1.WithPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPort (port As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithPort.WithPort port" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="port" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="port"><span data-ttu-id="b7230-103">ポート番号です。</span><span class="sxs-lookup"><span data-stu-id="b7230-103">A port number.</span></span></param>
        <summary>
            <span data-ttu-id="b7230-104">正常性の監視を呼び出すためのポート番号を指定します。</span><span class="sxs-lookup"><span data-stu-id="b7230-104">Specifies the port number to call for health monitoring.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b7230-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b7230-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>