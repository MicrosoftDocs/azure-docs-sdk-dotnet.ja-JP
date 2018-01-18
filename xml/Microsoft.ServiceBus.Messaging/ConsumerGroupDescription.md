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
    <summary><span data-ttu-id="07835-101">コンシューマー グループの説明を表します。</span><span class="sxs-lookup"><span data-stu-id="07835-101">Represents a description of the consumer group.</span></span></summary>
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
        <param name="eventHubPath"><span data-ttu-id="07835-102">イベント ハブのパス。</span><span class="sxs-lookup"><span data-stu-id="07835-102">The path of the event hub.</span></span></param>
        <param name="consumerGroupName"><span data-ttu-id="07835-103">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="07835-103">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="07835-104"><see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="07835-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" /> class.</span></span></summary>
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
        <summary><span data-ttu-id="07835-105">メッセージが作成された正確な時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="07835-105">Gets the exact time the message was created.</span></span></summary>
        <value><span data-ttu-id="07835-106">メッセージが作成された正確な時刻です。</span><span class="sxs-lookup"><span data-stu-id="07835-106">The exact time the message was created.</span></span></value>
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
        <summary><span data-ttu-id="07835-107">取得または event hub のパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="07835-107">Gets or sets the path of the event hub.</span></span></summary>
        <value><span data-ttu-id="07835-108">Event Hub のパス。</span><span class="sxs-lookup"><span data-stu-id="07835-108">The path of the Event Hub.</span></span></value>
        <remarks><span data-ttu-id="07835-109">これへの相対パス、<see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />です。</span><span class="sxs-lookup"><span data-stu-id="07835-109">This is a relative path to the <see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />.</span></span>
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
        <summary><span data-ttu-id="07835-110">コンシューマーの名前のグループの説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="07835-110">Gets the name of the consumer group description.</span></span></summary>
        <value><span data-ttu-id="07835-111">コンシューマー グループの説明の名前。</span><span class="sxs-lookup"><span data-stu-id="07835-111">The name of the consumer group description.</span></span></value>
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
        <summary><span data-ttu-id="07835-112">メッセージが更新された正確な時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="07835-112">Gets the exact time the message has been updated.</span></span></summary>
        <value><span data-ttu-id="07835-113">メッセージが更新された時刻。</span><span class="sxs-lookup"><span data-stu-id="07835-113">The time the message has been updated.</span></span></value>
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
        <summary><span data-ttu-id="07835-114">取得またはユーザーのメタデータを設定します。</span><span class="sxs-lookup"><span data-stu-id="07835-114">Gets or sets the user metadata.</span></span></summary>
        <value><span data-ttu-id="07835-115">ユーザーのメタデータ。</span><span class="sxs-lookup"><span data-stu-id="07835-115">The user metadata.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>