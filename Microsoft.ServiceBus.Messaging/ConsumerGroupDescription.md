<Type Name="ConsumerGroupDescription" FullName="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription">
  <TypeSignature Language="C#" Value="public sealed class ConsumerGroupDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ConsumerGroupDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ConsumerGroupDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type ConsumerGroupDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="ConsumerGroupDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>コンシューマー グループの説明を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConsumerGroupDescription (string eventHubPath, string consumerGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string eventHubPath, string consumerGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (eventHubPath As String, consumerGroupName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.ConsumerGroupDescription : string * string -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="new Microsoft.ServiceBus.Messaging.ConsumerGroupDescription (eventHubPath, consumerGroupName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">イベント ハブのパス。</param>
        <param name="consumerGroupName">サブスクリプションの名前。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription.CreatedAt" />
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
    <Member MemberName="EventHubPath">
      <MemberSignature Language="C#" Value="public string EventHubPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription.EventHubPath" />
      <MemberSignature Language="VB.NET" Value="Public Property EventHubPath As String" />
      <MemberSignature Language="F#" Value="member this.EventHubPath : string with get, set" Usage="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription.EventHubPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または event hub のパスを設定します。</summary>
        <value>Event Hub のパス。</value>
        <remarks>これへの相対パス、<see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>コンシューマーの名前のグループの説明を取得します。</summary>
        <value>コンシューマー グループの説明の名前。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription.UpdatedAt" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription.UserMetadata" />
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