<Type Name="VirtualMachineScaleSetExtension" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetExtension : Microsoft.Azure.Management.Compute.Fluent.Models.SubResourceReadOnly" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetExtension extends Microsoft.Azure.Management.Compute.Fluent.Models.SubResourceReadOnly" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetExtension&#xA;Inherits SubResourceReadOnly" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetExtension = class&#xA;    inherit SubResourceReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Fluent.Models.SubResourceReadOnly</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="93444-101">仮想マシン スケール セット拡張機能をについて説明します。</span><span class="sxs-lookup"><span data-stu-id="93444-101">Describes a Virtual Machine Scale Set Extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetExtension ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="93444-102">VirtualMachineScaleSetExtension クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="93444-102">Initializes a new instance of the VirtualMachineScaleSetExtension class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetExtension (string id = null, string name = null, string forceUpdateTag = null, string publisher = null, string type = null, string typeHandlerVersion = null, Nullable&lt;bool&gt; autoUpgradeMinorVersion = null, object settings = null, object protectedSettings = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string forceUpdateTag, string publisher, string type, string typeHandlerVersion, valuetype System.Nullable`1&lt;bool&gt; autoUpgradeMinorVersion, object settings, object protectedSettings, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Object,System.Object,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional forceUpdateTag As String = null, Optional publisher As String = null, Optional type As String = null, Optional typeHandlerVersion As String = null, Optional autoUpgradeMinorVersion As Nullable(Of Boolean) = null, Optional settings As Object = null, Optional protectedSettings As Object = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension : string * string * string * string * string * string * Nullable&lt;bool&gt; * obj * obj * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension (id, name, forceUpdateTag, publisher, type, typeHandlerVersion, autoUpgradeMinorVersion, settings, protectedSettings, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="forceUpdateTag" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="typeHandlerVersion" Type="System.String" />
        <Parameter Name="autoUpgradeMinorVersion" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="settings" Type="System.Object" />
        <Parameter Name="protectedSettings" Type="System.Object" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="forceUpdateTag">To be added.</param>
        <param name="publisher">To be added.</param>
        <param name="type">To be added.</param>
        <param name="typeHandlerVersion">To be added.</param>
        <param name="autoUpgradeMinorVersion">To be added.</param>
        <param name="settings">To be added.</param>
        <param name="protectedSettings">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoUpgradeMinorVersion">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoUpgradeMinorVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoUpgradeMinorVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.AutoUpgradeMinorVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoUpgradeMinorVersion As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoUpgradeMinorVersion : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.AutoUpgradeMinorVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoUpgradeMinorVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="93444-103">取得またはマイナー バージョン間で、拡張機能ハンドラーを自動的にアップグレードする必要があるかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="93444-103">Gets or sets whether the extension handler should be automatically upgraded across minor versions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceUpdateTag">
      <MemberSignature Language="C#" Value="public string ForceUpdateTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForceUpdateTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.ForceUpdateTag" />
      <MemberSignature Language="VB.NET" Value="Public Property ForceUpdateTag As String" />
      <MemberSignature Language="F#" Value="member this.ForceUpdateTag : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.ForceUpdateTag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.forceUpdateTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="93444-104">取得または拡張機能の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="93444-104">Gets or sets the name of the extension.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedSettings">
      <MemberSignature Language="C#" Value="public object ProtectedSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ProtectedSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.ProtectedSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedSettings As Object" />
      <MemberSignature Language="F#" Value="member this.ProtectedSettings : obj with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.ProtectedSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.protectedSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="93444-105">取得または json 形式を設定、拡張機能の設定を保護します。</span><span class="sxs-lookup"><span data-stu-id="93444-105">Gets or sets json formatted protected settings for the extension.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="93444-106">応答でのみ表示されます、プロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="93444-106">Gets the provisioning state, which only appears in the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Publisher">
      <MemberSignature Language="C#" Value="public string Publisher { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Publisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.Publisher" />
      <MemberSignature Language="VB.NET" Value="Public Property Publisher As String" />
      <MemberSignature Language="F#" Value="member this.Publisher : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.Publisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publisher")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="93444-107">取得または拡張機能ハンドラーのパブリッシャーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="93444-107">Gets or sets the name of the extension handler publisher.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public object Settings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.Settings" />
      <MemberSignature Language="VB.NET" Value="Public Property Settings As Object" />
      <MemberSignature Language="F#" Value="member this.Settings : obj with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.settings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="93444-108">取得または拡張機能の json 形式の公開設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="93444-108">Gets or sets json formatted public settings for the extension.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="93444-109">取得または拡張機能ハンドラーの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="93444-109">Gets or sets the type of the extension handler.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeHandlerVersion">
      <MemberSignature Language="C#" Value="public string TypeHandlerVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TypeHandlerVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.TypeHandlerVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property TypeHandlerVersion As String" />
      <MemberSignature Language="F#" Value="member this.TypeHandlerVersion : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension.TypeHandlerVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.typeHandlerVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="93444-110">取得または拡張機能ハンドラーの種類のバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="93444-110">Gets or sets the type version of the extension handler.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>