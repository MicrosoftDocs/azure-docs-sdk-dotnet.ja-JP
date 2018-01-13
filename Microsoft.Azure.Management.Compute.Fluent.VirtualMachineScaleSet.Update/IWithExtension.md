<Type Name="IWithExtension" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithExtension">
  <TypeSignature Language="C#" Value="public interface IWithExtension" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExtension" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithExtension" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExtension" />
  <TypeSignature Language="F#" Value="type IWithExtension = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            拡張子を指定できるように、仮想マシンの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineNewExtension">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt; DefineNewExtension (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt; DefineNewExtension(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithExtension.DefineNewExtension(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewExtension (name As String) As IBlank(Of IWithApply)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewExtension : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt;" Usage="iWithExtension.DefineNewExtension name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">拡張機能の参照名です。</param>
        <summary>
            スケール セット内の仮想マシンにアタッチされている拡張機能の参照の定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>拡張機能参照の定義の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateExtension">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate UpdateExtension (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate UpdateExtension(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithExtension.UpdateExtension(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateExtension (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateExtension : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate" Usage="iWithExtension.UpdateExtension name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">拡張機能の参照名。</param>
        <summary>
            スケール セット内の仮想マシンに割り当てられている既存の拡張機能の更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>拡張機能参照の更新の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutExtension">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutExtension (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutExtension(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithExtension.WithoutExtension(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutExtension (name As String) As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithoutExtension : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithExtension.WithoutExtension name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">削除/アンインストールする拡張機能の参照名。</param>
        <summary>
            スケール セット内の仮想マシンから指定した名前の拡張機能を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>