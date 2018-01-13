<Type Name="IWithTimeout&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithTimeout&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithTimeout&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTimeout`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithTimeout`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTimeout(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithTimeout&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るには、親アプリケーション ゲートウェイ定義の段階です。</typeparam>
    <summary>
            アプリケーション ゲートウェイ プローブ定義できるようにする、プローブと考えられる after の時間を指定の段階が失敗しました。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithTimeoutInSeconds (int seconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithTimeoutInSeconds(int32 seconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithTimeout`1.WithTimeoutInSeconds(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTimeoutInSeconds (seconds As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTimeoutInSeconds : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithTimeout.WithTimeoutInSeconds seconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="seconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="seconds">1 ~ 86400 秒の数。</param>
        <summary>
            プローブと見なされるまで、応答の待機に失敗しました (秒) の時間を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>