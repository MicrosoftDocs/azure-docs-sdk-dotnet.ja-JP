<Type Name="EventHubRuntimeInformation" FullName="Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation">
  <TypeSignature Language="C#" Value="public class EventHubRuntimeInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventHubRuntimeInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class EventHubRuntimeInformation" />
  <TypeSignature Language="F#" Value="type EventHubRuntimeInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>作成するために必要な Event Hubs ランタイム情報を返します<see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" />または<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />オブジェクト。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubRuntimeInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または Event Hub の作成時刻を設定します。</summary>
        <value><see cref="T:System.DateTime" /> を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionCount">
      <MemberSignature Language="C#" Value="public int PartitionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PartitionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation.PartitionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PartitionCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation.PartitionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または Event Hub のパーティションの数を設定します。</summary>
        <value><see cref="T:System.Int32" /> を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionIds">
      <MemberSignature Language="C#" Value="public string[] PartitionIds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string[] PartitionIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation.PartitionIds" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionIds As String()" />
      <MemberSignature Language="F#" Value="member this.PartitionIds : string[] with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation.PartitionIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または Event Hub のパーティション ID を設定します。</summary>
        <value><see cref="T:System.String" /> を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または Event Hub へのパスを設定します。</summary>
        <value><see cref="T:System.String" /> を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>