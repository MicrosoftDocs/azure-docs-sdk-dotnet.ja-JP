<Type Name="IWithComputerNamePrefix" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithComputerNamePrefix">
  <TypeSignature Language="C#" Value="public interface IWithComputerNamePrefix" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithComputerNamePrefix" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithComputerNamePrefix" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithComputerNamePrefix" />
  <TypeSignature Language="F#" Value="type IWithComputerNamePrefix = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="698a3-101">仮想マシンのスケールのステージでは、コンピューター名のプレフィックスを指定できるように定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="698a3-101">The stage of a virtual machine scale set definition allowing to specify the computer name prefix.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithComputerNamePrefix">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithComputerNamePrefix (string namePrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithComputerNamePrefix(string namePrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithComputerNamePrefix.WithComputerNamePrefix(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithComputerNamePrefix (namePrefix As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithComputerNamePrefix : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate" Usage="iWithComputerNamePrefix.WithComputerNamePrefix namePrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="namePrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="namePrefix"><span data-ttu-id="698a3-102">スケールには、仮想マシンの自動生成された名前のプレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="698a3-102">The prefix for the auto-generated names of the virtual machines in the scale set.</span></span></param>
        <summary>
            <span data-ttu-id="698a3-103">スケール セット内の仮想マシンの名前を自動生成するために使用する名前プレフィックスを指定します。</span><span class="sxs-lookup"><span data-stu-id="698a3-103">Specifies the name prefix to use for auto-generating the names for the virtual machines in the scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="698a3-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="698a3-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>