<Type Name="IWithLoadBalancer" FullName="Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IWithLoadBalancer">
  <TypeSignature Language="C#" Value="public interface IWithLoadBalancer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLoadBalancer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IWithLoadBalancer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLoadBalancer" />
  <TypeSignature Language="F#" Value="type IWithLoadBalancer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ロード バランサーに関連付けるには、この IP 構成を指定できるようにネットワーク インターフェイスの IP 構成の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingLoadBalancerBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithExistingLoadBalancerBackend (Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string backendName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithExistingLoadBalancerBackend(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string backendName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IWithLoadBalancer.WithExistingLoadBalancerBackend(Microsoft.Azure.Management.Network.Fluent.ILoadBalancer,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingLoadBalancerBackend (loadBalancer As ILoadBalancer, backendName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingLoadBalancerBackend : Microsoft.Azure.Management.Network.Fluent.ILoadBalancer * string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate" Usage="iWithLoadBalancer.WithExistingLoadBalancerBackend (loadBalancer, backendName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadBalancer" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
        <Parameter Name="backendName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="loadBalancer">既存のロード バランサーです。</param>
        <param name="backendName">上の既存のバックエンドの名前はロード バランサーです。</param>
        <summary>
            ロード バランサーに関連付けるには、この IP 構成を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingLoadBalancerInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithExistingLoadBalancerInboundNatRule (Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string inboundNatRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithExistingLoadBalancerInboundNatRule(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string inboundNatRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IWithLoadBalancer.WithExistingLoadBalancerInboundNatRule(Microsoft.Azure.Management.Network.Fluent.ILoadBalancer,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingLoadBalancerInboundNatRule (loadBalancer As ILoadBalancer, inboundNatRuleName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingLoadBalancerInboundNatRule : Microsoft.Azure.Management.Network.Fluent.ILoadBalancer * string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate" Usage="iWithLoadBalancer.WithExistingLoadBalancerInboundNatRule (loadBalancer, inboundNatRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadBalancer" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
        <Parameter Name="inboundNatRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="loadBalancer">既存のロード バランサーです。</param>
        <param name="inboundNatRuleName">選択されているロード バランサーの既存の受信 NAT 規則の名前。</param>
        <summary>
            ロード バランサーの指定に関連付けるには、この IP 構成の着信 NAT ルール。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutLoadBalancerBackends">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithoutLoadBalancerBackends ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithoutLoadBalancerBackends() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IWithLoadBalancer.WithoutLoadBalancerBackends" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutLoadBalancerBackends () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutLoadBalancerBackends : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate" Usage="iWithLoadBalancer.WithoutLoadBalancerBackends " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ロード バランサーのバックエンドとの既存のすべての関連付けを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutLoadBalancerInboundNatRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithoutLoadBalancerInboundNatRules ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithoutLoadBalancerInboundNatRules() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IWithLoadBalancer.WithoutLoadBalancerInboundNatRules" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutLoadBalancerInboundNatRules () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutLoadBalancerInboundNatRules : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate" Usage="iWithLoadBalancer.WithoutLoadBalancerInboundNatRules " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ロード バランサーとの既存のすべての関連付けの削除の受信 NAT 規則です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>