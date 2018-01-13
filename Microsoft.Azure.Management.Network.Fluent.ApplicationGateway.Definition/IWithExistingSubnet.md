<Type Name="IWithExistingSubnet" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithExistingSubnet">
  <TypeSignature Language="C#" Value="public interface IWithExistingSubnet : Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Definition.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExistingSubnet implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Definition.IWithSubnet`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithExistingSubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExistingSubnet&#xA;Implements IWithSubnet(Of IWithCreate)" />
  <TypeSignature Language="F#" Value="type IWithExistingSubnet = interface&#xA;    interface IWithSubnet&lt;IWithCreate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Definition.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            アプリケーション ゲートウェイ サブネットを指定するようにアプリケーション ゲートウェイ定義のステージからプライベート IP アドレスの取得です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.ISubnet subnet);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.ISubnet subnet) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithExistingSubnet.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.ISubnet)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (subnet As ISubnet) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.ISubnet -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate" Usage="iWithExistingSubnet.WithExistingSubnet subnet" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate</ReturnType>
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
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithExistingSubnet.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.INetwork,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (network As INetwork, subnetName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.INetwork * string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate" Usage="iWithExistingSubnet.WithExistingSubnet (network, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate</ReturnType>
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
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>