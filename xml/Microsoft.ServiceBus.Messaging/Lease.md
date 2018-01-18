<Type Name="Lease" FullName="Microsoft.ServiceBus.Messaging.Lease">
  <TypeSignature Language="C#" Value="public class Lease" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Lease extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.Lease" />
  <TypeSignature Language="VB.NET" Value="Public Class Lease" />
  <TypeSignature Language="F#" Value="type Lease = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="1c6a7-101">パーティションの所有権情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-101">Contains partition ownership information.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Lease ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Lease.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="1c6a7-102"><see cref="T:Microsoft.ServiceBus.Messaging.Lease" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.Lease" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Lease (Microsoft.ServiceBus.Messaging.Lease source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.Messaging.Lease source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Lease.#ctor(Microsoft.ServiceBus.Messaging.Lease)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (source As Lease)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.Lease : Microsoft.ServiceBus.Messaging.Lease -&gt; Microsoft.ServiceBus.Messaging.Lease" Usage="new Microsoft.ServiceBus.Messaging.Lease source" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.ServiceBus.Messaging.Lease" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="1c6a7-103">指定した<see cref="M:Microsoft.ServiceBus.Messaging.Lease.#ctor(Microsoft.ServiceBus.Messaging.Lease)" />インスタンスから、プロパティの値がコピーされます。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-103">The specified <see cref="M:Microsoft.ServiceBus.Messaging.Lease.#ctor(Microsoft.ServiceBus.Messaging.Lease)" /> instance where its property values will be copied from.</span></span></param>
        <summary><span data-ttu-id="1c6a7-104">新しいインスタンスを初期化、 <see cref="T:Microsoft.ServiceBus.Messaging.Lease" /> 、指定したクラス<see cref="M:Microsoft.ServiceBus.Messaging.Lease.#ctor(Microsoft.ServiceBus.Messaging.Lease)" />参照と値。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.Lease" /> class with the specified <see cref="M:Microsoft.ServiceBus.Messaging.Lease.#ctor(Microsoft.ServiceBus.Messaging.Lease)" /> value as reference.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Epoch">
      <MemberSignature Language="C#" Value="public long Epoch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Epoch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.Epoch" />
      <MemberSignature Language="VB.NET" Value="Public Property Epoch As Long" />
      <MemberSignature Language="F#" Value="member this.Epoch : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.Epoch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="1c6a7-105">取得または競合するノードの間でパーティションの最新の所有者を特定する使用できる値は、リースのエポック年を設定します。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-105">Gets or sets the epoch year of the lease, which is a value you can use to determine the most recent owner of a partition between competing nodes.</span></span></summary>
        <value><span data-ttu-id="1c6a7-106">リースのエポック年。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-106">The epoch year of the lease.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Lease.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="lease.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="1c6a7-107">比較対象のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-107">The object to compare.</span></span></param>
        <summary><span data-ttu-id="1c6a7-108">このインスタンスが、指定したオブジェクトと等しいかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-108">Determines whether this instance is equal to the specified object.</span></span></summary>
        <returns><span data-ttu-id="1c6a7-109">このインスタンスが指定したオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-109">true if this instance is equal to the specified object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Lease.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="lease.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="1c6a7-110">現在のインスタンスのハッシュ コードを返します。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-110">Returns the hash code of the current instance.</span></span></summary>
        <returns><span data-ttu-id="1c6a7-111">現在のインスタンスのハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-111">The hash code of the current instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsExpired">
      <MemberSignature Language="C#" Value="public virtual bool IsExpired ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsExpired() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Lease.IsExpired" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsExpired () As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsExpired : unit -&gt; bool&#xA;override this.IsExpired : unit -&gt; bool" Usage="lease.IsExpired " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="1c6a7-112">リースの期限が切れているかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-112">Determines whether the lease is expired.</span></span></summary>
        <returns><span data-ttu-id="1c6a7-113">リースの有効期限が切れて; 場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-113">true if the lease is expired; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offset">
      <MemberSignature Language="C#" Value="public string Offset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />
      <MemberSignature Language="VB.NET" Value="Public Property Offset As String" />
      <MemberSignature Language="F#" Value="member this.Offset : string with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.Offset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="1c6a7-114">取得またはストリーム内のオフセットの現在の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-114">Gets or sets the current value for the offset in the stream.</span></span></summary>
        <value><span data-ttu-id="1c6a7-115">リースのオフセット。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-115">The lease offset.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Owner">
      <MemberSignature Language="C#" Value="public string Owner { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Owner" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.Owner" />
      <MemberSignature Language="VB.NET" Value="Public Property Owner As String" />
      <MemberSignature Language="F#" Value="member this.Owner : string with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.Owner" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="1c6a7-116">取得またはパーティションのホスト所有者を設定します。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-116">Gets or sets the host owner for the partition.</span></span></summary>
        <value><span data-ttu-id="1c6a7-117">パーティションのホストの所有者です。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-117">The host owner of the partition.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="1c6a7-118">このリースが属しているパーティションの ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-118">Gets the ID of the partition to which this lease belongs.</span></span></summary>
        <value><span data-ttu-id="1c6a7-119">パーティションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-119">The partition identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="1c6a7-120">取得またはストリームの最後のチェックポイントが設定されたシーケンス番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-120">Gets or sets the last checkpointed sequence number in the stream.</span></span></summary>
        <value><span data-ttu-id="1c6a7-121"><see cref="T:System.Int64" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-121">Returns <see cref="T:System.Int64" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.Token" />
      <MemberSignature Language="VB.NET" Value="Public Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.Token" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="1c6a7-122">取得またはホスト間で同時に管理リース トークンを設定します。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-122">Gets or sets the lease token that manages concurrency between hosts.</span></span> <span data-ttu-id="1c6a7-123">必要なすべてのリソースへの単一のアクセスを保証するためにこのトークンを使用することができます、<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-123">You can use this token to guarantee single access to any resource needed by the <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> object.</span></span></summary>
        <value><span data-ttu-id="1c6a7-124">リース トークンです。</span><span class="sxs-lookup"><span data-stu-id="1c6a7-124">The lease token.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>