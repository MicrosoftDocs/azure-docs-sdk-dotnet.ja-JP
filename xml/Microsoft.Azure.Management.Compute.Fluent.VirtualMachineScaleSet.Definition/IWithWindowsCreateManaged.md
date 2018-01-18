<Type Name="IWithWindowsCreateManaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged">
  <TypeSignature Language="C#" Value="public interface IWithWindowsCreateManaged : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithWindowsCreateManaged implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithAvailabilityZone, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithBootDiagnostics, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCapacity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithComputerNamePrefix, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCustomData, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithExtension, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDiskOptionals, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedServiceIdentity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOSDiskSettings, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOverProvision, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithStorageAccount, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUpgradePolicy, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithWindowsCreateManaged&#xA;Implements IBeta, ICreatable(Of IVirtualMachineScaleSet), IDefinitionWithTags(Of IWithCreate), IWithManagedCreate" />
  <TypeSignature Language="F#" Value="type IWithWindowsCreateManaged = interface&#xA;    interface IWithManagedCreate&#xA;    interface IWithManagedDataDisk&#xA;    interface IWithManagedDiskOptionals&#xA;    interface IWithAvailabilityZone&#xA;    interface IBeta&#xA;    interface IWithCreate&#xA;    interface ICreatable&lt;IVirtualMachineScaleSet&gt;&#xA;    interface IIndexable&#xA;    interface IWithOSDiskSettings&#xA;    interface IWithComputerNamePrefix&#xA;    interface IWithCapacity&#xA;    interface IWithUpgradePolicy&#xA;    interface IWithOverProvision&#xA;    interface IWithStorageAccount&#xA;    interface IWithCustomData&#xA;    interface IWithExtension&#xA;    interface IWithManagedServiceIdentity&#xA;    interface IWithBootDiagnostics&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="aa2b8-101">Windows 仮想マシンのスケールのステージの設定を含むすべての最低限必要な入力を作成するリソースの定義を指定する省略可能なその他の設定も可能ですが。</span><span class="sxs-lookup"><span data-stu-id="aa2b8-101">The stage of a Windows virtual machine scale set definition which contains all the minimum required inputs for the resource to be created, but also allows for any other optional settings to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAutoUpdate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged WithAutoUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged WithAutoUpdate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged.WithAutoUpdate" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAutoUpdate () As IWithWindowsCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithAutoUpdate : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged" Usage="iWithWindowsCreateManaged.WithAutoUpdate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="aa2b8-102">自動更新を有効にします。</span><span class="sxs-lookup"><span data-stu-id="aa2b8-102">Enables automatic updates.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="aa2b8-103">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="aa2b8-103">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutAutoUpdate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged WithoutAutoUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged WithoutAutoUpdate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged.WithoutAutoUpdate" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAutoUpdate () As IWithWindowsCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithoutAutoUpdate : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged" Usage="iWithWindowsCreateManaged.WithoutAutoUpdate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="aa2b8-104">自動更新を無効にします。</span><span class="sxs-lookup"><span data-stu-id="aa2b8-104">Disables automatic updates.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="aa2b8-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="aa2b8-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutVMAgent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged WithoutVMAgent ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged WithoutVMAgent() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged.WithoutVMAgent" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutVMAgent () As IWithWindowsCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithoutVMAgent : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged" Usage="iWithWindowsCreateManaged.WithoutVMAgent " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="aa2b8-106">VM エージェントを無効にします。</span><span class="sxs-lookup"><span data-stu-id="aa2b8-106">Disables the VM agent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="aa2b8-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="aa2b8-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithTimeZone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged WithTimeZone (string timeZone);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged WithTimeZone(string timeZone) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged.WithTimeZone(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTimeZone (timeZone As String) As IWithWindowsCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithTimeZone : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged" Usage="iWithWindowsCreateManaged.WithTimeZone timeZone" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeZone" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="timeZone"><span data-ttu-id="aa2b8-108">タイム ゾーンです。</span><span class="sxs-lookup"><span data-stu-id="aa2b8-108">A time zone.</span></span></param>
        <summary>
            <span data-ttu-id="aa2b8-109">使用する仮想マシンのタイム ゾーンを指定します。</span><span class="sxs-lookup"><span data-stu-id="aa2b8-109">Specifies the time zone for the virtual machines to use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="aa2b8-110">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="aa2b8-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithVMAgent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged WithVMAgent ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged WithVMAgent() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged.WithVMAgent" />
      <MemberSignature Language="VB.NET" Value="Public Function WithVMAgent () As IWithWindowsCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithVMAgent : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged" Usage="iWithWindowsCreateManaged.WithVMAgent " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="aa2b8-111">VM エージェントを有効にします。</span><span class="sxs-lookup"><span data-stu-id="aa2b8-111">Enables the VM agent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="aa2b8-112">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="aa2b8-112">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWinRM">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged WithWinRM (Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener listener);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged WithWinRM(class Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener listener) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged.WithWinRM(Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWinRM (listener As WinRMListener) As IWithWindowsCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithWinRM : Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged" Usage="iWithWindowsCreateManaged.WithWinRM listener" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="listener" Type="Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener" />
      </Parameters>
      <Docs>
        <param name="listener"><span data-ttu-id="aa2b8-113">WinRM リスナー。</span><span class="sxs-lookup"><span data-stu-id="aa2b8-113">A WinRM listener.</span></span></param>
        <summary>
            <span data-ttu-id="aa2b8-114">WinRM リスナーを指定します。</span><span class="sxs-lookup"><span data-stu-id="aa2b8-114">Specifies the WinRM listener.</span></span>
            <span data-ttu-id="aa2b8-115">このメソッドを呼び出すたびでは、VM の WinRM リスナーのリストに指定されたリスナーを追加します。</span><span class="sxs-lookup"><span data-stu-id="aa2b8-115">Each call to this method adds the given listener to the list of VM's WinRM listeners.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="aa2b8-116">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="aa2b8-116">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>