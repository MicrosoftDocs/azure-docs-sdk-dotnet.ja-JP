<Type Name="Range&lt;T&gt;" FullName="Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class Range&lt;T&gt; : IComparable&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;&gt;, IEquatable&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;&gt; where T : IComparable&lt;T&gt;, IEquatable&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Range`1&lt;(class System.IComparable`1&lt;!T&gt;, class System.IEquatable`1&lt;!T&gt;) T&gt; extends System.Object implements class System.IComparable`1&lt;class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt;&gt;, class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Partitioning.Range`1" />
  <TypeSignature Language="VB.NET" Value="Public Class Range(Of T)&#xA;Implements IComparable(Of Range(Of T)), IEquatable(Of Range(Of T))" />
  <TypeSignature Language="F#" Value="type Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; = class&#xA;    interface IEquatable&lt;Range&lt;'T&gt;&gt;&#xA;    interface IComparable&lt;Range&lt;'T&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <InterfaceName>System.IComparable&lt;T&gt;</InterfaceName>
        <InterfaceName>System.IEquatable&lt;T&gt;</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IComparable&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for classes used with IPartitionResolver is now obsolete. It's recommended that you use partitioned collections for higher storage and throughput.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <typeparam name="T"><span data-ttu-id="21b4a-101">範囲の比較に使用できる任意の型。</span><span class="sxs-lookup"><span data-stu-id="21b4a-101">Any type that can be used for range comparison.</span></span></typeparam>
    <summary>
            <span data-ttu-id="21b4a-102">によって使用されている範囲を表すクラス、 <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="21b4a-102">A class that represents a range used by the <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> class in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="21b4a-103">IPartitionResolver で使用されるクラスのサポートは廃止されました。</span><span class="sxs-lookup"><span data-stu-id="21b4a-103">Support for classes used with IPartitionResolver is now obsolete.</span></span> <span data-ttu-id="21b4a-104">使用することをお勧め<a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">パーティション分割コレクション</a>の記憶域とスループットが向上します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-104">It's recommended that you use <a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">Partitioned Collections</a> for higher storage and throughput.</span></span>
            </remarks>
    <altmember cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" />
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Range (T point);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!T point) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.#ctor(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (point As T)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; : 'T -&gt; Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt;" Usage="new Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt; point" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="point" Type="T" />
      </Parameters>
      <Docs>
        <param name="point"><span data-ttu-id="21b4a-105">範囲の作成に使用する値。</span><span class="sxs-lookup"><span data-stu-id="21b4a-105">A value that is used to create the range.</span></span></param>
        <summary>
            <span data-ttu-id="21b4a-106">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" />クラスの単一の値。</span><span class="sxs-lookup"><span data-stu-id="21b4a-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" /> class for a single value.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="21b4a-107">不連続/単一値のパーティション構成を作成するためには、このコンス トラクターを使用します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-107">Use this constructor for building a partitioning scheme for discrete/single values.</span></span>
            <span data-ttu-id="21b4a-108">によって使用されている範囲を表す範囲クラス、 <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="21b4a-108">The Range class that represents a range used by the <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> class in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Range (T low, T high);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!T low, !T high) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.#ctor(`0,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (low As T, high As T)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; : 'T * 'T -&gt; Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt;" Usage="new Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt; (low, high)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="low" Type="T" />
        <Parameter Name="high" Type="T" />
      </Parameters>
      <Docs>
        <param name="low"><span data-ttu-id="21b4a-109">範囲の安値。</span><span class="sxs-lookup"><span data-stu-id="21b4a-109">The low value in the range.</span></span></param>
        <param name="high"><span data-ttu-id="21b4a-110">範囲の上位の値。</span><span class="sxs-lookup"><span data-stu-id="21b4a-110">The high value in the range.</span></span></param>
        <summary>
            <span data-ttu-id="21b4a-111">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" />クラスの指定および下限値を使用します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-111">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" /> class using the specified low and high values.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="21b4a-112">によって使用されている範囲を表す範囲クラス、 <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="21b4a-112">The Range class that represents a range used by the <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> class in the Azure Cosmos DB service.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="21b4a-113">範囲が有効でない場合は、例外をスロー (低、高より大きい)。</span><span class="sxs-lookup"><span data-stu-id="21b4a-113">Throws an exception if the range is invalid (low is greater than high).</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CompareTo">
      <MemberSignature Language="C#" Value="public int CompareTo (Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt; other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 CompareTo(class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt; other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.CompareTo(Microsoft.Azure.Documents.Partitioning.Range{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompareTo (other As Range(Of T)) As Integer" />
      <MemberSignature Language="F#" Value="abstract member CompareTo : Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; -&gt; int&#xA;override this.CompareTo : Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; -&gt; int" Usage="range.CompareTo other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IComparable`1.CompareTo(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="21b4a-114">比較する他の範囲です。</span><span class="sxs-lookup"><span data-stu-id="21b4a-114">The other range to compare to.</span></span></param>
        <summary>
            <span data-ttu-id="21b4a-115">2 つの範囲を比較します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-115">Compares two ranges.</span></span>
            </summary>
        <returns><span data-ttu-id="21b4a-116">範囲が大きい場合、渡された範囲では、1 より小さい場合は-1 と等しい場合は 0 を返します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-116">Returns -1 if the range is smaller than the passed range, 1 if bigger and 0 if equal.</span></span></returns>
        <remarks>
            <span data-ttu-id="21b4a-117">によって使用されている範囲を表す範囲クラス、 <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="21b4a-117">The Range class that represents a range used by the <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> class in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt; other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Contains(class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt; other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.Contains(Microsoft.Azure.Documents.Partitioning.Range{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (other As Range(Of T)) As Boolean" />
      <MemberSignature Language="F#" Value="member this.Contains : Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; -&gt; bool" Usage="range.Contains other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="21b4a-118">この範囲に含まれているかどうかにチェックされる入力範囲。</span><span class="sxs-lookup"><span data-stu-id="21b4a-118">The input range to be checked if it's contained in this range.</span></span></param>
        <summary>
            <span data-ttu-id="21b4a-119">範囲に別の範囲が含まれているかどうかをチェック.</span><span class="sxs-lookup"><span data-stu-id="21b4a-119">Checks if the range contains another range..</span></span>
            </summary>
        <returns><span data-ttu-id="21b4a-120">入力範囲が範囲に含まれている場合は true を返します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-120">Returns true if the input range is contained in the range.</span></span></returns>
        <remarks>
            <span data-ttu-id="21b4a-121">によって使用されている範囲を表す範囲クラス、 <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="21b4a-121">The Range class that represents a range used by the <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> class in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (T point);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Contains(!T point) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.Contains(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (point As T) As Boolean" />
      <MemberSignature Language="F#" Value="member this.Contains : 'T -&gt; bool" Usage="range.Contains point" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="point" Type="T" />
      </Parameters>
      <Docs>
        <param name="point"><span data-ttu-id="21b4a-122">チェックインする場合、範囲のキー。</span><span class="sxs-lookup"><span data-stu-id="21b4a-122">The key to be checked if in the range.</span></span></param>
        <summary>
            <span data-ttu-id="21b4a-123">範囲に、キーが含まれるかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-123">Checks if the range contains a key.</span></span>
            </summary>
        <returns><span data-ttu-id="21b4a-124">キーが、範囲内にある場合は true を返します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-124">Returns true if the key is in the range.</span></span></returns>
        <remarks>
            <span data-ttu-id="21b4a-125">によって使用されている範囲を表す範囲クラス、 <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="21b4a-125">The Range class that represents a range used by the <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> class in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt; other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt; other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.Equals(Microsoft.Azure.Documents.Partitioning.Range{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Range(Of T)) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; -&gt; bool" Usage="range.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="21b4a-126">この範囲と比較する入力の範囲です。</span><span class="sxs-lookup"><span data-stu-id="21b4a-126">the input range to be compared with this range.</span></span></param>
        <summary>
            <span data-ttu-id="21b4a-127">2 つの範囲が等しいかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-127">Checks if two ranges are equal.</span></span>
            </summary>
        <returns><span data-ttu-id="21b4a-128">入力範囲がこの範囲に等しい場合は true を返します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-128">Returns true if the input range is equal to this range.</span></span></returns>
        <remarks>
            <span data-ttu-id="21b4a-129">によって使用されている範囲を表す範囲クラス、 <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="21b4a-129">The Range class that represents a range used by the <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> class in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="range.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="21b4a-130">範囲のハッシュ コードを作成します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-130">Creates the hashcode for the range.</span></span>
            </summary>
        <returns><span data-ttu-id="21b4a-131">範囲のハッシュ コードを返します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-131">Returns the hashcode for the range.</span></span></returns>
        <remarks>
            <span data-ttu-id="21b4a-132">によって使用されている範囲を表す範囲クラス、 <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="21b4a-132">The Range class that represents a range used by the <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> class in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="High">
      <MemberSignature Language="C#" Value="public T High { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T High" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.Range`1.High" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property High As T" />
      <MemberSignature Language="F#" Value="member this.High : 'T" Usage="Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt;.High" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="21b4a-133">範囲内には、高の値を取得します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-133">Gets the high value in the range.</span></span>
            </summary>
        <value>
            <span data-ttu-id="21b4a-134">範囲の上位の値。</span><span class="sxs-lookup"><span data-stu-id="21b4a-134">The high value in the range.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="21b4a-135">によって使用されている範囲を表す範囲クラス、 <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="21b4a-135">The Range class that represents a range used by the <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> class in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Intersect">
      <MemberSignature Language="C#" Value="public bool Intersect (Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt; other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Intersect(class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt; other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.Intersect(Microsoft.Azure.Documents.Partitioning.Range{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function Intersect (other As Range(Of T)) As Boolean" />
      <MemberSignature Language="F#" Value="member this.Intersect : Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; -&gt; bool" Usage="range.Intersect other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="21b4a-136">入力<see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" />この範囲と比較します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-136">the input <see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" /> to be compared with this range.</span></span></param>
        <summary>
            <span data-ttu-id="21b4a-137">場合確認範囲<paramref name="other" />この範囲と交差します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-137">Checks if the range <paramref name="other" /> intersects with this range.</span></span>
            </summary>
        <returns><span data-ttu-id="21b4a-138">2 つの範囲が互いに交差する場合は true を返します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-138">Returns true if the two ranges intersect with each other.</span></span></returns>
        <remarks>
            <span data-ttu-id="21b4a-139">によって使用されている範囲を表す範囲クラス、 <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="21b4a-139">The Range class that represents a range used by the <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> class in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Low">
      <MemberSignature Language="C#" Value="public T Low { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Low" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.Range`1.Low" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Low As T" />
      <MemberSignature Language="F#" Value="member this.Low : 'T" Usage="Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt;.Low" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="21b4a-140">範囲の下端の値を取得します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-140">Gets the low value in the range.</span></span>
            </summary>
        <value>
            <span data-ttu-id="21b4a-141">範囲の安値。</span><span class="sxs-lookup"><span data-stu-id="21b4a-141">The low value in the range.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="21b4a-142">によって使用されている範囲を表す範囲クラス、 <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="21b4a-142">The Range class that represents a range used by the <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> class in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="range.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="21b4a-143">範囲を「低、高」の形式で文字列に変換します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-143">Converts the range to a string in the form of "low,high"</span></span>
            </summary>
        <returns><span data-ttu-id="21b4a-144">範囲の文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="21b4a-144">Returns A string representation of the range.</span></span></returns>
        <remarks>
            <span data-ttu-id="21b4a-145">によって使用されている範囲を表す範囲クラス、 <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="21b4a-145">The Range class that represents a range used by the <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> class in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>