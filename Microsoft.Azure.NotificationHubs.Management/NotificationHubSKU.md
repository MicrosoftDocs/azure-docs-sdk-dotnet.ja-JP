<Type Name="NotificationHubSKU" FullName="Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU">
  <TypeSignature Language="C#" Value="public class NotificationHubSKU" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NotificationHubSKU extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU" />
  <TypeSignature Language="VB.NET" Value="Public Class NotificationHubSKU" />
  <TypeSignature Language="F#" Value="type NotificationHubSKU = class" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="NotificationHubSKU", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>通知ハブの SKU を提供します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotificationHubSKU ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAllowedApiCallsPerDayPerUnit">
      <MemberSignature Language="C#" Value="public long MaxAllowedApiCallsPerDayPerUnit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxAllowedApiCallsPerDayPerUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.MaxAllowedApiCallsPerDayPerUnit" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAllowedApiCallsPerDayPerUnit As Long" />
      <MemberSignature Language="F#" Value="member this.MaxAllowedApiCallsPerDayPerUnit : int64 with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.MaxAllowedApiCallsPerDayPerUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, Name="MaxAllowedApiCallsPerDayPerUnit", Order=1008)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または単位あたり 1 日あたりの許可されている API 呼び出しの最大数を設定します。</summary>
        <value>単位あたり 1 日あたりの API 呼び出しが最大です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAllowedDevicesPerUnit">
      <MemberSignature Language="C#" Value="public long MaxAllowedDevicesPerUnit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxAllowedDevicesPerUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.MaxAllowedDevicesPerUnit" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAllowedDevicesPerUnit As Long" />
      <MemberSignature Language="F#" Value="member this.MaxAllowedDevicesPerUnit : int64 with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.MaxAllowedDevicesPerUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Name="MaxAllowedDevicesPerUnit", Order=1006)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または単位あたりの許可されているデバイスの最大数を設定します。</summary>
        <value>単位あたりのデバイスが最大です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAllowedOperationsPerDayPerUnit">
      <MemberSignature Language="C#" Value="public long MaxAllowedOperationsPerDayPerUnit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxAllowedOperationsPerDayPerUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.MaxAllowedOperationsPerDayPerUnit" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAllowedOperationsPerDayPerUnit As Long" />
      <MemberSignature Language="F#" Value="member this.MaxAllowedOperationsPerDayPerUnit : int64 with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.MaxAllowedOperationsPerDayPerUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, Name="MaxAllowedOperationsPerDayPerUnit", Order=1004)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または単位あたり 1 日あたりの最大の許可された操作を設定します。</summary>
        <value>単位あたり 1 日あたりの操作が最大です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAllowedPushesPerDayPerUnit">
      <MemberSignature Language="C#" Value="public long MaxAllowedPushesPerDayPerUnit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxAllowedPushesPerDayPerUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.MaxAllowedPushesPerDayPerUnit" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAllowedPushesPerDayPerUnit As Long" />
      <MemberSignature Language="F#" Value="member this.MaxAllowedPushesPerDayPerUnit : int64 with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.MaxAllowedPushesPerDayPerUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, Name="MaxAllowedPushesPerDayPerUnit", Order=1007)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または最大許容ユニットあたり 1 日あたりのプッシュを設定します。</summary>
        <value>最大許容ユニットごとに 1 日にプッシュします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAllowedRegistrationsPerUnit">
      <MemberSignature Language="C#" Value="public long MaxAllowedRegistrationsPerUnit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxAllowedRegistrationsPerUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.MaxAllowedRegistrationsPerUnit" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAllowedRegistrationsPerUnit As Long" />
      <MemberSignature Language="F#" Value="member this.MaxAllowedRegistrationsPerUnit : int64 with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.MaxAllowedRegistrationsPerUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Name="MaxAllowedRegistrationsPerUnit", Order=1005)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または単位あたりの最大許容登録を設定します。</summary>
        <value>単位あたりの登録が最大です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAllowedUnits">
      <MemberSignature Language="C#" Value="public int MaxAllowedUnits { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxAllowedUnits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.MaxAllowedUnits" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAllowedUnits As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxAllowedUnits : int with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.MaxAllowedUnits" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Name="MaxAllowedUnits", Order=1002)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または最大許容ユニット数を設定します。</summary>
        <value>最大ユニットです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinAllowedUnits">
      <MemberSignature Language="C#" Value="public int MinAllowedUnits { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MinAllowedUnits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.MinAllowedUnits" />
      <MemberSignature Language="VB.NET" Value="Public Property MinAllowedUnits As Integer" />
      <MemberSignature Language="F#" Value="member this.MinAllowedUnits : int with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.MinAllowedUnits" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Name="MinAllowedUnits", Order=1003)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または最小単位の値を設定します。</summary>
        <value>許容される最小の単位。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SKU">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Management.NotificationHubSKUType SKU;" />
      <MemberSignature Language="ILAsm" Value=".field public valuetype Microsoft.Azure.NotificationHubs.Management.NotificationHubSKUType SKU" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.SKU" />
      <MemberSignature Language="VB.NET" Value="Public SKU As NotificationHubSKUType " />
      <MemberSignature Language="F#" Value="val mutable SKU : Microsoft.Azure.NotificationHubs.Management.NotificationHubSKUType" Usage="Microsoft.Azure.NotificationHubs.Management.NotificationHubSKU.SKU" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DataAnnotations.Key</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Name="SKU", Order=1001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Management.NotificationHubSKUType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>通知ハブの在庫管理単位を指定します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>