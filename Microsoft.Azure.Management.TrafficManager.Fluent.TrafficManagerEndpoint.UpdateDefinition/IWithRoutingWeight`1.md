<Type Name="IWithRoutingWeight&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithRoutingWeight&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithRoutingWeight&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRoutingWeight`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithRoutingWeight`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRoutingWeight(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithRoutingWeight&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">WithAttach.attach() の戻り値の型。</typeparam>
    <summary>
            エンドポイントの重み係数の指定を許可する traffic manager エンドポイントの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRoutingWeight">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithRoutingWeight (int weight);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithRoutingWeight(int32 weight) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithRoutingWeight`1.WithRoutingWeight(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRoutingWeight (weight As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithRoutingWeight : int -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithRoutingWeight.WithRoutingWeight weight" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
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
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>