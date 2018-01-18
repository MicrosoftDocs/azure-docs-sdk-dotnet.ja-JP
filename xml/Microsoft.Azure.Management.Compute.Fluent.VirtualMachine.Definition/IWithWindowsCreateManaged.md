<Type Name="IWithWindowsCreateManaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged">
  <TypeSignature Language="C#" Value="public interface IWithWindowsCreateManaged : Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithFromImageCreateOptionsManaged, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithWindowsCreateManaged implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithAvailabilitySet, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithAvailabilityZone, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithBootDiagnostics, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithExtension, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithFromImageCreateOptionsManaged, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedServiceIdentity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPlan, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithVMSize, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithWindowsCreateManaged&#xA;Implements IBeta, ICreatable(Of IVirtualMachine), IDefinitionWithTags(Of IWithCreate), IWithFromImageCreateOptionsManaged" />
  <TypeSignature Language="F#" Value="type IWithWindowsCreateManaged = interface&#xA;    interface IWithFromImageCreateOptionsManaged&#xA;    interface IWithManagedCreate&#xA;    interface IWithManagedDataDisk&#xA;    interface IWithAvailabilityZone&#xA;    interface IBeta&#xA;    interface IWithCreate&#xA;    interface ICreatable&lt;IVirtualMachine&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;&#xA;    interface IWithOSDiskSettings&#xA;    interface IWithVMSize&#xA;    interface IWithStorageAccount&#xA;    interface IWithAvailabilitySet&#xA;    interface IWithSecondaryNetworkInterface&#xA;    interface IWithExtension&#xA;    interface IWithPlan&#xA;    interface IWithBootDiagnostics&#xA;    interface IWithManagedServiceIdentity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithFromImageCreateOptionsManaged</InterfaceName>
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
            <span data-ttu-id="c035e-101">Windows 仮想マシンの定義のリソースを作成するには、最低限必要な入力を含むのステージを指定する省略可能なその他の設定も可能ですが。</span><span class="sxs-lookup"><span data-stu-id="c035e-101">The stage of a Windows virtual machine definition which contains all the minimum required inputs for the resource to be created, but also allows for any other optional settings to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutAutoUpdate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged WithoutAutoUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged WithoutAutoUpdate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged.WithoutAutoUpdate" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAutoUpdate () As IWithWindowsCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithoutAutoUpdate : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged" Usage="iWithWindowsCreateManaged.WithoutAutoUpdate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c035e-102">自動更新を無効にします。</span><span class="sxs-lookup"><span data-stu-id="c035e-102">Disables automatic updates.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c035e-103">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c035e-103">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutVMAgent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged WithoutVMAgent ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged WithoutVMAgent() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged.WithoutVMAgent" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutVMAgent () As IWithWindowsCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithoutVMAgent : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged" Usage="iWithWindowsCreateManaged.WithoutVMAgent " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c035e-104">VM エージェントのプロビジョニングできないようにします。</span><span class="sxs-lookup"><span data-stu-id="c035e-104">Prevents the provisioning of a VM agent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c035e-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c035e-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithTimeZone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged WithTimeZone (string timeZone);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged WithTimeZone(string timeZone) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged.WithTimeZone(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTimeZone (timeZone As String) As IWithWindowsCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithTimeZone : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged" Usage="iWithWindowsCreateManaged.WithTimeZone timeZone" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeZone" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="timeZone"><span data-ttu-id="c035e-106">タイム ゾーンです。</span><span class="sxs-lookup"><span data-stu-id="c035e-106">A time zone.</span></span></param>
        <summary>
            <span data-ttu-id="c035e-107">タイム ゾーンを指定します。</span><span class="sxs-lookup"><span data-stu-id="c035e-107">Specifies the time-zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c035e-108">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c035e-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWinRM">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged WithWinRM (Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener listener);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged WithWinRM(class Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener listener) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged.WithWinRM(Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWinRM (listener As WinRMListener) As IWithWindowsCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithWinRM : Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged" Usage="iWithWindowsCreateManaged.WithWinRM listener" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithWindowsCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="listener" Type="Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener" />
      </Parameters>
      <Docs>
        <param name="listener"><span data-ttu-id="c035e-109">WinRM リスナー。</span><span class="sxs-lookup"><span data-stu-id="c035e-109">A WinRM listener.</span></span></param>
        <summary>
            <span data-ttu-id="c035e-110">WinRM リスナーを指定します。</span><span class="sxs-lookup"><span data-stu-id="c035e-110">Specifies  WinRM listener.</span></span>
            <span data-ttu-id="c035e-111">このメソッドを呼び出すたびでは、VM の WinRM リスナーのリストに指定されたリスナーを追加します。</span><span class="sxs-lookup"><span data-stu-id="c035e-111">Each call to this method adds the given listener to the list of the VM's WinRM listeners.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c035e-112">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c035e-112">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>