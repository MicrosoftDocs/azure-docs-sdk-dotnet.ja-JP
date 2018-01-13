<Type Name="IWithWindowsAdminUsernameUnmanaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameUnmanaged">
  <TypeSignature Language="C#" Value="public interface IWithWindowsAdminUsernameUnmanaged" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithWindowsAdminUsernameUnmanaged" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameUnmanaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithWindowsAdminUsernameUnmanaged" />
  <TypeSignature Language="F#" Value="type IWithWindowsAdminUsernameUnmanaged = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8ced1-101">Windows 仮想マシンのスケールのステージでは、管理者のユーザー名を指定できるように定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ced1-101">The stage of the Windows virtual machine scale set definition allowing to specify administrator user name.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAdminUsername">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordUnmanaged WithAdminUsername (string adminUserName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordUnmanaged WithAdminUsername(string adminUserName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminUsernameUnmanaged.WithAdminUsername(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAdminUsername (adminUserName As String) As IWithWindowsAdminPasswordUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithAdminUsername : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordUnmanaged" Usage="iWithWindowsAdminUsernameUnmanaged.WithAdminUsername adminUserName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="adminUserName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="adminUserName"><span data-ttu-id="8ced1-102">Windows 管理者のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="8ced1-102">The Windows administrator user name.</span></span> <span data-ttu-id="8ced1-103">これにより、Windows ユーザー名の必要な名前付け規則が従う必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ced1-103">This must follow the required naming convention for Windows user name.</span></span></param>
        <summary>
            <span data-ttu-id="8ced1-104">Windows 仮想マシンの管理者ユーザー名を指定します。</span><span class="sxs-lookup"><span data-stu-id="8ced1-104">Specifies the administrator user name for the Windows virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8ced1-105">Linux VM の作成可能な定義を表す段階です。</span><span class="sxs-lookup"><span data-stu-id="8ced1-105">The stage representing creatable Linux VM definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>