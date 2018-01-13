<Type Name="Epoch" FullName="System.Fabric.Epoch">
  <TypeSignature Language="C#" Value="public struct Epoch : IComparable&lt;System.Fabric.Epoch&gt;, IEquatable&lt;System.Fabric.Epoch&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi serializable sealed beforefieldinit Epoch extends System.ValueType implements class System.IComparable`1&lt;valuetype System.Fabric.Epoch&gt;, class System.IEquatable`1&lt;valuetype System.Fabric.Epoch&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Epoch" />
  <TypeSignature Language="VB.NET" Value="Public Structure Epoch&#xA;Implements IComparable(Of Epoch), IEquatable(Of Epoch)" />
  <TypeSignature Language="F#" Value="type Epoch = struct" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IComparable&lt;System.Fabric.Epoch&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IEquatable&lt;System.Fabric.Epoch&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para> <span data-ttu-id="1be97-101">Service Fabric でパーティションの現在のバージョンを表します。</span><span class="sxs-lookup"><span data-stu-id="1be97-101">Represents the current version of the partition in Service Fabric.</span></span> </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="1be97-102">エポックは、全体として、パーティションの構成番号です。</span><span class="sxs-lookup"><span data-stu-id="1be97-102">An Epoch is a configuration number for the partition as a whole.</span></span> <span data-ttu-id="1be97-103">レプリカの構成は、プライマリ レプリカの変更、新しいプライマリ レプリカからレプリケートされた操作は、古いプライマリ レプリカによって送信されたものから新しいエポックと呼ばれますと例については、変更を設定するとします。</span><span class="sxs-lookup"><span data-stu-id="1be97-103">When the configuration of the replica set changes, for example when the Primary replica changes, the operations that are replicated from the new Primary replica are said to be a new Epoch from the ones which were sent by the old Primary replica.</span></span> <span data-ttu-id="1be97-104">プライマリが変更されたというは、通常、元のプライマリ レプリカの影響を受ける失敗によって影響を受けませんセカンダリ レプリカに直接表示されません。</span><span class="sxs-lookup"><span data-stu-id="1be97-104">The fact that the Primary has changed is not directly visible to Secondary replicas, which are usually unaffected by the failure that affected the original Primary replica.</span></span> <span data-ttu-id="1be97-105">プライマリ レプリカが変更されたことを追跡するために、セカンダリ レプリカに伝達するがします。</span><span class="sxs-lookup"><span data-stu-id="1be97-105">To track that the Primary replica has changed has to be communicated to the Secondary replica.</span></span> <span data-ttu-id="1be97-106">使用してこのような通信が発生した、<see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="1be97-106">This communication occurs via the <see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" /> method.</span></span> <span data-ttu-id="1be97-107">ほとんどのサービスは、エポックが変更されたことを認識し、システム内の操作とイベントの相対順序を判別するエポックを比較する通常で十分ですので、エポックの内部フィールドの詳細を無視してかまいません。</span><span class="sxs-lookup"><span data-stu-id="1be97-107">Most services can ignore the details of the inner fields of the Epoch as it is usually sufficient to know that the Epoch has changed and to compare Epochs to determine relative ordering of operations and events in the system.</span></span> <span data-ttu-id="1be97-108">比較操作は、この目的で提供されます。</span><span class="sxs-lookup"><span data-stu-id="1be97-108">Comparison operations are provided for this purpose.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Epoch (long dataLossNumber, long configurationNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 dataLossNumber, int64 configurationNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.#ctor(System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (dataLossNumber As Long, configurationNumber As Long)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Epoch : int64 * int64 -&gt; System.Fabric.Epoch" Usage="new System.Fabric.Epoch (dataLossNumber, configurationNumber)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataLossNumber" Type="System.Int64" />
        <Parameter Name="configurationNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="dataLossNumber">
          <para><span data-ttu-id="1be97-109"><see cref="T:System.Int64" />データの損失が疑われるたびに更新される増加する値を表すです。</span><span class="sxs-lookup"><span data-stu-id="1be97-109">An <see cref="T:System.Int64" /> representing an increasing value which is updated whenever data loss is suspected.</span></span></para>
        </param>
        <param name="configurationNumber">
          <para><span data-ttu-id="1be97-110"><see cref="T:System.Int64" />このレプリカの設定が変更されるたびに更新が増加する値を表すです。</span><span class="sxs-lookup"><span data-stu-id="1be97-110">An <see cref="T:System.Int64" /> representing an increasing value that is updated whenever the configuration of this replica set changes.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1be97-111">新しいインスタンスを初期化、<see cref="T:System.Fabric.Epoch" />構成番号と指定したデータ損失の数を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="1be97-111">Initializes a new instance of the <see cref="T:System.Fabric.Epoch" /> class with the specified data loss number and configuration number.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompareTo">
      <MemberSignature Language="C#" Value="public int CompareTo (System.Fabric.Epoch other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 CompareTo(valuetype System.Fabric.Epoch other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.CompareTo(System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompareTo (other As Epoch) As Integer" />
      <MemberSignature Language="F#" Value="abstract member CompareTo : System.Fabric.Epoch -&gt; int&#xA;override this.CompareTo : System.Fabric.Epoch -&gt; int" Usage="epoch.CompareTo other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IComparable`1.CompareTo(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="other">
          <para><span data-ttu-id="1be97-112"><see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-112">The <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1be97-113">これと比較<see cref="T:System.Fabric.Epoch" />を指定したオブジェクト<paramref name="other" /><see cref="T:System.Fabric.Epoch" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-113">Compares this <see cref="T:System.Fabric.Epoch" /> object to the specified <paramref name="other" /><see cref="T:System.Fabric.Epoch" /> object.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1be97-114"><see cref="T:System.Int32" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="1be97-114">Returns <see cref="T:System.Int32" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationNumber">
      <MemberSignature Language="C#" Value="public long ConfigurationNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ConfigurationNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Epoch.ConfigurationNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property ConfigurationNumber As Long" />
      <MemberSignature Language="F#" Value="member this.ConfigurationNumber : int64 with get, set" Usage="System.Fabric.Epoch.ConfigurationNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1be97-115">この現在の構成番号のプロパティを設定を取得または<see cref="T:System.Fabric.Epoch" />です。</span><span class="sxs-lookup"><span data-stu-id="1be97-115">Gets or sets the current configuration number property in this <see cref="T:System.Fabric.Epoch" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="1be97-116">返します、<see cref="T:System.Int64" />構成番号を表します。</span><span class="sxs-lookup"><span data-stu-id="1be97-116">Returns an <see cref="T:System.Int64" /> representing the configuration number.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="1be97-117">構成番号は、このレプリカの設定が変更されるたびに更新される増加する値です。</span><span class="sxs-lookup"><span data-stu-id="1be97-117">The configuration number is an increasing value that is updated whenever the configuration of this replica set changes.</span></span> <span data-ttu-id="1be97-118">サービスが通知され、現在の構成番号の場合にのみ<see cref="M:System.Fabric.IReplicator.UpdateEpochAsync(System.Fabric.Epoch,System.Threading.CancellationToken)" />メソッドは、レプリカ セットのプライマリ レプリカを変更しようとすると、結果として呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="1be97-118">The services are informed of the current configuration number only when <see cref="M:System.Fabric.IReplicator.UpdateEpochAsync(System.Fabric.Epoch,System.Threading.CancellationToken)" /> method is called as a result of an attempt to change the Primary replica of the replica set.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLossNumber">
      <MemberSignature Language="C#" Value="public long DataLossNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DataLossNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Epoch.DataLossNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property DataLossNumber As Long" />
      <MemberSignature Language="F#" Value="member this.DataLossNumber : int64 with get, set" Usage="System.Fabric.Epoch.DataLossNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1be97-119">この現在のデータ ロス数を取得<see cref="T:System.Fabric.Epoch" />です。</span><span class="sxs-lookup"><span data-stu-id="1be97-119">Gets the current data loss number in this <see cref="T:System.Fabric.Epoch" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="1be97-120">返します、<see cref="T:System.Int64" />現在のデータが失われる番号を表します。</span><span class="sxs-lookup"><span data-stu-id="1be97-120">Returns an <see cref="T:System.Int64" /> representing the current data loss number.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="1be97-121">データ損失の数のプロパティは、レプリカのレプリカのクォーラムの損失を設定しているプライマリ レプリカを含む場合として、データの損失が疑われるたびに更新される増加する値です。</span><span class="sxs-lookup"><span data-stu-id="1be97-121">The data loss number property is an increasing value which is updated whenever data loss is suspected, as when loss of a quorum of replicas in the replica set that includes the Primary replica.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (System.Fabric.Epoch other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(valuetype System.Fabric.Epoch other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.Equals(System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : System.Fabric.Epoch -&gt; bool" Usage="epoch.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="other">
          <para><span data-ttu-id="1be97-122">現在の <see cref="T:System.Fabric.Epoch" /> オブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-122">The object to compare with the current <see cref="T:System.Fabric.Epoch" /> object.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1be97-123">決定するかどうか、指定した<see cref="T:System.Fabric.Epoch" />オブジェクトが現在<see cref="T:System.Fabric.Epoch" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-123">Determines whether the specified <see cref="T:System.Fabric.Epoch" /> object is equal to the current <see cref="T:System.Fabric.Epoch" /> object.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="1be97-124"><languageKeyword>true</languageKeyword>場合、指定した<see cref="T:System.Fabric.Epoch" />オブジェクトが現在<see cref="T:System.Fabric.Epoch" />オブジェクト。 それ以外の場合、 <languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="1be97-124"><languageKeyword>true</languageKeyword> if the specified <see cref="T:System.Fabric.Epoch" /> object is equal to the current <see cref="T:System.Fabric.Epoch" /> object; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="epoch.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">
          <para><span data-ttu-id="1be97-125">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-125">The object to compare with the current object.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1be97-126">指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="1be97-126">Determines whether the specified object is equal to the current object.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="1be97-127"><languageKeyword>true</languageKeyword>指定したオブジェクトが現在のオブジェクトと等しい、それ以外の場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="1be97-127"><languageKeyword>true</languageKeyword> if the specified object is equal to the current object; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="epoch.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="1be97-128">ハッシュ関数として機能、<see cref="T:System.Fabric.Epoch" />型です。</span><span class="sxs-lookup"><span data-stu-id="1be97-128">Serves as a hash function for the <see cref="T:System.Fabric.Epoch" /> type.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1be97-129">A<see cref="T:System.Int32" />現在のハッシュ コードを表す<see cref="T:System.Fabric.Epoch" />.</span><span class="sxs-lookup"><span data-stu-id="1be97-129">A <see cref="T:System.Int32" /> representing a hash code for the current <see cref="T:System.Fabric.Epoch" />..</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_Equality(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left = right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para><span data-ttu-id="1be97-130">左側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-130">The left <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <param name="right">
          <para><span data-ttu-id="1be97-131">右側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-131">The right <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1be97-132">指定した 2 つの <see cref="T:System.Fabric.Epoch" /> オブジェクトの値が同一かどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="1be97-132">Determines whether two specified <see cref="T:System.Fabric.Epoch" /> objects have the same value.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="1be97-133"><languageKeyword>true</languageKeyword>場合の値<paramref name="left" />はの値と同じ<paramref name="right" />、それ以外の<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="1be97-133"><languageKeyword>true</languageKeyword> if the value of <paramref name="left" /> is the same as the value of <paramref name="right" />; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_GreaterThan">
      <MemberSignature Language="C#" Value="public static bool operator &gt; (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_GreaterThan(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_GreaterThan(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &gt; (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &gt; ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left &gt; right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para><span data-ttu-id="1be97-134">左側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-134">The left <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <param name="right">
          <para><span data-ttu-id="1be97-135">右側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-135">The right <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1be97-136">いずれかを指定するかどうかを判断<see cref="T:System.Fabric.Epoch" />オブジェクトが指定した別のよりも大きい<see cref="T:System.Fabric.Epoch" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-136">Determines whether one specified <see cref="T:System.Fabric.Epoch" /> object is greater than another specified <see cref="T:System.Fabric.Epoch" /> object.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="1be97-137"><languageKeyword>true</languageKeyword>場合の値<paramref name="left" />の値よりも大きい<paramref name="right" />、それ以外の<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="1be97-137"><languageKeyword>true</languageKeyword> if the value of <paramref name="left" /> is greater than the value of <paramref name="right" />; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_GreaterThanOrEqual">
      <MemberSignature Language="C#" Value="public static bool operator &gt;= (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_GreaterThanOrEqual(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_GreaterThanOrEqual(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &gt;= (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &gt;= ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left &gt;= right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para><span data-ttu-id="1be97-138">左側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-138">The left <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <param name="right">
          <para><span data-ttu-id="1be97-139">右側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-139">The right <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1be97-140">いずれかを指定するかどうかを判断<see cref="T:System.Fabric.Epoch" />オブジェクトが指定した別以上<see cref="T:System.Fabric.Epoch" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-140">Determines whether one specified <see cref="T:System.Fabric.Epoch" /> object is greater than or equal to another specified <see cref="T:System.Fabric.Epoch" /> object.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="1be97-141"><languageKeyword>true</languageKeyword>場合の値<paramref name="left" />より大きいかの値に等しい<paramref name="right" />、それ以外の<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="1be97-141"><languageKeyword>true</languageKeyword> if the value of <paramref name="left" /> is greater than or equal to the value of <paramref name="right" />; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_Inequality(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="System.Fabric.Epoch.op_Inequality (left, right)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para><span data-ttu-id="1be97-142">左側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-142">The left <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <param name="right">
          <para><span data-ttu-id="1be97-143">右側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-143">The right <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1be97-144">指定した 2 つあるかどうかを判断<see cref="T:System.Fabric.Epoch" />オブジェクトが異なる値を設定します。</span><span class="sxs-lookup"><span data-stu-id="1be97-144">Determines whether two specified <see cref="T:System.Fabric.Epoch" /> objects have different values.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="1be97-145"><languageKeyword>true</languageKeyword>場合の値<paramref name="left" />の値とは異なる<paramref name="right" />、それ以外の<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="1be97-145"><languageKeyword>true</languageKeyword> if the value of <paramref name="left" /> is different than the value of <paramref name="right" />; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_LessThan">
      <MemberSignature Language="C#" Value="public static bool operator &lt; (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_LessThan(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_LessThan(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &lt; (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &lt; ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left &lt; right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para><span data-ttu-id="1be97-146">左側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-146">The left <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <param name="right">
          <para><span data-ttu-id="1be97-147">右側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-147">The right <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1be97-148">いずれかを指定するかどうかを判断<see cref="T:System.Fabric.Epoch" />オブジェクトが指定した別より小さい<see cref="T:System.Fabric.Epoch" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-148">Determines whether one specified <see cref="T:System.Fabric.Epoch" /> object is less than another specified <see cref="T:System.Fabric.Epoch" /> object.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="1be97-149"><languageKeyword>true</languageKeyword>場合の値<paramref name="left" />がの値より小さい<paramref name="right" />、それ以外の<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="1be97-149"><languageKeyword>true</languageKeyword> if the value of <paramref name="left" /> is less than the value of <paramref name="right" />; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_LessThanOrEqual">
      <MemberSignature Language="C#" Value="public static bool operator &lt;= (System.Fabric.Epoch left, System.Fabric.Epoch right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_LessThanOrEqual(valuetype System.Fabric.Epoch left, valuetype System.Fabric.Epoch right) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Epoch.op_LessThanOrEqual(System.Fabric.Epoch,System.Fabric.Epoch)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &lt;= (left As Epoch, right As Epoch) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &lt;= ) : System.Fabric.Epoch * System.Fabric.Epoch -&gt; bool" Usage="left &lt;= right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="System.Fabric.Epoch" />
        <Parameter Name="right" Type="System.Fabric.Epoch" />
      </Parameters>
      <Docs>
        <param name="left">
          <para><span data-ttu-id="1be97-150">左側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-150">The left <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <param name="right">
          <para><span data-ttu-id="1be97-151">右側の<see cref="T:System.Fabric.Epoch" />と比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-151">The right <see cref="T:System.Fabric.Epoch" /> object to compare.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1be97-152">いずれかを指定するかどうかを判断<see cref="T:System.Fabric.Epoch" />オブジェクトが指定した別小さい<see cref="T:System.Fabric.Epoch" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1be97-152">Determines whether one specified <see cref="T:System.Fabric.Epoch" /> object is less than or equal to another specified <see cref="T:System.Fabric.Epoch" /> object.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="1be97-153"><languageKeyword>true</languageKeyword>場合の値<paramref name="left" />がの値未満<paramref name="right" />、それ以外の<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="1be97-153"><languageKeyword>true</languageKeyword> if the value of <paramref name="left" /> is less than or equal to the value of <paramref name="right" />; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>