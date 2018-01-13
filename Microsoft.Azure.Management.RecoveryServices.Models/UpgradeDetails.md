<Type Name="UpgradeDetails" FullName="Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails">
  <TypeSignature Language="C#" Value="public class UpgradeDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UpgradeDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class UpgradeDetails" />
  <TypeSignature Language="F#" Value="type UpgradeDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            資格情報コンテナーをアップグレードするための詳細。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpgradeDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            UpgradeDetails クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpgradeDetails (string operationId = null, Nullable&lt;DateTime&gt; startTimeUtc = null, Nullable&lt;DateTime&gt; lastUpdatedTimeUtc = null, Nullable&lt;DateTime&gt; endTimeUtc = null, string status = null, string message = null, string triggerType = null, string upgradedResourceId = null, string previousResourceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string operationId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTimeUtc, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastUpdatedTimeUtc, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTimeUtc, string status, string message, string triggerType, string upgradedResourceId, string previousResourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.#ctor(System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional operationId As String = null, Optional startTimeUtc As Nullable(Of DateTime) = null, Optional lastUpdatedTimeUtc As Nullable(Of DateTime) = null, Optional endTimeUtc As Nullable(Of DateTime) = null, Optional status As String = null, Optional message As String = null, Optional triggerType As String = null, Optional upgradedResourceId As String = null, Optional previousResourceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails : string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails (operationId, startTimeUtc, lastUpdatedTimeUtc, endTimeUtc, status, message, triggerType, upgradedResourceId, previousResourceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="startTimeUtc" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastUpdatedTimeUtc" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTimeUtc" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="triggerType" Type="System.String" />
        <Parameter Name="upgradedResourceId" Type="System.String" />
        <Parameter Name="previousResourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operationId">コンテナーのアップグレード操作の ID です。</param>
        <param name="startTimeUtc">アップグレード操作が開始された UTC 時刻です。</param>
        <param name="lastUpdatedTimeUtc">アップグレード操作の状態が最後に更新された UTC 時間です。</param>
        <param name="endTimeUtc">アップグレード操作の終了時刻が UTC 時刻です。</param>
        <param name="status">コンテナーのアップグレード操作の状態です。
            使用可能な値が含まれます: 'Unknown'、'処理中'、'アップグレード'、'失敗'</param>
        <param name="message">アップグレードの操作に関する情報を含むユーザー メッセージです。</param>
        <param name="triggerType">資格情報コンテナー アップ グレードがトリガーされた方法です。 使用可能な値が含まれます: 'UserTriggered'、'ForcedUpgrade'</param>
        <param name="upgradedResourceId">アップグレード済みの資格情報コンテナーのリソース ID です。</param>
        <param name="previousResourceId">アップグレードする前に、資格情報コンテナーのリソース ID です。</param>
        <summary>
            UpgradeDetails クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.EndTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.EndTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTimeUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アップグレード操作の終了時刻が UTC 時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdatedTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastUpdatedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastUpdatedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.LastUpdatedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastUpdatedTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastUpdatedTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.LastUpdatedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastUpdatedTimeUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アップグレード操作の状態が最後に更新された UTC 時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ユーザーが、アップグレードの操作に関する情報を格納するメッセージを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public string OperationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationId As String" />
      <MemberSignature Language="F#" Value="member this.OperationId : string" Usage="Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.OperationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンテナーのアップグレード操作の ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousResourceId">
      <MemberSignature Language="C#" Value="public string PreviousResourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PreviousResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.PreviousResourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousResourceId As String" />
      <MemberSignature Language="F#" Value="member this.PreviousResourceId : string" Usage="Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.PreviousResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="previousResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アップグレードする前に、資格情報コンテナーのリソース ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.StartTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.StartTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTimeUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アップグレード操作が開始された UTC 時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンテナーのアップグレード操作の状態を取得します。 使用可能な値が含まれます: 'Unknown'、'処理中'、'アップグレード'、'失敗'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerType">
      <MemberSignature Language="C#" Value="public string TriggerType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TriggerType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.TriggerType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggerType As String" />
      <MemberSignature Language="F#" Value="member this.TriggerType : string" Usage="Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.TriggerType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="triggerType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            資格情報コンテナー アップ グレードがトリガーされた方法を取得します。 使用可能な値が含まれます: 'UserTriggered'、'ForcedUpgrade'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradedResourceId">
      <MemberSignature Language="C#" Value="public string UpgradedResourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradedResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.UpgradedResourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradedResourceId As String" />
      <MemberSignature Language="F#" Value="member this.UpgradedResourceId : string" Usage="Microsoft.Azure.Management.RecoveryServices.Models.UpgradeDetails.UpgradedResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="upgradedResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アップグレード済みの資格情報コンテナーのリソース ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>