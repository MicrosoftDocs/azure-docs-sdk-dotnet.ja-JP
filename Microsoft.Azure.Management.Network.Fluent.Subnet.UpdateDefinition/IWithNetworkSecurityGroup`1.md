<Type Name="IWithNetworkSecurityGroup&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithNetworkSecurityGroup&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNetworkSecurityGroup&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNetworkSecurityGroup`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithNetworkSecurityGroup`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNetworkSecurityGroup(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithNetworkSecurityGroup&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">親の型。</typeparam>
    <summary>
            ネットワーク セキュリティ グループに割り当てるサブネットを指定できるように、サブネット定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingNetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithExistingNetworkSecurityGroup (Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup nsg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithExistingNetworkSecurityGroup(class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup nsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithNetworkSecurityGroup`1.WithExistingNetworkSecurityGroup(Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingNetworkSecurityGroup (nsg As INetworkSecurityGroup) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingNetworkSecurityGroup : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithNetworkSecurityGroup.WithExistingNetworkSecurityGroup nsg" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nsg" Type="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup" />
      </Parameters>
      <Docs>
        <param name="nsg">ネットワーク セキュリティ グループを割り当てます。</param>
        <summary>
            このサブネットには、既存のネットワーク セキュリティ グループを割り当てます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingNetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithExistingNetworkSecurityGroup (string resourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithExistingNetworkSecurityGroup(string resourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithNetworkSecurityGroup`1.WithExistingNetworkSecurityGroup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingNetworkSecurityGroup (resourceId As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingNetworkSecurityGroup : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithNetworkSecurityGroup.WithExistingNetworkSecurityGroup resourceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceId">ネットワーク セキュリティ グループのリソース ID です。</param>
        <summary>
            このサブネットには、既存のネットワーク セキュリティ グループを割り当てます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>