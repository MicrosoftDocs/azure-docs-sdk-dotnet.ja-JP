<Type Name="VirtualMachineScaleSetInstanceView" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetInstanceView" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetInstanceView extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetInstanceView" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetInstanceView = class" />
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
            <span data-ttu-id="2dd41-101">仮想マシンのスケールのインスタンス ビューを設定します。</span><span class="sxs-lookup"><span data-stu-id="2dd41-101">The instance view of a virtual machine scale set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetInstanceView ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView.#ctor" />
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
            <span data-ttu-id="2dd41-102">VirtualMachineScaleSetInstanceView クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2dd41-102">Initializes a new instance of the VirtualMachineScaleSetInstanceView class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetInstanceView (Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceViewStatusesSummary virtualMachine = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMExtensionsSummary&gt; extensions = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; statuses = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceViewStatusesSummary virtualMachine, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMExtensionsSummary&gt; extensions, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; statuses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView.#ctor(Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceViewStatusesSummary,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMExtensionsSummary},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.InstanceViewStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional virtualMachine As VirtualMachineScaleSetInstanceViewStatusesSummary = null, Optional extensions As IList(Of VirtualMachineScaleSetVMExtensionsSummary) = null, Optional statuses As IList(Of InstanceViewStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceViewStatusesSummary * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMExtensionsSummary&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView (virtualMachine, extensions, statuses)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="virtualMachine" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceViewStatusesSummary" />
        <Parameter Name="extensions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMExtensionsSummary&gt;" />
        <Parameter Name="statuses" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="virtualMachine"><span data-ttu-id="2dd41-103">仮想マシンのスケールの概要をインスタンス ビューの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="2dd41-103">The instance view status summary for the virtual machine scale set.</span></span></param>
        <param name="extensions"><span data-ttu-id="2dd41-104">拡張機能の情報です。</span><span class="sxs-lookup"><span data-stu-id="2dd41-104">The extensions information.</span></span></param>
        <param name="statuses"><span data-ttu-id="2dd41-105">リソースの状態情報です。</span><span class="sxs-lookup"><span data-stu-id="2dd41-105">The resource status information.</span></span></param>
        <summary>
            <span data-ttu-id="2dd41-106">VirtualMachineScaleSetInstanceView クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2dd41-106">Initializes a new instance of the VirtualMachineScaleSetInstanceView class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Extensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMExtensionsSummary&gt; Extensions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMExtensionsSummary&gt; Extensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView.Extensions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Extensions As IList(Of VirtualMachineScaleSetVMExtensionsSummary)" />
      <MemberSignature Language="F#" Value="member this.Extensions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMExtensionsSummary&gt;" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView.Extensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extensions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMExtensionsSummary&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2dd41-107">拡張機能の情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="2dd41-107">Gets the extensions information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statuses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; Statuses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; Statuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView.Statuses" />
      <MemberSignature Language="VB.NET" Value="Public Property Statuses As IList(Of InstanceViewStatus)" />
      <MemberSignature Language="F#" Value="member this.Statuses : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView.Statuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statuses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2dd41-108">取得またはリソースの状態情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="2dd41-108">Gets or sets the resource status information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachine">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceViewStatusesSummary VirtualMachine { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceViewStatusesSummary VirtualMachine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView.VirtualMachine" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachine As VirtualMachineScaleSetInstanceViewStatusesSummary" />
      <MemberSignature Language="F#" Value="member this.VirtualMachine : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceViewStatusesSummary" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView.VirtualMachine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceViewStatusesSummary</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2dd41-109">仮想マシン スケール セットの概要インスタンス ビューの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="2dd41-109">Gets the instance view status summary for the virtual machine scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>