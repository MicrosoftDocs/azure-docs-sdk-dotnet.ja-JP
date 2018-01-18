<Type Name="IWithCapacity" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithCapacity">
  <TypeSignature Language="C#" Value="public interface IWithCapacity" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCapacity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithCapacity" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCapacity" />
  <TypeSignature Language="F#" Value="type IWithCapacity = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f3986-101">仮想マシンのスケールのステージでは、スケール セット内の仮想マシンの数を指定できるように定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="f3986-101">The stage of a virtual machine scale set definition allowing to specify the number of virtual machines in the scale set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithCapacity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithCapacity (int capacity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithCapacity(int32 capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithCapacity.WithCapacity(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCapacity (capacity As Integer) As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithCapacity : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithCapacity.WithCapacity capacity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="capacity" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="capacity"><span data-ttu-id="f3986-102">スケールの仮想マシンの容量を設定します。</span><span class="sxs-lookup"><span data-stu-id="f3986-102">The virtual machine capacity of the scale set.</span></span></param>
        <summary>
            <span data-ttu-id="f3986-103">スケール セット内には、新しいバーチャル マシン数を指定します。</span><span class="sxs-lookup"><span data-stu-id="f3986-103">Specifies the new number of virtual machines in the scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f3986-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f3986-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>