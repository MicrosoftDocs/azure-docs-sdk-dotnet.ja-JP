<Type Name="IWithPort" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IWithPort">
  <TypeSignature Language="C#" Value="public interface IWithPort" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPort" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IWithPort" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPort" />
  <TypeSignature Language="F#" Value="type IWithPort = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7d569-101">HTTP プローブのステージでは、監視するポート番号を変更する許可を更新します。</span><span class="sxs-lookup"><span data-stu-id="7d569-101">The stage of the HTTP probe update allowing to modify the port number to monitor.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IUpdate WithPort (int port);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IUpdate WithPort(int32 port) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IWithPort.WithPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPort (port As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IUpdate" Usage="iWithPort.WithPort port" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="port" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="port"><span data-ttu-id="7d569-102">ポート番号です。</span><span class="sxs-lookup"><span data-stu-id="7d569-102">A port number.</span></span></param>
        <summary>
            <span data-ttu-id="7d569-103">正常性の監視を呼び出すためのポート番号を指定します。</span><span class="sxs-lookup"><span data-stu-id="7d569-103">Specifies the port number to call for health monitoring.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7d569-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="7d569-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>