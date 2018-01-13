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
            トラフィック マネージャー プロファイル エンドポイントのエンドポイントの優先度を指定できるように更新の段階です。
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
        <param name="priority">エンドポイントの優先度。</param>
        <summary>
            優先順位ベースのルーティング メソッドは TrafficRoutingMethod.PRIORITY プロファイルで有効になっているときに使用されるエンドポイントの重みを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>