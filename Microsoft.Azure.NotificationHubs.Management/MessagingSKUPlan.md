<Type Name="MessagingSKUPlan" FullName="Microsoft.Azure.NotificationHubs.Management.MessagingSKUPlan">
  <TypeSignature Language="C#" Value="public class MessagingSKUPlan" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MessagingSKUPlan extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Management.MessagingSKUPlan" />
  <TypeSignature Language="VB.NET" Value="Public Class MessagingSKUPlan" />
  <TypeSignature Language="F#" Value="type MessagingSKUPlan = class" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="NamespaceSKUPlan", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>メッセージング SKU プランを表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingSKUPlan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Management.MessagingSKUPlan.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.Management.MessagingSKUPlan" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Revision">
      <MemberSignature Language="C#" Value="public long Revision { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Revision" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.MessagingSKUPlan.Revision" />
      <MemberSignature Language="VB.NET" Value="Public Property Revision As Long" />
      <MemberSignature Language="F#" Value="member this.Revision : int64 with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.MessagingSKUPlan.Revision" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Revision", Order=1005)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはプラン リビジョンを設定します。</summary>
        <value>プランのリビジョン。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectedEventHubUnit">
      <MemberSignature Language="C#" Value="public int SelectedEventHubUnit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SelectedEventHubUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.MessagingSKUPlan.SelectedEventHubUnit" />
      <MemberSignature Language="VB.NET" Value="Public Property SelectedEventHubUnit As Integer" />
      <MemberSignature Language="F#" Value="member this.SelectedEventHubUnit : int with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.MessagingSKUPlan.SelectedEventHubUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=false, Name="SelectedEventHubUnit", Order=1002)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または選択したイベント ハブの単位を設定します。</summary>
        <value>選択されたイベント ハブの単位。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SKU">
      <MemberSignature Language="C#" Value="public int SKU { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SKU" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.MessagingSKUPlan.SKU" />
      <MemberSignature Language="VB.NET" Value="Public Property SKU As Integer" />
      <MemberSignature Language="F#" Value="member this.SKU : int with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.MessagingSKUPlan.SKU" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="SKU", Order=1001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または在庫管理単位を設定します。</summary>
        <value>在庫保管単位。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.MessagingSKUPlan.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.Azure.NotificationHubs.Management.MessagingSKUPlan.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="UpdatedAt", Order=1004)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または、プランが更新された正確な時間を設定します。</summary>
        <value>正確な時間、プランが更新されました。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>