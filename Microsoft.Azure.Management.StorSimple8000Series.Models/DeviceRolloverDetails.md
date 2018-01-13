<Type Name="DeviceRolloverDetails" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails">
  <TypeSignature Language="C#" Value="public class DeviceRolloverDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeviceRolloverDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class DeviceRolloverDetails" />
  <TypeSignature Language="F#" Value="type DeviceRolloverDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="abbeb-101">サービス データ暗号化キーのロール オーバーの他のデバイスの詳細。</span><span class="sxs-lookup"><span data-stu-id="abbeb-101">The additional device details for the service data encryption key rollover.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceRolloverDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="abbeb-102">DeviceRolloverDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="abbeb-102">Initializes a new instance of the DeviceRolloverDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceRolloverDetails (Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationEligibility&gt; authorizationEligibility = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationStatus&gt; authorizationStatus = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.InEligibilityCategory&gt; inEligibilityReason = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationEligibility&gt; authorizationEligibility, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationStatus&gt; authorizationStatus, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.InEligibilityCategory&gt; inEligibilityReason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails.#ctor(System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationEligibility},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationStatus},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.InEligibilityCategory})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional authorizationEligibility As Nullable(Of AuthorizationEligibility) = null, Optional authorizationStatus As Nullable(Of AuthorizationStatus) = null, Optional inEligibilityReason As Nullable(Of InEligibilityCategory) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationEligibility&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationStatus&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.InEligibilityCategory&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails (authorizationEligibility, authorizationStatus, inEligibilityReason)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authorizationEligibility" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationEligibility&gt;" />
        <Parameter Name="authorizationStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationStatus&gt;" />
        <Parameter Name="inEligibilityReason" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.InEligibilityCategory&gt;" />
      </Parameters>
      <Docs>
        <param name="authorizationEligibility"><span data-ttu-id="abbeb-103">サービス データ暗号化キーのロール オーバーのデバイスの適格性の状態。</span><span class="sxs-lookup"><span data-stu-id="abbeb-103">The eligibility status of device for service data encryption key rollover.</span></span> <span data-ttu-id="abbeb-104">使用可能な値が含まれます: '外します'、''</span><span class="sxs-lookup"><span data-stu-id="abbeb-104">Possible values include: 'InEligible', 'Eligible'</span></span></param>
        <param name="authorizationStatus"><span data-ttu-id="abbeb-105">サービス データ暗号化キーのロール オーバーのデバイスの承認状態です。</span><span class="sxs-lookup"><span data-stu-id="abbeb-105">The authorization status of the device for service data encryption key rollover.</span></span> <span data-ttu-id="abbeb-106">使用可能な値が含まれます: '無効'、'Enabled'</span><span class="sxs-lookup"><span data-stu-id="abbeb-106">Possible values include: 'Disabled', 'Enabled'</span></span></param>
        <param name="inEligibilityReason"><span data-ttu-id="abbeb-107">デバイスの inEligibility 理由できない場合に、サービス データ暗号化キーのロール オーバーの条件に適合します。</span><span class="sxs-lookup"><span data-stu-id="abbeb-107">The reason for inEligibility of device, in case it's not eligible for service data encryption key rollover.</span></span> <span data-ttu-id="abbeb-108">使用可能な値が含まれます: 'DeviceNotOnline'、'NotSupportedAppliance'、'RolloverPending'</span><span class="sxs-lookup"><span data-stu-id="abbeb-108">Possible values include: 'DeviceNotOnline', 'NotSupportedAppliance', 'RolloverPending'</span></span></param>
        <summary>
            <span data-ttu-id="abbeb-109">DeviceRolloverDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="abbeb-109">Initializes a new instance of the DeviceRolloverDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationEligibility">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationEligibility&gt; AuthorizationEligibility { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationEligibility&gt; AuthorizationEligibility" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails.AuthorizationEligibility" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthorizationEligibility As Nullable(Of AuthorizationEligibility)" />
      <MemberSignature Language="F#" Value="member this.AuthorizationEligibility : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationEligibility&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails.AuthorizationEligibility" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authorizationEligibility")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationEligibility&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="abbeb-110">取得または、サービス データ暗号化キーのロール オーバーのデバイスの適格性の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="abbeb-110">Gets or sets the eligibility status of device for service data encryption key rollover.</span></span> <span data-ttu-id="abbeb-111">使用可能な値が含まれます: '外します'、''</span><span class="sxs-lookup"><span data-stu-id="abbeb-111">Possible values include: 'InEligible', 'Eligible'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationStatus&gt; AuthorizationStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationStatus&gt; AuthorizationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails.AuthorizationStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthorizationStatus As Nullable(Of AuthorizationStatus)" />
      <MemberSignature Language="F#" Value="member this.AuthorizationStatus : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationStatus&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails.AuthorizationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authorizationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AuthorizationStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="abbeb-112">取得または、サービス データ暗号化キーのロール オーバーのデバイスの認証の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="abbeb-112">Gets or sets the authorization status of the device for service data encryption key rollover.</span></span> <span data-ttu-id="abbeb-113">使用可能な値が含まれます: '無効'、'Enabled'</span><span class="sxs-lookup"><span data-stu-id="abbeb-113">Possible values include: 'Disabled', 'Enabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InEligibilityReason">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.InEligibilityCategory&gt; InEligibilityReason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.InEligibilityCategory&gt; InEligibilityReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails.InEligibilityReason" />
      <MemberSignature Language="VB.NET" Value="Public Property InEligibilityReason As Nullable(Of InEligibilityCategory)" />
      <MemberSignature Language="F#" Value="member this.InEligibilityReason : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.InEligibilityCategory&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails.InEligibilityReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="inEligibilityReason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.InEligibilityCategory&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="abbeb-114">取得または、サービス データ暗号化キーのロール オーバーに適していない場合に、デバイスの inEligibility の理由を設定します。</span><span class="sxs-lookup"><span data-stu-id="abbeb-114">Gets or sets the reason for inEligibility of device, in case it's not eligible for service data encryption key rollover.</span></span> <span data-ttu-id="abbeb-115">使用可能な値が含まれます: 'DeviceNotOnline'、'NotSupportedAppliance'、'RolloverPending'</span><span class="sxs-lookup"><span data-stu-id="abbeb-115">Possible values include: 'DeviceNotOnline', 'NotSupportedAppliance', 'RolloverPending'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>