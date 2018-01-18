<Type Name="IWithCapacity" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCapacity">
  <TypeSignature Language="C#" Value="public interface IWithCapacity" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCapacity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCapacity" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCapacity" />
  <TypeSignature Language="F#" Value="type IWithCapacity = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a65bc-101">仮想マシンのスケールのステージでは、スケール セット内の仮想マシンの数を指定できるように定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="a65bc-101">The stage of the virtual machine scale set definition allowing to specify number of virtual machines in the scale set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithCapacity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithCapacity (int capacity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithCapacity(int32 capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCapacity.WithCapacity(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCapacity (capacity As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithCapacity : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate" Usage="iWithCapacity.WithCapacity capacity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="capacity" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="capacity"><span data-ttu-id="a65bc-102">仮想マシンの数。</span><span class="sxs-lookup"><span data-stu-id="a65bc-102">Number of virtual machines.</span></span></param>
        <summary>
            <span data-ttu-id="a65bc-103">スケール セット内の仮想マシンの最大数を指定します。</span><span class="sxs-lookup"><span data-stu-id="a65bc-103">Specifies the maximum number of virtual machines in the scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a65bc-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="a65bc-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>