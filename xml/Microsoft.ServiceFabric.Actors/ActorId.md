<Type Name="ActorId" FullName="Microsoft.ServiceFabric.Actors.ActorId">
  <TypeSignature Language="C#" Value="public sealed class ActorId : IComparable&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;, IEquatable&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorId extends System.Object implements class System.IComparable`1&lt;class Microsoft.ServiceFabric.Actors.ActorId&gt;, class System.IEquatable`1&lt;class Microsoft.ServiceFabric.Actors.ActorId&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.ActorId" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorId&#xA;Implements IComparable(Of ActorId), IEquatable(Of ActorId)" />
  <TypeSignature Language="F#" Value="type ActorId = class&#xA;    interface IEquatable&lt;ActorId&gt;&#xA;    interface IComparable&lt;ActorId&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IComparable&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="ActorId")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="dd739-101">ActorId では、アクター サービス内でアクターの id を表します。</span><span class="sxs-lookup"><span data-stu-id="dd739-101">The ActorId represents the identity of an actor within an actor service.</span></span> <span data-ttu-id="dd739-102">これには、使用するアクターが実行を参照してください、アクター サービスのパーティションを識別するには<see cref="M:Microsoft.ServiceFabric.Actors.ActorId.GetPartitionKey" /></span><span class="sxs-lookup"><span data-stu-id="dd739-102">This is used to identify the partition of the actor service inside which the actor will run, see <see cref="M:Microsoft.ServiceFabric.Actors.ActorId.GetPartitionKey" /></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorId (Guid id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.#ctor(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As Guid)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.ActorId : Guid -&gt; Microsoft.ServiceFabric.Actors.ActorId" Usage="new Microsoft.ServiceFabric.Actors.ActorId id" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="dd739-103">アクターの id の値です。</span><span class="sxs-lookup"><span data-stu-id="dd739-103">Value for actor id.</span></span></param>
        <summary>
            <span data-ttu-id="dd739-104">型の Id 値を持つ ActorId クラスの新しいインスタンスを初期化<see cref="T:System.Guid" />です。</span><span class="sxs-lookup"><span data-stu-id="dd739-104">Initializes a new instance of ActorId class with Id value of type <see cref="T:System.Guid" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorId (long id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.#ctor(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.ActorId : int64 -&gt; Microsoft.ServiceFabric.Actors.ActorId" Usage="new Microsoft.ServiceFabric.Actors.ActorId id" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="dd739-105">アクターの id の値です。</span><span class="sxs-lookup"><span data-stu-id="dd739-105">Value for actor id.</span></span></param>
        <summary>
            <span data-ttu-id="dd739-106">型の Id 値を持つ ActorId クラスの新しいインスタンスを初期化<see cref="T:System.Int64" />です。</span><span class="sxs-lookup"><span data-stu-id="dd739-106">Initializes a new instance of ActorId class with Id value of type <see cref="T:System.Int64" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorId (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.ActorId : string -&gt; Microsoft.ServiceFabric.Actors.ActorId" Usage="new Microsoft.ServiceFabric.Actors.ActorId id" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="dd739-107">アクターの id の値です。</span><span class="sxs-lookup"><span data-stu-id="dd739-107">Value for actor id.</span></span></param>
        <summary>
            <span data-ttu-id="dd739-108">型の Id 値を持つ ActorId クラスの新しいインスタンスを初期化<see cref="T:System.String" />です。</span><span class="sxs-lookup"><span data-stu-id="dd739-108">Initializes a new instance of ActorId class with Id value of type <see cref="T:System.String" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompareTo">
      <MemberSignature Language="C#" Value="public int CompareTo (Microsoft.ServiceFabric.Actors.ActorId other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 CompareTo(class Microsoft.ServiceFabric.Actors.ActorId other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.CompareTo(Microsoft.ServiceFabric.Actors.ActorId)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompareTo (other As ActorId) As Integer" />
      <MemberSignature Language="F#" Value="abstract member CompareTo : Microsoft.ServiceFabric.Actors.ActorId -&gt; int&#xA;override this.CompareTo : Microsoft.ServiceFabric.Actors.ActorId -&gt; int" Usage="actorId.CompareTo other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IComparable`1.CompareTo(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.ServiceFabric.Actors.ActorId" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="dd739-109">このインスタンスと比較する actorId です。</span><span class="sxs-lookup"><span data-stu-id="dd739-109">The actorId to compare with this instance.</span></span> </param>
        <summary>
            <span data-ttu-id="dd739-110">このインスタンスと指定した比較<see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />オブジェクトをこのインスタンスについてよりも前、後ろ、またはが指定されていると、並べ替え順序において同じ位置に表示されますでかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="dd739-110">Compares this instance with a specified <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> object and indicates whether this instance precedes, follows, or appears in the same position in the sort order as the specified actorId.</span></span> 
            </summary>
        <returns><span data-ttu-id="dd739-111">このインスタンスについてよりも前、後ろ、または、他のパラメーターと並べ替え順序で同じ位置に表示されますでかどうかを示す 32 ビット符号付き整数。</span><span class="sxs-lookup"><span data-stu-id="dd739-111">A 32-bit signed integer that indicates whether this instance precedes, follows, or appears in the same position in the sort order as the other parameter.</span></span></returns>
        <remarks><span data-ttu-id="dd739-112">同じ、両方のインスタンスである場合は、比較を id に基づいて行われます<see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />です。</span><span class="sxs-lookup"><span data-stu-id="dd739-112">The comparison is done based on the id if both the instances have same <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />.</span></span>
            <span data-ttu-id="dd739-113">場合<see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />は比較を実行し、異なるに基づいてアクター id の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="dd739-113">If <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> is different, then comparison is done based on string representation of the actor id.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRandom">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Actors.ActorId CreateRandom ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Actors.ActorId CreateRandom() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.CreateRandom" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateRandom () As ActorId" />
      <MemberSignature Language="F#" Value="static member CreateRandom : unit -&gt; Microsoft.ServiceFabric.Actors.ActorId" Usage="Microsoft.ServiceFabric.Actors.ActorId.CreateRandom " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorId</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dd739-114">新しいインスタンスを作成、<see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />の種類の<see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Long" />ランダムで<see cref="T:System.Int64" />id 値です。</span><span class="sxs-lookup"><span data-stu-id="dd739-114">Create a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> of kind <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Long" /> with a random <see cref="T:System.Int64" /> id value.</span></span> 
            </summary>
        <returns><span data-ttu-id="dd739-115">新しい ActorId オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="dd739-115">A new ActorId object.</span></span></returns>
        <remarks><span data-ttu-id="dd739-116">このメソッドはスレッド セーフであり、新しい生成ランダム<see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />たびに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="dd739-116">This method is thread-safe and generates a new random <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> every time it is called.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.ServiceFabric.Actors.ActorId other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.ServiceFabric.Actors.ActorId other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.Equals(Microsoft.ServiceFabric.Actors.ActorId)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As ActorId) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.ServiceFabric.Actors.ActorId -&gt; bool" Usage="actorId.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.ServiceFabric.Actors.ActorId" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="dd739-117">このインスタンスと比較する actorId です。</span><span class="sxs-lookup"><span data-stu-id="dd739-117">The actorId to compare to this instance.</span></span> </param>
        <summary>
            <span data-ttu-id="dd739-118">このインスタンスと、指定した別の <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> の値が同一かどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="dd739-118">Determines whether this instance and another specified <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> object have the same value.</span></span>
            </summary>
        <returns><span data-ttu-id="dd739-119">true の場合、<see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />とその他のパラメーターの id は同じです、 <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> ; このインスタンスの id とそれ以外の場合は false。</span><span class="sxs-lookup"><span data-stu-id="dd739-119">true if the <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> and id of the other parameter is the same as the <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> and id of this instance; otherwise, false.</span></span> <span data-ttu-id="dd739-120">その他のフィールドが null の場合、メソッドは false を返します。</span><span class="sxs-lookup"><span data-stu-id="dd739-120">If other is null, the method returns false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="actorId.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="dd739-121">このインスタンスと比較する actorId です。</span><span class="sxs-lookup"><span data-stu-id="dd739-121">The actorId to compare to this instance.</span></span> </param>
        <summary>
            <span data-ttu-id="dd739-122">このインスタンスと、指定したオブジェクトの値が同一かどうかを判断します。<see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> オブジェクトを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="dd739-122">Determines whether this instance and a specified object, which must also be a <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> object, have the same value.</span></span> <span data-ttu-id="dd739-123">オーバーライド<see cref="M:System.Object.Equals(System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="dd739-123">Overrides <see cref="M:System.Object.Equals(System.Object)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="dd739-124">obj が場合は true、<see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />し、その値がこのインスタンスと同じです。 それ以外の場合は false。</span><span class="sxs-lookup"><span data-stu-id="dd739-124">true if obj is a <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> and its value is the same as this instance; otherwise, false.</span></span> <span data-ttu-id="dd739-125">Obj が null の場合、メソッドは false を返します。</span><span class="sxs-lookup"><span data-stu-id="dd739-125">If obj is null, the method returns false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGuidId">
      <MemberSignature Language="C#" Value="public Guid GetGuidId ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.Guid GetGuidId() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.GetGuidId" />
      <MemberSignature Language="VB.NET" Value="Public Function GetGuidId () As Guid" />
      <MemberSignature Language="F#" Value="member this.GetGuidId : unit -&gt; Guid" Usage="actorId.GetGuidId " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dd739-126">ActorId の id を取得が<see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />は<see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Guid" />します。</span><span class="sxs-lookup"><span data-stu-id="dd739-126">Gets id for ActorId whose <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> is <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Guid" />.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="dd739-127"><see cref="T:System.Guid" />ActorId の id 値です。</span><span class="sxs-lookup"><span data-stu-id="dd739-127"><see cref="T:System.Guid" />The id value for ActorId.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="dd739-128"><see cref="P:Microsoft.ServiceFabric.Actors.ActorId.Kind" />はありません<see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Guid" /></span><span class="sxs-lookup"><span data-stu-id="dd739-128">The <see cref="P:Microsoft.ServiceFabric.Actors.ActorId.Kind" /> is not <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Guid" /></span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="actorId.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dd739-129">オーバーライド<see cref="M:System.Object.GetHashCode" />です。</span><span class="sxs-lookup"><span data-stu-id="dd739-129">Overrides <see cref="M:System.Object.GetHashCode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="dd739-130">現在のオブジェクトのハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="dd739-130">Hash code for the current object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLongId">
      <MemberSignature Language="C#" Value="public long GetLongId ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int64 GetLongId() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.GetLongId" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLongId () As Long" />
      <MemberSignature Language="F#" Value="member this.GetLongId : unit -&gt; int64" Usage="actorId.GetLongId " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dd739-131">ActorId の id を取得が<see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />は<see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Long" />します。</span><span class="sxs-lookup"><span data-stu-id="dd739-131">Gets id for ActorId whose <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> is <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Long" />.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="dd739-132"><see cref="T:System.Int64" />ActorId の id 値です。</span><span class="sxs-lookup"><span data-stu-id="dd739-132"><see cref="T:System.Int64" />The id value for ActorId.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="dd739-133"><see cref="P:Microsoft.ServiceFabric.Actors.ActorId.Kind" />はありません<see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Long" /></span><span class="sxs-lookup"><span data-stu-id="dd739-133">The <see cref="P:Microsoft.ServiceFabric.Actors.ActorId.Kind" /> is not <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Long" /></span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionKey">
      <MemberSignature Language="C#" Value="public long GetPartitionKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int64 GetPartitionKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.GetPartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionKey () As Long" />
      <MemberSignature Language="F#" Value="member this.GetPartitionKey : unit -&gt; int64" Usage="actorId.GetPartitionKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dd739-134">この ActorId のパーティション キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="dd739-134">Gets the partition key for this ActorId.</span></span>
            </summary>
        <returns><span data-ttu-id="dd739-135">この ActorId を担当するアクター サービスのパーティションを検索するためのキー。</span><span class="sxs-lookup"><span data-stu-id="dd739-135">The key for locating the partition of the actor service that is responsible for this ActorId.</span></span></returns>
        <remarks>
          <list type="bullet">
            <item><span data-ttu-id="dd739-136">アクター サービスが常にパーティション分割を使用して<see cref="F:System.Fabric.Description.PartitionScheme.UniformInt64Range" />スキームです。</span><span class="sxs-lookup"><span data-stu-id="dd739-136">The actor service is always partitioned using <see cref="F:System.Fabric.Description.PartitionScheme.UniformInt64Range" /> scheme.</span></span> <span data-ttu-id="dd739-137">したがって、パーティション キーが<see cref="T:System.Int64" />型です。</span><span class="sxs-lookup"><span data-stu-id="dd739-137">Therefore the partition key is of <see cref="T:System.Int64" /> type.</span></span></item>
            <item><span data-ttu-id="dd739-138">基づくパーティション分割キーを生成、<see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />次のようにする id 値および: <list type="bullet"> <item> <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.String" />: UTF8 バイト文字列 id の CRC64 ハッシュ</item><item> <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Guid" />: Guid id のバイト数の CRC64 ハッシュ</item><item> <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Long" />: 長い id の実際の値。</item></list></span><span class="sxs-lookup"><span data-stu-id="dd739-138">The partition key is generated based on the <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> and the id value as follows: <list type="bullet"><item><see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.String" />: CRC64 hash of the UTF8 bytes of the string id.</item><item><see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Guid" />: CRC64 hash of the bytes of the guid id.</item><item><see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Long" />: Actual value of the long id.</item></list></span></span></item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStringId">
      <MemberSignature Language="C#" Value="public string GetStringId ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetStringId() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.GetStringId" />
      <MemberSignature Language="VB.NET" Value="Public Function GetStringId () As String" />
      <MemberSignature Language="F#" Value="member this.GetStringId : unit -&gt; string" Usage="actorId.GetStringId " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dd739-139">ActorId の id を取得が<see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />は<see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.String" />します。</span><span class="sxs-lookup"><span data-stu-id="dd739-139">Gets id for ActorId whose <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> is <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.String" />.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="dd739-140"><see cref="T:System.String" />ActorId の id 値です。</span><span class="sxs-lookup"><span data-stu-id="dd739-140"><see cref="T:System.String" />The id value for ActorId.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="dd739-141"><see cref="P:Microsoft.ServiceFabric.Actors.ActorId.Kind" />はありません<see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Guid" /></span><span class="sxs-lookup"><span data-stu-id="dd739-141">The <see cref="P:Microsoft.ServiceFabric.Actors.ActorId.Kind" /> is not <see cref="F:Microsoft.ServiceFabric.Actors.ActorIdKind.Guid" /></span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.ActorIdKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Actors.ActorIdKind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.ActorId.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As ActorIdKind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.ServiceFabric.Actors.ActorIdKind" Usage="Microsoft.ServiceFabric.Actors.ActorId.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorIdKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd739-142">取得、 <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> ActorId 用です。</span><span class="sxs-lookup"><span data-stu-id="dd739-142">Gets the <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> for the ActorId.</span></span>
            </summary>
        <value>
          <span data-ttu-id="dd739-143"><see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />ActorId します。</span><span class="sxs-lookup"><span data-stu-id="dd739-143"><see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> for the ActorId.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (Microsoft.ServiceFabric.Actors.ActorId x, Microsoft.ServiceFabric.Actors.ActorId y);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(class Microsoft.ServiceFabric.Actors.ActorId x, class Microsoft.ServiceFabric.Actors.ActorId y) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.op_Equality(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.ActorId)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (x As ActorId, y As ActorId) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : Microsoft.ServiceFabric.Actors.ActorId * Microsoft.ServiceFabric.Actors.ActorId -&gt; bool" Usage="x = y" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="x" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="y" Type="Microsoft.ServiceFabric.Actors.ActorId" />
      </Parameters>
      <Docs>
        <param name="x"><span data-ttu-id="dd739-144">Null の比較、または最初 actorId です。</span><span class="sxs-lookup"><span data-stu-id="dd739-144">The first actorId to compare, or null.</span></span> </param>
        <param name="y"><span data-ttu-id="dd739-145">Null の比較、または 2 番目の actorId します。</span><span class="sxs-lookup"><span data-stu-id="dd739-145">The second actorId to compare, or null.</span></span> </param>
        <summary>
            <span data-ttu-id="dd739-146">2 つの指定した actorIds は、同じ id を持っているかどうかを判断し、<see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />です。</span><span class="sxs-lookup"><span data-stu-id="dd739-146">Determines whether two specified actorIds have the same id and <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />.</span></span>
            </summary>
        <returns><span data-ttu-id="dd739-147">true の場合、id および<see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />が同じ 2 つのオブジェクト。 それ以外の場合、false です。</span><span class="sxs-lookup"><span data-stu-id="dd739-147">true if the id and <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> is same for both objects; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (Microsoft.ServiceFabric.Actors.ActorId x, Microsoft.ServiceFabric.Actors.ActorId y);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(class Microsoft.ServiceFabric.Actors.ActorId x, class Microsoft.ServiceFabric.Actors.ActorId y) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.op_Inequality(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.ActorId)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (x As ActorId, y As ActorId) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : Microsoft.ServiceFabric.Actors.ActorId * Microsoft.ServiceFabric.Actors.ActorId -&gt; bool" Usage="Microsoft.ServiceFabric.Actors.ActorId.op_Inequality (x, y)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="x" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="y" Type="Microsoft.ServiceFabric.Actors.ActorId" />
      </Parameters>
      <Docs>
        <param name="x"><span data-ttu-id="dd739-148">Null の比較、または最初 actorId です。</span><span class="sxs-lookup"><span data-stu-id="dd739-148">The first actorId to compare, or null.</span></span> </param>
        <param name="y"><span data-ttu-id="dd739-149">Null の比較、または 2 番目の actorId します。</span><span class="sxs-lookup"><span data-stu-id="dd739-149">The second actorId to compare, or null.</span></span> </param>
        <summary>
            <span data-ttu-id="dd739-150">2 つの指定された actorIds が id の値が異なるかどうかを判断し、<see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />です。</span><span class="sxs-lookup"><span data-stu-id="dd739-150">Determines whether two specified actorIds have different values for id and <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />.</span></span>
            </summary>
        <returns><span data-ttu-id="dd739-151">true の場合、id または<see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" />が両方のオブジェクトのさまざまなであるそれ以外の場合、true を指定します。</span><span class="sxs-lookup"><span data-stu-id="dd739-151">true if the id or <see cref="T:Microsoft.ServiceFabric.Actors.ActorIdKind" /> is different for both objects; otherwise, true.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorId.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="actorId.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dd739-152">オーバーライド<see cref="M:System.Object.ToString" />です。</span><span class="sxs-lookup"><span data-stu-id="dd739-152">Overrides <see cref="M:System.Object.ToString" />.</span></span>
            </summary>
        <returns><span data-ttu-id="dd739-153">現在のオブジェクトを表す文字列を返します。</span><span class="sxs-lookup"><span data-stu-id="dd739-153">Returns a string that represents the current object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>