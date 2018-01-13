<Type Name="IWithInboundNatRule" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatRule">
  <TypeSignature Language="C#" Value="public interface IWithInboundNatRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInboundNatRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInboundNatRule" />
  <TypeSignature Language="F#" Value="type IWithInboundNatRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ロード バランサーのステージでは、定義、削除、または受信 NAT 規則を編集する許可を更新します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineInboundNatRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineInboundNatRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatRule.DefineInboundNatRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineInboundNatRule (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineInboundNatRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;" Usage="iWithInboundNatRule.DefineInboundNatRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">受信 NAT 規則の名前。</param>
        <summary>
            新規の受信 NAT 規則の定義を開始します。
            定義は、LoadBalancerInboundNatRule.UpdateDefinitionStages.WithAttach.attach() への呼び出しで完了する必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>新しいの着信 NAT ルール定義の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IUpdate UpdateInboundNatRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IUpdate UpdateInboundNatRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatRule.UpdateInboundNatRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateInboundNatRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateInboundNatRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IUpdate" Usage="iWithInboundNatRule.UpdateInboundNatRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">更新する受信 NAT 規則の名前。</param>
        <summary>
            更新プログラムを既存の受信 NAT 規則の説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>着信 NAT ルールの更新の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutInboundNatRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutInboundNatRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatRule.WithoutInboundNatRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutInboundNatRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutInboundNatRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate" Usage="iWithInboundNatRule.WithoutInboundNatRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">このロード バランサー上には既存の受信 NAT 規則の名前。</param>
        <summary>
            ロード バランサーから指定した受信 NAT 規則を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>