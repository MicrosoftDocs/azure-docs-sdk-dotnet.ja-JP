<Type Name="IWithUpgradePolicy" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUpgradePolicy">
  <TypeSignature Language="C#" Value="public interface IWithUpgradePolicy" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithUpgradePolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUpgradePolicy" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithUpgradePolicy" />
  <TypeSignature Language="F#" Value="type IWithUpgradePolicy = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            仮想マシンのスケールのステージでは、アップグレード ポリシーを指定できるように定義を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithUpgradeMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithUpgradeMode (Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode upgradeMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithUpgradeMode(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode upgradeMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUpgradePolicy.WithUpgradeMode(Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode)" />
      <MemberSignature Language="F#" Value="abstract member WithUpgradeMode : Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate" Usage="iWithUpgradePolicy.WithUpgradeMode upgradeMode" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeMode" Type="Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode" />
      </Parameters>
      <Docs>
        <param name="upgradeMode">アップグレード ポリシー モードの場合です。</param>
        <summary>
            仮想マシン スケール セットのアップグレード ポリシーのモードを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>