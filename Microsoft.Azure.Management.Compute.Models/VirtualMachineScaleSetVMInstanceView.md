<Type Name="VirtualMachineScaleSetVMInstanceView" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetVMInstanceView" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetVMInstanceView extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetVMInstanceView" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetVMInstanceView = class" />
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
            仮想マシンのスケールのインスタンス ビューでは、VM を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVMInstanceView ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.#ctor" />
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
            VirtualMachineScaleSetVMInstanceView クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVMInstanceView (Nullable&lt;int&gt; platformUpdateDomain = null, Nullable&lt;int&gt; platformFaultDomain = null, string rdpThumbPrint = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView vmAgent = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskInstanceView&gt; disks = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView&gt; extensions = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus vmHealth = null, Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView bootDiagnostics = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; statuses = null, string placementGroupId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; platformUpdateDomain, valuetype System.Nullable`1&lt;int32&gt; platformFaultDomain, string rdpThumbPrint, class Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView vmAgent, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.DiskInstanceView&gt; disks, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView&gt; extensions, class Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus vmHealth, class Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView bootDiagnostics, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; statuses, string placementGroupId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.DiskInstanceView},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView},Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus,Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.InstanceViewStatus},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional platformUpdateDomain As Nullable(Of Integer) = null, Optional platformFaultDomain As Nullable(Of Integer) = null, Optional rdpThumbPrint As String = null, Optional vmAgent As VirtualMachineAgentInstanceView = null, Optional disks As IList(Of DiskInstanceView) = null, Optional extensions As IList(Of VirtualMachineExtensionInstanceView) = null, Optional vmHealth As VirtualMachineHealthStatus = null, Optional bootDiagnostics As BootDiagnosticsInstanceView = null, Optional statuses As IList(Of InstanceViewStatus) = null, Optional placementGroupId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView : Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskInstanceView&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView&gt; * Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus * Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView (platformUpdateDomain, platformFaultDomain, rdpThumbPrint, vmAgent, disks, extensions, vmHealth, bootDiagnostics, statuses, placementGroupId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="platformUpdateDomain" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="platformFaultDomain" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="rdpThumbPrint" Type="System.String" />
        <Parameter Name="vmAgent" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView" />
        <Parameter Name="disks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskInstanceView&gt;" />
        <Parameter Name="extensions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView&gt;" />
        <Parameter Name="vmHealth" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus" />
        <Parameter Name="bootDiagnostics" Type="Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView" />
        <Parameter Name="statuses" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt;" />
        <Parameter Name="placementGroupId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="platformUpdateDomain">更新ドメインの数。</param>
        <param name="platformFaultDomain">フォールト ドメインの数。</param>
        <param name="rdpThumbPrint">リモート デスクトップ証明書の拇印。</param>
        <param name="vmAgent">VM エージェントは、仮想マシンで実行します。</param>
        <param name="disks">ディスク情報です。</param>
        <param name="extensions">拡張機能の情報です。</param>
        <param name="vmHealth">仮想マシンの正常性状態です。</param>
        <param name="bootDiagnostics">ブート診断は、デバッグ機能を VM の状態を診断するには、コンソール出力とスクリーン ショットを表示することができます。 &lt;ブラジル&gt;&lt;br&gt; Linux 仮想マシンのコンソールのログの出力に簡単に表示できます。
            &lt;ブラジル&gt;&lt;br&gt; Windows と Linux の両方の仮想マシンの Azure することもできます、ハイパーバイザーから仮想マシンのスクリーン ショットを参照してください。</param>
        <param name="statuses">リソースの状態情報です。</param>
        <param name="placementGroupId">VM が実行されている配置グループです。 VM の割り当てが解除された場合、placementGroupId は与えられません。</param>
        <summary>
            VirtualMachineScaleSetVMInstanceView クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BootDiagnostics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView BootDiagnostics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView BootDiagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.BootDiagnostics" />
      <MemberSignature Language="VB.NET" Value="Public Property BootDiagnostics As BootDiagnosticsInstanceView" />
      <MemberSignature Language="F#" Value="member this.BootDiagnostics : Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.BootDiagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bootDiagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはブート診断は VM の状態を診断するには、コンソール出力とスクリーン ショットを表示することができますが、デバッグ機能を設定します。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Linux 仮想マシンのコンソールのログの出力に簡単に表示できます。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Windows と Linux の両方の仮想マシンの Azure することもできます、ハイパーバイザーから仮想マシンのスクリーン ショットを参照してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Disks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskInstanceView&gt; Disks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.DiskInstanceView&gt; Disks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.Disks" />
      <MemberSignature Language="VB.NET" Value="Public Property Disks As IList(Of DiskInstanceView)" />
      <MemberSignature Language="F#" Value="member this.Disks : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskInstanceView&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.Disks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="disks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskInstanceView&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはディスクの情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Extensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView&gt; Extensions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView&gt; Extensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.Extensions" />
      <MemberSignature Language="VB.NET" Value="Public Property Extensions As IList(Of VirtualMachineExtensionInstanceView)" />
      <MemberSignature Language="F#" Value="member this.Extensions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.Extensions" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または拡張機能の情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlacementGroupId">
      <MemberSignature Language="C#" Value="public string PlacementGroupId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PlacementGroupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.PlacementGroupId" />
      <MemberSignature Language="VB.NET" Value="Public Property PlacementGroupId As String" />
      <MemberSignature Language="F#" Value="member this.PlacementGroupId : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.PlacementGroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="placementGroupId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または VM が実行されている配置グループを設定します。 VM の割り当てが解除された場合、placementGroupId は与えられません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformFaultDomain">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PlatformFaultDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PlatformFaultDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.PlatformFaultDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property PlatformFaultDomain As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PlatformFaultDomain : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.PlatformFaultDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            取得またはフォールト ドメインの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformUpdateDomain">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PlatformUpdateDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PlatformUpdateDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.PlatformUpdateDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property PlatformUpdateDomain As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PlatformUpdateDomain : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.PlatformUpdateDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            取得または更新ドメインの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RdpThumbPrint">
      <MemberSignature Language="C#" Value="public string RdpThumbPrint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RdpThumbPrint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.RdpThumbPrint" />
      <MemberSignature Language="VB.NET" Value="Public Property RdpThumbPrint As String" />
      <MemberSignature Language="F#" Value="member this.RdpThumbPrint : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.RdpThumbPrint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            取得またはリモート デスクトップ証明書の拇印を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statuses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; Statuses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; Statuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.Statuses" />
      <MemberSignature Language="VB.NET" Value="Public Property Statuses As IList(Of InstanceViewStatus)" />
      <MemberSignature Language="F#" Value="member this.Statuses : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.Statuses" />
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
            取得またはリソースの状態情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VmAgent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView VmAgent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView VmAgent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.VmAgent" />
      <MemberSignature Language="VB.NET" Value="Public Property VmAgent As VirtualMachineAgentInstanceView" />
      <MemberSignature Language="F#" Value="member this.VmAgent : Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.VmAgent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmAgent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想マシンで実行されている VM エージェントを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VmHealth">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus VmHealth { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus VmHealth" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.VmHealth" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VmHealth As VirtualMachineHealthStatus" />
      <MemberSignature Language="F#" Value="member this.VmHealth : Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.VmHealth" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmHealth")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            仮想マシンの正常性状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>