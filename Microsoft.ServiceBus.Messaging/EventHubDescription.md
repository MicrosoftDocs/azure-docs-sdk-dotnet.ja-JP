<Type Name="EventHubDescription" FullName="Microsoft.ServiceBus.Messaging.EventHubDescription">
  <TypeSignature Language="C#" Value="public sealed class EventHubDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventHubDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventHubDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type EventHubDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.EntityDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="EventHubDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>Event Hub のメタデータの説明を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubDescription (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventHubDescription : string -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="new Microsoft.ServiceBus.Messaging.EventHubDescription path" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスを基準とした event hub のパスです。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authorization As AuthorizationRules" />
      <MemberSignature Language="F#" Value="member this.Authorization : Microsoft.ServiceBus.Messaging.AuthorizationRules" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.AuthorizationRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" /> を取得します。</summary>
        <value><see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" />。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージが作成された正確な時刻を取得します。</summary>
        <value>メッセージが作成された正確な時刻です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageRetentionInDays">
      <MemberSignature Language="C#" Value="public long MessageRetentionInDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MessageRetentionInDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.MessageRetentionInDays" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageRetentionInDays As Long" />
      <MemberSignature Language="F#" Value="member this.MessageRetentionInDays : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.MessageRetentionInDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定をこの Event Hub にイベントを保持する日数を指定します。</summary>
        <value>日以内にイベント データの保存期間。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionCount">
      <MemberSignature Language="C#" Value="public int PartitionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PartitionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PartitionCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはイベント ハブのシャードの現在の数を設定します。</summary>
        <value>Event Hub では、サブスクリプションの数を返します。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">パーティション数の値が負の値である場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="PartitionIds">
      <MemberSignature Language="C#" Value="public string[] PartitionIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string[] PartitionIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionIds As String()" />
      <MemberSignature Language="F#" Value="member this.PartitionIds : string[]" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>イベント ハブを作成するパーティションの識別子を取得します。</summary>
        <value><see cref="T:System.String" /> を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Event Hub の完全なパスを取得します。</summary>
        <value>Event Hub のパス。</value>
        <remarks>
              これへの相対パス、<see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />です。
            </remarks>
        <exception cref="T:System.InvalidOperationException">インスタンスが読み取り専用としてマークされている場合は、このプロパティの値を設定しようとしましたがスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As EntityStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.ServiceBus.Messaging.EntityStatus with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定 (有効または無効になっています)、イベント ハブの現在の状態。</summary>
        <value>イベント ハブの現在の状態。</value>
        <remarks>この状態は、実際に更新された時間を取得できません。
            最新の状態を取得するには、更新の説明、<see cref="M:Microsoft.ServiceBus.NamespaceManager.GetEventHub(System.String)" />メソッド</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージが更新された正確な時刻を取得します。</summary>
        <value>メッセージが更新された時刻。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはユーザーのメタデータを設定します。</summary>
        <value>ユーザーのメタデータ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>