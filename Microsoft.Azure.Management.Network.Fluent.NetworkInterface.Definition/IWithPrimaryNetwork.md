<Type Name="IWithPrimaryNetwork" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryNetwork" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryNetwork" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryNetwork" />
  <TypeSignature Language="F#" Value="type IWithPrimaryNetwork = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            プライマリ IP 構成の仮想ネットワークを指定を許可するネットワーク インターフェイスの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetworkSubnet WithExistingPrimaryNetwork (Microsoft.Azure.Management.Network.Fluent.INetwork network);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetworkSubnet WithExistingPrimaryNetwork(class Microsoft.Azure.Management.Network.Fluent.INetwork network) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork.WithExistingPrimaryNetwork(Microsoft.Azure.Management.Network.Fluent.INetwork)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryNetwork (network As INetwork) As IWithPrimaryNetworkSubnet" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryNetwork : Microsoft.Azure.Management.Network.Fluent.INetwork -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetworkSubnet" Usage="iWithPrimaryNetwork.WithExistingPrimaryNetwork network" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetworkSubnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
      </Parameters>
      <Docs>
        <param name="network">既存の仮想ネットワークです。</param>
        <summary>
            既存の仮想ネットワークをネットワーク インターフェイスのプライマリ IP 構成に関連付けます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetwork&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork.WithNewPrimaryNetwork(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetwork})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryNetwork (creatable As ICreatable(Of INetwork)) As IWithPrimaryPrivateIP" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryNetwork : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP" Usage="iWithPrimaryNetwork.WithNewPrimaryNetwork creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">新しい仮想ネットワークの作成可能な定義です。</param>
        <summary>
            指定された定義に基づくネットワーク インターフェイスのプライマリ IP 構成に関連付ける場合は、新しい仮想ネットワークを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork (string addressSpace);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork(string addressSpace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork.WithNewPrimaryNetwork(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryNetwork (addressSpace As String) As IWithPrimaryPrivateIP" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryNetwork : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP" Usage="iWithPrimaryNetwork.WithNewPrimaryNetwork addressSpace" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addressSpace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="addressSpace">仮想ネットワークのアドレス空間です。</param>
        <summary>
            ネットワーク インターフェイスのプライマリ IP 構成に関連付ける場合は、新しい仮想ネットワークを作成します。
            仮想ネットワークは、同じリソース グループとネットワーク インターフェイスの時点でのリージョンに作成されますが、指定されたアドレス空間と、ネットワークの IP アドレス空間の全体をカバーする既定のサブネットが作成されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork (string name, string addressSpace);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork(string name, string addressSpace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork.WithNewPrimaryNetwork(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryNetwork (name As String, addressSpace As String) As IWithPrimaryPrivateIP" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryNetwork : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP" Usage="iWithPrimaryNetwork.WithNewPrimaryNetwork (name, addressSpace)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="addressSpace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">新しい仮想ネットワークの名前。</param>
        <param name="addressSpace">された仮想ネットワークのアドレス空間です。</param>
        <summary>
            ネットワーク インターフェイスのプライマリ IP 構成に関連付ける場合は、新しい仮想ネットワークを作成します。
            仮想ネットワークは、同じリソース グループとネットワーク インターフェイスの時点でのリージョンに作成されますが、指定されたアドレス空間と、ネットワークの IP アドレス空間の全体をカバーする既定のサブネットが作成されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>