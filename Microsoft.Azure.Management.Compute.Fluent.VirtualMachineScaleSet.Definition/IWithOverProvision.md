<Type Name="IWithOverProvision" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOverProvision">
  <TypeSignature Language="C#" Value="public interface IWithOverProvision" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithOverProvision" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOverProvision" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithOverProvision" />
  <TypeSignature Language="F#" Value="type IWithOverProvision = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            仮想マシンのスケールのステージでは、スケール セット内の仮想マシンの過剰プロビジョニングするかどうかを指定できるように定義を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutOverProvisioning">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithoutOverProvisioning ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithoutOverProvisioning() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOverProvision.WithoutOverProvisioning" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutOverProvisioning () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithoutOverProvisioning : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate" Usage="iWithOverProvision.WithoutOverProvisioning " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            無効には、仮想マシンの過剰なプロビジョニング。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithOverProvision">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithOverProvision (bool enabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithOverProvision(bool enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOverProvision.WithOverProvision(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOverProvision (enabled As Boolean) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithOverProvision : bool -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate" Usage="iWithOverProvision.WithOverProvision enabled" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="enabled">
            True のスケールには、仮想マシンのフェールオーバー 0provisioning を有効にする場合設定、それ以外の場合は false。
            </param>
        <summary>
            有効または仮想マシン スケール セット内の過剰なプロビジョニングを無効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithOverProvisioning">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithOverProvisioning ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithOverProvisioning() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOverProvision.WithOverProvisioning" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOverProvisioning () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithOverProvisioning : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate" Usage="iWithOverProvision.WithOverProvisioning " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            仮想マシンの過剰プロビジョニングを有効します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>