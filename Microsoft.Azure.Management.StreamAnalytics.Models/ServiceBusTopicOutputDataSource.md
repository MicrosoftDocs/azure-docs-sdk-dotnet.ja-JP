<Type Name="ServiceBusTopicOutputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource">
  <TypeSignature Language="C#" Value="public class ServiceBusTopicOutputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceBusTopicOutputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusTopicOutputDataSource&#xA;Inherits OutputDataSource" />
  <TypeSignature Language="F#" Value="type ServiceBusTopicOutputDataSource = class&#xA;    inherit OutputDataSource" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.ServiceBus/Topic")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Service Bus トピックの出力データ ソースをについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusTopicOutputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ServiceBusTopicOutputDataSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusTopicOutputDataSource (string serviceBusNamespace = null, string sharedAccessPolicyName = null, string sharedAccessPolicyKey = null, string topicName = null, System.Collections.Generic.IList&lt;string&gt; propertyColumns = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceBusNamespace, string sharedAccessPolicyName, string sharedAccessPolicyKey, string topicName, class System.Collections.Generic.IList`1&lt;string&gt; propertyColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceBusNamespace As String = null, Optional sharedAccessPolicyName As String = null, Optional sharedAccessPolicyKey As String = null, Optional topicName As String = null, Optional propertyColumns As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource : string * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource (serviceBusNamespace, sharedAccessPolicyName, sharedAccessPolicyKey, topicName, propertyColumns)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceBusNamespace" Type="System.String" />
        <Parameter Name="sharedAccessPolicyName" Type="System.String" />
        <Parameter Name="sharedAccessPolicyKey" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="propertyColumns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceBusNamespace">目的のイベント ハブ、Service Bus のキュー、Service Bus トピックなどに関連付けられている名前空間。PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="sharedAccessPolicyName">イベント ハブ、Service Bus キュー、Service Bus トピックなどの共有アクセス ポリシーの名前。PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="sharedAccessPolicyKey">指定した共有アクセス ポリシーの共有アクセス ポリシー キー。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="topicName">Service Bus トピックの名前。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="propertyColumns">カスタム プロパティとして Service Bus メッセージにアタッチされている出力列の名前の文字列配列。</param>
        <summary>
            ServiceBusTopicOutputDataSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyColumns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; PropertyColumns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; PropertyColumns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.PropertyColumns" />
      <MemberSignature Language="VB.NET" Value="Public Property PropertyColumns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PropertyColumns : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.PropertyColumns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.propertyColumns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはカスタム プロパティとして Service Bus メッセージにアタッチされている出力列の名前の文字列配列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusNamespace">
      <MemberSignature Language="C#" Value="public string ServiceBusNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.ServiceBusNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusNamespace As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusNamespace : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.ServiceBusNamespace" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.SharedAccessPolicyKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessPolicyKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessPolicyKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.SharedAccessPolicyKey" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.SharedAccessPolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessPolicyName As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessPolicyName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.SharedAccessPolicyName" />
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
    <Member MemberName="TopicName">
      <MemberSignature Language="C#" Value="public string TopicName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.TopicName" />
      <MemberSignature Language="VB.NET" Value="Public Property TopicName As String" />
      <MemberSignature Language="F#" Value="member this.TopicName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.TopicName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.topicName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Service Bus トピックの名前を設定します。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>