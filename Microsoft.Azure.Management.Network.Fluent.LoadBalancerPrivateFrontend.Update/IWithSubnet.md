<Type Name="IWithSubnet" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Update.IWithSubnet">
  <TypeSignature Language="C#" Value="public interface IWithSubnet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSubnet" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Update.IWithSubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSubnet" />
  <TypeSignature Language="F#" Value="type IWithSubnet = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            選択したネットワークのサブネットを指定する許可するプライベート フロント エンドの更新の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Update.IUpdate WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Update.IUpdate WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Update.IWithSubnet.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.INetwork,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (network As INetwork, subnetName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.INetwork * string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Update.IUpdate" Usage="iWithSubnet.WithExistingSubnet (network, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="network">仮想ネットワークが、サブネットに存在します。</param>
        <param name="subnetName">サブネットの名前。</param>
        <summary>
            内部ロード バランサーのこのプライベート フロント エンドに指定されたサブネットを割り当てます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>