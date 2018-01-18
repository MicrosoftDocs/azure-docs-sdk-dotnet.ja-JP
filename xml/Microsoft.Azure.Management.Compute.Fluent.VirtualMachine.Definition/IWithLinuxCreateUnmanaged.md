<Type Name="IWithLinuxCreateUnmanaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateUnmanaged">
  <TypeSignature Language="C#" Value="public interface IWithLinuxCreateUnmanaged : Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithFromImageCreateOptionsUnmanaged, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLinuxCreateUnmanaged implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithAvailabilitySet, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithBootDiagnostics, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithExtension, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithFromImageCreateOptionsUnmanaged, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedServiceIdentity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPlan, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedDataDisk, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithVMSize, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateUnmanaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLinuxCreateUnmanaged&#xA;Implements IBeta, ICreatable(Of IVirtualMachine), IDefinitionWithTags(Of IWithCreate), IWithFromImageCreateOptionsUnmanaged" />
  <TypeSignature Language="F#" Value="type IWithLinuxCreateUnmanaged = interface&#xA;    interface IWithFromImageCreateOptionsUnmanaged&#xA;    interface IWithUnmanagedCreate&#xA;    interface IWithUnmanagedDataDisk&#xA;    interface IWithCreate&#xA;    interface ICreatable&lt;IVirtualMachine&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;&#xA;    interface IWithOSDiskSettings&#xA;    interface IWithVMSize&#xA;    interface IWithStorageAccount&#xA;    interface IWithAvailabilitySet&#xA;    interface IWithSecondaryNetworkInterface&#xA;    interface IWithExtension&#xA;    interface IWithPlan&#xA;    interface IWithBootDiagnostics&#xA;    interface IWithManagedServiceIdentity&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithFromImageCreateOptionsUnmanaged</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="bb39e-101">Linux 仮想マシンの定義を作成するリソースの最低限必要な入力を含むのステージを指定する省略可能なその他の設定も可能ですが。</span><span class="sxs-lookup"><span data-stu-id="bb39e-101">The stage of a Linux virtual machine definition which contains all the minimum required inputs for the resource to be created, but also allows for any other optional settings to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSsh">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateUnmanaged WithSsh (string publicKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateUnmanaged WithSsh(string publicKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateUnmanaged.WithSsh(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSsh (publicKey As String) As IWithLinuxCreateUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithSsh : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateUnmanaged" Usage="iWithLinuxCreateUnmanaged.WithSsh publicKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publicKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publicKey"><span data-ttu-id="bb39e-102">PEM 形式での SSH 公開キー。</span><span class="sxs-lookup"><span data-stu-id="bb39e-102">An SSH public key in the PEM format.</span></span></param>
        <summary>
            <span data-ttu-id="bb39e-103">SSH 公開キーを指定します。</span><span class="sxs-lookup"><span data-stu-id="bb39e-103">Specifies an SSH public key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="bb39e-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="bb39e-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>