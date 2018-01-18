<Type Name="IWithCustomData" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCustomData">
  <TypeSignature Language="C#" Value="public interface IWithCustomData" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCustomData" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCustomData" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCustomData" />
  <TypeSignature Language="F#" Value="type IWithCustomData = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="18613-101">仮想マシンのスケールのステージでは、カスタム データを指定できるように定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="18613-101">The stage of the virtual machine scale set definition allowing to specify the custom data.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithCustomData">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithCustomData (string base64EncodedCustomData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithCustomData(string base64EncodedCustomData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCustomData.WithCustomData(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCustomData (base64EncodedCustomData As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithCustomData : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate" Usage="iWithCustomData.WithCustomData base64EncodedCustomData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="base64EncodedCustomData" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="base64EncodedCustomData"><span data-ttu-id="18613-102">カスタム データを base64 にエンコードします。</span><span class="sxs-lookup"><span data-stu-id="18613-102">The base64 encoded custom data.</span></span></param>
        <summary>
            <span data-ttu-id="18613-103">仮想マシン スケール セット用のカスタム データを指定します。</span><span class="sxs-lookup"><span data-stu-id="18613-103">Specifies the custom data for the virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="18613-104">定義に次のステージ。</span><span class="sxs-lookup"><span data-stu-id="18613-104">The next stage in the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>