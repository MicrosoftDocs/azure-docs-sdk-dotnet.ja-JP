<Type Name="IWithManagedDataDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk">
  <TypeSignature Language="C#" Value="public interface IWithManagedDataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithManagedDataDisk" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithManagedDataDisk" />
  <TypeSignature Language="F#" Value="type IWithManagedDataDisk = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            マネージ データ ディスクを指定できるように仮想マシンの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithExistingDataDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk disk);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithExistingDataDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk disk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithExistingDataDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingDataDisk (disk As IDisk) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingDataDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithExistingDataDisk disk" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
      </Parameters>
      <Docs>
        <param name="disk">既存の管理対象ディスクです。</param>
        <summary>
            既存のソース管理されているディスクを仮想マシンに関連付けます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithExistingDataDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk disk, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithExistingDataDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk disk, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithExistingDataDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingDataDisk (disk As IDisk, lun As Integer, cachingType As CachingTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingDataDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithExistingDataDisk (disk, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="disk">管理対象のディスク。</param>
        <param name="lun">ディスクの LUN です。</param>
        <param name="cachingType">キャッシュの型。</param>
        <summary>
            既存のソース管理対象ディスクを仮想マシンに関連付けし、追加の設定を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithExistingDataDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk disk, int newSizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithExistingDataDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk disk, int32 newSizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithExistingDataDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk,System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingDataDisk (disk As IDisk, newSizeInGB As Integer, lun As Integer, cachingType As CachingTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingDataDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk * int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithExistingDataDisk (disk, newSizeInGB, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
        <Parameter Name="newSizeInGB" Type="System.Int32" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="disk">管理対象のディスク。</param>
        <param name="newSizeInGB">ディスク サイズ (GB) のサイズを変更します。</param>
        <param name="lun">ディスクの LUN です。</param>
        <param name="cachingType">キャッシュの型。</param>
        <summary>
            既存のソース管理対象ディスクを仮想マシンに関連付けし、追加の設定を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithNewDataDisk(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Compute.Fluent.IDisk})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (creatable As ICreatable(Of IDisk)) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDisk creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">作成可能なディスクの定義。</param>
        <summary>
            管理対象ディスクの特定の定義で明示的に作成およびデータ ディスクとして仮想マシンにアタッチされている必要がありますを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithNewDataDisk(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDisk sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">Gb マネージ ディスクのサイズ。</param>
        <summary>
            管理対象ディスクを特定のサイズで暗黙的に作成する必要があることを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; creatable, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; creatable, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithNewDataDisk(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Compute.Fluent.IDisk},System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (creatable As ICreatable(Of IDisk), lun As Integer, cachingType As CachingTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt; * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDisk (creatable, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt;" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="creatable">作成可能なディスク。</param>
        <param name="lun">データ ディスク LUN。</param>
        <param name="cachingType">データ ディスク型をキャッシュします。</param>
        <summary>
            管理対象ディスクを特定の定義で明示的に作成して、データ ディスクとして仮想マシンにアタッチする必要があることを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk (int sizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk(int32 sizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithNewDataDisk(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer, lun As Integer, cachingType As CachingTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDisk (sizeInGB, lun, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">Gb マネージ ディスクのサイズ。</param>
        <param name="lun">ディスクの LUN です。</param>
        <param name="cachingType">キャッシュの型。</param>
        <summary>
            管理対象ディスクを指定した設定で暗黙的に作成する必要があることを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk (int sizeInGB, int lun, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDisk(int32 sizeInGB, int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithNewDataDisk(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes,Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDisk (sizeInGB As Integer, lun As Integer, cachingType As CachingTypes, storageAccountType As StorageAccountTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDisk : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes * Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDisk (sizeInGB, lun, cachingType, storageAccountType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
        <Parameter Name="storageAccountType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">Gb マネージ ディスクのサイズ。</param>
        <param name="lun">ディスクの LUN です。</param>
        <param name="cachingType">キャッシュの型。</param>
        <param name="storageAccountType">ストレージ アカウントの種類。</param>
        <summary>
            管理対象ディスクを指定した設定で暗黙的に作成する必要があることを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDiskFromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDiskFromImage (int imageLun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDiskFromImage(int32 imageLun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithNewDataDiskFromImage(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDiskFromImage (imageLun As Integer) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDiskFromImage : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDiskFromImage imageLun" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
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
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDiskFromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDiskFromImage (int imageLun, int newSizeInGB, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDiskFromImage(int32 imageLun, int32 newSizeInGB, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithNewDataDiskFromImage(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDiskFromImage (imageLun As Integer, newSizeInGB As Integer, cachingType As CachingTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDiskFromImage : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDiskFromImage (imageLun, newSizeInGB, cachingType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
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
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDataDiskFromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDiskFromImage (int imageLun, int newSizeInGB, Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate WithNewDataDiskFromImage(int32 imageLun, int32 newSizeInGB, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk.WithNewDataDiskFromImage(System.Int32,System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes,Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDataDiskFromImage (imageLun As Integer, newSizeInGB As Integer, cachingType As CachingTypes, storageAccountType As StorageAccountTypes) As IWithManagedCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDataDiskFromImage : int * int * Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes * Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate" Usage="iWithManagedDataDisk.WithNewDataDiskFromImage (imageLun, newSizeInGB, cachingType, storageAccountType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate</ReturnType>
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
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>