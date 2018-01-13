<Type Name="NamespaceDescription" FullName="Microsoft.ServiceBus.Management.NamespaceDescription">
  <TypeSignature Language="C#" Value="public class NamespaceDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NamespaceDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Management.NamespaceDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class NamespaceDescription" />
  <TypeSignature Language="F#" Value="type NamespaceDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="NamespaceDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>サービス名前空間の目的のセマンティクスを定義します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Management.NamespaceDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.Management.NamespaceDescription" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcsManagementEndpoint">
      <MemberSignature Language="C#" Value="public Uri AcsManagementEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri AcsManagementEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.NamespaceDescription.AcsManagementEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property AcsManagementEndpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.AcsManagementEndpoint : Uri with get, set" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.AcsManagementEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="AcsManagementEndpoint", Order=105)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはアクセス制御サービスの管理エンドポイントを設定します。</summary>
        <value>アクセス制御サービス管理エンドポイント。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.NamespaceDescription.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="ConnectionString", Order=107)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはサーバーに接続するクライアントによって使用される接続文字列を設定します。</summary>
        <value>サーバーに接続するクライアントによって使用される接続文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateACSNamespace">
      <MemberSignature Language="C#" Value="public bool CreateACSNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CreateACSNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.NamespaceDescription.CreateACSNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateACSNamespace As Boolean" />
      <MemberSignature Language="F#" Value="member this.CreateACSNamespace : bool with get, set" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.CreateACSNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="CreateACSNamespace", Order=204)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または ACS 名前空間を作成するかどうかを示す値を設定します。</summary>
        <value>ACS 名前空間が作成された場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.NamespaceDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime with get, set" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="CreatedAt", Order=104)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または名前空間が作成された日付を設定します。</summary>
        <value>名前空間が作成された日付。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Critical">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Critical { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Critical" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.NamespaceDescription.Critical" />
      <MemberSignature Language="VB.NET" Value="Public Property Critical As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Critical : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.Critical" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Critical", Order=110)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または説明が重要な説明を null 許容であるかどうかを設定します。</summary>
        <value>この説明は、null 許容の重要な説明です。 場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultKey">
      <MemberSignature Language="C#" Value="public string DefaultKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.NamespaceDescription.DefaultKey" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultKey As String" />
      <MemberSignature Language="F#" Value="member this.DefaultKey : string with get, set" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.DefaultKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="DefaultKey", Order=102)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または名前空間の既定のキーを設定します。</summary>
        <value>名前空間の既定のキー。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public bool Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.NamespaceDescription.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.Enabled : bool with get, set" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=false, Name="Enabled", Order=109)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このインスタンスが有効になっているかどうかを指定します。</summary>
        <value>このインスタンスが有効である場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubEnabled">
      <MemberSignature Language="C#" Value="public bool EventHubEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EventHubEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.NamespaceDescription.EventHubEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property EventHubEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.EventHubEnabled : bool with get, set" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.EventHubEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="EventHubEnabled", Order=205)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>イベント ハブが有効になっているかどうかを指定します。</summary>
        <value>イベント ハブが有効である場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessagingSku">
      <MemberSignature Language="C#" Value="public int MessagingSku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MessagingSku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.NamespaceDescription.MessagingSku" />
      <MemberSignature Language="VB.NET" Value="Public Property MessagingSku As Integer" />
      <MemberSignature Language="F#" Value="member this.MessagingSku : int with get, set" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.MessagingSku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="MessagingSku", Order=207)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessagingSkuPlan">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Management.MessagingSKUPlan MessagingSkuPlan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Management.MessagingSKUPlan MessagingSkuPlan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.NamespaceDescription.MessagingSkuPlan" />
      <MemberSignature Language="VB.NET" Value="Public Property MessagingSkuPlan As MessagingSKUPlan" />
      <MemberSignature Language="F#" Value="member this.MessagingSkuPlan : Microsoft.ServiceBus.Management.MessagingSKUPlan with get, set" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.MessagingSkuPlan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="MessagingSkuPlan", Order=209)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Management.MessagingSKUPlan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.NamespaceDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Name", Order=100)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または名前空間の名前を設定します。</summary>
        <value>名前空間の名前。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NamespaceType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.ServiceBus.Management.NamespaceType&gt; NamespaceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.ServiceBus.Management.NamespaceType&gt; NamespaceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.NamespaceDescription.NamespaceType" />
      <MemberSignature Language="VB.NET" Value="Public Property NamespaceType As Nullable(Of NamespaceType)" />
      <MemberSignature Language="F#" Value="member this.NamespaceType : Nullable&lt;Microsoft.ServiceBus.Management.NamespaceType&gt; with get, set" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.NamespaceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="NamespaceType", Order=206)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.ServiceBus.Management.NamespaceType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または名前空間のメッセージング エンティティの種類を設定 (キュー、トピック、リレー、Event Hubs または通知ハブ) を含めることができます。 詳細については、「<see cref="T:Microsoft.ServiceBus.Management.NamespaceType" />」を参照してください。</summary>
        <value><see cref="T:Microsoft.ServiceBus.Management.NamespaceType" /> を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Region">
      <MemberSignature Language="C#" Value="public string Region { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Region" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.NamespaceDescription.Region" />
      <MemberSignature Language="VB.NET" Value="Public Property Region As String" />
      <MemberSignature Language="F#" Value="member this.Region : string with get, set" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.Region" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Region", Order=101)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または顧客データを保存する Microsoft データ センターの地理的地域を設定します。</summary>
        <value>顧客データを保存する Microsoft データ センターの地理的地域。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serializer">
      <MemberSignature Language="C#" Value="public static readonly System.Runtime.Serialization.DataContractSerializer Serializer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class System.Runtime.Serialization.DataContractSerializer Serializer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Management.NamespaceDescription.Serializer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Serializer As DataContractSerializer " />
      <MemberSignature Language="F#" Value=" staticval mutable Serializer : System.Runtime.Serialization.DataContractSerializer" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.Serializer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.DataContractSerializer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>名前空間に関連付けられているデータ コントラクト シリアライザー。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusEndpoint">
      <MemberSignature Language="C#" Value="public Uri ServiceBusEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceBusEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.NamespaceDescription.ServiceBusEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusEndpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceBusEndpoint : Uri with get, set" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.ServiceBusEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="ServiceBusEndpoint", Order=106)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはサービス バスのエンド ポイント値を設定します。</summary>
        <value>サービス バスのエンド ポイント値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Management.NamespaceState Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Management.NamespaceState Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.NamespaceDescription.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As NamespaceState" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.ServiceBus.Management.NamespaceState with get, set" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Status", Order=103)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Management.NamespaceState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または名前空間の状態を設定します。</summary>
        <value>名前空間の状態。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.NamespaceDescription.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.ServiceBus.Management.NamespaceDescription.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="SubscriptionId", Order=108)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または名前空間のサブスクリプション識別子を設定します。</summary>
        <value>名前空間のサブスクリプションの識別子です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>