<Type Name="IWithVMSize" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithVMSize">
  <TypeSignature Language="C#" Value="public interface IWithVMSize" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithVMSize" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithVMSize" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithVMSize" />
  <TypeSignature Language="F#" Value="type IWithVMSize = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            VM サイズを選択できるように、仮想マシンの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSize">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithSize (Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes size);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithSize(class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes size) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithVMSize.WithSize(Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSize (size As VirtualMachineSizeTypes) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithSize : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithVMSize.WithSize size" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="size" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes" />
      </Parameters>
      <Docs>
        <param name="size">バーチャル マシンの利用可能なサイズの一覧からサイズです。</param>
        <summary>
            仮想マシンのサイズを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithSize">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithSize (string sizeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithSize(string sizeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithVMSize.WithSize(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSize (sizeName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithSize : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithVMSize.WithSize sizeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sizeName">テキストとして、仮想マシンのサイズの名前。</param>
        <summary>
            仮想マシンのサイズを選択します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>