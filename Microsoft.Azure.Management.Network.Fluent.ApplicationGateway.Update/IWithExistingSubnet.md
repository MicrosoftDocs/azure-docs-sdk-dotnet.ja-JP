<Type Name="IWithExistingSubnet" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithExistingSubnet">
  <TypeSignature Language="C#" Value="public interface IWithExistingSubnet : Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Update.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExistingSubnet implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Update.IWithSubnet`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithExistingSubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExistingSubnet&#xA;Implements IWithSubnet(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IWithExistingSubnet = interface&#xA;    interface IWithSubnet&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Update.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            アプリケーション ゲートウェイの更新を許可するサブネットを指定のステージは、アプリケーション ゲートウェイからプライベート IP アドレスの取得です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.ISubnet subnet);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.ISubnet subnet) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithExistingSubnet.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.ISubnet)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (subnet As ISubnet) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.ISubnet -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithExistingSubnet.WithExistingSubnet subnet" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.Network.Fluent.ISubnet" />
      </Parameters>
      <Docs>
        <param name="subnet">既存のサブネットです。</param>
        <summary>
            アプリケーション ゲートウェイのサブネットからプライベート IP アドレスの取得を指定します。
            既に存在しない場合は、新しい IP 構成が作成します。
            プライベート (内部) フロント エンド、いずれかが有効になっている場合は、構成もこのサブネットを使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithExistingSubnet.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.INetwork,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (network As INetwork, subnetName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.INetwork * string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithExistingSubnet.WithExistingSubnet (network, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="network">仮想ネットワーク サブネットでは、一部です。</param>
        <param name="subnetName">選択したネットワーク内のサブネットの名前。</param>
        <summary>
            アプリケーション ゲートウェイのサブネットからプライベート IP アドレスの取得を指定します。
            既に存在しない場合は、新しい IP 構成が作成します。
            プライベート (内部) フロント エンド、いずれかが有効になっている場合は、構成もこのサブネットを使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>