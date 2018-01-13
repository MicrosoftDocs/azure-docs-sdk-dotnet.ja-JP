<Type Name="IWithSourceVirtualMachine" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithSourceVirtualMachine">
  <TypeSignature Language="C#" Value="public interface IWithSourceVirtualMachine" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSourceVirtualMachine" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithSourceVirtualMachine" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSourceVirtualMachine" />
  <TypeSignature Language="F#" Value="type IWithSourceVirtualMachine = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ソース バーチャル マシンを選択できるように、イメージ定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromVirtualMachine">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreate FromVirtualMachine (Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine virtualMachine);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreate FromVirtualMachine(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine virtualMachine) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithSourceVirtualMachine.FromVirtualMachine(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromVirtualMachine (virtualMachine As IVirtualMachine) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member FromVirtualMachine : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreate" Usage="iWithSourceVirtualMachine.FromVirtualMachine virtualMachine" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="virtualMachine" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine" />
      </Parameters>
      <Docs>
        <param name="virtualMachine">ソース バーチャル マシンです。</param>
        <summary>
            OS のソースのディスク イメージとイメージのデータ ディスクのイメージとは、バーチャル マシンの OS とデータ ディスクを使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="FromVirtualMachine">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreate FromVirtualMachine (string virtualMachineId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreate FromVirtualMachine(string virtualMachineId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithSourceVirtualMachine.FromVirtualMachine(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromVirtualMachine (virtualMachineId As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member FromVirtualMachine : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreate" Usage="iWithSourceVirtualMachine.FromVirtualMachine virtualMachineId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="virtualMachineId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="virtualMachineId">ソース バーチャル マシンのリソース id です。</param>
        <summary>
            バーチャル マシンの OS ディスクとデータ ディスクを OS ディスクのイメージと、このイメージのデータ ディスク イメージのソースとして使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>