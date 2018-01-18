<Type Name="IWithUnmanagedDataDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk">
  <TypeSignature Language="C#" Value="public interface IWithUnmanagedDataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithUnmanagedDataDisk" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithUnmanagedDataDisk" />
  <TypeSignature Language="F#" Value="type IWithUnmanagedDataDisk = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4edf7-101">アンマネージ データ ディスクの構成を指定できるように仮想マシンの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="4edf7-101">The stage of a virtual machine definition allowing to specify unmanaged data disk configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt; DefineUnmanagedDataDisk (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt; DefineUnmanagedDataDisk(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.DefineUnmanagedDataDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineUnmanagedDataDisk (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineUnmanagedDataDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt;" Usage="iWithUnmanagedDataDisk.DefineUnmanagedDataDisk name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="4edf7-102">データ ディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="4edf7-102">The name for the data disk.</span></span></param>
        <summary>
            <span data-ttu-id="4edf7-103">その構成、仮想マシンに接続する空のアンマネージ データ ディスクの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="4edf7-103">Begins the definition of a blank unmanaged data disk to be attached to the virtual machine along with its configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4edf7-104">データ ディスクの定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="4edf7-104">The first stage of the data disk definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate UpdateUnmanagedDataDisk (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate UpdateUnmanagedDataDisk(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.UpdateUnmanagedDataDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateUnmanagedDataDisk (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateUnmanagedDataDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate" Usage="iWithUnmanagedDataDisk.UpdateUnmanagedDataDisk name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="4edf7-105">既存のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="4edf7-105">The name of an existing disk.</span></span></param>
        <summary>
            <span data-ttu-id="4edf7-106">このバーチャル マシンの既存のアンマネージ データ ディスクの更新プログラムの説明を開始します。</span><span class="sxs-lookup"><span data-stu-id="4edf7-106">Begins the description of an update of an existing unmanaged data disk of this virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4edf7-107">データ ディスクの更新の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="4edf7-107">The first stage of the data disk update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingUnmanagedDataDisk (string storageAccountName, string containerName, string vhdName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingUnmanagedDataDisk(string storageAccountName, string containerName, string vhdName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.WithExistingUnmanagedDataDisk(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingUnmanagedDataDisk (storageAccountName As String, containerName As String, vhdName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingUnmanagedDataDisk : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithUnmanagedDataDisk.WithExistingUnmanagedDataDisk (storageAccountName, containerName, vhdName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="vhdName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName"><span data-ttu-id="4edf7-108">ストレージ アカウント名。</span><span class="sxs-lookup"><span data-stu-id="4edf7-108">The storage account name.</span></span></param>
        <param name="containerName"><span data-ttu-id="4edf7-109">VHD ファイルを保持するコンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="4edf7-109">The name of the container holding the VHD file.</span></span></param>
        <param name="vhdName"><span data-ttu-id="4edf7-110">VHD ファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="4edf7-110">The name for the VHD file.</span></span></param>
        <summary>
            <span data-ttu-id="4edf7-111">データ ディスクとして仮想マシンにアタッチする必要がある既存の VHD を指定します。</span><span class="sxs-lookup"><span data-stu-id="4edf7-111">Specifies an existing VHD that needs to be attached to the virtual machine as data disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4edf7-112">VM の作成可能な定義を表す段階です。</span><span class="sxs-lookup"><span data-stu-id="4edf7-112">The stage representing creatable VM definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewUnmanagedDataDisk (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewUnmanagedDataDisk(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.WithNewUnmanagedDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewUnmanagedDataDisk (sizeInGB As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewUnmanagedDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithUnmanagedDataDisk.WithNewUnmanagedDataDisk sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB"><span data-ttu-id="4edf7-113">GB のディスク サイズです。</span><span class="sxs-lookup"><span data-stu-id="4edf7-113">The disk size in GB.</span></span></param>
        <summary>
            <span data-ttu-id="4edf7-114">新しい空白のアンマネージ データ ディスクを仮想マシンに接続する必要があることを指定します。</span><span class="sxs-lookup"><span data-stu-id="4edf7-114">Specifies that a new blank unmanaged data disk needs to be attached to virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4edf7-115">VM の作成可能な定義を表す段階です。</span><span class="sxs-lookup"><span data-stu-id="4edf7-115">The stage representing creatable VM definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutUnmanagedDataDisk (int lun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutUnmanagedDataDisk(int32 lun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.WithoutUnmanagedDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutUnmanagedDataDisk (lun As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutUnmanagedDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithUnmanagedDataDisk.WithoutUnmanagedDataDisk lun" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="lun"><span data-ttu-id="4edf7-116">削除するデータ ディスクの論理ユニット番号。</span><span class="sxs-lookup"><span data-stu-id="4edf7-116">The logical unit number of the data disk to remove.</span></span></param>
        <summary>
            <span data-ttu-id="4edf7-117">バーチャル マシンからアンマネージ データ ディスクをデタッチします。</span><span class="sxs-lookup"><span data-stu-id="4edf7-117">Detaches a unmanaged data disk from the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4edf7-118">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="4edf7-118">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutUnmanagedDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutUnmanagedDataDisk (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutUnmanagedDataDisk(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk.WithoutUnmanagedDataDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutUnmanagedDataDisk (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutUnmanagedDataDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithUnmanagedDataDisk.WithoutUnmanagedDataDisk name" />
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
        <param name="name"><span data-ttu-id="4edf7-119">削除する既存のデータ ディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="4edf7-119">The name of an existing data disk to remove.</span></span></param>
        <summary>
            <span data-ttu-id="4edf7-120">バーチャル マシンから、アンマネージ データ ディスクをデタッチします。</span><span class="sxs-lookup"><span data-stu-id="4edf7-120">Detaches an unmanaged data disk from the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4edf7-121">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="4edf7-121">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>