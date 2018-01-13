<Type Name="IWithPublicIPAddress" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress">
  <TypeSignature Language="C#" Value="public interface IWithPublicIPAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPublicIPAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPublicIPAddress" />
  <TypeSignature Language="F#" Value="type IWithPublicIPAddress = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            関連付ける、プライマリ ネットワーク インターフェイス、パブリック IP アドレスを許可する仮想マシンの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithExistingPrimaryPublicIPAddress (Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress publicIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithExistingPrimaryPublicIPAddress(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress publicIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress.WithExistingPrimaryPublicIPAddress(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryPublicIPAddress (publicIPAddress As IPublicIPAddress) As IWithOS" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryPublicIPAddress : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS" Usage="iWithPublicIPAddress.WithExistingPrimaryPublicIPAddress publicIPAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publicIPAddress" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress" />
      </Parameters>
      <Docs>
        <param name="publicIPAddress">既存のパブリック IP アドレス。</param>
        <summary>
            既存のパブリック IP アドレスを VM のプライマリ ネットワーク インターフェイスに関連付けます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithNewPrimaryPublicIPAddress (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithNewPrimaryPublicIPAddress(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress.WithNewPrimaryPublicIPAddress(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryPublicIPAddress (creatable As ICreatable(Of IPublicIPAddress)) As IWithOS" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryPublicIPAddress : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS" Usage="iWithPublicIPAddress.WithNewPrimaryPublicIPAddress creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">新しいパブリック IP の作成可能な定義です。</param>
        <summary>
            VM のプライマリ ネットワーク インターフェイスに関連付ける新しいパブリック IP アドレスを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithNewPrimaryPublicIPAddress (string leafDnsLabel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithNewPrimaryPublicIPAddress(string leafDnsLabel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress.WithNewPrimaryPublicIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryPublicIPAddress (leafDnsLabel As String) As IWithOS" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryPublicIPAddress : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS" Usage="iWithPublicIPAddress.WithNewPrimaryPublicIPAddress leafDnsLabel" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leafDnsLabel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="leafDnsLabel">リーフ ドメイン ラベルです。</param>
        <summary>
            新しいパブリック IP アドレスを同じ地域およびリソース グループで指定した DNS ラベルで、リソースとして作成し、VM のプライマリ ネットワーク インターフェイスに関連付けます。
            パブリック IP アドレスの内部名は、DNS ラベルから導き出されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithoutPrimaryPublicIPAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithoutPrimaryPublicIPAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress.WithoutPrimaryPublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryPublicIPAddress () As IWithOS" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryPublicIPAddress : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS" Usage="iWithPublicIPAddress.WithoutPrimaryPublicIPAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            VM されませんが、パブリック IP アドレスを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>