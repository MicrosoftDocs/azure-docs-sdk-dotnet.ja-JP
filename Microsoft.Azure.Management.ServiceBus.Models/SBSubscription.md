<Type Name="SBSubscription" FullName="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription">
  <TypeSignature Language="C#" Value="public class SBSubscription : Microsoft.Azure.Management.ServiceBus.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SBSubscription extends Microsoft.Azure.Management.ServiceBus.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription" />
  <TypeSignature Language="VB.NET" Value="Public Class SBSubscription&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type SBSubscription = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ServiceBus.Models.Resource</BaseTypeName>
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
      <MemberSignature Language="C#" Value="public SBSubscription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SBSubscription クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBSubscription (string id = null, string name = null, string type = null, Nullable&lt;long&gt; messageCount = null, Nullable&lt;DateTime&gt; createdAt = null, Nullable&lt;DateTime&gt; accessedAt = null, Nullable&lt;DateTime&gt; updatedAt = null, Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails countDetails = null, Nullable&lt;TimeSpan&gt; lockDuration = null, Nullable&lt;bool&gt; requiresSession = null, Nullable&lt;TimeSpan&gt; defaultMessageTimeToLive = null, Nullable&lt;bool&gt; deadLetteringOnMessageExpiration = null, Nullable&lt;TimeSpan&gt; duplicateDetectionHistoryTimeWindow = null, Nullable&lt;int&gt; maxDeliveryCount = null, Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; status = null, Nullable&lt;bool&gt; enableBatchedOperations = null, Nullable&lt;TimeSpan&gt; autoDeleteOnIdle = null, string forwardTo = null, string forwardDeadLetteredMessagesTo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype System.Nullable`1&lt;int64&gt; messageCount, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; accessedAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updatedAt, class Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails countDetails, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; lockDuration, valuetype System.Nullable`1&lt;bool&gt; requiresSession, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; defaultMessageTimeToLive, valuetype System.Nullable`1&lt;bool&gt; deadLetteringOnMessageExpiration, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; duplicateDetectionHistoryTimeWindow, valuetype System.Nullable`1&lt;int32&gt; maxDeliveryCount, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; status, valuetype System.Nullable`1&lt;bool&gt; enableBatchedOperations, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoDeleteOnIdle, string forwardTo, string forwardDeadLetteredMessagesTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.#ctor(System.String,System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails,System.Nullable{System.TimeSpan},System.Nullable{System.Boolean},System.Nullable{System.TimeSpan},System.Nullable{System.Boolean},System.Nullable{System.TimeSpan},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.ServiceBus.Models.EntityStatus},System.Nullable{System.Boolean},System.Nullable{System.TimeSpan},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional messageCount As Nullable(Of Long) = null, Optional createdAt As Nullable(Of DateTime) = null, Optional accessedAt As Nullable(Of DateTime) = null, Optional updatedAt As Nullable(Of DateTime) = null, Optional countDetails As MessageCountDetails = null, Optional lockDuration As Nullable(Of TimeSpan) = null, Optional requiresSession As Nullable(Of Boolean) = null, Optional defaultMessageTimeToLive As Nullable(Of TimeSpan) = null, Optional deadLetteringOnMessageExpiration As Nullable(Of Boolean) = null, Optional duplicateDetectionHistoryTimeWindow As Nullable(Of TimeSpan) = null, Optional maxDeliveryCount As Nullable(Of Integer) = null, Optional status As Nullable(Of EntityStatus) = null, Optional enableBatchedOperations As Nullable(Of Boolean) = null, Optional autoDeleteOnIdle As Nullable(Of TimeSpan) = null, Optional forwardTo As String = null, Optional forwardDeadLetteredMessagesTo As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.SBSubscription : string * string * string * Nullable&lt;int64&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails * Nullable&lt;TimeSpan&gt; * Nullable&lt;bool&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;bool&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; * Nullable&lt;bool&gt; * Nullable&lt;TimeSpan&gt; * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBSubscription" Usage="new Microsoft.Azure.Management.ServiceBus.Models.SBSubscription (id, name, type, messageCount, createdAt, accessedAt, updatedAt, countDetails, lockDuration, requiresSession, defaultMessageTimeToLive, deadLetteringOnMessageExpiration, duplicateDetectionHistoryTimeWindow, maxDeliveryCount, status, enableBatchedOperations, autoDeleteOnIdle, forwardTo, forwardDeadLetteredMessagesTo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="messageCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="accessedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updatedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="countDetails" Type="Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails" />
        <Parameter Name="lockDuration" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="requiresSession" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="defaultMessageTimeToLive" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="deadLetteringOnMessageExpiration" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="duplicateDetectionHistoryTimeWindow" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxDeliveryCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt;" />
        <Parameter Name="enableBatchedOperations" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="autoDeleteOnIdle" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="forwardTo" Type="System.String" />
        <Parameter Name="forwardDeadLetteredMessagesTo" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソース Id</param>
        <param name="name">リソース名</param>
        <param name="type">リソースの種類</param>
        <param name="messageCount">メッセージの数。</param>
        <param name="createdAt">メッセージが作成された正確な時刻です。</param>
        <param name="accessedAt">前回のでは、このサブスクリプションの受信要求が発生しました。</param>
        <param name="updatedAt">メッセージが更新された正確な時刻です。</param>
        <param name="countDetails">メッセージ数の詳細</param>
        <param name="lockDuration">サブスクリプションの ISO 8061 ロック期間 timespan です。 既定値は 1 分です。</param>
        <param name="requiresSession">サブスクリプションがセッションの概念をサポートしているかを示す値。</param>
        <param name="defaultMessageTimeToLive">ISO 8061 既定の有効期限値 timespan をメッセージです。 これは、その後、メッセージは期限切れ、メッセージが Service Bus に送信されたときから開始期間です。 これは、TimeToLive がメッセージ自体に設定されていない場合に使用される既定値です。</param>
        <param name="deadLetteringOnMessageExpiration">メッセージの有効期限が切れるときに、サブスクリプションで配信不能サポートを持つかどうかを示す値です。</param>
        <param name="duplicateDetectionHistoryTimeWindow">ISO 8601 timeSpan 構造体、重複データ検出の履歴の期間を定義します。 既定値は、10 分です。</param>
        <param name="maxDeliveryCount">最大配信数。</param>
        <param name="status">メッセージング エンティティの状態の値を列挙します。 使用可能な値が含まれます: 'Active'、'Disabled'、'復元中'、'SendDisabled'、'ReceiveDisabled'、'作成中'、'削除'、'名前変更'、'Unknown'</param>
        <param name="enableBatchedOperations">サーバー側のバッチ操作が有効になっているかどうかを示す値です。</param>
        <param name="autoDeleteOnIdle">ISO 8061 timeSpan アイドル間隔が、トピックが自動的に削除します。 最小時間は、5 分です。</param>
        <param name="forwardTo">メッセージを転送するキュー/トピック名</param>
        <param name="forwardDeadLetteredMessagesTo">配信不能メッセージを転送キューまたはトピック名</param>
        <summary>
            SBSubscription クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.AutoDeleteOnIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoDeleteOnIdle")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトピックは自動的に削除するまで ISO 8061 timeSpan アイドル間隔を設定します。 最小時間は、5 分です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails CountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails CountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.CountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.CountDetails : Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.CountDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.countDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージ カウントの詳細を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            メッセージが作成された正確な時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetteringOnMessageExpiration">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DeadLetteringOnMessageExpiration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DeadLetteringOnMessageExpiration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.DeadLetteringOnMessageExpiration" />
      <MemberSignature Language="VB.NET" Value="Public Property DeadLetteringOnMessageExpiration As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DeadLetteringOnMessageExpiration : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.DeadLetteringOnMessageExpiration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.DefaultMessageTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultMessageTimeToLive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または有効な値に対するメッセージ timespan を ISO 8061 既定を設定します。 これは、その後、メッセージは期限切れ、メッセージが Service Bus に送信されたときから開始期間です。 これは、TimeToLive がメッセージ自体に設定されていない場合に使用される既定値です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateDetectionHistoryTimeWindow">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; DuplicateDetectionHistoryTimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property DuplicateDetectionHistoryTimeWindow As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.DuplicateDetectionHistoryTimeWindow : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.DuplicateDetectionHistoryTimeWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.duplicateDetectionHistoryTimeWindow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または重複データ検出の履歴の期間を定義する ISO 8601 timeSpan 構造体を設定します。 既定値は、10 分です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBatchedOperations">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableBatchedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableBatchedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.EnableBatchedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBatchedOperations As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableBatchedOperations : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.EnableBatchedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Member MemberName="ForwardDeadLetteredMessagesTo">
      <MemberSignature Language="C#" Value="public string ForwardDeadLetteredMessagesTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardDeadLetteredMessagesTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardDeadLetteredMessagesTo : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.ForwardDeadLetteredMessagesTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.forwardDeadLetteredMessagesTo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            キュー/トピック名配信不能メッセージの転送を取得または設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardTo">
      <MemberSignature Language="C#" Value="public string ForwardTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.ForwardTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardTo : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.ForwardTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.forwardTo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            キュー/トピック名、メッセージの転送を取得または設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; LockDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; LockDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.LockDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property LockDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.LockDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.LockDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lockDuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブスクリプションの ISO 8061 ロック期間 timespan を設定します。
            既定値は 1 分です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDeliveryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.MaxDeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDeliveryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.MaxDeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.MessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MessageCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.MessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.RequiresSession" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresSession As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequiresSession : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.RequiresSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of EntityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、メッセージング エンティティの状態の値を列挙します。 使用可能な値が含まれます: 'Active'、'Disabled'、'復元中'、'SendDisabled'、'ReceiveDisabled'、'作成中'、'削除'、'名前変更'、'Unknown'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            メッセージが更新された正確な時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>