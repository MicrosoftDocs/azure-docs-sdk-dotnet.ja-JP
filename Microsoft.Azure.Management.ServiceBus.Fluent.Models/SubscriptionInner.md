<Type Name="SubscriptionInner" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner">
  <TypeSignature Language="C#" Value="public class SubscriptionInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubscriptionInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner" />
  <TypeSignature Language="VB.NET" Value="Public Class SubscriptionInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type SubscriptionInner = class&#xA;    inherit Resource" />
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
            サブスクリプション リソースの説明です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SubscriptionInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;DateTime&gt; accessedAt = null, string autoDeleteOnIdle = null, Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails countDetails = null, Nullable&lt;DateTime&gt; createdAt = null, string defaultMessageTimeToLive = null, Nullable&lt;bool&gt; deadLetteringOnFilterEvaluationExceptions = null, Nullable&lt;bool&gt; deadLetteringOnMessageExpiration = null, Nullable&lt;bool&gt; enableBatchedOperations = null, string lockDuration = null, Nullable&lt;int&gt; maxDeliveryCount = null, Nullable&lt;long&gt; messageCount = null, Nullable&lt;bool&gt; requiresSession = null, Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt; status = null, Nullable&lt;DateTime&gt; updatedAt = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; accessedAt, string autoDeleteOnIdle, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails countDetails, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, string defaultMessageTimeToLive, valuetype System.Nullable`1&lt;bool&gt; deadLetteringOnFilterEvaluationExceptions, valuetype System.Nullable`1&lt;bool&gt; deadLetteringOnMessageExpiration, valuetype System.Nullable`1&lt;bool&gt; enableBatchedOperations, string lockDuration, valuetype System.Nullable`1&lt;int32&gt; maxDeliveryCount, valuetype System.Nullable`1&lt;int64&gt; messageCount, valuetype System.Nullable`1&lt;bool&gt; requiresSession, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt; status, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updatedAt) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails,System.Nullable{System.DateTime},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional accessedAt As Nullable(Of DateTime) = null, Optional autoDeleteOnIdle As String = null, Optional countDetails As MessageCountDetails = null, Optional createdAt As Nullable(Of DateTime) = null, Optional defaultMessageTimeToLive As String = null, Optional deadLetteringOnFilterEvaluationExceptions As Nullable(Of Boolean) = null, Optional deadLetteringOnMessageExpiration As Nullable(Of Boolean) = null, Optional enableBatchedOperations As Nullable(Of Boolean) = null, Optional lockDuration As String = null, Optional maxDeliveryCount As Nullable(Of Integer) = null, Optional messageCount As Nullable(Of Long) = null, Optional requiresSession As Nullable(Of Boolean) = null, Optional status As Nullable(Of EntityStatus) = null, Optional updatedAt As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails * Nullable&lt;DateTime&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner" Usage="new Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner (location, id, name, type, tags, accessedAt, autoDeleteOnIdle, countDetails, createdAt, defaultMessageTimeToLive, deadLetteringOnFilterEvaluationExceptions, deadLetteringOnMessageExpiration, enableBatchedOperations, lockDuration, maxDeliveryCount, messageCount, requiresSession, status, updatedAt)" />
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
        <Parameter Name="countDetails" Type="Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="defaultMessageTimeToLive" Type="System.String" />
        <Parameter Name="deadLetteringOnFilterEvaluationExceptions" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="deadLetteringOnMessageExpiration" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableBatchedOperations" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="lockDuration" Type="System.String" />
        <Parameter Name="maxDeliveryCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="messageCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="requiresSession" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt;" />
        <Parameter Name="updatedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="accessedAt">前回のでは、このサブスクリプションの受信要求が発生しました。</param>
        <param name="autoDeleteOnIdle">TimeSpan トピックは自動的に削除するまでのアイドル間隔です。 最小時間は、5 分です。 Loc 期間 https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx.、サービスは、c# 標準 TimeSpan 書式指定を受け入れます
            形式は ' ください。このプロパティの値を HH:MM:SS' と既定値は 10675199 日です。</param>
        <param name="countDetails">To be added.</param>
        <param name="createdAt">サブスクリプションが作成された正確な時刻です。</param>
        <param name="defaultMessageTimeToLive">有効期限の値を既定のメッセージ時間。 これは、その後、メッセージは期限切れ、メッセージが Service Bus に送信されたときから開始期間です。 これは、TimeToLive がメッセージ自体に設定されていない場合に使用される既定値です。
            Loc 期間 https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx.、サービスは、c# 標準 TimeSpan 書式指定を受け入れます
            形式は ' ください。このプロパティの値を HH:MM:SS' と既定値は 10675199 日です。</param>
        <param name="deadLetteringOnFilterEvaluationExceptions">サブスクリプションがフィルター評価例外ではサポート停止している文字を持つかどうかを示す値です。</param>
        <param name="deadLetteringOnMessageExpiration">メッセージの有効期限が切れるときに、サブスクリプションで配信不能サポートを持つかどうかを示す値です。</param>
        <param name="enableBatchedOperations">サーバー側のバッチ操作が有効になっているかどうかを示す値です。</param>
        <param name="lockDuration">ロック期間は、サブスクリプションを期間します。 サービスが、c# 標準 TimeSpan 書式指定の loc 期間 https://msdn.microsoft.com/en-us/library/ee372286 (v=vs.110).aspx を受け入れます</param>
        <param name="maxDeliveryCount">最大配信数。</param>
        <param name="messageCount">メッセージの数。</param>
        <param name="requiresSession">サブスクリプションがセッションの概念をサポートしているかを示す値。</param>
        <param name="status">メッセージング エンティティの状態の値を列挙します。 使用可能な値が含まれます: 'Active'、'作成中'、'削除'、'Disabled'、'ReceiveDisabled'、'名前'、'復元'、'SendDisabled'、'Unknown'</param>
        <param name="updatedAt">サブスクリプションが更新された正確な時刻です。</param>
        <summary>
            SubscriptionInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.AccessedAt" />
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
            このサブスクリプションの受信要求があった最後の時間を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public string AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As String" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.AutoDeleteOnIdle" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.CountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.CountDetails : Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.CountDetails" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.CreatedAt" />
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
            サブスクリプションが作成された正確な時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetteringOnFilterEvaluationExceptions">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DeadLetteringOnFilterEvaluationExceptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DeadLetteringOnFilterEvaluationExceptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.DeadLetteringOnFilterEvaluationExceptions" />
      <MemberSignature Language="VB.NET" Value="Public Property DeadLetteringOnFilterEvaluationExceptions As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DeadLetteringOnFilterEvaluationExceptions : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.DeadLetteringOnFilterEvaluationExceptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deadLetteringOnFilterEvaluationExceptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブスクリプションがフィルター評価例外ではサポート停止している文字を持つかどうかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetteringOnMessageExpiration">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DeadLetteringOnMessageExpiration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DeadLetteringOnMessageExpiration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.DeadLetteringOnMessageExpiration" />
      <MemberSignature Language="VB.NET" Value="Public Property DeadLetteringOnMessageExpiration As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DeadLetteringOnMessageExpiration : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.DeadLetteringOnMessageExpiration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deadLetteringOnMessageExpiration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメッセージの有効期限が切れるときに、サブスクリプションで配信不能サポートを持つかどうかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTimeToLive">
      <MemberSignature Language="C#" Value="public string DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As String" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.DefaultMessageTimeToLive" />
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
    <Member MemberName="EnableBatchedOperations">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableBatchedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableBatchedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.EnableBatchedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBatchedOperations As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableBatchedOperations : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.EnableBatchedOperations" />
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
    <Member MemberName="LockDuration">
      <MemberSignature Language="C#" Value="public string LockDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LockDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.LockDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property LockDuration As String" />
      <MemberSignature Language="F#" Value="member this.LockDuration : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.LockDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lockDuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、ロック期間の期間サブスクリプション。 サービスが、c# 標準 TimeSpan 書式指定の loc 期間 https://msdn.microsoft.com/en-us/library/ee372286 (v=vs.110).aspx を受け入れます
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDeliveryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.MaxDeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDeliveryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.MaxDeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxDeliveryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または最大配信回数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.MessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MessageCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.MessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.messageCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージの数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresSession">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequiresSession { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequiresSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.RequiresSession" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresSession As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequiresSession : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.RequiresSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requiresSession")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブスクリプションがセッションの概念をサポートしているかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of EntityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.Status" />
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
            取得または設定は、メッセージング エンティティの状態の値を列挙します。 使用可能な値が含まれます: 'Active'、'作成中'、'削除'、'Disabled'、'ReceiveDisabled'、'名前'、'復元'、'SendDisabled'、'Unknown'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner.UpdatedAt" />
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
            サブスクリプションが更新された正確な時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>