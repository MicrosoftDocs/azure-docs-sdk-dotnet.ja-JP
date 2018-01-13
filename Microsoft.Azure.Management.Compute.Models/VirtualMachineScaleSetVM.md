<Type Name="VirtualMachineScaleSetVM" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetVM : Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetVM extends Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetVM&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetVM = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            仮想マシン スケール セットの仮想マシンについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVM ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.#ctor" />
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
            VirtualMachineScaleSetVM クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVM (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string instanceId = null, Microsoft.Azure.Management.Compute.Models.Sku sku = null, Nullable&lt;bool&gt; latestModelApplied = null, string vmId = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView instanceView = null, Microsoft.Azure.Management.Compute.Models.HardwareProfile hardwareProfile = null, Microsoft.Azure.Management.Compute.Models.StorageProfile storageProfile = null, Microsoft.Azure.Management.Compute.Models.OSProfile osProfile = null, Microsoft.Azure.Management.Compute.Models.NetworkProfile networkProfile = null, Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile diagnosticsProfile = null, Microsoft.Azure.Management.Compute.Models.SubResource availabilitySet = null, string provisioningState = null, string licenseType = null, Microsoft.Azure.Management.Compute.Models.Plan plan = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; resources = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string instanceId, class Microsoft.Azure.Management.Compute.Models.Sku sku, valuetype System.Nullable`1&lt;bool&gt; latestModelApplied, string vmId, class Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView instanceView, class Microsoft.Azure.Management.Compute.Models.HardwareProfile hardwareProfile, class Microsoft.Azure.Management.Compute.Models.StorageProfile storageProfile, class Microsoft.Azure.Management.Compute.Models.OSProfile osProfile, class Microsoft.Azure.Management.Compute.Models.NetworkProfile networkProfile, class Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile diagnosticsProfile, class Microsoft.Azure.Management.Compute.Models.SubResource availabilitySet, string provisioningState, string licenseType, class Microsoft.Azure.Management.Compute.Models.Plan plan, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; resources) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.Compute.Models.Sku,System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView,Microsoft.Azure.Management.Compute.Models.HardwareProfile,Microsoft.Azure.Management.Compute.Models.StorageProfile,Microsoft.Azure.Management.Compute.Models.OSProfile,Microsoft.Azure.Management.Compute.Models.NetworkProfile,Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile,Microsoft.Azure.Management.Compute.Models.SubResource,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Plan,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.Compute.Models.Sku * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView * Microsoft.Azure.Management.Compute.Models.HardwareProfile * Microsoft.Azure.Management.Compute.Models.StorageProfile * Microsoft.Azure.Management.Compute.Models.OSProfile * Microsoft.Azure.Management.Compute.Models.NetworkProfile * Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile * Microsoft.Azure.Management.Compute.Models.SubResource * string * string * Microsoft.Azure.Management.Compute.Models.Plan * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM (location, id, name, type, tags, instanceId, sku, latestModelApplied, vmId, instanceView, hardwareProfile, storageProfile, osProfile, networkProfile, diagnosticsProfile, availabilitySet, provisioningState, licenseType, plan, resources)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Compute.Models.Sku" />
        <Parameter Name="latestModelApplied" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="vmId" Type="System.String" />
        <Parameter Name="instanceView" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView" />
        <Parameter Name="hardwareProfile" Type="Microsoft.Azure.Management.Compute.Models.HardwareProfile" />
        <Parameter Name="storageProfile" Type="Microsoft.Azure.Management.Compute.Models.StorageProfile" />
        <Parameter Name="osProfile" Type="Microsoft.Azure.Management.Compute.Models.OSProfile" />
        <Parameter Name="networkProfile" Type="Microsoft.Azure.Management.Compute.Models.NetworkProfile" />
        <Parameter Name="diagnosticsProfile" Type="Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile" />
        <Parameter Name="availabilitySet" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="licenseType" Type="System.String" />
        <Parameter Name="plan" Type="Microsoft.Azure.Management.Compute.Models.Plan" />
        <Parameter Name="resources" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;" />
      </Parameters>
      <Docs>
        <param name="location">リソースの場所</param>
        <param name="id">リソース Id</param>
        <param name="name">リソース名</param>
        <param name="type">リソースの種類</param>
        <param name="tags">リソース タグ</param>
        <param name="instanceId">仮想マシン インスタンスの id。</param>
        <param name="sku">バーチャル マシン SKU です。</param>
        <param name="latestModelApplied">仮想マシンに最新のモデルが適用されているかどうかを指定します。</param>
        <param name="vmId">Azure VM 一意の id。</param>
        <param name="instanceView">仮想マシン インスタンス ビューです。</param>
        <param name="hardwareProfile">仮想マシンのハードウェアの設定を指定します。</param>
        <param name="storageProfile">仮想マシンのディスクの記憶域の設定を指定します。</param>
        <param name="osProfile">バーチャル マシンのオペレーティング システムの設定を指定します。</param>
        <param name="networkProfile">仮想マシンのネットワーク インターフェイスを指定します。</param>
        <param name="diagnosticsProfile">ブート診断設定の状態を指定します。 &lt;ブラジル&gt;&lt;br&gt;最小 api バージョン: 2015-06-15 です。</param>
        <param name="availabilitySet">仮想マシンに割り当てられる可用性セットに関する情報を指定します。
            同じ可用性セットで指定された仮想マシンは、可用性が最大限に別のノードに割り当てられます。 可用性セットの詳細については、次を参照してください。[仮想マシンの可用性管理](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-manage-availability?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json)です。
            &lt;ブラジル&gt;&lt;br&gt; Azure の計画されたメンテナンスの詳細については、次を参照してください[Azure の仮想マシンの定期保守](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-planned-maintenance?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;ブラジル。&gt;現時点では、VM のみに追加できます可用性セットの作成時にします。 既存の仮想マシンは、可用性セットに追加できません。</param>
        <param name="provisioningState">プロビジョニングの状態、応答でのみ表示されます。</param>
        <param name="licenseType">イメージまたは使用されているディスクがライセンス済み、内部設置型を指定します。 この要素は、Windows Server オペレーティング システムを含むイメージでのみ使用します。
            &lt;ブラジル&gt;&lt;br&gt;指定できる値は: &lt;br&gt;&lt;br&gt; Windows_Client &lt;br&gt;&lt;br&gt;Windows_Server &lt;br&gt;&lt;br&gt;この要素が更新プログラムの要求に含まれている場合、値が初期値に一致する必要があります。 この値を更新することはできません。 &lt;ブラジル&gt;&lt;br&gt;詳細については、次を参照してください[ハイブリッドを使用して特典 Windows Server 用 Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;br&gt;最小値。api バージョン: 2015-06-15</param>
        <param name="plan">仮想マシンの作成に使用する marketplace イメージに関する情報を指定します。 この要素は marketplace イメージのみ使用されます。 API から marketplace イメージを使用することができます、前に、画像がプログラムでの使用を有効にする必要があります。  Azure ポータルで、検索、marketplace イメージを使用して、をクリックする**はじめに - をプログラムでは、展開する&gt;**です。
            必要な情報を入力し、クリックして**保存**です。</param>
        <param name="resources">仮想マシンの子の拡張機能リソース。</param>
        <summary>
            VirtualMachineScaleSetVM クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilitySet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource AvailabilitySet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource AvailabilitySet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.AvailabilitySet" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailabilitySet As SubResource" />
      <MemberSignature Language="F#" Value="member this.AvailabilitySet : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.AvailabilitySet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availabilitySet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、仮想マシンに割り当てられる可用性セットに関する情報を指定します。 同じ可用性セットで指定された仮想マシンは、可用性が最大限に別のノードに割り当てられます。 可用性セットの詳細については、次を参照してください。[仮想マシンの可用性管理](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-manage-availability?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json)です。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Azure の計画されたメンテナンスの詳細については、次を参照してください[Azure の仮想マシンの定期保守](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-planned-maintenance?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt; br&amp;gt;&amp; 。lt; br&amp;gt;現時点では、VM は可用性セットの作成時にのみ追加できます。 既存の仮想マシンは、可用性セットに追加できません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile DiagnosticsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile DiagnosticsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.DiagnosticsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property DiagnosticsProfile As DiagnosticsProfile" />
      <MemberSignature Language="F#" Value="member this.DiagnosticsProfile : Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.DiagnosticsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.diagnosticsProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、ブート診断設定の状態を指定します。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;最小 api バージョン: 2015-06-15 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HardwareProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.HardwareProfile HardwareProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.HardwareProfile HardwareProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.HardwareProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property HardwareProfile As HardwareProfile" />
      <MemberSignature Language="F#" Value="member this.HardwareProfile : Microsoft.Azure.Management.Compute.Models.HardwareProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.HardwareProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hardwareProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.HardwareProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、仮想マシンのハードウェアの設定を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceId">
      <MemberSignature Language="C#" Value="public string InstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.InstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceId As String" />
      <MemberSignature Language="F#" Value="member this.InstanceId : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.InstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="instanceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            仮想マシン インスタンスの ID を取得します
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceView">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView InstanceView { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView InstanceView" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.InstanceView" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceView As VirtualMachineInstanceView" />
      <MemberSignature Language="F#" Value="member this.InstanceView : Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.InstanceView" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.instanceView")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            仮想マシン インスタンス ビューを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LatestModelApplied">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; LatestModelApplied { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; LatestModelApplied" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.LatestModelApplied" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LatestModelApplied As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.LatestModelApplied : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.LatestModelApplied" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.latestModelApplied")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得するには、仮想マシンに最新のモデルが適用されているかどうかを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.licenseType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、イメージまたは使用されているディスクがライセンス済み、内部設置型を指定します。 この要素は、Windows Server オペレーティング システムを含むイメージでのみ使用します。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;指定できる値は: &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Windows_Client &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Windows_Server &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;この要素が更新プログラムの要求に含まれている場合、値は、初期値と一致する必要があります。
            この値を更新することはできません。 &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;詳細については、次を参照してください[ハイブリッドを使用して特典 Windows Server 用 Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt; br&amp;gt;&amp; 。lt; br&amp;gt;最小 api バージョン: 2015-06-15
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.NetworkProfile NetworkProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.NetworkProfile NetworkProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.NetworkProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkProfile As NetworkProfile" />
      <MemberSignature Language="F#" Value="member this.NetworkProfile : Microsoft.Azure.Management.Compute.Models.NetworkProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.NetworkProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.NetworkProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、仮想マシンのネットワーク インターフェイスを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.OSProfile OsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.OSProfile OsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.OsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property OsProfile As OSProfile" />
      <MemberSignature Language="F#" Value="member this.OsProfile : Microsoft.Azure.Management.Compute.Models.OSProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.OsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.osProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OSProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、バーチャル マシンのオペレーティング システムの設定を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Plan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.Plan Plan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.Plan Plan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.Plan" />
      <MemberSignature Language="VB.NET" Value="Public Property Plan As Plan" />
      <MemberSignature Language="F#" Value="member this.Plan : Microsoft.Azure.Management.Compute.Models.Plan with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.Plan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="plan")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Plan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、仮想マシンの作成に使用する marketplace イメージに関する情報を指定します。 この要素は marketplace イメージのみ使用されます。 API から marketplace イメージを使用することができます、前に、画像がプログラムでの使用を有効にする必要があります。  Azure ポータルで、検索、marketplace イメージを使用して、をクリックする**はじめに - をプログラムでは、展開する&amp;gt;**です。
            必要な情報を入力し、クリックして**保存**です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            応答でのみ表示されます、プロビジョニングの状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; Resources { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.Resources" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resources As IList(Of VirtualMachineExtension)" />
      <MemberSignature Language="F#" Value="member this.Resources : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.Resources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resources")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            拡張機能リソースの仮想マシンの子を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.Sku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Models.Sku" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.Sku" />
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
            仮想マシンの SKU を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.StorageProfile StorageProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.StorageProfile StorageProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.StorageProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageProfile As StorageProfile" />
      <MemberSignature Language="F#" Value="member this.StorageProfile : Microsoft.Azure.Management.Compute.Models.StorageProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.StorageProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.StorageProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、仮想マシンのディスクの記憶域の設定を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetVM.Validate " />
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
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmId">
      <MemberSignature Language="C#" Value="public string VmId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.VmId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VmId As String" />
      <MemberSignature Language="F#" Value="member this.VmId : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM.VmId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure VM の一意な ID を取得します
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>