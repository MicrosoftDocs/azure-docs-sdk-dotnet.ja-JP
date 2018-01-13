<Type Name="IWithRoutingPriority&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithRoutingPriority&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithRoutingPriority&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRoutingPriority`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithRoutingPriority`1" />
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
    <typeparam name="ParentT"><span data-ttu-id="36b65-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="36b65-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="36b65-102">エンドポイントの優先度を指定できるように、traffic manager エンドポイント定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="36b65-102">The stage of the traffic manager endpoint definition allowing to specify the endpoint priority.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRoutingPriority">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithRoutingPriority (int priority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithRoutingPriority(int32 priority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithRoutingPriority`1.WithRoutingPriority(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRoutingPriority (priority As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithRoutingPriority : int -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithRoutingPriority.WithRoutingPriority priority" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="priority" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="priority">
            <span data-ttu-id="36b65-103">このエンドポイントの優先順位。</span><span class="sxs-lookup"><span data-stu-id="36b65-103">Priority of this endpoint.</span></span> <span data-ttu-id="36b65-104">使用可能な値は、1 ~ 1000、値と低い値が高い優先順位を表します。</span><span class="sxs-lookup"><span data-stu-id="36b65-104">Possible values are from 1 to 1000, lower values represent higher priority.</span></span>
            </param>
        <summary>
            <span data-ttu-id="36b65-105">優先順位ベースのルーティング メソッドは TrafficRoutingMethod.PRIORITY プロファイルで有効になっているときに使用されるエンドポイントの重みを指定します。</span><span class="sxs-lookup"><span data-stu-id="36b65-105">Specifies the weight for the endpoint that will be used when priority-based routing method is  TrafficRoutingMethod.PRIORITY enabled on the profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="36b65-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="36b65-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>