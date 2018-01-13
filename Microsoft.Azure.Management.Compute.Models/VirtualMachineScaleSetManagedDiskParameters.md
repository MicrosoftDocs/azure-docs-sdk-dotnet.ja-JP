<Type Name="VirtualMachineScaleSetManagedDiskParameters" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetManagedDiskParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetManagedDiskParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetManagedDiskParameters" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetManagedDiskParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ScaleSet 管理ディスクのパラメーターについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetManagedDiskParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VirtualMachineScaleSetManagedDiskParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetManagedDiskParameters (Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; storageAccountType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Models.StorageAccountTypes})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional storageAccountType As Nullable(Of StorageAccountTypes) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters : Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters storageAccountType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccountType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt;" />
      </Parameters>
      <Docs>
        <param name="storageAccountType">管理対象ディスクのストレージ アカウントの種類を指定します。 指定できる値は: Standard_LRS またはが premium_lrs の場合。 使用可能な値が含まれます: 'Standard_LRS'、'Premium_LRS'</param>
        <summary>
            VirtualMachineScaleSetManagedDiskParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; StorageAccountType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountType As Nullable(Of StorageAccountTypes)" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、管理対象ディスクのストレージ アカウントの種類を指定します。 指定できる値は: Standard_LRS またはが premium_lrs の場合。 使用可能な値が含まれます: 'Standard_LRS'、'Premium_LRS'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>