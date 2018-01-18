<Type Name="PairedNamespaceOptions" FullName="Microsoft.ServiceBus.Messaging.PairedNamespaceOptions">
  <TypeSignature Language="C#" Value="public abstract class PairedNamespaceOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit PairedNamespaceOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class PairedNamespaceOptions" />
  <TypeSignature Language="F#" Value="type PairedNamespaceOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="bbb50-101">Service bus のメッセージングのペアの名前空間のオプションを表します。</span><span class="sxs-lookup"><span data-stu-id="bbb50-101">Represents the options for the paired namespace for the service bus messaging.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected PairedNamespaceOptions (Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, Microsoft.ServiceBus.Messaging.MessagingFactory secondaryMessagingFactory);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, class Microsoft.ServiceBus.Messaging.MessagingFactory secondaryMessagingFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.#ctor(Microsoft.ServiceBus.NamespaceManager,Microsoft.ServiceBus.Messaging.MessagingFactory)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (secondaryNamespaceManager As NamespaceManager, secondaryMessagingFactory As MessagingFactory)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.PairedNamespaceOptions : Microsoft.ServiceBus.NamespaceManager * Microsoft.ServiceBus.Messaging.MessagingFactory -&gt; Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" Usage="new Microsoft.ServiceBus.Messaging.PairedNamespaceOptions (secondaryNamespaceManager, secondaryMessagingFactory)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secondaryNamespaceManager" Type="Microsoft.ServiceBus.NamespaceManager" />
        <Parameter Name="secondaryMessagingFactory" Type="Microsoft.ServiceBus.Messaging.MessagingFactory" />
      </Parameters>
      <Docs>
        <param name="secondaryNamespaceManager"><span data-ttu-id="bbb50-102">セカンダリ名前空間マネージャー。</span><span class="sxs-lookup"><span data-stu-id="bbb50-102">The secondary namespace manager.</span></span></param>
        <param name="secondaryMessagingFactory"><span data-ttu-id="bbb50-103">ペアの名前空間に関連付けられているセカンダリ メッセージング ファクトリ。</span><span class="sxs-lookup"><span data-stu-id="bbb50-103">The secondary messaging factory associated with the paired namespace.</span></span></param>
        <summary><span data-ttu-id="bbb50-104"><see cref="T:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bbb50-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected PairedNamespaceOptions (Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, Microsoft.ServiceBus.Messaging.MessagingFactory secondaryMessagingFactory, TimeSpan failoverInterval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, class Microsoft.ServiceBus.Messaging.MessagingFactory secondaryMessagingFactory, valuetype System.TimeSpan failoverInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.#ctor(Microsoft.ServiceBus.NamespaceManager,Microsoft.ServiceBus.Messaging.MessagingFactory,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (secondaryNamespaceManager As NamespaceManager, secondaryMessagingFactory As MessagingFactory, failoverInterval As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.PairedNamespaceOptions : Microsoft.ServiceBus.NamespaceManager * Microsoft.ServiceBus.Messaging.MessagingFactory * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" Usage="new Microsoft.ServiceBus.Messaging.PairedNamespaceOptions (secondaryNamespaceManager, secondaryMessagingFactory, failoverInterval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secondaryNamespaceManager" Type="Microsoft.ServiceBus.NamespaceManager" />
        <Parameter Name="secondaryMessagingFactory" Type="Microsoft.ServiceBus.Messaging.MessagingFactory" />
        <Parameter Name="failoverInterval" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="secondaryNamespaceManager"><span data-ttu-id="bbb50-105">セカンダリ名前空間マネージャー。</span><span class="sxs-lookup"><span data-stu-id="bbb50-105">The secondary namespace manager.</span></span></param>
        <param name="secondaryMessagingFactory"><span data-ttu-id="bbb50-106">ペアの名前空間に関連付けられているセカンダリ メッセージング ファクトリ。</span><span class="sxs-lookup"><span data-stu-id="bbb50-106">The secondary messaging factory associated with the paired namespace.</span></span></param>
        <param name="failoverInterval"><span data-ttu-id="bbb50-107">メッセージ<see cref="T:System.TimeSpan" />間隔フェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="bbb50-107">The message <see cref="T:System.TimeSpan" /> interval failover.</span></span></param>
        <summary><span data-ttu-id="bbb50-108"><see cref="T:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bbb50-108">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearPairing">
      <MemberSignature Language="C#" Value="protected internal virtual void ClearPairing ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig newslot virtual instance void ClearPairing() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.ClearPairing" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Sub ClearPairing ()" />
      <MemberSignature Language="F#" Value="abstract member ClearPairing : unit -&gt; unit&#xA;override this.ClearPairing : unit -&gt; unit" Usage="pairedNamespaceOptions.ClearPairing " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="bbb50-109">ペアの名前空間のペアリングをディゾルブです。</span><span class="sxs-lookup"><span data-stu-id="bbb50-109">Dissolves the pairing of the paired namespace.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverInterval">
      <MemberSignature Language="C#" Value="public TimeSpan FailoverInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan FailoverInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.FailoverInterval" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailoverInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.FailoverInterval : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.FailoverInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bbb50-110">メッセージを取得します<see cref="T:System.TimeSpan" />間隔フェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="bbb50-110">Gets the message <see cref="T:System.TimeSpan" /> interval failover.</span></span></summary>
        <value><span data-ttu-id="bbb50-111">メッセージ<see cref="T:System.TimeSpan" />間隔フェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="bbb50-111">The message <see cref="T:System.TimeSpan" /> interval failover.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnNotifyPrimarySendResult">
      <MemberSignature Language="C#" Value="protected abstract void OnNotifyPrimarySendResult (string path, bool success);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnNotifyPrimarySendResult(string path, bool success) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.OnNotifyPrimarySendResult(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnNotifyPrimarySendResult (path As String, success As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member OnNotifyPrimarySendResult : string * bool -&gt; unit" Usage="pairedNamespaceOptions.OnNotifyPrimarySendResult (path, success)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="success" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="bbb50-112">パスの文字列です。</span><span class="sxs-lookup"><span data-stu-id="bbb50-112">The string of the path.</span></span></param>
        <param name="success"><span data-ttu-id="bbb50-113">true の場合は、結果を正常に送信します。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="bbb50-113">true if the results successfully send; otherwise, false.</span></span></param>
        <summary><span data-ttu-id="bbb50-114">結果の送信時にプライマリ メッセージングに通知します。</span><span class="sxs-lookup"><span data-stu-id="bbb50-114">Notifies the primary messaging on sending the result.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryMessagingFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingFactory SecondaryMessagingFactory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessagingFactory SecondaryMessagingFactory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.SecondaryMessagingFactory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryMessagingFactory As MessagingFactory" />
      <MemberSignature Language="F#" Value="member this.SecondaryMessagingFactory : Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.SecondaryMessagingFactory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bbb50-115">ペアの名前空間に関連付けられているセカンダリのメッセージング ファクトリを取得します。</span><span class="sxs-lookup"><span data-stu-id="bbb50-115">Gets the secondary messaging factory associated with the paired namespace.</span></span></summary>
        <value><span data-ttu-id="bbb50-116">ペアの名前空間に関連付けられているセカンダリ メッセージング ファクトリ。</span><span class="sxs-lookup"><span data-stu-id="bbb50-116">The secondary messaging factory associated with the paired namespace.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryNamespaceManager">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.NamespaceManager SecondaryNamespaceManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.NamespaceManager SecondaryNamespaceManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.SecondaryNamespaceManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryNamespaceManager As NamespaceManager" />
      <MemberSignature Language="F#" Value="member this.SecondaryNamespaceManager : Microsoft.ServiceBus.NamespaceManager" Usage="Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.SecondaryNamespaceManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NamespaceManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bbb50-117">キュー、トピック、サブスクリプションと対になった名前空間内のルールなどのエンティティを管理するオブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="bbb50-117">Gets the object that manages entities, such as queues, topics, subscriptions and rules in the paired namespace.</span></span></summary>
        <value><span data-ttu-id="bbb50-118">キュー、トピック、サブスクリプションと対になった名前空間内のルールなどのエンティティを管理するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bbb50-118">The object that manages entities, such as queues, topics, subscriptions and rules in the paired namespace.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>