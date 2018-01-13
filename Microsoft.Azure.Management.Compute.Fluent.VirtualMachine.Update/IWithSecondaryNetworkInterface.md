<Type Name="IWithSecondaryNetworkInterface" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithSecondaryNetworkInterface">
  <TypeSignature Language="C#" Value="public interface IWithSecondaryNetworkInterface" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSecondaryNetworkInterface" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithSecondaryNetworkInterface" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSecondaryNetworkInterface" />
  <TypeSignature Language="F#" Value="type IWithSecondaryNetworkInterface = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            追加のネットワーク インターフェイスの指定を許可するバーチャル マシンの更新の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingSecondaryNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingSecondaryNetworkInterface (Microsoft.Azure.Management.Network.Fluent.INetworkInterface networkInterface);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingSecondaryNetworkInterface(class Microsoft.Azure.Management.Network.Fluent.INetworkInterface networkInterface) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithSecondaryNetworkInterface.WithExistingSecondaryNetworkInterface(Microsoft.Azure.Management.Network.Fluent.INetworkInterface)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSecondaryNetworkInterface (networkInterface As INetworkInterface) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSecondaryNetworkInterface : Microsoft.Azure.Management.Network.Fluent.INetworkInterface -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithSecondaryNetworkInterface.WithExistingSecondaryNetworkInterface networkInterface" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
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
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewSecondaryNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewSecondaryNetworkInterface (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewSecondaryNetworkInterface(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithSecondaryNetworkInterface.WithNewSecondaryNetworkInterface(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetworkInterface})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewSecondaryNetworkInterface (creatable As ICreatable(Of INetworkInterface)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewSecondaryNetworkInterface : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithSecondaryNetworkInterface.WithNewSecondaryNetworkInterface creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">新しいネットワーク インターフェイスの定義を作成可能です。</param>
        <summary>
            仮想マシンに関連付ける新しいネットワーク インターフェイスを作成します。
            このメソッドの効果は加法、つまりそれを使用するたび、新しいセカンダリ ネットワーク インターフェイス、仮想マシンに追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutSecondaryNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutSecondaryNetworkInterface (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutSecondaryNetworkInterface(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithSecondaryNetworkInterface.WithoutSecondaryNetworkInterface(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutSecondaryNetworkInterface (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutSecondaryNetworkInterface : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithSecondaryNetworkInterface.WithoutSecondaryNetworkInterface name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">削除するセカンダリ ネットワーク インターフェイスの名前。</param>
        <summary>
            仮想マシンからセカンダリ ネットワーク インターフェイスを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>