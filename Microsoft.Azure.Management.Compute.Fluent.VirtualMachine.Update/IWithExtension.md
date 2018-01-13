<Type Name="IWithExtension" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithExtension">
  <TypeSignature Language="C#" Value="public interface IWithExtension" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExtension" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithExtension" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExtension" />
  <TypeSignature Language="F#" Value="type IWithExtension = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            拡張子を指定できるようにバーチャル マシンの更新の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineNewExtension">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt; DefineNewExtension (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt; DefineNewExtension(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithExtension.DefineNewExtension(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewExtension (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewExtension : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt;" Usage="iWithExtension.DefineNewExtension name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">拡張機能の参照名。</param>
        <summary>
            仮想マシンにアタッチされている拡張機能の定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>拡張機能定義の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateExtension">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate UpdateExtension (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate UpdateExtension(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithExtension.UpdateExtension(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateExtension (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateExtension : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate" Usage="iWithExtension.UpdateExtension name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">既存の拡張機能の参照名。</param>
        <summary>
            このバーチャル マシンの既存の拡張機能の更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>拡張機能の更新プログラムの最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutExtension">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutExtension (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutExtension(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithExtension.WithoutExtension(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutExtension (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutExtension : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithExtension.WithoutExtension name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">削除/アンインストールする拡張機能の参照名。</param>
        <summary>
            バーチャル マシンから拡張をデタッチします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>