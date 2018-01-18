<Type Name="ShardRange" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange">
  <TypeSignature Language="C#" Value="public sealed class ShardRange : IComparable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt;, IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ShardRange extends System.Object implements class System.IComparable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt;, class System.IEquatable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ShardRange&#xA;Implements IComparable(Of ShardRange), IEquatable(Of ShardRange)" />
  <TypeSignature Language="F#" Value="type ShardRange = class&#xA;    interface IComparable&lt;ShardRange&gt;&#xA;    interface IEquatable&lt;ShardRange&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IComparable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="52731-101">低キーとキーの最高のシャード キーの範囲。</span><span class="sxs-lookup"><span data-stu-id="52731-101">A range of shard keys between a low key and a high key.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="52731-102">低キーでは、包括的 (範囲の一部) を高、中にキーが排他 (範囲に含まれていません)。</span><span class="sxs-lookup"><span data-stu-id="52731-102">The low key is inclusive (part of the range) while the high key is exclusive (not part of the range).</span></span> <span data-ttu-id="52731-103">ShardRange クラスは変更できません。</span><span class="sxs-lookup"><span data-stu-id="52731-103">The ShardRange class is immutable.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShardRange (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey low, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey high);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey low, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey high) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.#ctor(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (low As ShardKey, high As ShardKey)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange (low, high)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="low" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
        <Parameter Name="high" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
      </Parameters>
      <Docs>
        <param name="low"><span data-ttu-id="52731-104">低境界 (包括)</span><span class="sxs-lookup"><span data-stu-id="52731-104">Low boundary (inclusive)</span></span></param>
        <param name="high"><span data-ttu-id="52731-105">高境界 (排他)</span><span class="sxs-lookup"><span data-stu-id="52731-105">High boundary (exclusive)</span></span></param>
        <summary><span data-ttu-id="52731-106">低境界 (包括) のシャード範囲 (排他) 高の高い境界の構築します。</span><span class="sxs-lookup"><span data-stu-id="52731-106">Constructs a shard range from low boundary (inclusive) to high high boundary (exclusive)</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompareTo">
      <MemberSignature Language="C#" Value="public int CompareTo (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 CompareTo(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.CompareTo(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompareTo (other As ShardRange) As Integer" />
      <MemberSignature Language="F#" Value="abstract member CompareTo : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange -&gt; int&#xA;override this.CompareTo : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange -&gt; int" Usage="shardRange.CompareTo other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IComparable`1.CompareTo(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="52731-107">このオブジェクトと比較してシャードの範囲です。</span><span class="sxs-lookup"><span data-stu-id="52731-107">The shard range compared with this object.</span></span></param>
        <summary>
            <span data-ttu-id="52731-108">2 つのシャードの範囲値の間の比較を実行します。</span><span class="sxs-lookup"><span data-stu-id="52731-108">Performs comparison between two shard range values.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="52731-109">-1: この範囲の低い境界がより小さい<paramref name="other" />の低い境界;-1: の低い境界値に一致し、この範囲の高い境界値が場合よりも低い<paramref name="other" />' s。</span><span class="sxs-lookup"><span data-stu-id="52731-109">-1 : if this range's low boundary is less than the <paramref name="other" />'s low boundary; -1 : if the low boundary values match and the high boundary value of this range is less than the <paramref name="other" />'s.</span></span>
            <span data-ttu-id="52731-110">1: 境界がより大きい場合、この範囲の高、<paramref name="other" />の高い境界; 1: この範囲の低い境界値がより高いかどうか<paramref name="other" />の下限の境界および境界の高この範囲の値に等しいまたはそれよりも小さいです<paramref name="other" />の高い境界です。</span><span class="sxs-lookup"><span data-stu-id="52731-110">1 : if this range's high boundary is greater than the <paramref name="other" />'s high boundary; 1 : if the low boundary value of this range is higher than <paramref name="other" />'s low boundary and high boundary value of this range is less than or equal to <paramref name="other" />'s high boundary .</span></span>
             <span data-ttu-id="52731-111">0: この範囲と同じ境界がある場合<paramref name="other" />です。</span><span class="sxs-lookup"><span data-stu-id="52731-111">0 : if this range has the same boundaries as <paramref name="other" />.</span></span>
             </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Contains(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.Contains(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (key As ShardKey) As Boolean" />
      <MemberSignature Language="F#" Value="member this.Contains : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey -&gt; bool" Usage="shardRange.Contains key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="52731-112">チェックするキー</span><span class="sxs-lookup"><span data-stu-id="52731-112">The key to check</span></span></param>
        <summary><span data-ttu-id="52731-113">指定したキーが、範囲内かどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="52731-113">Checks whether the specified key is inside the range.</span></span></summary>
        <returns><span data-ttu-id="52731-114">内側、false の場合は true それ以外の場合</span><span class="sxs-lookup"><span data-stu-id="52731-114">True if inside, false otherwise</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange range);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Contains(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange range) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.Contains(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (range As ShardRange) As Boolean" />
      <MemberSignature Language="F#" Value="member this.Contains : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange -&gt; bool" Usage="shardRange.Contains range" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="range" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />
      </Parameters>
      <Docs>
        <param name="range"><span data-ttu-id="52731-115">確認する範囲。</span><span class="sxs-lookup"><span data-stu-id="52731-115">The range to check.</span></span></param>
        <summary><span data-ttu-id="52731-116">範囲が、範囲内かどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="52731-116">Checks whether the range is inside the range.</span></span></summary>
        <returns><span data-ttu-id="52731-117">内側、false の場合は true それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="52731-117">True if inside, false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.Equals(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As ShardRange) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange -&gt; bool" Usage="shardRange.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="52731-118">比較する ShardRange です。</span><span class="sxs-lookup"><span data-stu-id="52731-118">ShardRange to compare with.</span></span></param>
        <summary>
            <span data-ttu-id="52731-119">他の等値比較を実行 ShardRange を指定します。</span><span class="sxs-lookup"><span data-stu-id="52731-119">Performs equality comparison with another given ShardRange.</span></span>
            </summary>
        <returns><span data-ttu-id="52731-120">True の場合は、同じシャードの範囲、false それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="52731-120">True if same shard range, false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="shardRange.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="52731-121">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="52731-121">The object to compare with the current object.</span></span></param>
        <summary>
            <span data-ttu-id="52731-122">指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="52731-122">Determines whether the specified object is equal to the current object.</span></span>
            </summary>
        <returns><span data-ttu-id="52731-123">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="52731-123">True if the specified object is equal to the current object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FullRangeBinary">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange FullRangeBinary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange FullRangeBinary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.FullRangeBinary" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property FullRangeBinary As ShardRange" />
      <MemberSignature Language="F#" Value="member this.FullRangeBinary : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.FullRangeBinary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="52731-124">最大値をキーの最小値から始まる完全範囲です。</span><span class="sxs-lookup"><span data-stu-id="52731-124">Full range that starts from the min value for a key to the max value.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FullRangeDateTime">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange FullRangeDateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange FullRangeDateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.FullRangeDateTime" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property FullRangeDateTime As ShardRange" />
      <MemberSignature Language="F#" Value="member this.FullRangeDateTime : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.FullRangeDateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="52731-125">最大値をキーの最小値から始まる完全範囲です。</span><span class="sxs-lookup"><span data-stu-id="52731-125">Full range that starts from the min value for a key to the max value.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FullRangeDateTimeOffset">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange FullRangeDateTimeOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange FullRangeDateTimeOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.FullRangeDateTimeOffset" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property FullRangeDateTimeOffset As ShardRange" />
      <MemberSignature Language="F#" Value="member this.FullRangeDateTimeOffset : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.FullRangeDateTimeOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="52731-126">最大値をキーの最小値から始まる完全範囲です。</span><span class="sxs-lookup"><span data-stu-id="52731-126">Full range that starts from the min value for a key to the max value.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FullRangeGuid">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange FullRangeGuid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange FullRangeGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.FullRangeGuid" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property FullRangeGuid As ShardRange" />
      <MemberSignature Language="F#" Value="member this.FullRangeGuid : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.FullRangeGuid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="52731-127">最大値をキーの最小値から始まる完全範囲です。</span><span class="sxs-lookup"><span data-stu-id="52731-127">Full range that starts from the min value for a key to the max value.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FullRangeInt32">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange FullRangeInt32 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange FullRangeInt32" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.FullRangeInt32" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property FullRangeInt32 As ShardRange" />
      <MemberSignature Language="F#" Value="member this.FullRangeInt32 : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.FullRangeInt32" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="52731-128">最大値をキーの最小値から始まる完全範囲です。</span><span class="sxs-lookup"><span data-stu-id="52731-128">Full range that starts from the min value for a key to the max value.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FullRangeInt64">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange FullRangeInt64 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange FullRangeInt64" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.FullRangeInt64" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property FullRangeInt64 As ShardRange" />
      <MemberSignature Language="F#" Value="member this.FullRangeInt64 : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.FullRangeInt64" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="52731-129">最大値をキーの最小値から始まる完全範囲です。</span><span class="sxs-lookup"><span data-stu-id="52731-129">Full range that starts from the min value for a key to the max value.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FullRangeTimeSpan">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange FullRangeTimeSpan { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange FullRangeTimeSpan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.FullRangeTimeSpan" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property FullRangeTimeSpan As ShardRange" />
      <MemberSignature Language="F#" Value="member this.FullRangeTimeSpan : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.FullRangeTimeSpan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="52731-130">最大値をキーの最小値から始まる完全範囲です。</span><span class="sxs-lookup"><span data-stu-id="52731-130">Full range that starts from the min value for a key to the max value.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="shardRange.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="52731-131">このインスタンスのハッシュ コードを計算します。</span><span class="sxs-lookup"><span data-stu-id="52731-131">Calculates the hash code for this instance.</span></span>
            </summary>
        <returns><span data-ttu-id="52731-132">オブジェクトのハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="52731-132">Hash code for the object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="High">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey High { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey High" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.High" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property High As ShardKey" />
      <MemberSignature Language="F#" Value="member this.High : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.High" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="52731-133">高境界 (排他) のアクセサー。</span><span class="sxs-lookup"><span data-stu-id="52731-133">Accessor for high boundary (exclusive).</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType KeyType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType KeyType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.KeyType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyType As ShardKeyType" />
      <MemberSignature Language="F#" Value="member this.KeyType : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.KeyType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="52731-134">シャードの範囲のキーの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="52731-134">Gets the key type of shard range.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Low">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey Low { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey Low" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.Low" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Low As ShardKey" />
      <MemberSignature Language="F#" Value="member this.Low : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.Low" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="52731-135">低境界 (包括) のアクセサー。</span><span class="sxs-lookup"><span data-stu-id="52731-135">Accessor for low boundary (inclusive).</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange left, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange left, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.op_Equality(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (left As ShardRange, right As ShardRange) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange -&gt; bool" Usage="left = right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />
        <Parameter Name="right" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />
      </Parameters>
      <Docs>
        <param name="left"><span data-ttu-id="52731-136">左側にあります。</span><span class="sxs-lookup"><span data-stu-id="52731-136">Left hand side</span></span></param>
        <param name="right"><span data-ttu-id="52731-137">右側にあります。</span><span class="sxs-lookup"><span data-stu-id="52731-137">Right hand side</span></span></param>
        <summary>
            <span data-ttu-id="52731-138">等値演算子。</span><span class="sxs-lookup"><span data-stu-id="52731-138">Equality operator.</span></span>
            </summary>
        <returns><span data-ttu-id="52731-139">2 つのオブジェクトが等しい場合は false 以外の場合は true。</span><span class="sxs-lookup"><span data-stu-id="52731-139">True if the two objects are equal, false in all other cases</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_GreaterThan">
      <MemberSignature Language="C#" Value="public static bool operator &gt; (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange left, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_GreaterThan(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange left, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.op_GreaterThan(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &gt; (left As ShardRange, right As ShardRange) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &gt; ) : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange -&gt; bool" Usage="left &gt; right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />
        <Parameter Name="right" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />
      </Parameters>
      <Docs>
        <param name="left"><span data-ttu-id="52731-140">左側にある<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />演算子のです。</span><span class="sxs-lookup"><span data-stu-id="52731-140">Left hand side <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" /> of the operator.</span></span></param>
        <param name="right"><span data-ttu-id="52731-141">右側にある<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />演算子のです。</span><span class="sxs-lookup"><span data-stu-id="52731-141">Right hand side <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" /> of the operator.</span></span></param>
        <summary>
            <span data-ttu-id="52731-142">比較する 2 つ<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />辞書式順序 (より大きい) を使用します。</span><span class="sxs-lookup"><span data-stu-id="52731-142">Compares two <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" /> using lexicographic order (greater than).</span></span>
            </summary>
        <returns><span data-ttu-id="52731-143">True の場合 lhs &gt; rhs</span><span class="sxs-lookup"><span data-stu-id="52731-143">True if lhs &gt; rhs</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_GreaterThanOrEqual">
      <MemberSignature Language="C#" Value="public static bool operator &gt;= (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange left, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_GreaterThanOrEqual(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange left, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.op_GreaterThanOrEqual(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &gt;= (left As ShardRange, right As ShardRange) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &gt;= ) : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange -&gt; bool" Usage="left &gt;= right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />
        <Parameter Name="right" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />
      </Parameters>
      <Docs>
        <param name="left"><span data-ttu-id="52731-144">左側にある<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />演算子のです。</span><span class="sxs-lookup"><span data-stu-id="52731-144">Left hand side <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" /> of the operator.</span></span></param>
        <param name="right"><span data-ttu-id="52731-145">右側にある<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />演算子のです。</span><span class="sxs-lookup"><span data-stu-id="52731-145">Right hand side <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" /> of the operator.</span></span></param>
        <summary>
            <span data-ttu-id="52731-146">比較する 2 つ<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />辞書式順序 (大きいまたは等しい) を使用します。</span><span class="sxs-lookup"><span data-stu-id="52731-146">Compares two <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" /> using lexicographic order (greater or equal).</span></span> 
            </summary>
        <returns><span data-ttu-id="52731-147">True の場合 lhs &gt;rhs を =</span><span class="sxs-lookup"><span data-stu-id="52731-147">True if lhs &gt;= rhs</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange left, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange left, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.op_Inequality(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (left As ShardRange, right As ShardRange) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange -&gt; bool" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.op_Inequality (left, right)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />
        <Parameter Name="right" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />
      </Parameters>
      <Docs>
        <param name="left"><span data-ttu-id="52731-148">左側にあります。</span><span class="sxs-lookup"><span data-stu-id="52731-148">Left hand side</span></span></param>
        <param name="right"><span data-ttu-id="52731-149">右側にあります。</span><span class="sxs-lookup"><span data-stu-id="52731-149">Right hand side</span></span></param>
        <summary>
            <span data-ttu-id="52731-150">非等値演算子。</span><span class="sxs-lookup"><span data-stu-id="52731-150">Inequality operator.</span></span>
            </summary>
        <returns><span data-ttu-id="52731-151">等しい、false の場合は、2 つのオブジェクトがない場合は true。</span><span class="sxs-lookup"><span data-stu-id="52731-151">True if the two objects are not equal, false in all other cases</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_LessThan">
      <MemberSignature Language="C#" Value="public static bool operator &lt; (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange left, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_LessThan(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange left, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.op_LessThan(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &lt; (left As ShardRange, right As ShardRange) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &lt; ) : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange -&gt; bool" Usage="left &lt; right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />
        <Parameter Name="right" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />
      </Parameters>
      <Docs>
        <param name="left"><span data-ttu-id="52731-152">左側にある<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />演算子のです。</span><span class="sxs-lookup"><span data-stu-id="52731-152">Left hand side <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" /> of the operator.</span></span></param>
        <param name="right"><span data-ttu-id="52731-153">右側にある<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />演算子のです。</span><span class="sxs-lookup"><span data-stu-id="52731-153">Right hand side <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" /> of the operator.</span></span></param>
        <summary>
            <span data-ttu-id="52731-154">比較する 2 つ<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />辞書式順序を使用して (より小さい)。</span><span class="sxs-lookup"><span data-stu-id="52731-154">Compares two <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" /> using lexicographic order (less than).</span></span>
            </summary>
        <returns><span data-ttu-id="52731-155">True の場合 lhs &lt; rhs</span><span class="sxs-lookup"><span data-stu-id="52731-155">True if lhs &lt; rhs</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_LessThanOrEqual">
      <MemberSignature Language="C#" Value="public static bool operator &lt;= (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange left, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange right);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_LessThanOrEqual(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange left, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.op_LessThanOrEqual(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator &lt;= (left As ShardRange, right As ShardRange) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( &lt;= ) : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange -&gt; bool" Usage="left &lt;= right" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />
        <Parameter Name="right" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />
      </Parameters>
      <Docs>
        <param name="left"><span data-ttu-id="52731-156">左側にある<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />演算子のです。</span><span class="sxs-lookup"><span data-stu-id="52731-156">Left hand side <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" /> of the operator.</span></span></param>
        <param name="right"><span data-ttu-id="52731-157">右側にある<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />演算子のです。</span><span class="sxs-lookup"><span data-stu-id="52731-157">Right hand side <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" /> of the operator.</span></span></param>
        <summary>
            <span data-ttu-id="52731-158">比較する 2 つ<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" />辞書式順序 (より小さいか等しい) を使用します。</span><span class="sxs-lookup"><span data-stu-id="52731-158">Compares two <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange" /> using lexicographic order (less or equal).</span></span> 
            </summary>
        <returns><span data-ttu-id="52731-159">True の場合 lhs &lt;rhs を =</span><span class="sxs-lookup"><span data-stu-id="52731-159">True if lhs &lt;= rhs</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="shardRange.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="52731-160">オブジェクトを文字列形式に変換します。</span><span class="sxs-lookup"><span data-stu-id="52731-160">Converts the object to its string representation.</span></span>
            </summary>
        <returns><span data-ttu-id="52731-161">オブジェクトの文字列表現。</span><span class="sxs-lookup"><span data-stu-id="52731-161">String representation of the object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>