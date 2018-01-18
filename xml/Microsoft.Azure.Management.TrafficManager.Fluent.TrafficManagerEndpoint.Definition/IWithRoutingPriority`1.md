<Type Name="IWithRoutingPriority&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithRoutingPriority&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithRoutingPriority&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRoutingPriority`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithRoutingPriority`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRoutingPriority(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithRoutingPriority&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="4ad7a-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="4ad7a-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="4ad7a-102">エンドポイントの優先度を指定できるように、traffic manager エンドポイント定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="4ad7a-102">The stage of the traffic manager endpoint definition allowing to specify the endpoint priority.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRoutingPriority">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;ParentT&gt; WithRoutingPriority (int priority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach`1&lt;!ParentT&gt; WithRoutingPriority(int32 priority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithRoutingPriority`1.WithRoutingPriority(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRoutingPriority (priority As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithRoutingPriority : int -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithRoutingPriority.WithRoutingPriority priority" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="priority" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="priority"><span data-ttu-id="4ad7a-103">エンドポイントの優先度。</span><span class="sxs-lookup"><span data-stu-id="4ad7a-103">The endpoint priority.</span></span></param>
        <summary>
            <span data-ttu-id="4ad7a-104">優先度ルーティング メソッド TrafficRoutingMethod.PRIORITY を使用して、親プロファイルが構成されている場合に使用されるエンドポイントの優先順位を指定します。</span><span class="sxs-lookup"><span data-stu-id="4ad7a-104">Specifies the priority for the endpoint that will be used when the parent profile is configured with Priority routing method  TrafficRoutingMethod.PRIORITY.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4ad7a-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="4ad7a-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>