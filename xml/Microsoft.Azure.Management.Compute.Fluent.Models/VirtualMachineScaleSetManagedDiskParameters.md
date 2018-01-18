<Type Name="VirtualMachineScaleSetManagedDiskParameters" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetManagedDiskParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetManagedDiskParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetManagedDiskParameters" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetManagedDiskParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="841ce-101">ScaleSet 管理ディスクのパラメーターについて説明します。</span><span class="sxs-lookup"><span data-stu-id="841ce-101">Describes the parameters of a ScaleSet managed disk.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetManagedDiskParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="841ce-102">VirtualMachineScaleSetManagedDiskParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="841ce-102">Initializes a new instance of the VirtualMachineScaleSetManagedDiskParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetManagedDiskParameters (Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt; storageAccountType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt; storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional storageAccountType As Nullable(Of StorageAccountTypes) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters storageAccountType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccountType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt;" />
      </Parameters>
      <Docs>
        <param name="storageAccountType"><span data-ttu-id="841ce-103">ストレージ アカウントの種類。</span><span class="sxs-lookup"><span data-stu-id="841ce-103">The Storage Account type.</span></span> <span data-ttu-id="841ce-104">使用可能な値が含まれます: 'Standard_LRS'、'Premium_LRS'</span><span class="sxs-lookup"><span data-stu-id="841ce-104">Possible values include: 'Standard_LRS', 'Premium_LRS'</span></span></param>
        <summary>
            <span data-ttu-id="841ce-105">VirtualMachineScaleSetManagedDiskParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="841ce-105">Initializes a new instance of the VirtualMachineScaleSetManagedDiskParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt; StorageAccountType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt; StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountType As Nullable(Of StorageAccountTypes)" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="841ce-106">取得またはストレージ アカウントの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="841ce-106">Gets or sets the Storage Account type.</span></span> <span data-ttu-id="841ce-107">使用可能な値が含まれます: 'Standard_LRS'、'Premium_LRS'</span><span class="sxs-lookup"><span data-stu-id="841ce-107">Possible values include: 'Standard_LRS', 'Premium_LRS'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>