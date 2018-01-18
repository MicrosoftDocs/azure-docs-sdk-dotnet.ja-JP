<Type Name="UniformInt64RangePartitionSchemeDescription" FullName="System.Fabric.Description.UniformInt64RangePartitionSchemeDescription">
  <TypeSignature Language="C#" Value="public sealed class UniformInt64RangePartitionSchemeDescription : System.Fabric.Description.PartitionSchemeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UniformInt64RangePartitionSchemeDescription extends System.Fabric.Description.PartitionSchemeDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UniformInt64RangePartitionSchemeDescription&#xA;Inherits PartitionSchemeDescription" />
  <TypeSignature Language="F#" Value="type UniformInt64RangePartitionSchemeDescription = class&#xA;    inherit PartitionSchemeDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.PartitionSchemeDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="13ee0-101">整数の範囲が均等に複数のパーティションに割り当てられているパーティション構成について説明します。</span><span class="sxs-lookup"><span data-stu-id="13ee0-101">Describes a partitioning scheme where an integer range is allocated evenly across a number of partitions.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UniformInt64RangePartitionSchemeDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="13ee0-102"><see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="13ee0-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UniformInt64RangePartitionSchemeDescription (int partitionCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 partitionCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.#ctor(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionCount As Integer)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.UniformInt64RangePartitionSchemeDescription : int -&gt; System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" Usage="new System.Fabric.Description.UniformInt64RangePartitionSchemeDescription partitionCount" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="partitionCount">
          <para><span data-ttu-id="13ee0-103">スキーム内のパーティションの数。</span><span class="sxs-lookup"><span data-stu-id="13ee0-103">The number of partitions in the scheme.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="13ee0-104">新しいインスタンスを初期化、<see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" />パーティション数を指定することによってクラスです。</span><span class="sxs-lookup"><span data-stu-id="13ee0-104">Initializes a new instance of the <see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" /> class by specifying the partition count.</span></span></para>
        </summary>
        <remarks><span data-ttu-id="13ee0-105">範囲の低いキーが既定で長い。MinValue とキーの最高値を既定の長さ。MaxValue です。</span><span class="sxs-lookup"><span data-stu-id="13ee0-105">The low key of the range defaults to long.MinValue and the high key defaults to long.MaxValue.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UniformInt64RangePartitionSchemeDescription (int partitionCount, long lowKey, long highKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 partitionCount, int64 lowKey, int64 highKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.#ctor(System.Int32,System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionCount As Integer, lowKey As Long, highKey As Long)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.UniformInt64RangePartitionSchemeDescription : int * int64 * int64 -&gt; System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" Usage="new System.Fabric.Description.UniformInt64RangePartitionSchemeDescription (partitionCount, lowKey, highKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionCount" Type="System.Int32" />
        <Parameter Name="lowKey" Type="System.Int64" />
        <Parameter Name="highKey" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionCount">
          <para><span data-ttu-id="13ee0-106">スキーム内のパーティションの数。</span><span class="sxs-lookup"><span data-stu-id="13ee0-106">The number of partitions in the scheme.</span></span></para>
        </param>
        <param name="lowKey"><span data-ttu-id="13ee0-107">範囲の低キー。</span><span class="sxs-lookup"><span data-stu-id="13ee0-107">The low key of the range.</span></span></param>
        <param name="highKey"><span data-ttu-id="13ee0-108">範囲の高キー。</span><span class="sxs-lookup"><span data-stu-id="13ee0-108">The high key of the range.</span></span></param>
        <summary>
          <para><span data-ttu-id="13ee0-109">新しいインスタンスを初期化、<see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" />クラス パーティション数と範囲の値を指定します。</span><span class="sxs-lookup"><span data-stu-id="13ee0-109">Initializes a new instance of the <see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" /> class by specifying the partition count and the range values.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighKey">
      <MemberSignature Language="C#" Value="public long HighKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HighKey" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.HighKey" />
      <MemberSignature Language="VB.NET" Value="Public Property HighKey As Long" />
      <MemberSignature Language="F#" Value="member this.HighKey : int64 with get, set" Usage="System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.HighKey" />
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
          <para><span data-ttu-id="13ee0-110">取得またはサービスでサポートされているキーの範囲の包含的上限を設定します。</span><span class="sxs-lookup"><span data-stu-id="13ee0-110">Gets or sets the inclusive upper bound on the range of keys that is supported by the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="13ee0-111">サービスでサポートされているキーの範囲の包含的上限です。</span><span class="sxs-lookup"><span data-stu-id="13ee0-111">The inclusive upper bound on the range of keys that is supported by the service.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LowKey">
      <MemberSignature Language="C#" Value="public long LowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LowKey" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.LowKey" />
      <MemberSignature Language="VB.NET" Value="Public Property LowKey As Long" />
      <MemberSignature Language="F#" Value="member this.LowKey : int64 with get, set" Usage="System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.LowKey" />
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
          <para><span data-ttu-id="13ee0-112">取得またはサービスでサポートされているキーの範囲の下限を設定します。</span><span class="sxs-lookup"><span data-stu-id="13ee0-112">Gets or sets the inclusive lower bound on the range of keys that is supported by the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="13ee0-113">サービスでサポートされているキーの範囲の下限。</span><span class="sxs-lookup"><span data-stu-id="13ee0-113">The inclusive lower bound on the range of keys that is supported by the service.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionCount">
      <MemberSignature Language="C#" Value="public int PartitionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PartitionCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.PartitionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PartitionCount : int with get, set" Usage="System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.PartitionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="13ee0-114">取得またはパーティションの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="13ee0-114">Gets or sets the partition count.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="13ee0-115">パーティションの数。</span><span class="sxs-lookup"><span data-stu-id="13ee0-115">The partition count.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="13ee0-116">これにこのサービスがパーティション分割されているパーティションの数を指定します。</span><span class="sxs-lookup"><span data-stu-id="13ee0-116">Specifies the number of partitions into which this service is partitioned.</span></span> <span data-ttu-id="13ee0-117">各パーティションは、約数は同じキーを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="13ee0-117">Each partition receives approximately the same number of keys.</span></span> <span data-ttu-id="13ee0-118">減算することによって、番号が決まり<languagekeyword>HighKey</languagekeyword>から<languagekeyword>LowKey</languagekeyword>で合計で割ること<languagekeyword>PartitionCount</languagekeyword>です。</span><span class="sxs-lookup"><span data-stu-id="13ee0-118">The number is determined by subtracting <languagekeyword>HighKey</languagekeyword> from <languagekeyword>LowKey</languagekeyword> and dividing the sum by <languagekeyword>PartitionCount</languagekeyword>.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>