<Type Name="VirtualMachineScaleSet" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSet : Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSet extends Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSet&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSet = class&#xA;    inherit Resource" />
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
            仮想マシン スケール セットをについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSet ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.#ctor" />
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
            VirtualMachineScaleSet クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSet (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Compute.Models.Sku sku = null, Microsoft.Azure.Management.Compute.Models.Plan plan = null, Microsoft.Azure.Management.Compute.Models.UpgradePolicy upgradePolicy = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile virtualMachineProfile = null, string provisioningState = null, Nullable&lt;bool&gt; overprovision = null, string uniqueId = null, Nullable&lt;bool&gt; singlePlacementGroup = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity identity = null, System.Collections.Generic.IList&lt;string&gt; zones = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Compute.Models.Sku sku, class Microsoft.Azure.Management.Compute.Models.Plan plan, class Microsoft.Azure.Management.Compute.Models.UpgradePolicy upgradePolicy, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile virtualMachineProfile, string provisioningState, valuetype System.Nullable`1&lt;bool&gt; overprovision, string uniqueId, valuetype System.Nullable`1&lt;bool&gt; singlePlacementGroup, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity identity, class System.Collections.Generic.IList`1&lt;string&gt; zones) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Compute.Models.Sku,Microsoft.Azure.Management.Compute.Models.Plan,Microsoft.Azure.Management.Compute.Models.UpgradePolicy,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile,System.String,System.Nullable{System.Boolean},System.String,System.Nullable{System.Boolean},Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Compute.Models.Sku * Microsoft.Azure.Management.Compute.Models.Plan * Microsoft.Azure.Management.Compute.Models.UpgradePolicy * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile * string * Nullable&lt;bool&gt; * string * Nullable&lt;bool&gt; * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet (location, id, name, type, tags, sku, plan, upgradePolicy, virtualMachineProfile, provisioningState, overprovision, uniqueId, singlePlacementGroup, identity, zones)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Compute.Models.Sku" />
        <Parameter Name="plan" Type="Microsoft.Azure.Management.Compute.Models.Plan" />
        <Parameter Name="upgradePolicy" Type="Microsoft.Azure.Management.Compute.Models.UpgradePolicy" />
        <Parameter Name="virtualMachineProfile" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="overprovision" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="uniqueId" Type="System.String" />
        <Parameter Name="singlePlacementGroup" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity" />
        <Parameter Name="zones" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="location">リソースの場所</param>
        <param name="id">リソース Id</param>
        <param name="name">リソース名</param>
        <param name="type">リソースの種類</param>
        <param name="tags">リソース タグ</param>
        <param name="sku">仮想マシン スケール セットの sku。</param>
        <param name="plan">仮想マシンの作成に使用する marketplace イメージに関する情報を指定します。 この要素は marketplace イメージのみ使用されます。 API から marketplace イメージを使用することができます、前に、画像がプログラムでの使用を有効にする必要があります。  Azure ポータルで、検索、marketplace イメージを使用して、をクリックする**はじめに - をプログラムでは、展開する&gt;**です。
            必要な情報を入力し、クリックして**保存**です。</param>
        <param name="upgradePolicy">アップグレードのポリシー。</param>
        <param name="virtualMachineProfile">バーチャル マシン プロファイル。</param>
        <param name="provisioningState">プロビジョニングの状態、応答でのみ表示されます。</param>
        <param name="overprovision">仮想マシン スケール セットを overprovisioned する必要があるかどうかを指定します。</param>
        <param name="uniqueId">仮想マシン スケール セットを一意に識別する ID を指定します。</param>
        <param name="singlePlacementGroup">True の場合は、スケールの最大サイズは 100 の仮想マシンの 1 つの配置グループ セットが制限されます。</param>
        <param name="identity">構成されている場合、仮想マシン スケール セットの id。</param>
        <param name="zones">仮想マシンのスケールでは、ゾーンを設定します。</param>
        <summary>
            VirtualMachineScaleSet クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As VirtualMachineScaleSetIdentity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または構成されている場合に、仮想マシン スケール セットの id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Overprovision">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Overprovision { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Overprovision" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.Overprovision" />
      <MemberSignature Language="VB.NET" Value="Public Property Overprovision As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Overprovision : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.Overprovision" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.overprovision")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、仮想マシン スケール セットを overprovisioned する必要があるかどうかを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Plan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.Plan Plan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.Plan Plan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.Plan" />
      <MemberSignature Language="VB.NET" Value="Public Property Plan As Plan" />
      <MemberSignature Language="F#" Value="member this.Plan : Microsoft.Azure.Management.Compute.Models.Plan with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.Plan" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.ProvisioningState" />
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
    <Member MemberName="SinglePlacementGroup">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SinglePlacementGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SinglePlacementGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.SinglePlacementGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property SinglePlacementGroup As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SinglePlacementGroup : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.SinglePlacementGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.singlePlacementGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または true の場合は、スケール サイズの最大 100 の仮想マシンの 1 つの配置のグループに設定されてこの制限を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.Sku" />
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
            取得または仮想マシン スケール セットの sku を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UniqueId">
      <MemberSignature Language="C#" Value="public string UniqueId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UniqueId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.UniqueId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UniqueId As String" />
      <MemberSignature Language="F#" Value="member this.UniqueId : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.UniqueId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.uniqueId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得では、仮想マシン スケール セットを一意に識別する ID を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradePolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.UpgradePolicy UpgradePolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.UpgradePolicy UpgradePolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.UpgradePolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradePolicy As UpgradePolicy" />
      <MemberSignature Language="F#" Value="member this.UpgradePolicy : Microsoft.Azure.Management.Compute.Models.UpgradePolicy with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.UpgradePolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.upgradePolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.UpgradePolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアップグレード ポリシーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSet.Validate " />
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
    <Member MemberName="VirtualMachineProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile VirtualMachineProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile VirtualMachineProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.VirtualMachineProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineProfile As VirtualMachineScaleSetVMProfile" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.VirtualMachineProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualMachineProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバーチャル マシンのプロファイルを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Zones">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Zones { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Zones" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.Zones" />
      <MemberSignature Language="VB.NET" Value="Public Property Zones As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Zones : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet.Zones" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="zones")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはゾーンを設定する仮想マシンのスケールを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>