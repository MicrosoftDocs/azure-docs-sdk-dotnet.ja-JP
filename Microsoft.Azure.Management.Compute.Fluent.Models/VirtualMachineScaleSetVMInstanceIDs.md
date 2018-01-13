<Type Name="VirtualMachineScaleSetVMInstanceIDs" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceIDs">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetVMInstanceIDs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetVMInstanceIDs extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceIDs" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetVMInstanceIDs" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetVMInstanceIDs = class" />
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
            <span data-ttu-id="5eac5-101">VM スケール セットから仮想マシン インスタンス Id の一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="5eac5-101">Specifies a list of virtual machine instance IDs from the VM scale set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVMInstanceIDs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceIDs.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5eac5-102">VirtualMachineScaleSetVMInstanceIDs クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5eac5-102">Initializes a new instance of the VirtualMachineScaleSetVMInstanceIDs class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVMInstanceIDs (System.Collections.Generic.IList&lt;string&gt; instanceIds = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; instanceIds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceIDs.#ctor(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional instanceIds As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceIDs : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceIDs" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceIDs instanceIds" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instanceIds"><span data-ttu-id="5eac5-103">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="5eac5-103">The virtual machine scale set instance ids.</span></span></param>
        <summary>
            <span data-ttu-id="5eac5-104">VirtualMachineScaleSetVMInstanceIDs クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5eac5-104">Initializes a new instance of the VirtualMachineScaleSetVMInstanceIDs class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; InstanceIds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; InstanceIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceIDs.InstanceIds" />
      <MemberSignature Language="VB.NET" Value="Public Property InstanceIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.InstanceIds : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceIDs.InstanceIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="5eac5-105">取得または仮想マシン スケール セットのインスタンス id を設定します。</span><span class="sxs-lookup"><span data-stu-id="5eac5-105">Gets or sets the virtual machine scale set instance ids.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>