<Type Name="EventHubPartitionRuntimeInformation" FullName="Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation">
  <TypeSignature Language="C#" Value="public class EventHubPartitionRuntimeInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventHubPartitionRuntimeInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class EventHubPartitionRuntimeInformation" />
  <TypeSignature Language="F#" Value="type EventHubPartitionRuntimeInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            イベント ハブ パーティションに関する情報が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubPartitionRuntimeInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSequenceNumber">
      <MemberSignature Language="C#" Value="public long BeginSequenceNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 BeginSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation.BeginSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property BeginSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.BeginSequenceNumber : int64 with get, set" Usage="Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation.BeginSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="LastEnqueuedOffset">
      <MemberSignature Language="C#" Value="public string LastEnqueuedOffset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastEnqueuedOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation.LastEnqueuedOffset" />
      <MemberSignature Language="VB.NET" Value="Public Property LastEnqueuedOffset As String" />
      <MemberSignature Language="F#" Value="member this.LastEnqueuedOffset : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation.LastEnqueuedOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="LastEnqueuedSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastEnqueuedSequenceNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastEnqueuedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation.LastEnqueuedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property LastEnqueuedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastEnqueuedSequenceNumber : int64 with get, set" Usage="Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation.LastEnqueuedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="LastEnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastEnqueuedTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastEnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation.LastEnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property LastEnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastEnqueuedTimeUtc : DateTime with get, set" Usage="Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation.LastEnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Event Hub の論理パーティションのパーティション ID を取得します。</summary>
        <value>パーティションの識別子です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>イベント ハブのパスを取得します。</summary>
        <value>イベント ハブのパス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>