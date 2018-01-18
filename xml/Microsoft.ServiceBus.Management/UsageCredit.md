<Type Name="UsageCredit" FullName="Microsoft.ServiceBus.Management.UsageCredit">
  <TypeSignature Language="C#" Value="public class UsageCredit : IEquatable&lt;Microsoft.ServiceBus.Management.UsageCredit&gt;, System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UsageCredit extends System.Object implements class System.IEquatable`1&lt;class Microsoft.ServiceBus.Management.UsageCredit&gt;, class System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Management.UsageCredit" />
  <TypeSignature Language="VB.NET" Value="Public Class UsageCredit&#xA;Implements IEquatable(Of UsageCredit), IExtensibleDataObject" />
  <TypeSignature Language="F#" Value="type UsageCredit = class&#xA;    interface IExtensibleDataObject&#xA;    interface IEquatable&lt;UsageCredit&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.ServiceBus.Management.UsageCredit&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Runtime.Serialization.IExtensibleDataObject</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="UsageCredit", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="a6979-101">使用状況の信用調査を表します。</span><span class="sxs-lookup"><span data-stu-id="a6979-101">Represents the usage credit management.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UsageCredit ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Management.UsageCredit.#ctor" />
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
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.ServiceBus.Management.UsageCredit other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.ServiceBus.Management.UsageCredit other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Management.UsageCredit.Equals(Microsoft.ServiceBus.Management.UsageCredit)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As UsageCredit) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.ServiceBus.Management.UsageCredit -&gt; bool" Usage="usageCredit.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.ServiceBus.Management.UsageCredit" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="a6979-102">その他の使用状況の貸方を比較します。</span><span class="sxs-lookup"><span data-stu-id="a6979-102">The other usage credit to compare.</span></span></param>
        <summary><span data-ttu-id="a6979-103">このインスタンスが別の使用状況のクレジットと等しいかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="a6979-103">Specifies whether this instance is equal with another usage credit.</span></span></summary>
        <returns><span data-ttu-id="a6979-104">このインスタンスが別の使用状況クレジット; と等しい場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="a6979-104">true if this instance is equal with another usage credit; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtensionData">
      <MemberSignature Language="C#" Value="public System.Runtime.Serialization.ExtensionDataObject ExtensionData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Runtime.Serialization.ExtensionDataObject ExtensionData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.ExtensionData" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtensionData As ExtensionDataObject" />
      <MemberSignature Language="F#" Value="member this.ExtensionData : System.Runtime.Serialization.ExtensionDataObject with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.ExtensionData" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Runtime.Serialization.IExtensibleDataObject.ExtensionData</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.ExtensionDataObject</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a6979-105">取得または設定データを格納するオブジェクト</span><span class="sxs-lookup"><span data-stu-id="a6979-105">Gets or sets the object that stores data</span></span></summary>
        <value><span data-ttu-id="a6979-106">データを格納するオブジェクト</span><span class="sxs-lookup"><span data-stu-id="a6979-106">The object that stores data</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identifier">
      <MemberSignature Language="C#" Value="public string Identifier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Identifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.Identifier" />
      <MemberSignature Language="VB.NET" Value="Public Property Identifier As String" />
      <MemberSignature Language="F#" Value="member this.Identifier : string with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.Identifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=true, Name="Identifier", Order=1003)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a6979-107">取得またはクレジットの識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="a6979-107">Gets or sets the credit identifier.</span></span></summary>
        <value><span data-ttu-id="a6979-108">クレジットの識別子です。</span><span class="sxs-lookup"><span data-stu-id="a6979-108">The credit identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="KeyName", Order=1001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a6979-109">取得またはクレジットに関連付けられているキーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="a6979-109">Gets or sets the key name associated with the credit.</span></span></summary>
        <value><span data-ttu-id="a6979-110">クレジットに関連付けられているキーの名前。</span><span class="sxs-lookup"><span data-stu-id="a6979-110">The key name associated with the credit.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NamespaceName">
      <MemberSignature Language="C#" Value="public string NamespaceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NamespaceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.NamespaceName" />
      <MemberSignature Language="VB.NET" Value="Public Property NamespaceName As String" />
      <MemberSignature Language="F#" Value="member this.NamespaceName : string with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.NamespaceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a6979-111">取得またはクレジットに関連付けられている名前空間の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="a6979-111">Gets or sets the namespace name associated with the credit.</span></span></summary>
        <value><span data-ttu-id="a6979-112"><see cref="T:System.String" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a6979-112">Returns <see cref="T:System.String" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NHBasicUnit">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NHBasicUnit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NHBasicUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.NHBasicUnit" />
      <MemberSignature Language="VB.NET" Value="Public Property NHBasicUnit As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NHBasicUnit : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.NHBasicUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="NHBasicUnit", Order=1004)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a6979-113">取得または通知ハブのベーシック レベル単位を設定します。</span><span class="sxs-lookup"><span data-stu-id="a6979-113">Gets or sets the Basic Tier unit of the notification hub.</span></span></summary>
        <value><span data-ttu-id="a6979-114">通知ハブの基本単位。</span><span class="sxs-lookup"><span data-stu-id="a6979-114">The basic unit of the notification hub.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NHStandardUnit">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NHStandardUnit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NHStandardUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.NHStandardUnit" />
      <MemberSignature Language="VB.NET" Value="Public Property NHStandardUnit As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NHStandardUnit : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.NHStandardUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="NHStandardUnit", Order=1005)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a6979-115">取得または通知ハブのスタンダード レベル単位を設定します。</span><span class="sxs-lookup"><span data-stu-id="a6979-115">Gets or sets the Standard Tier unit of the notification hub.</span></span></summary>
        <value><span data-ttu-id="a6979-116">通知ハブの標準単位です。</span><span class="sxs-lookup"><span data-stu-id="a6979-116">The standard unit of the notification hub.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestorService">
      <MemberSignature Language="C#" Value="public string RequestorService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestorService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.RequestorService" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestorService As String" />
      <MemberSignature Language="F#" Value="member this.RequestorService : string with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.RequestorService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=true, Name="RequestorService", Order=1002)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a6979-117">取得またはリクエスター サービスを設定します。</span><span class="sxs-lookup"><span data-stu-id="a6979-117">Gets or sets the requestor service.</span></span></summary>
        <value><span data-ttu-id="a6979-118">要求元サービスです。</span><span class="sxs-lookup"><span data-stu-id="a6979-118">The requestor service.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Revision">
      <MemberSignature Language="C#" Value="public long Revision { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Revision" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.Revision" />
      <MemberSignature Language="VB.NET" Value="Public Property Revision As Long" />
      <MemberSignature Language="F#" Value="member this.Revision : int64 with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.Revision" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=false, Name="Revision", Order=1006)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a6979-119">取得またはクレジットのリビジョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="a6979-119">Gets or sets the credit revision.</span></span></summary>
        <value><span data-ttu-id="a6979-120">クレジット リビジョン。</span><span class="sxs-lookup"><span data-stu-id="a6979-120">The credit revision.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serializer">
      <MemberSignature Language="C#" Value="public static readonly System.Runtime.Serialization.DataContractSerializer Serializer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class System.Runtime.Serialization.DataContractSerializer Serializer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Management.UsageCredit.Serializer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Serializer As DataContractSerializer " />
      <MemberSignature Language="F#" Value=" staticval mutable Serializer : System.Runtime.Serialization.DataContractSerializer" Usage="Microsoft.ServiceBus.Management.UsageCredit.Serializer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.DataContractSerializer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a6979-121">使用状況のクレジット シリアライザーを指定します。</span><span class="sxs-lookup"><span data-stu-id="a6979-121">Specifies the usage credit serializer.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a6979-122">取得またはクレジットに関連付けられている Azure サブスクリプション ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="a6979-122">Gets or sets the Azure subscription ID associated with the credit.</span></span></summary>
        <value><span data-ttu-id="a6979-123"><see cref="T:System.String" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a6979-123">Returns <see cref="T:System.String" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Management.UsageCredit.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="usageCredit.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="a6979-124">文字列表現を返します<see cref="T:Microsoft.ServiceBus.Management.UsageCredit" />です。</span><span class="sxs-lookup"><span data-stu-id="a6979-124">Returns a string representation of <see cref="T:Microsoft.ServiceBus.Management.UsageCredit" />.</span></span></summary>
        <returns><span data-ttu-id="a6979-125">文字列表現<see cref="T:Microsoft.ServiceBus.Management.UsageCredit" />です。</span><span class="sxs-lookup"><span data-stu-id="a6979-125">A string representation of <see cref="T:Microsoft.ServiceBus.Management.UsageCredit" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="UpdatedAt", Order=1007)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a6979-126">取得またはクレジットの詳細が更新された最後の日付を設定します。</span><span class="sxs-lookup"><span data-stu-id="a6979-126">Gets or sets the last date when the credit details were updated.</span></span></summary>
        <value><span data-ttu-id="a6979-127">最後の日付では、クレジットの詳細が更新されました。</span><span class="sxs-lookup"><span data-stu-id="a6979-127">The last date when the credit details were updated.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>