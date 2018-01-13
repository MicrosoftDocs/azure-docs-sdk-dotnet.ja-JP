<Type Name="FailoverTarget" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget">
  <TypeSignature Language="C#" Value="public class FailoverTarget" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FailoverTarget extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget" />
  <TypeSignature Language="VB.NET" Value="Public Class FailoverTarget" />
  <TypeSignature Language="F#" Value="type FailoverTarget = class" />
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
            デバイスのフェールオーバーのターゲット デバイスとして適格性を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverTarget ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            FailoverTarget クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverTarget (string deviceId = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus&gt; deviceStatus = null, string modelDescription = null, string deviceSoftwareVersion = null, Nullable&lt;int&gt; dataContainersCount = null, Nullable&lt;int&gt; volumesCount = null, Nullable&lt;long&gt; availableLocalStorageInBytes = null, Nullable&lt;long&gt; availableTieredStorageInBytes = null, string deviceLocation = null, string friendlyDeviceSoftwareVersion = null, Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult eligibilityResult = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deviceId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus&gt; deviceStatus, string modelDescription, string deviceSoftwareVersion, valuetype System.Nullable`1&lt;int32&gt; dataContainersCount, valuetype System.Nullable`1&lt;int32&gt; volumesCount, valuetype System.Nullable`1&lt;int64&gt; availableLocalStorageInBytes, valuetype System.Nullable`1&lt;int64&gt; availableTieredStorageInBytes, string deviceLocation, string friendlyDeviceSoftwareVersion, class Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult eligibilityResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Int64},System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional deviceId As String = null, Optional deviceStatus As Nullable(Of DeviceStatus) = null, Optional modelDescription As String = null, Optional deviceSoftwareVersion As String = null, Optional dataContainersCount As Nullable(Of Integer) = null, Optional volumesCount As Nullable(Of Integer) = null, Optional availableLocalStorageInBytes As Nullable(Of Long) = null, Optional availableTieredStorageInBytes As Nullable(Of Long) = null, Optional deviceLocation As String = null, Optional friendlyDeviceSoftwareVersion As String = null, Optional eligibilityResult As TargetEligibilityResult = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget : string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget (deviceId, deviceStatus, modelDescription, deviceSoftwareVersion, dataContainersCount, volumesCount, availableLocalStorageInBytes, availableTieredStorageInBytes, deviceLocation, friendlyDeviceSoftwareVersion, eligibilityResult)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="deviceStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus&gt;" />
        <Parameter Name="modelDescription" Type="System.String" />
        <Parameter Name="deviceSoftwareVersion" Type="System.String" />
        <Parameter Name="dataContainersCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="volumesCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="availableLocalStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="availableTieredStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="deviceLocation" Type="System.String" />
        <Parameter Name="friendlyDeviceSoftwareVersion" Type="System.String" />
        <Parameter Name="eligibilityResult" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult" />
      </Parameters>
      <Docs>
        <param name="deviceId">デバイスのパス ID です。</param>
        <param name="deviceStatus">デバイスの状態です。 使用可能な値が含まれます: 'Unknown'、'オンライン'、'オフライン'、'を非アクティブ化'、'RequiresAttention'、'でメンテナンス モード'、'作成中'、'プロビジョニング'、'非アクティブ化する'、'削除済み'、'ReadyToSetup'</param>
        <param name="modelDescription">デバイスのモデル番号。</param>
        <param name="deviceSoftwareVersion">デバイスのソフトウェアのバージョン。</param>
        <param name="dataContainersCount">デバイスで datacontainers の数。</param>
        <param name="volumesCount">デバイス上のボリュームの数。</param>
        <param name="availableLocalStorageInBytes">利用可能なローカル ストレージの量 (バイト単位) デバイス。</param>
        <param name="availableTieredStorageInBytes">階層型記憶域の空きバイト数のデバイスで利用できる量。</param>
        <param name="deviceLocation">地理的場所 (クラウド アプライアンスにのみ適用)、デバイスのです。</param>
        <param name="friendlyDeviceSoftwareVersion">デバイス上のソフトウェアの現在のバージョンのフレンドリ名。</param>
        <param name="eligibilityResult">フェールオーバーのターゲット デバイスとして、デバイスの対象となる結果です。</param>
        <summary>
            FailoverTarget クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableLocalStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; AvailableLocalStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; AvailableLocalStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.AvailableLocalStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailableLocalStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.AvailableLocalStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.AvailableLocalStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="availableLocalStorageInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバイト数内のデバイスで利用可能なローカル ストレージの量を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableTieredStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; AvailableTieredStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; AvailableTieredStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.AvailableTieredStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailableTieredStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.AvailableTieredStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.AvailableTieredStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="availableTieredStorageInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスの使用可能な空き階層型記憶域の量をバイト単位で設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataContainersCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DataContainersCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DataContainersCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.DataContainersCount" />
      <MemberSignature Language="VB.NET" Value="Public Property DataContainersCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DataContainersCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.DataContainersCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataContainersCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスで datacontainers の数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceId">
      <MemberSignature Language="C#" Value="public string DeviceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.DeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceId As String" />
      <MemberSignature Language="F#" Value="member this.DeviceId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.DeviceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deviceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスのパス ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceLocation">
      <MemberSignature Language="C#" Value="public string DeviceLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.DeviceLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceLocation As String" />
      <MemberSignature Language="F#" Value="member this.DeviceLocation : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.DeviceLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deviceLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスの地理的場所 (クラウド アプライアンスにのみ適用) を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceSoftwareVersion">
      <MemberSignature Language="C#" Value="public string DeviceSoftwareVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceSoftwareVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.DeviceSoftwareVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceSoftwareVersion As String" />
      <MemberSignature Language="F#" Value="member this.DeviceSoftwareVersion : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.DeviceSoftwareVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deviceSoftwareVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスのソフトウェアのバージョンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus&gt; DeviceStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus&gt; DeviceStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.DeviceStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceStatus As Nullable(Of DeviceStatus)" />
      <MemberSignature Language="F#" Value="member this.DeviceStatus : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.DeviceStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deviceStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスの状態を設定します。 使用可能な値が含まれます: 'Unknown'、'オンライン'、'オフライン'、'を非アクティブ化'、'RequiresAttention'、'でメンテナンス モード'、'作成中'、'プロビジョニング'、'非アクティブ化する'、'削除済み'、'ReadyToSetup'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EligibilityResult">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult EligibilityResult { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult EligibilityResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.EligibilityResult" />
      <MemberSignature Language="VB.NET" Value="Public Property EligibilityResult As TargetEligibilityResult" />
      <MemberSignature Language="F#" Value="member this.EligibilityResult : Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.EligibilityResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eligibilityResult")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフェールオーバーのターゲット デバイスとして、デバイスの対象となる結果を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyDeviceSoftwareVersion">
      <MemberSignature Language="C#" Value="public string FriendlyDeviceSoftwareVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyDeviceSoftwareVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.FriendlyDeviceSoftwareVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyDeviceSoftwareVersion As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyDeviceSoftwareVersion : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.FriendlyDeviceSoftwareVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="friendlyDeviceSoftwareVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスにソフトウェアの現在のバージョンのフレンドリ名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModelDescription">
      <MemberSignature Language="C#" Value="public string ModelDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ModelDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.ModelDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property ModelDescription As String" />
      <MemberSignature Language="F#" Value="member this.ModelDescription : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.ModelDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="modelDescription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスのモデル番号を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumesCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; VolumesCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; VolumesCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.VolumesCount" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumesCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.VolumesCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget.VolumesCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="volumesCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイス上のボリュームの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>