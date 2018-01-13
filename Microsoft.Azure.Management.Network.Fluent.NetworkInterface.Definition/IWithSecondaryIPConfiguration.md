<Type Name="IWithSecondaryIPConfiguration" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithSecondaryIPConfiguration">
  <TypeSignature Language="C#" Value="public interface IWithSecondaryIPConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSecondaryIPConfiguration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithSecondaryIPConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSecondaryIPConfiguration" />
  <TypeSignature Language="F#" Value="type IWithSecondaryIPConfiguration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            セカンダリ IP 構成に関連付けるを許可するネットワーク インターフェイスの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineSecondaryIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate&gt; DefineSecondaryIPConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate&gt; DefineSecondaryIPConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithSecondaryIPConfiguration.DefineSecondaryIPConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSecondaryIPConfiguration (name As String) As IBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineSecondaryIPConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate&gt;" Usage="iWithSecondaryIPConfiguration.DefineSecondaryIPConfiguration name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">IP 構成の名前。</param>
        <summary>
            セカンダリ IP 構成の定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>セカンダリ IP 構成の定義の最初の段階です。</return>
      </Docs>
    </Member>
  </Members>
</Type>