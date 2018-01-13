<Type Name="Device" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.Device">
  <TypeSignature Language="C#" Value="public class Device : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Device extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.Device" />
  <TypeSignature Language="VB.NET" Value="Public Class Device&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type Device = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            StorSimple デバイスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Device ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            デバイス クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Device (string friendlyName, DateTime activationTime, string culture, string deviceDescription, string deviceSoftwareVersion, Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus deviceConfigurationStatus, string targetIqn, string modelDescription, Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus status, string serialNumber, Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType deviceType, Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId activeController, string friendlySoftwareVersion, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, string friendlySoftwareName = null, Nullable&lt;long&gt; availableLocalStorageInBytes = null, Nullable&lt;long&gt; availableTieredStorageInBytes = null, Nullable&lt;long&gt; provisionedTieredStorageInBytes = null, Nullable&lt;long&gt; provisionedLocalStorageInBytes = null, Nullable&lt;long&gt; provisionedVolumeSizeInBytes = null, Nullable&lt;long&gt; usingStorageInBytes = null, Nullable&lt;long&gt; totalTieredStorageInBytes = null, Nullable&lt;int&gt; agentGroupVersion = null, Nullable&lt;int&gt; networkInterfaceCardCount = null, string deviceLocation = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType&gt; virtualMachineApiType = null, Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails details = null, Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails rolloverDetails = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, valuetype System.DateTime activationTime, string culture, string deviceDescription, string deviceSoftwareVersion, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus deviceConfigurationStatus, string targetIqn, string modelDescription, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus status, string serialNumber, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType deviceType, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId activeController, string friendlySoftwareVersion, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, string friendlySoftwareName, valuetype System.Nullable`1&lt;int64&gt; availableLocalStorageInBytes, valuetype System.Nullable`1&lt;int64&gt; availableTieredStorageInBytes, valuetype System.Nullable`1&lt;int64&gt; provisionedTieredStorageInBytes, valuetype System.Nullable`1&lt;int64&gt; provisionedLocalStorageInBytes, valuetype System.Nullable`1&lt;int64&gt; provisionedVolumeSizeInBytes, valuetype System.Nullable`1&lt;int64&gt; usingStorageInBytes, valuetype System.Nullable`1&lt;int64&gt; totalTieredStorageInBytes, valuetype System.Nullable`1&lt;int32&gt; agentGroupVersion, valuetype System.Nullable`1&lt;int32&gt; networkInterfaceCardCount, string deviceLocation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType&gt; virtualMachineApiType, class Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails details, class Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails rolloverDetails) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.#ctor(System.String,System.DateTime,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType,Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType},Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails,Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.Device : string * DateTime * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus * string * Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType * Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType&gt; * Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails * Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Device" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.Device (friendlyName, activationTime, culture, deviceDescription, deviceSoftwareVersion, deviceConfigurationStatus, targetIqn, modelDescription, status, serialNumber, deviceType, activeController, friendlySoftwareVersion, id, name, type, kind, friendlySoftwareName, availableLocalStorageInBytes, availableTieredStorageInBytes, provisionedTieredStorageInBytes, provisionedLocalStorageInBytes, provisionedVolumeSizeInBytes, usingStorageInBytes, totalTieredStorageInBytes, agentGroupVersion, networkInterfaceCardCount, deviceLocation, virtualMachineApiType, details, rolloverDetails)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="activationTime" Type="System.DateTime" />
        <Parameter Name="culture" Type="System.String" />
        <Parameter Name="deviceDescription" Type="System.String" />
        <Parameter Name="deviceSoftwareVersion" Type="System.String" />
        <Parameter Name="deviceConfigurationStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus" />
        <Parameter Name="targetIqn" Type="System.String" />
        <Parameter Name="modelDescription" Type="System.String" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus" />
        <Parameter Name="serialNumber" Type="System.String" />
        <Parameter Name="deviceType" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType" />
        <Parameter Name="activeController" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId" />
        <Parameter Name="friendlySoftwareVersion" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="friendlySoftwareName" Type="System.String" />
        <Parameter Name="availableLocalStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="availableTieredStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="provisionedTieredStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="provisionedLocalStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="provisionedVolumeSizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="usingStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="totalTieredStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="agentGroupVersion" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="networkInterfaceCardCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="deviceLocation" Type="System.String" />
        <Parameter Name="virtualMachineApiType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType&gt;" />
        <Parameter Name="details" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails" />
        <Parameter Name="rolloverDetails" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails" />
      </Parameters>
      <Docs>
        <param name="friendlyName">デバイスのフレンドリ名。</param>
        <param name="activationTime">これで、デバイスがアクティブ化された UTC 時刻</param>
        <param name="culture">デバイスの言語のカルチャ設定です。
            例:"EN-US"</param>
        <param name="deviceDescription">デバイスの説明。</param>
        <param name="deviceSoftwareVersion">デバイスで実行されているソフトウェアのバージョン番号。</param>
        <param name="deviceConfigurationStatus">デバイスの現在の構成の状態。 使用可能な値が含まれます: '完了'、'Pending'</param>
        <param name="targetIqn">ターゲット IQN です。</param>
        <param name="modelDescription">デバイスのモデル。</param>
        <param name="status">デバイスの現在の状態。 使用可能な値が含まれます: 'Unknown'、'オンライン'、'オフライン'、'を非アクティブ化'、'RequiresAttention'、'でメンテナンス モード'、'作成中'、'プロビジョニング'、'非アクティブ化する'、'削除済み'、'ReadyToSetup'</param>
        <param name="serialNumber">シリアル番号。</param>
        <param name="deviceType">デバイスの種類。 使用可能な値が含まれます: '無効'、'Series8000VirtualAppliance'、'Series8000PhysicalAppliance'</param>
        <param name="activeController">デバイスのアクティブなコント ローラーの識別子。 使用可能な値が含まれます: 'Unknown'、'None'、'Controller0'、'Controller1'</param>
        <param name="friendlySoftwareVersion">デバイスのわかりやすいソフトウェア バージョンです。</param>
        <param name="id">オブジェクトを一意に識別するパス ID です。</param>
        <param name="name">オブジェクトの名前。</param>
        <param name="type">オブジェクトの階層型です。</param>
        <param name="kind">オブジェクトの種類。 現在は Series8000 はサポートされています。 使用可能な値が含まれます: 'Series8000'</param>
        <param name="friendlySoftwareName">デバイスで実行されているソフトウェアの表示名。</param>
        <param name="availableLocalStorageInBytes">デバイスでローカルに利用可能なストレージ (バイト単位)。</param>
        <param name="availableTieredStorageInBytes">階層化ボリュームのデバイスで利用可能なストレージ (バイト単位)。</param>
        <param name="provisionedTieredStorageInBytes">記憶域 (バイト単位) が、階層化ボリュームのデバイスにプロビジョニングされています。</param>
        <param name="provisionedLocalStorageInBytes">(その他のローカルの予約を含む)、デバイス上のローカル固定ボリュームのサイズをバイト単位でストレージです。</param>
        <param name="provisionedVolumeSizeInBytes">デバイス上の階層化されたローカル固定ボリュームのバイト単位の合計容量</param>
        <param name="usingStorageInBytes">ローカルを含め、デバイスで現在使用されているバイトのストレージとクラウド。</param>
        <param name="totalTieredStorageInBytes">合計階層型記憶域 (バイト単位) デバイスで使用します。</param>
        <param name="agentGroupVersion">デバイス エージェント グループのバージョン。</param>
        <param name="networkInterfaceCardCount">ネットワーク インターフェイス カードの数</param>
        <param name="deviceLocation">仮想アプライアンスの場所です。</param>
        <param name="virtualMachineApiType">Virtual machine API の種類。
            使用可能な値が含まれます: 'クラシック'、'Arm'</param>
        <param name="details">最後のポイントの数とボリューム コンテナーの数に関するその他のデバイスの詳細。</param>
        <param name="rolloverDetails">サービス データ暗号化キーのロール オーバーの他のデバイスの詳細。</param>
        <summary>
            デバイス クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivationTime">
      <MemberSignature Language="C#" Value="public DateTime ActivationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ActivationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ActivationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ActivationTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.ActivationTime : DateTime with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ActivationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.activationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定をデバイスがアクティブ化された UTC 時刻
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveController">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId ActiveController { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId ActiveController" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ActiveController" />
      <MemberSignature Language="VB.NET" Value="Public Property ActiveController As ControllerId" />
      <MemberSignature Language="F#" Value="member this.ActiveController : Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ActiveController" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.activeController")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスのアクティブなコント ローラーの識別子を設定します。
            使用可能な値が含まれます: 'Unknown'、'None'、'Controller0'、'Controller1'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AgentGroupVersion">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; AgentGroupVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; AgentGroupVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.AgentGroupVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property AgentGroupVersion As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.AgentGroupVersion : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.AgentGroupVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.agentGroupVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイス エージェント グループのバージョンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableLocalStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; AvailableLocalStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; AvailableLocalStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.AvailableLocalStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailableLocalStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.AvailableLocalStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.AvailableLocalStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availableLocalStorageInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、記憶域デバイスでローカルに利用可能なバイト数。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableTieredStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; AvailableTieredStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; AvailableTieredStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.AvailableTieredStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailableTieredStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.AvailableTieredStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.AvailableTieredStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availableTieredStorageInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、記憶域階層化ボリュームのデバイスで利用可能なバイト数。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Culture">
      <MemberSignature Language="C#" Value="public string Culture { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Culture" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.Culture" />
      <MemberSignature Language="VB.NET" Value="Public Property Culture As String" />
      <MemberSignature Language="F#" Value="member this.Culture : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.Culture" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.culture")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスの言語のカルチャ設定を設定します。 例:"EN-US"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As DeviceDetails" />
      <MemberSignature Language="F#" Value="member this.Details : Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または終了ポイントの数とボリューム コンテナーの数に関するその他のデバイスの詳細を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceConfigurationStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus DeviceConfigurationStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus DeviceConfigurationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceConfigurationStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceConfigurationStatus As DeviceConfigurationStatus" />
      <MemberSignature Language="F#" Value="member this.DeviceConfigurationStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceConfigurationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceConfigurationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスの現在の構成状態を設定します。
            使用可能な値が含まれます: '完了'、'Pending'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceDescription">
      <MemberSignature Language="C#" Value="public string DeviceDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceDescription As String" />
      <MemberSignature Language="F#" Value="member this.DeviceDescription : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceDescription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスの説明を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceLocation">
      <MemberSignature Language="C#" Value="public string DeviceLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceLocation As String" />
      <MemberSignature Language="F#" Value="member this.DeviceLocation : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想アプライアンスの場所を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceSoftwareVersion">
      <MemberSignature Language="C#" Value="public string DeviceSoftwareVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceSoftwareVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceSoftwareVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceSoftwareVersion As String" />
      <MemberSignature Language="F#" Value="member this.DeviceSoftwareVersion : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceSoftwareVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceSoftwareVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスで実行されているソフトウェアのバージョン番号を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType DeviceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType DeviceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceType" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceType As DeviceType" />
      <MemberSignature Language="F#" Value="member this.DeviceType : Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスの種類を設定します。 使用可能な値が含まれます: '無効'、'Series8000VirtualAppliance'、'Series8000PhysicalAppliance'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.FriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.friendlyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスのフレンドリ名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlySoftwareName">
      <MemberSignature Language="C#" Value="public string FriendlySoftwareName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlySoftwareName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.FriendlySoftwareName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlySoftwareName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlySoftwareName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.FriendlySoftwareName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.friendlySoftwareName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスで実行されているソフトウェアのフレンドリ名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlySoftwareVersion">
      <MemberSignature Language="C#" Value="public string FriendlySoftwareVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlySoftwareVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.FriendlySoftwareVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlySoftwareVersion As String" />
      <MemberSignature Language="F#" Value="member this.FriendlySoftwareVersion : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.FriendlySoftwareVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.friendlySoftwareVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスのわかりやすいソフトウェア バージョンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModelDescription">
      <MemberSignature Language="C#" Value="public string ModelDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ModelDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ModelDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property ModelDescription As String" />
      <MemberSignature Language="F#" Value="member this.ModelDescription : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ModelDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.modelDescription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスのモデルを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaceCardCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NetworkInterfaceCardCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NetworkInterfaceCardCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.NetworkInterfaceCardCount" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkInterfaceCardCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceCardCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.NetworkInterfaceCardCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkInterfaceCardCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のネットワーク インターフェイス カードの数
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisionedLocalStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ProvisionedLocalStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ProvisionedLocalStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ProvisionedLocalStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisionedLocalStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ProvisionedLocalStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ProvisionedLocalStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisionedLocalStorageInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または (その他のローカルの予約を含む)、デバイス上のローカル固定ボリュームのサイズをバイト単位で、記憶域を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisionedTieredStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ProvisionedTieredStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ProvisionedTieredStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ProvisionedTieredStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisionedTieredStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ProvisionedTieredStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ProvisionedTieredStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisionedTieredStorageInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、記憶域階層化ボリュームのデバイスがプロビジョニングされているバイト数。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisionedVolumeSizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ProvisionedVolumeSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ProvisionedVolumeSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ProvisionedVolumeSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisionedVolumeSizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ProvisionedVolumeSizeInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ProvisionedVolumeSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisionedVolumeSizeInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスに階層型ボリュームとローカル固定ボリュームのバイト単位の合計容量を設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RolloverDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails RolloverDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails RolloverDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.RolloverDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property RolloverDetails As DeviceRolloverDetails" />
      <MemberSignature Language="F#" Value="member this.RolloverDetails : Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.RolloverDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.rolloverDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または追加のデバイスの詳細、サービス データ暗号化キーのロール オーバーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerialNumber">
      <MemberSignature Language="C#" Value="public string SerialNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SerialNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.SerialNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SerialNumber As String" />
      <MemberSignature Language="F#" Value="member this.SerialNumber : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.SerialNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serialNumber")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはシリアル番号を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As DeviceStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスの現在の状態を設定します。 使用可能な値が含まれます: 'Unknown'、'オンライン'、'オフライン'、'を非アクティブ化'、'RequiresAttention'、'でメンテナンス モード'、'作成中'、'プロビジョニング'、'非アクティブ化する'、'削除済み'、'ReadyToSetup'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetIqn">
      <MemberSignature Language="C#" Value="public string TargetIqn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetIqn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.TargetIqn" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetIqn As String" />
      <MemberSignature Language="F#" Value="member this.TargetIqn : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.TargetIqn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetIqn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはターゲット IQN を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalTieredStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; TotalTieredStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; TotalTieredStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.TotalTieredStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalTieredStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.TotalTieredStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.TotalTieredStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.totalTieredStorageInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバイト数内のデバイスで利用可能な合計階層型記憶域を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsingStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; UsingStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; UsingStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.UsingStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property UsingStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.UsingStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.UsingStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usingStorageInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはローカルを含め、デバイスで現在使用されているバイト数で、記憶域を設定およびクラウド。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="device.Validate " />
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
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineApiType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType&gt; VirtualMachineApiType { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType&gt; VirtualMachineApiType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.VirtualMachineApiType" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineApiType As Nullable(Of VirtualMachineApiType)" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineApiType : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.VirtualMachineApiType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualMachineApiType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Virtual machine API の種類を取得します。 使用可能な値が含まれます: 'クラシック'、'Arm'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>