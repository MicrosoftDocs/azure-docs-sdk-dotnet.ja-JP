<Type Name="VirtualMachineScaleSetVMInstanceRequiredIDs" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceRequiredIDs">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetVMInstanceRequiredIDs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetVMInstanceRequiredIDs extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceRequiredIDs" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetVMInstanceRequiredIDs" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetVMInstanceRequiredIDs = class" />
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
            <span data-ttu-id="72d5f-101">VM スケール セットから仮想マシン インスタンス Id の一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="72d5f-101">Specifies a list of virtual machine instance IDs from the VM scale set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVMInstanceRequiredIDs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceRequiredIDs.#ctor" />
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
            <span data-ttu-id="72d5f-102">VirtualMachineScaleSetVMInstanceRequiredIDs クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="72d5f-102">Initializes a new instance of the VirtualMachineScaleSetVMInstanceRequiredIDs class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVMInstanceRequiredIDs (System.Collections.Generic.IList&lt;string&gt; instanceIds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; instanceIds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceRequiredIDs.#ctor(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (instanceIds As IList(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceRequiredIDs : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceRequiredIDs" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceRequiredIDs instanceIds" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instanceIds"><span data-ttu-id="72d5f-103">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="72d5f-103">The virtual machine scale set instance ids.</span></span></param>
        <summary>
            <span data-ttu-id="72d5f-104">VirtualMachineScaleSetVMInstanceRequiredIDs クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="72d5f-104">Initializes a new instance of the VirtualMachineScaleSetVMInstanceRequiredIDs class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; InstanceIds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; InstanceIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceRequiredIDs.InstanceIds" />
      <MemberSignature Language="VB.NET" Value="Public Property InstanceIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.InstanceIds : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceRequiredIDs.InstanceIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="instanceIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72d5f-105">取得または仮想マシン スケール セットのインスタンス id を設定します。</span><span class="sxs-lookup"><span data-stu-id="72d5f-105">Gets or sets the virtual machine scale set instance ids.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceRequiredIDs.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetVMInstanceRequiredIDs.Validate " />
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
            <span data-ttu-id="72d5f-106">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="72d5f-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="72d5f-107">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="72d5f-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>