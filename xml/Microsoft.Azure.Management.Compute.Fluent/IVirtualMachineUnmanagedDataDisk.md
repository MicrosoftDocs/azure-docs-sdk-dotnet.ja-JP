<Type Name="IVirtualMachineUnmanagedDataDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineUnmanagedDataDisk : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineUnmanagedDataDisk implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineUnmanagedDataDisk&#xA;Implements IChildResource(Of IVirtualMachine), IHasInner(Of DataDisk), IHasParent(Of IVirtualMachine)" />
  <TypeSignature Language="F#" Value="type IVirtualMachineUnmanagedDataDisk = interface&#xA;    interface IHasInner&lt;DataDisk&gt;&#xA;    interface IChildResource&lt;IVirtualMachine&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IVirtualMachine&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="598f9-101">仮想マシンのネイティブ データ ディスク。</span><span class="sxs-lookup"><span data-stu-id="598f9-101">A native data disk of a virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CachingType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes CachingType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes CachingType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk.CachingType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CachingType As CachingTypes" />
      <MemberSignature Language="F#" Value="member this.CachingType : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk.CachingType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="598f9-102">型のキャッシュ ディスクを取得します。</span><span class="sxs-lookup"><span data-stu-id="598f9-102">Gets the disk caching type.</span></span>
            <span data-ttu-id="598f9-103">使用可能な値が: 'None'、'ReadOnly'、'ReadWrite' です。</span><span class="sxs-lookup"><span data-stu-id="598f9-103">possible values are: 'None', 'ReadOnly', 'ReadWrite'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationMethod">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes CreationMethod { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes CreationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk.CreationMethod" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationMethod As DiskCreateOptionTypes" />
      <MemberSignature Language="F#" Value="member this.CreationMethod : Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk.CreationMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="598f9-104">このディスクを作成するときに使用される作成方法を取得します。</span><span class="sxs-lookup"><span data-stu-id="598f9-104">Gets the creation method used while creating this disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lun">
      <MemberSignature Language="C#" Value="public int Lun { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Lun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk.Lun" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Lun As Integer" />
      <MemberSignature Language="F#" Value="member this.Lun : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk.Lun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="598f9-105">このデータ ディスクに割り当てられた論理ユニットの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="598f9-105">Gets the logical unit number assigned to this data disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public int Size { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk.Size" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Size As Integer" />
      <MemberSignature Language="F#" Value="member this.Size : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk.Size" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="598f9-106">このデータ ディスクのサイズを GB 単位を取得します。</span><span class="sxs-lookup"><span data-stu-id="598f9-106">Gets the size of this data disk in GB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceImageUri">
      <MemberSignature Language="C#" Value="public string SourceImageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceImageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk.SourceImageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceImageUri As String" />
      <MemberSignature Language="F#" Value="member this.SourceImageUri : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk.SourceImageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="598f9-107">このディスクの作成元のソース バーチャル ハード ディスク ユーザー イメージへの Uri を取得します。</span><span class="sxs-lookup"><span data-stu-id="598f9-107">Gets Uri to the source virtual hard disk user image from which this disk was created.</span></span>
            <span data-ttu-id="598f9-108">このディスクがイメージに基づいていない場合は、null が返されます。</span><span class="sxs-lookup"><span data-stu-id="598f9-108">null will be returned if this disk is not based on an image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VhdUri">
      <MemberSignature Language="C#" Value="public string VhdUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VhdUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk.VhdUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VhdUri As String" />
      <MemberSignature Language="F#" Value="member this.VhdUri : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk.VhdUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="598f9-109">このデータ ディスクをバックアップする仮想ハード ディスクへの URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="598f9-109">Gets URI to the virtual hard disk backing this data disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>