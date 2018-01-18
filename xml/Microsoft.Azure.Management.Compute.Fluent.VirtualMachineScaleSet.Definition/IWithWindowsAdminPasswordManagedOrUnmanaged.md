<Type Name="IWithWindowsAdminPasswordManagedOrUnmanaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordManagedOrUnmanaged">
  <TypeSignature Language="C#" Value="public interface IWithWindowsAdminPasswordManagedOrUnmanaged" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithWindowsAdminPasswordManagedOrUnmanaged" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordManagedOrUnmanaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithWindowsAdminPasswordManagedOrUnmanaged" />
  <TypeSignature Language="F#" Value="type IWithWindowsAdminPasswordManagedOrUnmanaged = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d5acc-101">Windows 仮想マシンのスケールのステージでは、管理者のユーザー名を指定できるように定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="d5acc-101">The stage of the Windows virtual machine scale set definition allowing to specify administrator user name.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAdminPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManagedOrUnmanaged WithAdminPassword (string adminPassword);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManagedOrUnmanaged WithAdminPassword(string adminPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordManagedOrUnmanaged.WithAdminPassword(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAdminPassword (adminPassword As String) As IWithWindowsCreateManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithAdminPassword : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManagedOrUnmanaged" Usage="iWithWindowsAdminPasswordManagedOrUnmanaged.WithAdminPassword adminPassword" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="adminPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="adminPassword"><span data-ttu-id="d5acc-102">管理者パスワード。</span><span class="sxs-lookup"><span data-stu-id="d5acc-102">The administrator password.</span></span> <span data-ttu-id="d5acc-103">これにより、Azure Windows 仮想マシンのパスワードの基準が従う必要があります。</span><span class="sxs-lookup"><span data-stu-id="d5acc-103">This must follow the criteria for Azure Windows VM password.</span></span></param>
        <summary>
            <span data-ttu-id="d5acc-104">Windows 仮想マシンの管理者パスワードを指定します。</span><span class="sxs-lookup"><span data-stu-id="d5acc-104">Specifies the administrator password for the Windows virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d5acc-105">Windows VM の作成可能な定義を表す段階です。</span><span class="sxs-lookup"><span data-stu-id="d5acc-105">The stage representing creatable Windows VM definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>