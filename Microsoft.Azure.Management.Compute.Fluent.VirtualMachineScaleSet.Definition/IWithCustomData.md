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
            仮想マシンのスケールのステージでは、カスタム データを指定できるように定義を設定します。
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
        <param name="base64EncodedCustomData">カスタム データを base64 にエンコードします。</param>
        <summary>
            仮想マシン スケール セット用のカスタム データを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義に次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>