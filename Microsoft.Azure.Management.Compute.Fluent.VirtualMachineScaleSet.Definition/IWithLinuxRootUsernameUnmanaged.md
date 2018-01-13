<Type Name="IWithLinuxRootUsernameUnmanaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameUnmanaged">
  <TypeSignature Language="C#" Value="public interface IWithLinuxRootUsernameUnmanaged" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLinuxRootUsernameUnmanaged" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameUnmanaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLinuxRootUsernameUnmanaged" />
  <TypeSignature Language="F#" Value="type IWithLinuxRootUsernameUnmanaged = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7ce43-101">Linux 仮想マシンのスケールのステージでは、SSH ルート ユーザーの名前を指定できるように定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="7ce43-101">The stage of the Linux virtual machine scale set definition allowing to specify SSH root user name.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRootUsername">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootPasswordOrPublicKeyUnmanaged WithRootUsername (string rootUserName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootPasswordOrPublicKeyUnmanaged WithRootUsername(string rootUserName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameUnmanaged.WithRootUsername(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRootUsername (rootUserName As String) As IWithLinuxRootPasswordOrPublicKeyUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithRootUsername : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootPasswordOrPublicKeyUnmanaged" Usage="iWithLinuxRootUsernameUnmanaged.WithRootUsername rootUserName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootPasswordOrPublicKeyUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rootUserName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="rootUserName"><span data-ttu-id="7ce43-102">Linux ユーザー名の必要な命名規則に従ったルート ユーザーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce43-102">A root user name following the required naming convention for Linux user names.</span></span></param>
        <summary>
            <span data-ttu-id="7ce43-103">Linux 仮想マシンの SSH ルート ユーザー名を指定します。</span><span class="sxs-lookup"><span data-stu-id="7ce43-103">Specifies the SSH root user name for the Linux virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7ce43-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="7ce43-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>