<Type Name="IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged">
  <TypeSignature Language="C#" Value="public interface IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged" />
  <TypeSignature Language="F#" Value="type IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged = interface" />
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManagedOrUnmanaged WithRootPassword (string rootPassword);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManagedOrUnmanaged WithRootPassword(string rootPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged.WithRootPassword(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRootPassword (rootPassword As String) As IWithLinuxCreateManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithRootPassword : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManagedOrUnmanaged" Usage="iWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged.WithRootPassword rootPassword" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rootPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="rootPassword">Azure Linux VM のパスワードの複雑さの条件を次のパスワード。</param>
        <summary>
            Linux 仮想マシンの SSH ルート パスワードを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithSsh">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManagedOrUnmanaged WithSsh (string publicKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManagedOrUnmanaged WithSsh(string publicKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged.WithSsh(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSsh (publicKey As String) As IWithLinuxCreateManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithSsh : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManagedOrUnmanaged" Usage="iWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged.WithSsh publicKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManagedOrUnmanaged</ReturnType>
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