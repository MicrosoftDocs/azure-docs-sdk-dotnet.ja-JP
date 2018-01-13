<Type Name="SBTopic" FullName="Microsoft.Azure.Management.ServiceBus.Models.SBTopic">
  <TypeSignature Language="C#" Value="public class SBTopic : Microsoft.Azure.Management.ServiceBus.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SBTopic extends Microsoft.Azure.Management.ServiceBus.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.SBTopic" />
  <TypeSignature Language="VB.NET" Value="Public Class SBTopic&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type SBTopic = class&#xA;    inherit Resource" />
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
            トピックのリソースの説明。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBTopic ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SBTopic クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBTopic (string id = null, string name = null, string type = null, Nullable&lt;long&gt; sizeInBytes = null, Nullable&lt;DateTime&gt; createdAt = null, Nullable&lt;DateTime&gt; updatedAt = null, Nullable&lt;DateTime&gt; accessedAt = null, Nullable&lt;int&gt; subscriptionCount = null, Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails countDetails = null, Nullable&lt;TimeSpan&gt; defaultMessageTimeToLive = null, Nullable&lt;int&gt; maxSizeInMegabytes = null, Nullable&lt;bool&gt; requiresDuplicateDetection = null, Nullable&lt;TimeSpan&gt; duplicateDetectionHistoryTimeWindow = null, Nullable&lt;bool&gt; enableBatchedOperations = null, Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; status = null, Nullable&lt;bool&gt; supportOrdering = null, Nullable&lt;TimeSpan&gt; autoDeleteOnIdle = null, Nullable&lt;bool&gt; enablePartitioning = null, Nullable&lt;bool&gt; enableExpress = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype System.Nullable`1&lt;int64&gt; sizeInBytes, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updatedAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; accessedAt, valuetype System.Nullable`1&lt;int32&gt; subscriptionCount, class Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails countDetails, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; defaultMessageTimeToLive, valuetype System.Nullable`1&lt;int32&gt; maxSizeInMegabytes, valuetype System.Nullable`1&lt;bool&gt; requiresDuplicateDetection, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; duplicateDetectionHistoryTimeWindow, valuetype System.Nullable`1&lt;bool&gt; enableBatchedOperations, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; status, valuetype System.Nullable`1&lt;bool&gt; supportOrdering, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoDeleteOnIdle, valuetype System.Nullable`1&lt;bool&gt; enablePartitioning, valuetype System.Nullable`1&lt;bool&gt; enableExpress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.#ctor(System.String,System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Int32},Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails,System.Nullable{System.TimeSpan},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{System.TimeSpan},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.ServiceBus.Models.EntityStatus},System.Nullable{System.Boolean},System.Nullable{System.TimeSpan},System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional sizeInBytes As Nullable(Of Long) = null, Optional createdAt As Nullable(Of DateTime) = null, Optional updatedAt As Nullable(Of DateTime) = null, Optional accessedAt As Nullable(Of DateTime) = null, Optional subscriptionCount As Nullable(Of Integer) = null, Optional countDetails As MessageCountDetails = null, Optional defaultMessageTimeToLive As Nullable(Of TimeSpan) = null, Optional maxSizeInMegabytes As Nullable(Of Integer) = null, Optional requiresDuplicateDetection As Nullable(Of Boolean) = null, Optional duplicateDetectionHistoryTimeWindow As Nullable(Of TimeSpan) = null, Optional enableBatchedOperations As Nullable(Of Boolean) = null, Optional status As Nullable(Of EntityStatus) = null, Optional supportOrdering As Nullable(Of Boolean) = null, Optional autoDeleteOnIdle As Nullable(Of TimeSpan) = null, Optional enablePartitioning As Nullable(Of Boolean) = null, Optional enableExpress As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.SBTopic : string * string * string * Nullable&lt;int64&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; * Nullable&lt;bool&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBTopic" Usage="new Microsoft.Azure.Management.ServiceBus.Models.SBTopic (id, name, type, sizeInBytes, createdAt, updatedAt, accessedAt, subscriptionCount, countDetails, defaultMessageTimeToLive, maxSizeInMegabytes, requiresDuplicateDetection, duplicateDetectionHistoryTimeWindow, enableBatchedOperations, status, supportOrdering, autoDeleteOnIdle, enablePartitioning, enableExpress)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="sizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updatedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="accessedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="subscriptionCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="countDetails" Type="Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails" />
        <Parameter Name="defaultMessageTimeToLive" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxSizeInMegabytes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requiresDuplicateDetection" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="duplicateDetectionHistoryTimeWindow" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enableBatchedOperations" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt;" />
        <Parameter Name="supportOrdering" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="autoDeleteOnIdle" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enablePartitioning" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableExpress" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソース Id</param>
        <param name="name">リソース名</param>
        <param name="type">リソースの種類</param>
        <param name="sizeInBytes">(バイト単位) のトピックのサイズ。</param>
        <param name="createdAt">メッセージが作成された正確な時刻です。</param>
        <param name="updatedAt">メッセージが更新された正確な時刻です。</param>
        <param name="accessedAt">最後に、メッセージが送信された、または、このトピックの内容を要求を受信しました。</param>
        <param name="subscriptionCount">サブスクリプションの数。</param>
        <param name="countDetails">メッセージ カウントの詳細</param>
        <param name="defaultMessageTimeToLive">ISO 8601 既定の有効期限値 timespan をメッセージです。 これは、その後、メッセージは期限切れ、メッセージが Service Bus に送信されたときから開始期間です。 これは、TimeToLive がメッセージ自体に設定されていない場合に使用される既定値です。</param>
        <param name="maxSizeInMegabytes">トピック用に割り当てるメモリのサイズをメガバイト単位でトピックの最大サイズ。
            既定値は 1024 です。</param>
        <param name="requiresDuplicateDetection">このトピックの内容が重複検出が必要かどうかを示す値。</param>
        <param name="duplicateDetectionHistoryTimeWindow">ISO8601 timespan 構造体、重複データ検出の履歴の期間を定義します。 既定値は、10 分です。</param>
        <param name="enableBatchedOperations">サーバー側のバッチ操作が有効になっているかどうかを示す値です。</param>
        <param name="status">メッセージング エンティティの状態の値を列挙します。 使用可能な値が含まれます: 'Active'、'Disabled'、'復元中'、'SendDisabled'、'ReceiveDisabled'、'作成中'、'削除'、'名前変更'、'Unknown'</param>
        <param name="supportOrdering">トピックが順序付けをサポートしているかどうかを示す値です。</param>
        <param name="autoDeleteOnIdle">ISO 8601 timespan アイドル間隔までのトピックは自動的に削除します。 最小時間は、5 分です。</param>
        <param name="enablePartitioning">複数のメッセージ ブローカーにわたって分割するトピックが有効になっているかどうかを示す値です。</param>
        <param name="enableExpress">エクスプレス エンティティが有効になっているかどうかを示す値です。 高速のトピックでは、永続的ストレージに書き込む前に一時的にメモリにメッセージを保持します。</param>
        <summary>
            SBTopic クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBTopic.AccessedAt" />
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
            このトピックのメッセージが送信された最終時刻を取得または要求を受信しました。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBTopic.AutoDeleteOnIdle" />
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
            取得またはトピックは自動的に削除するまで、ISO 8601 timespan アイドル間隔を設定します。 最小時間は、5 分です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails CountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails CountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.CountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.CountDetails : Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBTopic.CountDetails" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBTopic.CreatedAt" />
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
    <Member MemberName="DefaultMessageTimeToLive">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBTopic.DefaultMessageTimeToLive" />
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
            取得または有効な値に対するメッセージ timespan を ISO 8601 の既定値を設定します。 これは、その後、メッセージは期限切れ、メッセージが Service Bus に送信されたときから開始期間です。 これは、TimeToLive がメッセージ自体に設定されていない場合に使用される既定値です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateDetectionHistoryTimeWindow">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; DuplicateDetectionHistoryTimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property DuplicateDetectionHistoryTimeWindow As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.DuplicateDetectionHistoryTimeWindow : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBTopic.DuplicateDetectionHistoryTimeWindow" />
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
            取得または重複データ検出の履歴の期間を定義する ISO8601 timespan 構造体を設定します。 既定値は、10 分です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBatchedOperations">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableBatchedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableBatchedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.EnableBatchedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBatchedOperations As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableBatchedOperations : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBTopic.EnableBatchedOperations" />
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
    <Member MemberName="EnableExpress">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableExpress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableExpress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.EnableExpress" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableExpress As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableExpress : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBTopic.EnableExpress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.EnablePartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Property EnablePartitioning As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnablePartitioning : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBTopic.EnablePartitioning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxSizeInMegabytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxSizeInMegabytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.MaxSizeInMegabytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeInMegabytes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInMegabytes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBTopic.MaxSizeInMegabytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxSizeInMegabytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトピックに割り当てられたメモリのサイズはメガバイト単位で、このトピックの最大サイズを設定します。 既定値は 1024 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresDuplicateDetection">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequiresDuplicateDetection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequiresDuplicateDetection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.RequiresDuplicateDetection" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresDuplicateDetection As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequiresDuplicateDetection : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBTopic.RequiresDuplicateDetection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBTopic.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of EntityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBTopic.Status" />
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
    <Member MemberName="SubscriptionCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SubscriptionCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SubscriptionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.SubscriptionCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SubscriptionCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBTopic.SubscriptionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.SupportOrdering" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportOrdering As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SupportOrdering : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBTopic.SupportOrdering" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBTopic.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBTopic.UpdatedAt" />
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