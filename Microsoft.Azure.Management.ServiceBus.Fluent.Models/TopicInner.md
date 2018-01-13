<Type Name="TopicInner" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner">
  <TypeSignature Language="C#" Value="public class TopicInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TopicInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner" />
  <TypeSignature Language="VB.NET" Value="Public Class TopicInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type TopicInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            トピックのリソースの説明。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            TopicInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;DateTime&gt; accessedAt = null, string autoDeleteOnIdle = null, Nullable&lt;DateTime&gt; createdAt = null, Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails countDetails = null, string defaultMessageTimeToLive = null, string duplicateDetectionHistoryTimeWindow = null, Nullable&lt;bool&gt; enableBatchedOperations = null, Nullable&lt;bool&gt; enableExpress = null, Nullable&lt;bool&gt; enablePartitioning = null, Nullable&lt;long&gt; maxSizeInMegabytes = null, Nullable&lt;bool&gt; requiresDuplicateDetection = null, Nullable&lt;long&gt; sizeInBytes = null, Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt; status = null, Nullable&lt;int&gt; subscriptionCount = null, Nullable&lt;bool&gt; supportOrdering = null, Nullable&lt;DateTime&gt; updatedAt = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; accessedAt, string autoDeleteOnIdle, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails countDetails, string defaultMessageTimeToLive, string duplicateDetectionHistoryTimeWindow, valuetype System.Nullable`1&lt;bool&gt; enableBatchedOperations, valuetype System.Nullable`1&lt;bool&gt; enableExpress, valuetype System.Nullable`1&lt;bool&gt; enablePartitioning, valuetype System.Nullable`1&lt;int64&gt; maxSizeInMegabytes, valuetype System.Nullable`1&lt;bool&gt; requiresDuplicateDetection, valuetype System.Nullable`1&lt;int64&gt; sizeInBytes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt; status, valuetype System.Nullable`1&lt;int32&gt; subscriptionCount, valuetype System.Nullable`1&lt;bool&gt; supportOrdering, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updatedAt) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.DateTime},System.String,System.Nullable{System.DateTime},Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Int64},System.Nullable{System.Boolean},System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional accessedAt As Nullable(Of DateTime) = null, Optional autoDeleteOnIdle As String = null, Optional createdAt As Nullable(Of DateTime) = null, Optional countDetails As MessageCountDetails = null, Optional defaultMessageTimeToLive As String = null, Optional duplicateDetectionHistoryTimeWindow As String = null, Optional enableBatchedOperations As Nullable(Of Boolean) = null, Optional enableExpress As Nullable(Of Boolean) = null, Optional enablePartitioning As Nullable(Of Boolean) = null, Optional maxSizeInMegabytes As Nullable(Of Long) = null, Optional requiresDuplicateDetection As Nullable(Of Boolean) = null, Optional sizeInBytes As Nullable(Of Long) = null, Optional status As Nullable(Of EntityStatus) = null, Optional subscriptionCount As Nullable(Of Integer) = null, Optional supportOrdering As Nullable(Of Boolean) = null, Optional updatedAt As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;int64&gt; * Nullable&lt;bool&gt; * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner" Usage="new Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner (location, id, name, type, tags, accessedAt, autoDeleteOnIdle, createdAt, countDetails, defaultMessageTimeToLive, duplicateDetectionHistoryTimeWindow, enableBatchedOperations, enableExpress, enablePartitioning, maxSizeInMegabytes, requiresDuplicateDetection, sizeInBytes, status, subscriptionCount, supportOrdering, updatedAt)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="autoDeleteOnIdle" Type="System.String" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="countDetails" Type="Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails" />
        <Parameter Name="defaultMessageTimeToLive" Type="System.String" />
        <Parameter Name="duplicateDetectionHistoryTimeWindow" Type="System.String" />
        <Parameter Name="enableBatchedOperations" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableExpress" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enablePartitioning" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="maxSizeInMegabytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="requiresDuplicateDetection" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="sizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt;" />
        <Parameter Name="subscriptionCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="supportOrdering" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="updatedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="accessedAt">最後に、メッセージが送信された、または、このトピックの内容を要求を受信しました。</param>
        <param name="autoDeleteOnIdle">TimeSpan トピックは自動的に削除するまでのアイドル間隔です。 最小時間は、5 分です。 Loc 期間 https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx.、サービスは、c# 標準 TimeSpan 書式指定を受け入れます
            形式は ' ください。このプロパティの値を HH:MM:SS' と既定値は 10675199 日です。</param>
        <param name="createdAt">正確な時間、Tpoic が作成されました。</param>
        <param name="countDetails">To be added.</param>
        <param name="defaultMessageTimeToLive">有効期限の値を既定のメッセージ時間。 これは、その後、メッセージは期限切れ、メッセージが Service Bus に送信されたときから開始期間です。 これは、TimeToLive がメッセージ自体に設定されていない場合に使用される既定値です。
            Loc 期間 https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx.、サービスは、c# 標準 TimeSpan 書式指定を受け入れます
            形式は ' ください。このプロパティの値を HH:MM:SS' と既定値は 10675199 日です。</param>
        <param name="duplicateDetectionHistoryTimeWindow">重複データ検出の履歴の期間を定義する TimeSpan 構造体。 既定値は、10 分です。 Loc 期間 https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx.、サービスは、c# 標準 TimeSpan 書式指定を受け入れます
            形式は ' ください。このプロパティの値を HH:MM:SS' と既定値は 10675199 日です。</param>
        <param name="enableBatchedOperations">サーバー側のバッチ操作が有効になっているかどうかを示す値です。</param>
        <param name="enableExpress">エクスプレス エンティティが有効になっているかどうかを示す値です。 高速のトピックでは、永続的ストレージに書き込む前に一時的にメモリにメッセージを保持します。</param>
        <param name="enablePartitioning">複数のメッセージ ブローカーにわたって分割するトピックが有効になっているかどうかを示す値です。</param>
        <param name="maxSizeInMegabytes">トピック用に割り当てるメモリのサイズをメガバイト単位でトピックの最大サイズ。</param>
        <param name="requiresDuplicateDetection">このトピックの内容が重複検出が必要かどうかを示す値。</param>
        <param name="sizeInBytes">(バイト単位) のトピックのサイズ。</param>
        <param name="status">メッセージング エンティティの状態の値を列挙します。 使用可能な値が含まれます: 'Active'、'作成中'、'削除'、'Disabled'、'ReceiveDisabled'、'名前'、'復元'、'SendDisabled'、'Unknown'</param>
        <param name="subscriptionCount">サブスクリプションの数。</param>
        <param name="supportOrdering">トピックが順序付けをサポートしているかどうかを示す値です。</param>
        <param name="updatedAt">トピックが更新された正確な時刻です。</param>
        <summary>
            TopicInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このトピックのメッセージが送信された最終時刻を取得または要求を受信しました。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public string AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As String" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.AutoDeleteOnIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoDeleteOnIdle")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトピックは自動的に削除するまで timeSpan アイドル間隔を設定します。 最小時間は、5 分です。 Loc 期間 https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx.、サービスは、c# 標準 TimeSpan 書式指定を受け入れます
            形式は ' ください。このプロパティの値を HH:MM:SS' と既定値は 10675199 日です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails CountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails CountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.CountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.CountDetails : Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.CountDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.countDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tpoic が作成された正確な時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTimeToLive">
      <MemberSignature Language="C#" Value="public string DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As String" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.DefaultMessageTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultMessageTimeToLive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または既定のメッセージの時刻を有効期限値に設定します。 これは、その後、メッセージは期限切れ、メッセージが Service Bus に送信されたときから開始期間です。 これは、TimeToLive がメッセージ自体に設定されていない場合に使用される既定値です。 Loc 期間 https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx.、サービスは、c# 標準 TimeSpan 書式指定を受け入れます
            形式は ' ください。このプロパティの値を HH:MM:SS' と既定値は 10675199 日です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateDetectionHistoryTimeWindow">
      <MemberSignature Language="C#" Value="public string DuplicateDetectionHistoryTimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property DuplicateDetectionHistoryTimeWindow As String" />
      <MemberSignature Language="F#" Value="member this.DuplicateDetectionHistoryTimeWindow : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.DuplicateDetectionHistoryTimeWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.duplicateDetectionHistoryTimeWindow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または重複データ検出の履歴の期間を定義する timeSpan 構造体を設定します。 既定値は、10 分です。 Loc 期間 https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx.、サービスは、c# 標準 TimeSpan 書式指定を受け入れます
            形式は ' ください。このプロパティの値を HH:MM:SS' と既定値は 10675199 日です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBatchedOperations">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableBatchedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableBatchedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.EnableBatchedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBatchedOperations As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableBatchedOperations : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.EnableBatchedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableBatchedOperations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサーバー側のバッチ操作が有効になっているかどうかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableExpress">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableExpress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableExpress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.EnableExpress" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableExpress As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableExpress : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.EnableExpress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableExpress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Express のエンティティが有効になっているかどうかを示す値を設定します。 高速のトピックでは、永続的ストレージに書き込む前に一時的にメモリにメッセージを保持します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnablePartitioning">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnablePartitioning { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnablePartitioning" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.EnablePartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Property EnablePartitioning As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnablePartitioning : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.EnablePartitioning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enablePartitioning")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または複数のメッセージ ブローカーにわたって分割するトピックが有効になっているかどうかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeInMegabytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxSizeInMegabytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxSizeInMegabytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.MaxSizeInMegabytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeInMegabytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInMegabytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.MaxSizeInMegabytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxSizeInMegabytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトピックに割り当てられたメモリのサイズはメガバイト単位で、このトピックの最大サイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresDuplicateDetection">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequiresDuplicateDetection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequiresDuplicateDetection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.RequiresDuplicateDetection" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresDuplicateDetection As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequiresDuplicateDetection : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.RequiresDuplicateDetection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requiresDuplicateDetection")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのトピックの内容が重複検出が必要かどうかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sizeInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            」トピックのサイズをバイト単位で取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of EntityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得では、メッセージング エンティティの状態の値を列挙します。 使用可能な値が含まれます: 'Active'、'作成中'、'削除'、'Disabled'、'ReceiveDisabled'、'名前'、'復元'、'SendDisabled'、'Unknown'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SubscriptionCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SubscriptionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.SubscriptionCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SubscriptionCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.SubscriptionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subscriptionCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サブスクリプションの数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportOrdering">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SupportOrdering { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SupportOrdering" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.SupportOrdering" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportOrdering As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SupportOrdering : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.SupportOrdering" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.supportOrdering")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトピックが順序付けをサポートするかどうかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.updatedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            トピックが更新された正確な時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>