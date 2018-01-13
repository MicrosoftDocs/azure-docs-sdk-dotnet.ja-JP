<Type Name="IWithManagedDataDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk">
  <TypeSignature Language="C#" Value="public interface IWithManagedDataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithManagedDataDisk" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithManagedDataDisk" />
  <TypeSignature Language="F#" Value="type IWithManagedDataDisk = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            仮想マシンのスケールのステージでは、マネージ データ ディスクを指定できるように定義を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDisk (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDisk(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk.WithNewDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDisk sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">管理対象ディスクのサイズ。</param>
        <summary>
            管理対象ディスクを特定のサイズで暗黙的に作成する必要があることを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>仮想マシンの定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDisk (int sizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDisk(int32 sizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk.WithNewDataDisk(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer, lun As Integer, cachingType As CachingTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDisk (sizeInGB, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">管理対象ディスクのサイズ。</param>
        <param name="lun">ディスクの LUN です。</param>
        <param name="cachingType">キャッシュの型。</param>
        <summary>
            管理対象ディスクを指定した設定で暗黙的に作成する必要があることを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>仮想マシンの定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDisk (int sizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDisk(int32 sizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk.WithNewDataDisk(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes,Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer, lun As Integer, cachingType As CachingTypes, storageAccountType As StorageAccountTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes * Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDisk (sizeInGB, lun, cachingType, storageAccountType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
        <Parameter Name="storageAccountType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">管理対象ディスクのサイズ。</param>
        <param name="lun">ディスクの LUN です。</param>
        <param name="cachingType">キャッシュの型。</param>
        <param name="storageAccountType">ストレージ アカウントの種類。</param>
        <summary>
            管理対象ディスクを指定した設定で暗黙的に作成する必要があることを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>仮想マシンの定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDiskFromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDiskFromImage (int imageLun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDiskFromImage(int32 imageLun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk.WithNewDataDiskFromImage(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDiskFromImage (imageLun As Integer) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDiskFromImage : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDiskFromImage imageLun" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageLun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="imageLun">ソース データのディスク イメージの LUN です。</param>
        <summary>
            データ ディスクを仮想マシンのイメージに、データ ディスクのイメージから作成することを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>仮想マシンの定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDiskFromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDiskFromImage (int imageLun, int newSizeInGB, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDiskFromImage(int32 imageLun, int32 newSizeInGB, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk.WithNewDataDiskFromImage(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDiskFromImage (imageLun As Integer, newSizeInGB As Integer, cachingType As CachingTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDiskFromImage : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDiskFromImage (imageLun, newSizeInGB, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageLun" Type="System.Int32" />
        <Parameter Name="newSizeInGB" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="imageLun">ソース データのディスク イメージの LUN です。</param>
        <param name="newSizeInGB">データ ディスク イメージで指定された既定のサイズをオーバーライドする新しいサイズ。</param>
        <param name="cachingType">キャッシュの型。</param>
        <summary>
            データ ディスクを仮想マシンのイメージに、データ ディスクのイメージから作成することを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>仮想マシンの定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDiskFromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDiskFromImage (int imageLun, int newSizeInGB, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate WithNewDataDiskFromImage(int32 imageLun, int32 newSizeInGB, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedDataDisk.WithNewDataDiskFromImage(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes,Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDiskFromImage (imageLun As Integer, newSizeInGB As Integer, cachingType As CachingTypes, storageAccountType As StorageAccountTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDiskFromImage : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes * Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDiskFromImage (imageLun, newSizeInGB, cachingType, storageAccountType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageLun" Type="System.Int32" />
        <Parameter Name="newSizeInGB" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
        <Parameter Name="storageAccountType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes" />
      </Parameters>
      <Docs>
        <param name="imageLun">ソース データのディスク イメージの LUN です。</param>
        <param name="newSizeInGB">データ ディスク イメージで指定された既定のサイズをオーバーライドする新しいサイズ。</param>
        <param name="cachingType">キャッシュの型。</param>
        <param name="storageAccountType">ストレージ アカウントの種類。</param>
        <summary>
            データ ディスクを仮想マシンのイメージに、データ ディスクのイメージから作成することを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>仮想マシンの定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>