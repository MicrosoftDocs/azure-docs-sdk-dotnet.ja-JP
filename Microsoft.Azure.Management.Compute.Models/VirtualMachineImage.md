<Type Name="VirtualMachineImage" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineImage">
  <TypeSignature Language="C#" Value="public class VirtualMachineImage : Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineImage extends Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineImage" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineImage&#xA;Inherits VirtualMachineImageResource" />
  <TypeSignature Language="F#" Value="type VirtualMachineImage = class&#xA;    inherit VirtualMachineImageResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5a69b-101">仮想マシン イメージをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="5a69b-101">Describes a Virtual Machine Image.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineImage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineImage.#ctor" />
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
            <span data-ttu-id="5a69b-102">VirtualMachineImage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5a69b-102">Initializes a new instance of the VirtualMachineImage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineImage (string name, string location, string id = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Compute.Models.PurchasePlan plan = null, Microsoft.Azure.Management.Compute.Models.OSDiskImage osDiskImage = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DataDiskImage&gt; dataDiskImages = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string location, string id, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Compute.Models.PurchasePlan plan, class Microsoft.Azure.Management.Compute.Models.OSDiskImage osDiskImage, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.DataDiskImage&gt; dataDiskImages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineImage.#ctor(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Compute.Models.PurchasePlan,Microsoft.Azure.Management.Compute.Models.OSDiskImage,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.DataDiskImage})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineImage : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Compute.Models.PurchasePlan * Microsoft.Azure.Management.Compute.Models.OSDiskImage * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DataDiskImage&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineImage" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineImage (name, location, id, tags, plan, osDiskImage, dataDiskImages)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="plan" Type="Microsoft.Azure.Management.Compute.Models.PurchasePlan" />
        <Parameter Name="osDiskImage" Type="Microsoft.Azure.Management.Compute.Models.OSDiskImage" />
        <Parameter Name="dataDiskImages" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DataDiskImage&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5a69b-103">リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="5a69b-103">The name of the resource.</span></span></param>
        <param name="location"><span data-ttu-id="5a69b-104">リソースのサポートされている Azure の場所。</span><span class="sxs-lookup"><span data-stu-id="5a69b-104">The supported Azure location of the resource.</span></span></param>
        <param name="id"><span data-ttu-id="5a69b-105">リソース Id</span><span class="sxs-lookup"><span data-stu-id="5a69b-105">Resource Id</span></span></param>
        <param name="tags"><span data-ttu-id="5a69b-106">仮想マシンに割り当てられているタグを指定します。</span><span class="sxs-lookup"><span data-stu-id="5a69b-106">Specifies the tags that are assigned to the virtual machine.</span></span> <span data-ttu-id="5a69b-107">詳細については、タグを使用して、次を参照してください。[タグを使用して Azure リソースを整理する](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-using-tags.md)です。</span><span class="sxs-lookup"><span data-stu-id="5a69b-107">For more information about using tags, see [Using tags to organize your Azure resources](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-using-tags.md).</span></span></param>
        <param name="plan">To be added.</param>
        <param name="osDiskImage">To be added.</param>
        <param name="dataDiskImages">To be added.</param>
        <summary>
            <span data-ttu-id="5a69b-108">VirtualMachineImage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5a69b-108">Initializes a new instance of the VirtualMachineImage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDiskImages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DataDiskImage&gt; DataDiskImages { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.DataDiskImage&gt; DataDiskImages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineImage.DataDiskImages" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDiskImages As IList(Of DataDiskImage)" />
      <MemberSignature Language="F#" Value="member this.DataDiskImages : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DataDiskImage&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineImage.DataDiskImages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataDiskImages")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DataDiskImage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsDiskImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.OSDiskImage OsDiskImage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.OSDiskImage OsDiskImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineImage.OsDiskImage" />
      <MemberSignature Language="VB.NET" Value="Public Property OsDiskImage As OSDiskImage" />
      <MemberSignature Language="F#" Value="member this.OsDiskImage : Microsoft.Azure.Management.Compute.Models.OSDiskImage with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineImage.OsDiskImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.osDiskImage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OSDiskImage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Plan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.PurchasePlan Plan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.PurchasePlan Plan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineImage.Plan" />
      <MemberSignature Language="VB.NET" Value="Public Property Plan As PurchasePlan" />
      <MemberSignature Language="F#" Value="member this.Plan : Microsoft.Azure.Management.Compute.Models.PurchasePlan with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineImage.Plan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.plan")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.PurchasePlan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineImage.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="virtualMachineImage.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5a69b-109">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="5a69b-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5a69b-110">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5a69b-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>