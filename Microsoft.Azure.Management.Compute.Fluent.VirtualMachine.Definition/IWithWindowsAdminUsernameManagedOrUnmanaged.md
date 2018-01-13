<Type Name="IWithWindowsAdminUsernameManagedOrUnmanaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged">
  <TypeSignature Language="C#" Value="public interface IWithWindowsAdminUsernameManagedOrUnmanaged" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithWindowsAdminUsernameManagedOrUnmanaged" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithWindowsAdminUsernameManagedOrUnmanaged" />
  <TypeSignature Language="F#" Value="type IWithWindowsAdminUsernameManagedOrUnmanaged = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            管理者ユーザー名を指定するように Windows 仮想マシンの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAdminUsername">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminPasswordManagedOrUnmanaged WithAdminUsername (string adminUserName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminPasswordManagedOrUnmanaged WithAdminUsername(string adminUserName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged.WithAdminUsername(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAdminUsername (adminUserName As String) As IWithWindowsAdminPasswordManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithAdminUsername : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminPasswordManagedOrUnmanaged" Usage="iWithWindowsAdminUsernameManagedOrUnmanaged.WithAdminUsername adminUserName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsAdminPasswordManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="adminUserName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="adminUserName">次の Windows ユーザー名の必要な名前付け規則のユーザー名。</param>
        <summary>
            Windows 仮想マシンの管理者ユーザー名を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>