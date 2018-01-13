<Type Name="EventHubOutputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource">
  <TypeSignature Language="C#" Value="public class EventHubOutputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventHubOutputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class EventHubOutputDataSource&#xA;Inherits OutputDataSource" />
  <TypeSignature Language="F#" Value="type EventHubOutputDataSource = class&#xA;    inherit OutputDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.ServiceBus/EventHub")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Event Hub の出力データ ソースをについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubOutputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            EventHubOutputDataSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubOutputDataSource (string serviceBusNamespace = null, string sharedAccessPolicyName = null, string sharedAccessPolicyKey = null, string eventHubName = null, string partitionKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceBusNamespace, string sharedAccessPolicyName, string sharedAccessPolicyKey, string eventHubName, string partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceBusNamespace As String = null, Optional sharedAccessPolicyName As String = null, Optional sharedAccessPolicyKey As String = null, Optional eventHubName As String = null, Optional partitionKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource : string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource (serviceBusNamespace, sharedAccessPolicyName, sharedAccessPolicyKey, eventHubName, partitionKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceBusNamespace" Type="System.String" />
        <Parameter Name="sharedAccessPolicyName" Type="System.String" />
        <Parameter Name="sharedAccessPolicyKey" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="partitionKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceBusNamespace">目的のイベント ハブ、Service Bus のキュー、Service Bus トピックなどに関連付けられている名前空間。PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="sharedAccessPolicyName">イベント ハブ、Service Bus キュー、Service Bus トピックなどの共有アクセス ポリシーの名前。PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="sharedAccessPolicyKey">指定した共有アクセス ポリシーの共有アクセス ポリシー キー。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="eventHubName">イベント ハブの名前。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="partitionKey">キー/列をイベント データを送信するパーティションを決定するために使用します。</param>
        <summary>
            EventHubOutputDataSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubName">
      <MemberSignature Language="C#" Value="public string EventHubName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource.EventHubName" />
      <MemberSignature Language="VB.NET" Value="Public Property EventHubName As String" />
      <MemberSignature Language="F#" Value="member this.EventHubName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource.EventHubName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.eventHubName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはイベント ハブの名前を設定します。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partitionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはイベント データを送信するパーティションを決定するために使用するキー/列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusNamespace">
      <MemberSignature Language="C#" Value="public string ServiceBusNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource.ServiceBusNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusNamespace As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusNamespace : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource.ServiceBusNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceBusNamespace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または目的のイベント ハブ、Service Bus のキュー、Service Bus トピックなどに関連付けられている名前空間を設定します。PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessPolicyKey">
      <MemberSignature Language="C#" Value="public string SharedAccessPolicyKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessPolicyKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource.SharedAccessPolicyKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessPolicyKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessPolicyKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource.SharedAccessPolicyKey" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource.SharedAccessPolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessPolicyName As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessPolicyName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.EventHubOutputDataSource.SharedAccessPolicyName" />
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
            取得またはイベント ハブ、Service Bus キュー、Service Bus トピックなどの共有アクセス ポリシー名を設定します。PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>