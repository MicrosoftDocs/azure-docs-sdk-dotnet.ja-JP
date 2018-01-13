<Type Name="ScheduledNotification" FullName="Microsoft.Azure.NotificationHubs.ScheduledNotification">
  <TypeSignature Language="C#" Value="public class ScheduledNotification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScheduledNotification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.ScheduledNotification" />
  <TypeSignature Language="VB.NET" Value="Public Class ScheduledNotification" />
  <TypeSignature Language="F#" Value="type ScheduledNotification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="ScheduledNotification", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>スケジュールを表す<see cref="T:Microsoft.Azure.NotificationHubs.Notification" />です。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduledNotification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ScheduledNotification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.ScheduledNotification" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Payload">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Notification Payload { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.Notification Payload" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ScheduledNotification.Payload" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Payload As Notification" />
      <MemberSignature Language="F#" Value="member this.Payload : Microsoft.Azure.NotificationHubs.Notification" Usage="Microsoft.Azure.NotificationHubs.ScheduledNotification.Payload" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="Payload", Order=1001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Notification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはこの定期的な通知のペイロードを設定します。</summary>
        <value>このペイロードは、通知をスケジュールします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledNotificationId">
      <MemberSignature Language="C#" Value="public string ScheduledNotificationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScheduledNotificationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ScheduledNotification.ScheduledNotificationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledNotificationId As String" />
      <MemberSignature Language="F#" Value="member this.ScheduledNotificationId : string" Usage="Microsoft.Azure.NotificationHubs.ScheduledNotification.ScheduledNotificationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="ScheduledNotificationId", Order=1002)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または通知 id を設定します。</summary>
        <value>通知の識別子です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledTime">
      <MemberSignature Language="C#" Value="public DateTimeOffset ScheduledTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset ScheduledTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ScheduledNotification.ScheduledTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledTime As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.ScheduledTime : DateTimeOffset" Usage="Microsoft.Azure.NotificationHubs.ScheduledNotification.ScheduledTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="ScheduledTime", Order=1003)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはスケジュールされた時刻を設定します。</summary>
        <value>スケジュールされた時刻。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public string Tags { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ScheduledNotification.Tags" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tags As String" />
      <MemberSignature Language="F#" Value="member this.Tags : string" Usage="Microsoft.Azure.NotificationHubs.ScheduledNotification.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="Tags", Order=1004)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または通知タグを設定します。</summary>
        <value>通知タグです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackingId">
      <MemberSignature Language="C#" Value="public string TrackingId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TrackingId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ScheduledNotification.TrackingId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TrackingId As String" />
      <MemberSignature Language="F#" Value="member this.TrackingId : string" Usage="Microsoft.Azure.NotificationHubs.ScheduledNotification.TrackingId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="TrackingId", Order=1005)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または追跡 id を設定します。</summary>
        <value>追跡の識別子です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>