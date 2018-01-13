<Type Name="VirtualMachineScaleSetSku" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetSku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetSku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetSku" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetSku = class" />
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
            <span data-ttu-id="ab10c-101">使用可能な仮想マシン スケール セット sku をについて説明します。</span><span class="sxs-lookup"><span data-stu-id="ab10c-101">Describes an available virtual machine scale set sku.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku.#ctor" />
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
            <span data-ttu-id="ab10c-102">VirtualMachineScaleSetSku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ab10c-102">Initializes a new instance of the VirtualMachineScaleSetSku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetSku (string resourceType = null, Microsoft.Azure.Management.Compute.Models.Sku sku = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSkuCapacity capacity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string resourceType, class Microsoft.Azure.Management.Compute.Models.Sku sku, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSkuCapacity capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku.#ctor(System.String,Microsoft.Azure.Management.Compute.Models.Sku,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSkuCapacity)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku : string * Microsoft.Azure.Management.Compute.Models.Sku * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSkuCapacity -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku (resourceType, sku, capacity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Compute.Models.Sku" />
        <Parameter Name="capacity" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSkuCapacity" />
      </Parameters>
      <Docs>
        <param name="resourceType"><span data-ttu-id="ab10c-103">Sku のリソースの種類に適用されます。</span><span class="sxs-lookup"><span data-stu-id="ab10c-103">The type of resource the sku applies to.</span></span></param>
        <param name="sku"><span data-ttu-id="ab10c-104">Sku。</span><span class="sxs-lookup"><span data-stu-id="ab10c-104">The Sku.</span></span></param>
        <param name="capacity"><span data-ttu-id="ab10c-105">スケール セット内の仮想マシンの数を指定します。</span><span class="sxs-lookup"><span data-stu-id="ab10c-105">Specifies the number of virtual machines in the scale set.</span></span></param>
        <summary>
            <span data-ttu-id="ab10c-106">VirtualMachineScaleSetSku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ab10c-106">Initializes a new instance of the VirtualMachineScaleSetSku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSkuCapacity Capacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSkuCapacity Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Capacity As VirtualMachineScaleSetSkuCapacity" />
      <MemberSignature Language="F#" Value="member this.Capacity : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSkuCapacity" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSkuCapacity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ab10c-107">取得は、スケール セット内の仮想マシンの数を指定します。</span><span class="sxs-lookup"><span data-stu-id="ab10c-107">Gets specifies the number of virtual machines in the scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ab10c-108">Sku の対象リソースの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="ab10c-108">Gets the type of resource the sku applies to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.Sku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Models.Sku" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ab10c-109">Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="ab10c-109">Gets the Sku.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>