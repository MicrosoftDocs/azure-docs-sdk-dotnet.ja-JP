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
            仮想マシンのスケールのステージでは、スケール セット内の仮想マシンの数を指定できるように定義を設定します。
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
        <param name="capacity">スケールの仮想マシンの容量を設定します。</param>
        <summary>
            スケール セット内には、新しいバーチャル マシン数を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>