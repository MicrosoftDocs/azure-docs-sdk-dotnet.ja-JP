<Type Name="IWithIdleTimeout&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IWithIdleTimeout&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithIdleTimeout&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIdleTimeout`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IWithIdleTimeout`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIdleTimeout(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithIdleTimeout&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">親のロード バランサーの種類。</typeparam>
    <summary>
            この受信 NAT 規則のアイドル状態の接続タイムアウトを指定を許可する受信の NAT ルール定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IWithAttach&lt;ParentT&gt; WithIdleTimeoutInMinutes (int minutes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IWithAttach`1&lt;!ParentT&gt; WithIdleTimeoutInMinutes(int32 minutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IWithIdleTimeout`1.WithIdleTimeoutInMinutes(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIdleTimeoutInMinutes (minutes As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithIdleTimeoutInMinutes : int -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithIdleTimeout.WithIdleTimeoutInMinutes minutes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="minutes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minutes">分数。</param>
        <summary>
            アイドル接続のタイムアウト時間を分単位で指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>