<Type Name="SecuritySettingsPatch" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch">
  <TypeSignature Language="C#" Value="public class SecuritySettingsPatch" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecuritySettingsPatch extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch" />
  <TypeSignature Language="VB.NET" Value="Public Class SecuritySettingsPatch" />
  <TypeSignature Language="F#" Value="type SecuritySettingsPatch = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="20633-101">デバイスのセキュリティ設定の更新プログラムの要求を表します。</span><span class="sxs-lookup"><span data-stu-id="20633-101">Represents the patch request for the security settings of a device.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecuritySettingsPatch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="20633-102">SecuritySettingsPatch クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="20633-102">Initializes a new instance of the SecuritySettingsPatch class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecuritySettingsPatch (Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch remoteManagementSettings = null, Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret deviceAdminPassword = null, Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret snapshotPassword = null, Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings chapSettings = null, Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings cloudApplianceSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch remoteManagementSettings, class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret deviceAdminPassword, class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret snapshotPassword, class Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings chapSettings, class Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings cloudApplianceSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch,Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret,Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret,Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings,Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch : Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch * Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret * Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret * Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings * Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch (remoteManagementSettings, deviceAdminPassword, snapshotPassword, chapSettings, cloudApplianceSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="remoteManagementSettings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch" />
        <Parameter Name="deviceAdminPassword" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" />
        <Parameter Name="snapshotPassword" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" />
        <Parameter Name="chapSettings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings" />
        <Parameter Name="cloudApplianceSettings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings" />
      </Parameters>
      <Docs>
        <param name="remoteManagementSettings"><span data-ttu-id="20633-103">リモート管理の設定。</span><span class="sxs-lookup"><span data-stu-id="20633-103">The remote management settings.</span></span></param>
        <param name="deviceAdminPassword"><span data-ttu-id="20633-104">デバイス管理者パスワード。</span><span class="sxs-lookup"><span data-stu-id="20633-104">The device administrator password.</span></span></param>
        <param name="snapshotPassword"><span data-ttu-id="20633-105">スナップショット マネージャーのパスワード。</span><span class="sxs-lookup"><span data-stu-id="20633-105">The snapshot manager password.</span></span></param>
        <param name="chapSettings"><span data-ttu-id="20633-106">デバイス CHAP とリバース CHAP 設定します。</span><span class="sxs-lookup"><span data-stu-id="20633-106">The device CHAP and reverse-CHAP settings.</span></span></param>
        <param name="cloudApplianceSettings"><span data-ttu-id="20633-107">クラウド アプライアンスの設定。</span><span class="sxs-lookup"><span data-stu-id="20633-107">The cloud appliance settings.</span></span></param>
        <summary>
            <span data-ttu-id="20633-108">SecuritySettingsPatch クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="20633-108">Initializes a new instance of the SecuritySettingsPatch class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChapSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings ChapSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings ChapSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch.ChapSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ChapSettings As ChapSettings" />
      <MemberSignature Language="F#" Value="member this.ChapSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch.ChapSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.chapSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ChapSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20633-109">取得または設定、デバイスの CHAP とリバース CHAP の設定。</span><span class="sxs-lookup"><span data-stu-id="20633-109">Gets or sets the device CHAP and reverse-CHAP settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudApplianceSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings CloudApplianceSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings CloudApplianceSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch.CloudApplianceSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudApplianceSettings As CloudApplianceSettings" />
      <MemberSignature Language="F#" Value="member this.CloudApplianceSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch.CloudApplianceSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cloudApplianceSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20633-110">取得またはクラウド アプライアンスの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="20633-110">Gets or sets the cloud appliance settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceAdminPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret DeviceAdminPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret DeviceAdminPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch.DeviceAdminPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceAdminPassword As AsymmetricEncryptedSecret" />
      <MemberSignature Language="F#" Value="member this.DeviceAdminPassword : Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch.DeviceAdminPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceAdminPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20633-111">取得またはデバイス管理者パスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="20633-111">Gets or sets the device administrator password.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteManagementSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch RemoteManagementSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch RemoteManagementSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch.RemoteManagementSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteManagementSettings As RemoteManagementSettingsPatch" />
      <MemberSignature Language="F#" Value="member this.RemoteManagementSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch.RemoteManagementSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.remoteManagementSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.RemoteManagementSettingsPatch</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20633-112">取得またはリモート管理設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="20633-112">Gets or sets the remote management settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret SnapshotPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret SnapshotPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch.SnapshotPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property SnapshotPassword As AsymmetricEncryptedSecret" />
      <MemberSignature Language="F#" Value="member this.SnapshotPassword : Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch.SnapshotPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.snapshotPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20633-113">取得またはスナップショット マネージャーのパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="20633-113">Gets or sets the snapshot manager password.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.SecuritySettingsPatch.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="securitySettingsPatch.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="20633-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="20633-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="20633-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="20633-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>