<Type Name="IWithNewVhdDiskSettings&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNewVhdDiskSettings&lt;ParentT&gt; : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithAttach&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNewVhdDiskSettings`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithAttach`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNewVhdDiskSettings(Of ParentT)&#xA;Implements IInDefinition(Of ParentT), IWithAttach(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithNewVhdDiskSettings&lt;'ParentT&gt; = interface&#xA;    interface IWithAttach&lt;'ParentT&gt;&#xA;    interface IInDefinition&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithAttach&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="b62ca-101">この定義をアタッチした後に戻るに親の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="b62ca-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="b62ca-102">により、ステージは、新しい VHD にベース ディスクを構成します。</span><span class="sxs-lookup"><span data-stu-id="b62ca-102">The stage that allows configure the disk based on new VHD.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="StoreAt">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings&lt;ParentT&gt; StoreAt (string storageAccountName, string containerName, string vhdName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings`1&lt;!ParentT&gt; StoreAt(string storageAccountName, string containerName, string vhdName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings`1.StoreAt(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function StoreAt (storageAccountName As String, containerName As String, vhdName As String) As IWithNewVhdDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member StoreAt : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings&lt;'ParentT&gt;" Usage="iWithNewVhdDiskSettings.StoreAt (storageAccountName, containerName, vhdName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="vhdName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName"><span data-ttu-id="b62ca-103">ストレージ アカウント名。</span><span class="sxs-lookup"><span data-stu-id="b62ca-103">The storage account name.</span></span></param>
        <param name="containerName"><span data-ttu-id="b62ca-104">新しい VHD ファイルを保持するコンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="b62ca-104">The name of the container to hold the new VHD file.</span></span></param>
        <param name="vhdName"><span data-ttu-id="b62ca-105">新しい VHD ファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="b62ca-105">The name for the new VHD file.</span></span></param>
        <summary>
            <span data-ttu-id="b62ca-106">新しい空のデータ ディスクに関連付けられている VHD を格納する必要が場所を指定します。</span><span class="sxs-lookup"><span data-stu-id="b62ca-106">Specifies where the VHD associated with the new blank data disk needs to be stored.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b62ca-107">データ ディスクの定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b62ca-107">The next stage of data disk definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithCaching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings&lt;ParentT&gt; WithCaching (Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings`1&lt;!ParentT&gt; WithCaching(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings`1.WithCaching(Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCaching (cachingType As CachingTypes) As IWithNewVhdDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithCaching : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings&lt;'ParentT&gt;" Usage="iWithNewVhdDiskSettings.WithCaching cachingType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="cachingType"><span data-ttu-id="b62ca-108">型のキャッシュ ディスク。</span><span class="sxs-lookup"><span data-stu-id="b62ca-108">The disk caching type.</span></span> <span data-ttu-id="b62ca-109">使用可能な値が含まれます。 'None'、'ReadOnly'、'ReadWrite' です。</span><span class="sxs-lookup"><span data-stu-id="b62ca-109">Possible values include: 'None', 'ReadOnly', 'ReadWrite'.</span></span></param>
        <summary>
            <span data-ttu-id="b62ca-110">データ ディスクのキャッシュの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="b62ca-110">Specifies the caching type for the data disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b62ca-111">データ ディスクの定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b62ca-111">The next stage of data disk definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithLun">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings&lt;ParentT&gt; WithLun (int lun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings`1&lt;!ParentT&gt; WithLun(int32 lun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings`1.WithLun(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLun (lun As Integer) As IWithNewVhdDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithLun : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings&lt;'ParentT&gt;" Usage="iWithNewVhdDiskSettings.WithLun lun" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="lun"><span data-ttu-id="b62ca-112">論理ユニットの数です。</span><span class="sxs-lookup"><span data-stu-id="b62ca-112">The logical unit number.</span></span></param>
        <summary>
            <span data-ttu-id="b62ca-113">データ ディスクの論理ユニット番号を指定します。</span><span class="sxs-lookup"><span data-stu-id="b62ca-113">Specifies the logical unit number for the data disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b62ca-114">データ ディスクの定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b62ca-114">The next stage of data disk definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>