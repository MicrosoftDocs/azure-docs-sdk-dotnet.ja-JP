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
            Linux 仮想マシンのスケールのステージでは、SSH ルート ユーザーの名前を指定できるように定義を設定します。
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
        <param name="rootUserName">Linux ユーザー名の必要な命名規則に従ったルート ユーザーの名前。</param>
        <summary>
            Linux 仮想マシンの SSH ルート ユーザー名を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>