<Type Name="IVirtualMachineDataDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineDataDisk : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineDataDisk implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineDataDisk&#xA;Implements IHasId, IHasInner(Of DataDisk), IHasName" />
  <TypeSignature Language="F#" Value="type IVirtualMachineDataDisk = interface&#xA;    interface IHasInner&lt;DataDisk&gt;&#xA;    interface IHasName&#xA;    interface IHasId" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="7204e-101">仮想マシンの管理対象のデータ ディスク。</span><span class="sxs-lookup"><span data-stu-id="7204e-101">A managed data disk of a virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CachingType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; CachingType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; CachingType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk.CachingType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CachingType As Nullable(Of CachingTypes)" />
      <MemberSignature Language="F#" Value="member this.CachingType : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk.CachingType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7204e-102">型のキャッシュ ディスクを取得します。</span><span class="sxs-lookup"><span data-stu-id="7204e-102">Gets the disk caching type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationMethod">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes CreationMethod { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes CreationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk.CreationMethod" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationMethod As DiskCreateOptionTypes" />
      <MemberSignature Language="F#" Value="member this.CreationMethod : Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk.CreationMethod" />
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
            <span data-ttu-id="7204e-103">このディスクを作成するときに使用される作成方法を取得します。</span><span class="sxs-lookup"><span data-stu-id="7204e-103">Gets the creation method used while creating this disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lun">
      <MemberSignature Language="C#" Value="public int Lun { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Lun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk.Lun" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Lun As Integer" />
      <MemberSignature Language="F#" Value="member this.Lun : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk.Lun" />
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
            <span data-ttu-id="7204e-104">このデータ ディスクに割り当てられた論理ユニットの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="7204e-104">Gets the logical unit number assigned to this data disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public int Size { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk.Size" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Size As Integer" />
      <MemberSignature Language="F#" Value="member this.Size : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk.Size" />
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
            <span data-ttu-id="7204e-105">このデータ ディスクのサイズを GB 単位を取得します。</span><span class="sxs-lookup"><span data-stu-id="7204e-105">Gets the size of this data disk in GB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt; StorageAccountType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt; StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageAccountType As Nullable(Of StorageAccountTypes)" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7204e-106">ディスクのストレージ アカウントの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="7204e-106">Gets the storage account type of the disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>