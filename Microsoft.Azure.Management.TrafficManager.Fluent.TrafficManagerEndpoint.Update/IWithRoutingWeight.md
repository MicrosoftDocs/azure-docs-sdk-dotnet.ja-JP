<Type Name="IWithRoutingWeight" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithRoutingWeight">
  <TypeSignature Language="C#" Value="public interface IWithRoutingWeight" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRoutingWeight" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithRoutingWeight" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRoutingWeight" />
  <TypeSignature Language="F#" Value="type IWithRoutingWeight = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            トラフィック マネージャー プロファイル エンドポイントのエンドポイントの重み係数の指定を許可する更新の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRoutingWeight">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate WithRoutingWeight (int weight);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate WithRoutingWeight(int32 weight) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithRoutingWeight.WithRoutingWeight(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRoutingWeight (weight As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithRoutingWeight : int -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate" Usage="iWithRoutingWeight.WithRoutingWeight weight" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="weight" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="weight">エンドポイントの太さ。</param>
        <summary>
            重量ベースのルーティング メソッド TrafficRoutingMethod.WEIGHTED がプロファイルに有効になっているときに使用されるエンドポイントの重みを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>