<Type Name="IWithWindowsAdminUsernameManagedOrUnmanaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged">
  <TypeSignature Language="C#" Value="public interface IWithWindowsAdminUsernameManagedOrUnmanaged" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithWindowsAdminUsernameManagedOrUnmanaged" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithWindowsAdminUsernameManagedOrUnmanaged" />
  <TypeSignature Language="F#" Value="type IWithWindowsAdminUsernameManagedOrUnmanaged = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="99e7e-101">Windows 仮想マシンのスケールのステージでは、管理者のユーザー名を指定できるように定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="99e7e-101">The stage of the Windows virtual machine scale set definition allowing to specify administrator user name.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAdminUsername">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordManagedOrUnmanaged WithAdminUsername (string adminUserName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordManagedOrUnmanaged WithAdminUsername(string adminUserName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameManagedOrUnmanaged.WithAdminUsername(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAdminUsername (adminUserName As String) As IWithWindowsAdminPasswordManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithAdminUsername : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordManagedOrUnmanaged" Usage="iWithWindowsAdminUsernameManagedOrUnmanaged.WithAdminUsername adminUserName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="adminUserName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="adminUserName"><span data-ttu-id="99e7e-102">Windows 管理者のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="99e7e-102">The Windows administrator user name.</span></span> <span data-ttu-id="99e7e-103">これにより、Windows ユーザー名の必要な名前付け規則が従う必要があります。</span><span class="sxs-lookup"><span data-stu-id="99e7e-103">This must follow the required naming convention for Windows user name.</span></span></param>
        <summary>
            <span data-ttu-id="99e7e-104">Windows 仮想マシンの管理者ユーザー名を指定します。</span><span class="sxs-lookup"><span data-stu-id="99e7e-104">Specifies the administrator user name for the Windows virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="99e7e-105">Linux VM の作成可能な定義を表す段階です。</span><span class="sxs-lookup"><span data-stu-id="99e7e-105">The stage representing creatable Linux VM definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>