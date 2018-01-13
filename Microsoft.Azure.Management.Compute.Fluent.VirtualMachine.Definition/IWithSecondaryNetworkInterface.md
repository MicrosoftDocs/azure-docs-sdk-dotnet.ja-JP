<Type Name="IWithSecondaryNetworkInterface" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface">
  <TypeSignature Language="C#" Value="public interface IWithSecondaryNetworkInterface" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSecondaryNetworkInterface" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSecondaryNetworkInterface" />
  <TypeSignature Language="F#" Value="type IWithSecondaryNetworkInterface = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            追加のネットワーク インターフェイスの指定を許可する仮想マシンの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingSecondaryNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithExistingSecondaryNetworkInterface (Microsoft.Azure.Management.Network.Fluent.INetworkInterface networkInterface);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithExistingSecondaryNetworkInterface(class Microsoft.Azure.Management.Network.Fluent.INetworkInterface networkInterface) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface.WithExistingSecondaryNetworkInterface(Microsoft.Azure.Management.Network.Fluent.INetworkInterface)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSecondaryNetworkInterface (networkInterface As INetworkInterface) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSecondaryNetworkInterface : Microsoft.Azure.Management.Network.Fluent.INetworkInterface -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithSecondaryNetworkInterface.WithExistingSecondaryNetworkInterface networkInterface" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="networkInterface" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterface" />
      </Parameters>
      <Docs>
        <param name="networkInterface">既存のネットワーク インターフェイスです。</param>
        <summary>
            既存のネットワーク インターフェイスを仮想マシンに関連付けます。
            このメソッドの効果は加法、つまりそれを使用するたび、新しいセカンダリ ネットワーク インターフェイス、仮想マシンに追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewSecondaryNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewSecondaryNetworkInterface (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewSecondaryNetworkInterface(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface.WithNewSecondaryNetworkInterface(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetworkInterface})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewSecondaryNetworkInterface (creatable As ICreatable(Of INetworkInterface)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewSecondaryNetworkInterface : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithSecondaryNetworkInterface.WithNewSecondaryNetworkInterface creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">新しいネットワーク インターフェイスの定義を作成可能です。</param>
        <summary>
            指定された定義に基づいて、仮想マシンに関連付ける新しいネットワーク インターフェイスを作成します。
            このメソッドの効果は加法、つまりそれを使用するたび、新しいセカンダリ ネットワーク インターフェイス、仮想マシンに追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>