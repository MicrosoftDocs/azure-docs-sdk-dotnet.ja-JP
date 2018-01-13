<Type Name="NamespaceDescription" FullName="Microsoft.Azure.NotificationHubs.Management.NamespaceDescription">
  <TypeSignature Language="C#" Value="public class NamespaceDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NamespaceDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class NamespaceDescription" />
  <TypeSignature Language="F#" Value="type NamespaceDescription = class" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="NamespaceDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="a0235-101">サービス名前空間の目的のセマンティクスを定義します。</span><span class="sxs-lookup"><span data-stu-id="a0235-101">Defines the desired semantics for a service namespace.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="a0235-102"><see cref="T:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a0235-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcsManagementEndpoint">
      <MemberSignature Language="C#" Value="public Uri AcsManagementEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri AcsManagementEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.AcsManagementEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property AcsManagementEndpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.AcsManagementEndpoint : Uri with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.AcsManagementEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="a0235-103">取得またはアクセス制御サービスの管理エンドポイントを設定します。</span><span class="sxs-lookup"><span data-stu-id="a0235-103">Gets or sets the management endpoint for the access control service.</span></span></summary>
        <value><span data-ttu-id="a0235-104">アクセス制御サービス管理エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="a0235-104">The management endpoint for the access control service.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="a0235-105">取得またはサーバーに接続するクライアントによって使用される接続文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="a0235-105">Gets or sets the connection string that is used by the client to connect to the server.</span></span></summary>
        <value><span data-ttu-id="a0235-106">サーバーに接続するクライアントによって使用される接続文字列。</span><span class="sxs-lookup"><span data-stu-id="a0235-106">The connection string that is used by the client to connect to the server.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateACSNamespace">
      <MemberSignature Language="C#" Value="public bool CreateACSNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CreateACSNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.CreateACSNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateACSNamespace As Boolean" />
      <MemberSignature Language="F#" Value="member this.CreateACSNamespace : bool with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.CreateACSNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="a0235-107">取得または ACS 名前空間を作成するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a0235-107">Gets or sets a value that indicates whether to create ACS namespace.</span></span></summary>
        <value><span data-ttu-id="a0235-108">ACS 名前空間が作成された場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="a0235-108">true if ACS namespace has been created; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="a0235-109">取得または名前空間が作成された日付を設定します。</span><span class="sxs-lookup"><span data-stu-id="a0235-109">Gets or sets the date when the namespace was created.</span></span></summary>
        <value><span data-ttu-id="a0235-110">名前空間が作成された日付。</span><span class="sxs-lookup"><span data-stu-id="a0235-110">The date when the namespace was created.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Critical">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Critical { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Critical" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.Critical" />
      <MemberSignature Language="VB.NET" Value="Public Property Critical As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Critical : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.Critical" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="a0235-111">取得または説明が重要な説明を null 許容であるかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="a0235-111">Gets or sets whether the description is a nullable critical description.</span></span></summary>
        <value><span data-ttu-id="a0235-112">この説明は、null 許容の重要な説明です。 場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="a0235-112">true if the description is a nullable critical description; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultKey">
      <MemberSignature Language="C#" Value="public string DefaultKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.DefaultKey" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultKey As String" />
      <MemberSignature Language="F#" Value="member this.DefaultKey : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.DefaultKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="a0235-113">取得または名前空間の既定のキーを設定します。</span><span class="sxs-lookup"><span data-stu-id="a0235-113">Gets or sets the default key for the namespace.</span></span></summary>
        <value><span data-ttu-id="a0235-114">名前空間の既定のキー。</span><span class="sxs-lookup"><span data-stu-id="a0235-114">The default key for the namespace.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public bool Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.Enabled : bool with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="a0235-115">このインスタンスが有効になっているかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="a0235-115">Specifies whether this instance is enabled.</span></span></summary>
        <value><span data-ttu-id="a0235-116">このインスタンスが有効である場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="a0235-116">true if this instance is enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubEnabled">
      <MemberSignature Language="C#" Value="public bool EventHubEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EventHubEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.EventHubEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property EventHubEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.EventHubEnabled : bool with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.EventHubEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <summary>
            <span data-ttu-id="a0235-117">(廃止)EventHub 機能が有効になっているかどうか</span><span class="sxs-lookup"><span data-stu-id="a0235-117">(obsolete) Whether eventHub feature is enabled</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="a0235-118">取得または名前空間の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="a0235-118">Gets or sets the name of the namespace.</span></span></summary>
        <value><span data-ttu-id="a0235-119">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="a0235-119">The name of the namespace.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NamespaceType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.NotificationHubs.Management.NamespaceType&gt; NamespaceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.NotificationHubs.Management.NamespaceType&gt; NamespaceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.NamespaceType" />
      <MemberSignature Language="VB.NET" Value="Public Property NamespaceType As Nullable(Of NamespaceType)" />
      <MemberSignature Language="F#" Value="member this.NamespaceType : Nullable&lt;Microsoft.Azure.NotificationHubs.Management.NamespaceType&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.NamespaceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="NamespaceType", Order=206)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.NotificationHubs.Management.NamespaceType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a0235-120">名前空間の型。</span><span class="sxs-lookup"><span data-stu-id="a0235-120">Type of the namespace.</span></span> <span data-ttu-id="a0235-121">NotificationHub または Mixed の場合は、名前空間に notificationHubs を作成できます。</span><span class="sxs-lookup"><span data-stu-id="a0235-121">If it is NotificationHub or Mixed, we could create notificationHubs in the namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Region">
      <MemberSignature Language="C#" Value="public string Region { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Region" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.Region" />
      <MemberSignature Language="VB.NET" Value="Public Property Region As String" />
      <MemberSignature Language="F#" Value="member this.Region : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.Region" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="a0235-122">取得または顧客データを保存する Microsoft データ センターの地理的地域を設定します。</span><span class="sxs-lookup"><span data-stu-id="a0235-122">Gets or sets the geographic region(s) of the Microsoft datacenters in which Customer Data will be stored.</span></span></summary>
        <value><span data-ttu-id="a0235-123">顧客データを保存する Microsoft データ センターの地理的地域。</span><span class="sxs-lookup"><span data-stu-id="a0235-123">The geographic region(s) of the Microsoft datacenters in which Customer Data will be stored.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serializer">
      <MemberSignature Language="C#" Value="public static readonly System.Runtime.Serialization.DataContractSerializer Serializer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class System.Runtime.Serialization.DataContractSerializer Serializer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.Serializer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Serializer As DataContractSerializer " />
      <MemberSignature Language="F#" Value=" staticval mutable Serializer : System.Runtime.Serialization.DataContractSerializer" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.Serializer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.DataContractSerializer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a0235-124">名前空間に関連付けられているデータ コントラクト シリアライザー。</span><span class="sxs-lookup"><span data-stu-id="a0235-124">The data contract serializer associated with the namespace.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusEndpoint">
      <MemberSignature Language="C#" Value="public Uri ServiceBusEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceBusEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.ServiceBusEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusEndpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceBusEndpoint : Uri with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.ServiceBusEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="a0235-125">取得またはサービス バスのエンド ポイント値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a0235-125">Gets or sets the service bus end point value.</span></span></summary>
        <value><span data-ttu-id="a0235-126">サービス バスのエンド ポイント値。</span><span class="sxs-lookup"><span data-stu-id="a0235-126">The service bus end point value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Management.NamespaceState Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.NotificationHubs.Management.NamespaceState Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As NamespaceState" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.NotificationHubs.Management.NamespaceState with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Status", Order=103)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Management.NamespaceState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a0235-127">取得または名前空間の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="a0235-127">Gets or sets the state of the namespace.</span></span></summary>
        <value><span data-ttu-id="a0235-128">名前空間の状態。</span><span class="sxs-lookup"><span data-stu-id="a0235-128">The state of the namespace.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceDescription.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="a0235-129">取得または名前空間のサブスクリプション識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="a0235-129">Gets or sets the namespace subscription identifier.</span></span></summary>
        <value><span data-ttu-id="a0235-130">名前空間のサブスクリプションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="a0235-130">The namespace subscription identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>