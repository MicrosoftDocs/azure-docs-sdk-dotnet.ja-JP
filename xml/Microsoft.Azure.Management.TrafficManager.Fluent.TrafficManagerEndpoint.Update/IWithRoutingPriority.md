<Type Name="IWithRoutingPriority" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithRoutingPriority">
  <TypeSignature Language="C#" Value="public interface IWithRoutingPriority" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRoutingPriority" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithRoutingPriority" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRoutingPriority" />
  <TypeSignature Language="F#" Value="type IWithRoutingPriority = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="50c1e-101">トラフィック マネージャー プロファイル エンドポイントのエンドポイントの優先度を指定できるように更新の段階です。</span><span class="sxs-lookup"><span data-stu-id="50c1e-101">The stage of the traffic manager profile endpoint update allowing to specify the endpoint priority.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRoutingPriority">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate WithRoutingPriority (int priority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate WithRoutingPriority(int32 priority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithRoutingPriority.WithRoutingPriority(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRoutingPriority (priority As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithRoutingPriority : int -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate" Usage="iWithRoutingPriority.WithRoutingPriority priority" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="priority" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="priority"><span data-ttu-id="50c1e-102">エンドポイントの優先度。</span><span class="sxs-lookup"><span data-stu-id="50c1e-102">The endpoint priority.</span></span></param>
        <summary>
            <span data-ttu-id="50c1e-103">優先順位ベースのルーティング メソッドは TrafficRoutingMethod.PRIORITY プロファイルで有効になっているときに使用されるエンドポイントの重みを指定します。</span><span class="sxs-lookup"><span data-stu-id="50c1e-103">Specifies the weight for the endpoint that will be used when priority-based routing method is  TrafficRoutingMethod.PRIORITY enabled on the profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="50c1e-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="50c1e-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>