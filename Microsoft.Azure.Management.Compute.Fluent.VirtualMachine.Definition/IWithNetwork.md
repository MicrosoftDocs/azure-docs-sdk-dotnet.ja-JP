<Type Name="IWithNetwork" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork">
  <TypeSignature Language="C#" Value="public interface IWithNetwork : Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrimaryNetworkInterface" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNetwork implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrimaryNetworkInterface" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNetwork&#xA;Implements IWithPrimaryNetworkInterface" />
  <TypeSignature Language="F#" Value="type IWithNetwork = interface&#xA;    interface IWithPrimaryNetworkInterface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrimaryNetworkInterface</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            新しいプライマリ ネットワーク インターフェイスを持つ仮想ネットワークを指定するように仮想マシンの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSubnet WithExistingPrimaryNetwork (Microsoft.Azure.Management.Network.Fluent.INetwork network);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSubnet WithExistingPrimaryNetwork(class Microsoft.Azure.Management.Network.Fluent.INetwork network) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork.WithExistingPrimaryNetwork(Microsoft.Azure.Management.Network.Fluent.INetwork)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryNetwork (network As INetwork) As IWithSubnet" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryNetwork : Microsoft.Azure.Management.Network.Fluent.INetwork -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSubnet" Usage="iWithNetwork.WithExistingPrimaryNetwork network" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSubnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
      </Parameters>
      <Docs>
        <param name="network">既存の仮想ネットワークです。</param>
        <summary>
            既存の仮想ネットワークをバーチャル マシンのプライマリ ネットワーク インターフェイスに関連付けます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP WithNewPrimaryNetwork (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP WithNewPrimaryNetwork(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetwork&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork.WithNewPrimaryNetwork(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetwork})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryNetwork (creatable As ICreatable(Of INetwork)) As IWithPrivateIP" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryNetwork : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP" Usage="iWithNetwork.WithNewPrimaryNetwork creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">新しい仮想ネットワークの作成可能な定義です。</param>
        <summary>
            指定された定義に基づくバーチャル マシンのプライマリ ネットワーク インターフェイスに関連付ける場合は、新しい仮想ネットワークを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP WithNewPrimaryNetwork (string addressSpace);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP WithNewPrimaryNetwork(string addressSpace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithNetwork.WithNewPrimaryNetwork(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryNetwork (addressSpace As String) As IWithPrivateIP" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryNetwork : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP" Usage="iWithNetwork.WithNewPrimaryNetwork addressSpace" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addressSpace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="addressSpace">仮想ネットワークのアドレス空間です。</param>
        <summary>
            バーチャル マシンのプライマリ ネットワーク インターフェイスに関連付ける場合は、新しい仮想ネットワークを作成します。
            仮想ネットワークは、同じリソース グループと仮想マシンの時点でのリージョンに作成されますが、指定されたアドレス空間と、ネットワークの IP アドレス空間の全体をカバーする既定のサブネットが作成されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>