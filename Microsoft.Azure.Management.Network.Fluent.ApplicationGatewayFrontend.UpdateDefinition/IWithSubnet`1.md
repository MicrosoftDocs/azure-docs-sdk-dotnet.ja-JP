<Type Name="IWithSubnet&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithSubnet&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSubnet&lt;ParentT&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.UpdateDefinition.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSubnet`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.UpdateDefinition.IWithSubnet`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithSubnet`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSubnet(Of ParentT)&#xA;Implements IWithSubnet(Of IWithAttach(Of ParentT))" />
  <TypeSignature Language="F#" Value="type IWithSubnet&lt;'ParentT&gt; = interface&#xA;    interface IWithSubnet&lt;IWithAttach&lt;'ParentT&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.UpdateDefinition.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るには、親アプリケーション ゲートウェイ定義の段階です。</typeparam>
    <summary>
            このアプリケーション ゲートウェイに表示されるようにする、選択したネットワークのサブネットを指定できるようにアプリケーション ゲートウェイ フロント エンドの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithSubnet`1.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.INetwork,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (network As INetwork, subnetName As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.INetwork * string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithSubnet.WithExistingSubnet (network, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="network">仮想ネットワークが、サブネットに存在します。</param>
        <param name="subnetName">サブネットの名前。</param>
        <summary>
            このプライベート フロント エンドに指定されたサブネットを割り当てます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>