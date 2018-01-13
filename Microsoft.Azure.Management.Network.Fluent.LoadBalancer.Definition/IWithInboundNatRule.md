<Type Name="IWithInboundNatRule" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithInboundNatRule">
  <TypeSignature Language="C#" Value="public interface IWithInboundNatRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInboundNatRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithInboundNatRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInboundNatRule" />
  <TypeSignature Language="F#" Value="type IWithInboundNatRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            新しい受信 NAT 規則の作成を許可するロード バランサーの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatRule&gt; DefineInboundNatRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatRule&gt; DefineInboundNatRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithInboundNatRule.DefineInboundNatRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineInboundNatRule (name As String) As IBlank(Of IWithCreateAndInboundNatRule)" />
      <MemberSignature Language="F#" Value="abstract member DefineInboundNatRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatRule&gt;" Usage="iWithInboundNatRule.DefineInboundNatRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">受信 NAT 規則の名前。</param>
        <summary>
            ロード バランサーに追加する新規の受信 NAT 規則の定義を開始します。
            定義は、LoadBalancerInboundNatRule.DefinitionStages.WithAttach.attach() への呼び出しで完了する必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>新しいの着信 NAT ルール定義の最初の段階です。</return>
      </Docs>
    </Member>
  </Members>
</Type>