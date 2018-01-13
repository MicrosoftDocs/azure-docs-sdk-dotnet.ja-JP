<Type Name="IWithLoadBalancingRule" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithLoadBalancingRule">
  <TypeSignature Language="C#" Value="public interface IWithLoadBalancingRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLoadBalancingRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithLoadBalancingRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLoadBalancingRule" />
  <TypeSignature Language="F#" Value="type IWithLoadBalancingRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ロード バランサーのステージでは、追加、削除、またはロード バランシング ルールの変更を許可するを更新します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineLoadBalancingRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineLoadBalancingRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineLoadBalancingRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithLoadBalancingRule.DefineLoadBalancingRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineLoadBalancingRule (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineLoadBalancingRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;" Usage="iWithLoadBalancingRule.DefineLoadBalancingRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">負荷分散の規則の名前。</param>
        <summary>
            ロード バランサーに追加する新しい負荷分散規則の定義を開始します。
            定義は、LoadBalancerTcpProbe.DefinitionStages.WithAttach.attach() への呼び出しで完了する必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>新しい負荷分散のルールの定義の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateLoadBalancingRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate UpdateLoadBalancingRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate UpdateLoadBalancingRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithLoadBalancingRule.UpdateLoadBalancingRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateLoadBalancingRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateLoadBalancingRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate" Usage="iWithLoadBalancingRule.UpdateLoadBalancingRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">負荷分散を更新する規則の名前。</param>
        <summary>
            更新プログラムを既存の負荷分散のこのロード バランサー上の規則の説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ロード バランシング ルールの更新の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutLoadBalancingRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutLoadBalancingRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutLoadBalancingRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithLoadBalancingRule.WithoutLoadBalancingRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutLoadBalancingRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutLoadBalancingRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate" Usage="iWithLoadBalancingRule.WithoutLoadBalancingRule name" />
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
        <param name="name">負荷分散を削除する規則の名前。</param>
        <summary>
            存在する場合は、指定した負荷分散のロード バランサーからの規則を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>