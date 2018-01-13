<Type Name="IoTHubStreamInputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource">
  <TypeSignature Language="C#" Value="public class IoTHubStreamInputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IoTHubStreamInputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class IoTHubStreamInputDataSource&#xA;Inherits StreamInputDataSource" />
  <TypeSignature Language="F#" Value="type IoTHubStreamInputDataSource = class&#xA;    inherit StreamInputDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Devices/IotHubs")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            ストリーム データを含む IoT Hub 入力データ ソースについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IoTHubStreamInputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            IoTHubStreamInputDataSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IoTHubStreamInputDataSource (string iotHubNamespace = null, string sharedAccessPolicyName = null, string sharedAccessPolicyKey = null, string consumerGroupName = null, string endpoint = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string iotHubNamespace, string sharedAccessPolicyName, string sharedAccessPolicyKey, string consumerGroupName, string endpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional iotHubNamespace As String = null, Optional sharedAccessPolicyName As String = null, Optional sharedAccessPolicyKey As String = null, Optional consumerGroupName As String = null, Optional endpoint As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource : string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource (iotHubNamespace, sharedAccessPolicyName, sharedAccessPolicyKey, consumerGroupName, endpoint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="iotHubNamespace" Type="System.String" />
        <Parameter Name="sharedAccessPolicyName" Type="System.String" />
        <Parameter Name="sharedAccessPolicyKey" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="endpoint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="iotHubNamespace">名前または IoT Hub の URI。
            PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="sharedAccessPolicyName">IoT hub 共有アクセス ポリシーの名前。 このポリシーがありますには、少なくとも、サービスのアクセス許可を接続します。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="sharedAccessPolicyKey">指定した共有アクセス ポリシーの共有アクセス ポリシー キー。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="consumerGroupName">IoT Hub からイベントを読み取るために使用する必要があります IoT Hub コンシューマー グループの名前。 指定しない場合、入力は Iot ハブの既定のコンシューマー グループを使用します。</param>
        <param name="endpoint">IoT Hub エンドポイントに接続する (ie。 メッセージやイベント、メッセージ/operationsMonitoringEvents などです。)。</param>
        <summary>
            IoTHubStreamInputDataSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsumerGroupName">
      <MemberSignature Language="C#" Value="public string ConsumerGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsumerGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.ConsumerGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsumerGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ConsumerGroupName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.ConsumerGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.consumerGroupName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または IoT Hub からイベントを読み取るために使用する必要があります IoT Hub コンシューマー グループの名前を設定します。 指定しない場合、入力は Iot ハブの既定のコンシューマー グループを使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定への接続に IoT Hub エンドポイント (ie。 メッセージやイベント、メッセージ/operationsMonitoringEvents などです。)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IotHubNamespace">
      <MemberSignature Language="C#" Value="public string IotHubNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IotHubNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.IotHubNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property IotHubNamespace As String" />
      <MemberSignature Language="F#" Value="member this.IotHubNamespace : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.IotHubNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.iotHubNamespace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、名前または IoT Hub の URI を設定します。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessPolicyKey">
      <MemberSignature Language="C#" Value="public string SharedAccessPolicyKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessPolicyKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.SharedAccessPolicyKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessPolicyKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessPolicyKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.SharedAccessPolicyKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sharedAccessPolicyKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または指定した共有アクセス ポリシーの共有アクセス ポリシーのキーを設定します。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessPolicyName">
      <MemberSignature Language="C#" Value="public string SharedAccessPolicyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessPolicyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.SharedAccessPolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessPolicyName As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessPolicyName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.SharedAccessPolicyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sharedAccessPolicyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または IoT hub 共有アクセス ポリシー名を設定します。 このポリシーがありますには、少なくとも、サービスのアクセス許可を接続します。
            PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>