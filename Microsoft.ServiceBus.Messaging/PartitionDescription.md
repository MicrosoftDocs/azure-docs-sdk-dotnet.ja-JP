<Type Name="PartitionDescription" FullName="Microsoft.ServiceBus.Messaging.PartitionDescription">
  <TypeSignature Language="C#" Value="public sealed class PartitionDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.PartitionDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type PartitionDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="PartitionDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>メタデータと Event Hub の論理パーティションのおおよそのランタイム情報を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionDescription (string eventHubPath, string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string eventHubPath, string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PartitionDescription.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (eventHubPath As String, partitionId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.PartitionDescription : string * string -&gt; Microsoft.ServiceBus.Messaging.PartitionDescription" Usage="new Microsoft.ServiceBus.Messaging.PartitionDescription (eventHubPath, partitionId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Event Hub のパス。</param>
        <param name="partitionId">パーティションの識別子です。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.PartitionDescription" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSequenceNumber">
      <MemberSignature Language="C#" Value="public long BeginSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 BeginSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionDescription.BeginSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BeginSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.BeginSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.PartitionDescription.BeginSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>開始シーケンス番号を取得します。</summary>
        <value>開始シーケンス番号。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsumerGroupName">
      <MemberSignature Language="C#" Value="public string ConsumerGroupName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsumerGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionDescription.ConsumerGroupName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsumerGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ConsumerGroupName : string" Usage="Microsoft.ServiceBus.Messaging.PartitionDescription.ConsumerGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>イベント ハブ コンシューマー グループの名前を取得します。</summary>
        <value>イベント ハブ コンシューマー グループです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSequenceNumber">
      <MemberSignature Language="C#" Value="public long EndSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 EndSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionDescription.EndSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.EndSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.PartitionDescription.EndSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>最後のシーケンス番号を取得します。</summary>
        <value>最後のシーケンス番号。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubPath">
      <MemberSignature Language="C#" Value="public string EventHubPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionDescription.EventHubPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubPath As String" />
      <MemberSignature Language="F#" Value="member this.EventHubPath : string" Usage="Microsoft.ServiceBus.Messaging.PartitionDescription.EventHubPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Event Hub のパスを取得します。</summary>
        <value>Event Hub のパス。</value>
        <remarks>
              これへの相対パス、<see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IncomingBytesPerSecond">
      <MemberSignature Language="C#" Value="public long IncomingBytesPerSecond { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 IncomingBytesPerSecond" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionDescription.IncomingBytesPerSecond" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IncomingBytesPerSecond As Long" />
      <MemberSignature Language="F#" Value="member this.IncomingBytesPerSecond : int64" Usage="Microsoft.ServiceBus.Messaging.PartitionDescription.IncomingBytesPerSecond" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>パーティションのイベント (1 秒あたりのバイト単位) のおおよその着信レートを取得します。</summary>
        <value><see cref="T:System.Int64" /> を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastEnqueuedOffset">
      <MemberSignature Language="C#" Value="public string LastEnqueuedOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastEnqueuedOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionDescription.LastEnqueuedOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastEnqueuedOffset As String" />
      <MemberSignature Language="F#" Value="member this.LastEnqueuedOffset : string" Usage="Microsoft.ServiceBus.Messaging.PartitionDescription.LastEnqueuedOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>最後にエンキューされたイベントのオフセットを取得します。</summary>
        <value>最後のエンキューされたイベントのオフセット。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastEnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastEnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastEnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionDescription.LastEnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastEnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastEnqueuedTimeUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.PartitionDescription.LastEnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>最後のイベントのエンキューされた UTC 時刻を取得します。</summary>
        <value>最後のイベントのエンキューされた時刻。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutgoingBytesPerSecond">
      <MemberSignature Language="C#" Value="public long OutgoingBytesPerSecond { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 OutgoingBytesPerSecond" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionDescription.OutgoingBytesPerSecond" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutgoingBytesPerSecond As Long" />
      <MemberSignature Language="F#" Value="member this.OutgoingBytesPerSecond : int64" Usage="Microsoft.ServiceBus.Messaging.PartitionDescription.OutgoingBytesPerSecond" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>指定されたコンシューマー グループ内のパーティションのおおよそ送信比率 (1 秒あたりのバイト単位) を取得します。</summary>
        <value><see cref="T:System.Int64" /> を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionDescription.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.ServiceBus.Messaging.PartitionDescription.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>所属する Event Hub のパーティション ID を取得します。</summary>
        <value>パーティションの識別子です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public long SizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PartitionDescription.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : int64" Usage="Microsoft.ServiceBus.Messaging.PartitionDescription.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>(バイト単位)、Event Hubs のパーティションのおおよそのサイズを取得します。</summary>
        <value><see cref="T:System.Int64" /> を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>