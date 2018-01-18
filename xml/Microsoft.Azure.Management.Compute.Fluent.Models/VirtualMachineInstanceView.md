<Type Name="VirtualMachineInstanceView" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView">
  <TypeSignature Language="C#" Value="public class VirtualMachineInstanceView" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineInstanceView extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineInstanceView" />
  <TypeSignature Language="F#" Value="type VirtualMachineInstanceView = class" />
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
            <span data-ttu-id="dca32-101">仮想マシンのインスタンス ビューです。</span><span class="sxs-lookup"><span data-stu-id="dca32-101">The instance view of a virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineInstanceView ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dca32-102">VirtualMachineInstanceView クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dca32-102">Initializes a new instance of the VirtualMachineInstanceView class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineInstanceView (Nullable&lt;int&gt; platformUpdateDomain = null, Nullable&lt;int&gt; platformFaultDomain = null, string rdpThumbPrint = null, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView vmAgent = null, Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus maintenanceRedeployStatus = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInstanceView&gt; disks = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView&gt; extensions = null, Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView bootDiagnostics = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; statuses = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; platformUpdateDomain, valuetype System.Nullable`1&lt;int32&gt; platformFaultDomain, string rdpThumbPrint, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView vmAgent, class Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus maintenanceRedeployStatus, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInstanceView&gt; disks, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView&gt; extensions, class Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView bootDiagnostics, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; statuses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView,Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.DiskInstanceView},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView},Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView : Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView * Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInstanceView&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView&gt; * Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView (platformUpdateDomain, platformFaultDomain, rdpThumbPrint, vmAgent, maintenanceRedeployStatus, disks, extensions, bootDiagnostics, statuses)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="platformUpdateDomain" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="platformFaultDomain" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="rdpThumbPrint" Type="System.String" />
        <Parameter Name="vmAgent" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView" />
        <Parameter Name="maintenanceRedeployStatus" Type="Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus" />
        <Parameter Name="disks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInstanceView&gt;" />
        <Parameter Name="extensions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView&gt;" />
        <Parameter Name="bootDiagnostics" Type="Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView" />
        <Parameter Name="statuses" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="platformUpdateDomain">To be added.</param>
        <param name="platformFaultDomain">To be added.</param>
        <param name="rdpThumbPrint">To be added.</param>
        <param name="vmAgent">To be added.</param>
        <param name="maintenanceRedeployStatus">To be added.</param>
        <param name="disks">To be added.</param>
        <param name="extensions">To be added.</param>
        <param name="bootDiagnostics">To be added.</param>
        <param name="statuses">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BootDiagnostics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView BootDiagnostics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView BootDiagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.BootDiagnostics" />
      <MemberSignature Language="VB.NET" Value="Public Property BootDiagnostics As BootDiagnosticsInstanceView" />
      <MemberSignature Language="F#" Value="member this.BootDiagnostics : Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.BootDiagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bootDiagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dca32-103">取得またはブート診断を設定します。</span><span class="sxs-lookup"><span data-stu-id="dca32-103">Gets or sets the boot diagnostics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Disks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInstanceView&gt; Disks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInstanceView&gt; Disks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.Disks" />
      <MemberSignature Language="VB.NET" Value="Public Property Disks As IList(Of DiskInstanceView)" />
      <MemberSignature Language="F#" Value="member this.Disks : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInstanceView&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.Disks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="disks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInstanceView&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dca32-104">取得またはバーチャル マシンのディスク情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="dca32-104">Gets or sets the virtual machine disk information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Extensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView&gt; Extensions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView&gt; Extensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.Extensions" />
      <MemberSignature Language="VB.NET" Value="Public Property Extensions As IList(Of VirtualMachineExtensionInstanceView)" />
      <MemberSignature Language="F#" Value="member this.Extensions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.Extensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extensions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dca32-105">取得または拡張機能の情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="dca32-105">Gets or sets the extensions information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaintenanceRedeployStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus MaintenanceRedeployStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus MaintenanceRedeployStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.MaintenanceRedeployStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property MaintenanceRedeployStatus As MaintenanceRedeployStatus" />
      <MemberSignature Language="F#" Value="member this.MaintenanceRedeployStatus : Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.MaintenanceRedeployStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maintenanceRedeployStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformFaultDomain">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PlatformFaultDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PlatformFaultDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.PlatformFaultDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property PlatformFaultDomain As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PlatformFaultDomain : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.PlatformFaultDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="platformFaultDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dca32-106">取得または設定は、仮想マシンのフォールト ドメインを指定します。</span><span class="sxs-lookup"><span data-stu-id="dca32-106">Gets or sets specifies the fault domain of the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformUpdateDomain">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PlatformUpdateDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PlatformUpdateDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.PlatformUpdateDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property PlatformUpdateDomain As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PlatformUpdateDomain : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.PlatformUpdateDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="platformUpdateDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dca32-107">取得または設定は、仮想マシンの更新ドメインを指定します。</span><span class="sxs-lookup"><span data-stu-id="dca32-107">Gets or sets specifies the update domain of the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RdpThumbPrint">
      <MemberSignature Language="C#" Value="public string RdpThumbPrint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RdpThumbPrint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.RdpThumbPrint" />
      <MemberSignature Language="VB.NET" Value="Public Property RdpThumbPrint As String" />
      <MemberSignature Language="F#" Value="member this.RdpThumbPrint : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.RdpThumbPrint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rdpThumbPrint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dca32-108">取得またはリモート デスクトップ証明書の拇印を設定します。</span><span class="sxs-lookup"><span data-stu-id="dca32-108">Gets or sets the Remote desktop certificate thumbprint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statuses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; Statuses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; Statuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.Statuses" />
      <MemberSignature Language="VB.NET" Value="Public Property Statuses As IList(Of InstanceViewStatus)" />
      <MemberSignature Language="F#" Value="member this.Statuses : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.Statuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statuses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dca32-109">取得またはリソースの状態情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="dca32-109">Gets or sets the resource status information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VmAgent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView VmAgent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView VmAgent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.VmAgent" />
      <MemberSignature Language="VB.NET" Value="Public Property VmAgent As VirtualMachineAgentInstanceView" />
      <MemberSignature Language="F#" Value="member this.VmAgent : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView.VmAgent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmAgent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dca32-110">取得または仮想マシンで実行されている VM エージェントを設定します。</span><span class="sxs-lookup"><span data-stu-id="dca32-110">Gets or sets the VM Agent running on the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>