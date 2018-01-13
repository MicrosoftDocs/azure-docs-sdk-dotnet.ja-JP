<Type Name="IWithInboundNatPool" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatPool">
  <TypeSignature Language="C#" Value="public interface IWithInboundNatPool" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInboundNatPool" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInboundNatPool" />
  <TypeSignature Language="F#" Value="type IWithInboundNatPool = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            仮想マシンのスケールの新しい着信 NAT プールの作成を許可するロード バランサーの更新プログラムのステージを設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineInboundNatPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineInboundNatPool (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineInboundNatPool(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatPool.DefineInboundNatPool(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineInboundNatPool (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineInboundNatPool : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;" Usage="iWithInboundNatPool.DefineInboundNatPool name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">着信 NAT プールの名前。</param>
        <summary>
            新しい着信 NAT プールの定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>新しいの着信 NAT プール定義の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateInboundNatPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Update.IUpdate UpdateInboundNatPool (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Update.IUpdate UpdateInboundNatPool(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatPool.UpdateInboundNatPool(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateInboundNatPool (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateInboundNatPool : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Update.IUpdate" Usage="iWithInboundNatPool.UpdateInboundNatPool name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatPool.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">更新する着信 NAT プールの名前。</param>
        <summary>
            既存の着信 NAT プールに更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>着信 NAT プールの更新プログラムの最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutInboundNatPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutInboundNatPool (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutInboundNatPool(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatPool.WithoutInboundNatPool(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutInboundNatPool (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutInboundNatPool : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate" Usage="iWithInboundNatPool.WithoutInboundNatPool name" />
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
        <param name="name">このロード バランサーの既存の着信 NAT プールの名前。</param>
        <summary>
            ロード バランサーから指定した着信 NAT プールを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>