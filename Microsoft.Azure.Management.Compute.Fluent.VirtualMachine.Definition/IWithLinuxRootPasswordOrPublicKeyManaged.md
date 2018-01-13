<Type Name="IWithLinuxRootPasswordOrPublicKeyManaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyManaged">
  <TypeSignature Language="C#" Value="public interface IWithLinuxRootPasswordOrPublicKeyManaged" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLinuxRootPasswordOrPublicKeyManaged" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyManaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLinuxRootPasswordOrPublicKeyManaged" />
  <TypeSignature Language="F#" Value="type IWithLinuxRootPasswordOrPublicKeyManaged = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            SSH ルート パスワードまたは公開キーを指定できるように、Linux 仮想マシンの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRootPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManaged WithRootPassword (string rootPassword);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManaged WithRootPassword(string rootPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyManaged.WithRootPassword(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRootPassword (rootPassword As String) As IWithLinuxCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithRootPassword : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManaged" Usage="iWithLinuxRootPasswordOrPublicKeyManaged.WithRootPassword rootPassword" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rootPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="rootPassword">次の Azure Linux VM のパスワードの複雑さの条件パスワードです。</param>
        <summary>
            Linux 仮想マシンの SSH ルート パスワードを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithSsh">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManaged WithSsh (string publicKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManaged WithSsh(string publicKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyManaged.WithSsh(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSsh (publicKey As String) As IWithLinuxCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithSsh : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManaged" Usage="iWithLinuxRootPasswordOrPublicKeyManaged.WithSsh publicKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publicKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publicKey">PEM 形式での SSH 公開キー。</param>
        <summary>
            SSH 公開キーを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>