<Type Name="IWithLinuxRootUsernameManagedOrUnmanaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged">
  <TypeSignature Language="C#" Value="public interface IWithLinuxRootUsernameManagedOrUnmanaged" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLinuxRootUsernameManagedOrUnmanaged" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLinuxRootUsernameManagedOrUnmanaged" />
  <TypeSignature Language="F#" Value="type IWithLinuxRootUsernameManagedOrUnmanaged = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            SSH ルート ユーザー名を指定するを許可する Linux 仮想マシンの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRootUsername">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged WithRootUsername (string rootUserName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged WithRootUsername(string rootUserName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootUsernameManagedOrUnmanaged.WithRootUsername(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRootUsername (rootUserName As String) As IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithRootUsername : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged" Usage="iWithLinuxRootUsernameManagedOrUnmanaged.WithRootUsername rootUserName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxRootPasswordOrPublicKeyManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rootUserName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="rootUserName">Linux のユーザー名の必要な名前付け規則を次のユーザー名。</param>
        <summary>
            Linux 仮想マシンの SSH ルート ユーザー名を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>