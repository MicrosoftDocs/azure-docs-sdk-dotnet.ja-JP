<Type Name="IWithUnmanagedDataDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedDataDisk">
  <TypeSignature Language="C#" Value="public interface IWithUnmanagedDataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithUnmanagedDataDisk" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithUnmanagedDataDisk" />
  <TypeSignature Language="F#" Value="type IWithUnmanagedDataDisk = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6b69f-101">アンマネージ データ ディスクを追加するように仮想マシンの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="6b69f-101">The stage of a virtual machine definition allowing to add an unmanaged data disk.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate&gt; DefineUnmanagedDataDisk (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate&gt; DefineUnmanagedDataDisk(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedDataDisk.DefineUnmanagedDataDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineUnmanagedDataDisk (name As String) As IBlank(Of IWithUnmanagedCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineUnmanagedDataDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate&gt;" Usage="iWithUnmanagedDataDisk.DefineUnmanagedDataDisk name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="6b69f-102">データ ディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="6b69f-102">The name for the data disk.</span></span></param>
        <summary>
            <span data-ttu-id="6b69f-103">仮想マシンにアタッチされているアンマネージ データ ディスクの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="6b69f-103">Begins definition of an unmanaged data disk to be attached to the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="6b69f-104">アンマネージ データ ディスク定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="6b69f-104">The first stage of an unmanaged data disk definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate WithExistingUnmanagedDataDisk (string storageAccountName, string containerName, string vhdName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate WithExistingUnmanagedDataDisk(string storageAccountName, string containerName, string vhdName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedDataDisk.WithExistingUnmanagedDataDisk(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingUnmanagedDataDisk (storageAccountName As String, containerName As String, vhdName As String) As IWithUnmanagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingUnmanagedDataDisk : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate" Usage="iWithUnmanagedDataDisk.WithExistingUnmanagedDataDisk (storageAccountName, containerName, vhdName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="vhdName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName"><span data-ttu-id="6b69f-105">ストレージ アカウント名。</span><span class="sxs-lookup"><span data-stu-id="6b69f-105">A storage account name.</span></span></param>
        <param name="containerName"><span data-ttu-id="6b69f-106">VHD ファイルを保持するコンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b69f-106">The name of the container holding the VHD file.</span></span></param>
        <param name="vhdName"><span data-ttu-id="6b69f-107">VHD ファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="6b69f-107">The name for the VHD file.</span></span></param>
        <summary>
            <span data-ttu-id="6b69f-108">既存のアンマネージ VHD をデータ ディスクとして仮想マシンにアタッチします。</span><span class="sxs-lookup"><span data-stu-id="6b69f-108">Attaches an existing unmanaged VHD as a data disk to the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="6b69f-109">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="6b69f-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate WithNewUnmanagedDataDisk (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate WithNewUnmanagedDataDisk(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedDataDisk.WithNewUnmanagedDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewUnmanagedDataDisk (sizeInGB As Integer) As IWithUnmanagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewUnmanagedDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate" Usage="iWithUnmanagedDataDisk.WithNewUnmanagedDataDisk sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithUnmanagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB"><span data-ttu-id="6b69f-110">GB のディスク サイズです。</span><span class="sxs-lookup"><span data-stu-id="6b69f-110">The disk size in GB.</span></span></param>
        <summary>
            <span data-ttu-id="6b69f-111">新しい空白のアンマネージ データ ディスクを仮想マシンにアタッチします。</span><span class="sxs-lookup"><span data-stu-id="6b69f-111">Attaches a new blank unmanaged data disk to the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="6b69f-112">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="6b69f-112">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>