<Type Name="NodeId" FullName="System.Fabric.NodeId">
  <TypeSignature Language="C#" Value="public class NodeId" />
  <TypeSignature Language="ILAsm" Value=".class public ansi beforefieldinit NodeId extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NodeId" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeId" />
  <TypeSignature Language="F#" Value="type NodeId = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="86bdf-101">ノード ID をカプセル化するクラス</span><span class="sxs-lookup"><span data-stu-id="86bdf-101">Class to encapsulate a node ID.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeId (System.Numerics.BigInteger high, System.Numerics.BigInteger low);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Numerics.BigInteger high, valuetype System.Numerics.BigInteger low) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.#ctor(System.Numerics.BigInteger,System.Numerics.BigInteger)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (high As BigInteger, low As BigInteger)" />
      <MemberSignature Language="F#" Value="new System.Fabric.NodeId : System.Numerics.BigInteger * System.Numerics.BigInteger -&gt; System.Fabric.NodeId" Usage="new System.Fabric.NodeId (high, low)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="high" Type="System.Numerics.BigInteger" />
        <Parameter Name="low" Type="System.Numerics.BigInteger" />
      </Parameters>
      <Docs>
        <param name="high">
          <para><span data-ttu-id="86bdf-102">最上位のコンポーネント、<see cref="T:System.Fabric.NodeId" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="86bdf-102">The high order component of the <see cref="T:System.Fabric.NodeId" /> object.</span></span></para>
        </param>
        <param name="low">
          <para><span data-ttu-id="86bdf-103">下位のコンポーネント、<see cref="T:System.Fabric.NodeId" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="86bdf-103">The low order component of the <see cref="T:System.Fabric.NodeId" /> object.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="86bdf-104">新しい初期化<see cref="T:System.Fabric.NodeId" />オブジェクト、指定したコンポーネントを注文高値と安値。</span><span class="sxs-lookup"><span data-stu-id="86bdf-104">Initializes a new <see cref="T:System.Fabric.NodeId" /> object, with the specified high and low order components.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="nodeId.Equals obj" />
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
          <para><span data-ttu-id="86bdf-105">現在の <see cref="T:System.Fabric.NodeId" /> と比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="86bdf-105">The object to compare with the current <see cref="T:System.Fabric.NodeId" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="86bdf-106">示すかどうかこの<see cref="T:System.Fabric.NodeId" />オブジェクトと指定したオブジェクトが等しい。</span><span class="sxs-lookup"><span data-stu-id="86bdf-106">Indicates whether this <see cref="T:System.Fabric.NodeId" /> object and the specified object are equal.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="86bdf-107">返します、<see cref="T:System.Boolean" />値が<languageKeyword>true</languageKeyword>オブジェクトが同じ種類し、同じ値を表す場合それ以外の場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="86bdf-107">Returns a <see cref="T:System.Boolean" /> value that is <languageKeyword>true</languageKeyword> if the objects are the same type and represent the same value; otherwise <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="nodeId.GetHashCode " />
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
          <para><span data-ttu-id="86bdf-108">この <see cref="T:System.Fabric.NodeId" /> オブジェクトのハッシュ コードを返します。</span><span class="sxs-lookup"><span data-stu-id="86bdf-108">Returns the hash code for this <see cref="T:System.Fabric.NodeId" /> object.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="86bdf-109">32 ビット符号付き整数ハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="86bdf-109">A 32-bit signed integer hash code.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="High">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger High { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger High" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeId.High" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property High As BigInteger" />
      <MemberSignature Language="F#" Value="member this.High : System.Numerics.BigInteger" Usage="System.Fabric.NodeId.High" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Numerics.BigInteger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="86bdf-110">最上位のコンポーネント、<see cref="T:System.Fabric.NodeId" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="86bdf-110">The high order component of the <see cref="T:System.Fabric.NodeId" /> object.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="86bdf-111"><see cref="T:System.Numerics.BigInteger" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="86bdf-111">Returns <see cref="T:System.Numerics.BigInteger" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Low">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger Low { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger Low" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeId.Low" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Low As BigInteger" />
      <MemberSignature Language="F#" Value="member this.Low : System.Numerics.BigInteger" Usage="System.Fabric.NodeId.Low" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Numerics.BigInteger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="86bdf-112">下位のコンポーネント、<see cref="T:System.Fabric.NodeId" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="86bdf-112">The low order component of the <see cref="T:System.Fabric.NodeId" /> object.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="86bdf-113"><see cref="T:System.Numerics.BigInteger" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="86bdf-113">Returns <see cref="T:System.Numerics.BigInteger" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (System.Fabric.NodeId value1, System.Fabric.NodeId value2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(class System.Fabric.NodeId value1, class System.Fabric.NodeId value2) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.op_Equality(System.Fabric.NodeId,System.Fabric.NodeId)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (value1 As NodeId, value2 As NodeId) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : System.Fabric.NodeId * System.Fabric.NodeId -&gt; bool" Usage="value1 = value2" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value1" Type="System.Fabric.NodeId" />
        <Parameter Name="value2" Type="System.Fabric.NodeId" />
      </Parameters>
      <Docs>
        <param name="value1">
          <para><span data-ttu-id="86bdf-114">A<see cref="T:System.Fabric.NodeId" />と比較するオブジェクト<paramref name="value2" />です。</span><span class="sxs-lookup"><span data-stu-id="86bdf-114">A <see cref="T:System.Fabric.NodeId" /> object to compare with <paramref name="value2" />.</span></span></para>
        </param>
        <param name="value2">
          <para><span data-ttu-id="86bdf-115">A<see cref="T:System.Fabric.NodeId" />と比較するオブジェクト<paramref name="value1" />です。</span><span class="sxs-lookup"><span data-stu-id="86bdf-115">A <see cref="T:System.Fabric.NodeId" /> object to compare with <paramref name="value1" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="86bdf-116">2 つの <see cref="T:System.Fabric.NodeId" /> オブジェクトの値が同一かどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="86bdf-116">Determines whether two <see cref="T:System.Fabric.NodeId" /> objects have the same value.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="86bdf-117">返します、<see cref="T:System.Boolean" />値が<languageKeyword>true</languageKeyword>オブジェクトと等価です。 それ以外の場合は、場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="86bdf-117">Returns a <see cref="T:System.Boolean" /> value that is <languageKeyword>true</languageKeyword> if the objects are equivalent; otherwise <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (System.Fabric.NodeId value1, System.Fabric.NodeId value2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(class System.Fabric.NodeId value1, class System.Fabric.NodeId value2) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.op_Inequality(System.Fabric.NodeId,System.Fabric.NodeId)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (value1 As NodeId, value2 As NodeId) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : System.Fabric.NodeId * System.Fabric.NodeId -&gt; bool" Usage="System.Fabric.NodeId.op_Inequality (value1, value2)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value1" Type="System.Fabric.NodeId" />
        <Parameter Name="value2" Type="System.Fabric.NodeId" />
      </Parameters>
      <Docs>
        <param name="value1">
          <para><span data-ttu-id="86bdf-118">A<see cref="T:System.Fabric.NodeId" />と比較するオブジェクト<paramref name="value2" />です。</span><span class="sxs-lookup"><span data-stu-id="86bdf-118">A <see cref="T:System.Fabric.NodeId" /> object to compare with <paramref name="value2" />.</span></span></para>
        </param>
        <param name="value2">
          <para><span data-ttu-id="86bdf-119">A<see cref="T:System.Fabric.NodeId" />と比較するオブジェクト<paramref name="value1" />です。</span><span class="sxs-lookup"><span data-stu-id="86bdf-119">A <see cref="T:System.Fabric.NodeId" /> object to compare with <paramref name="value1" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="86bdf-120">2 つの <see cref="T:System.Fabric.NodeId" /> オブジェクトの値が異なるかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="86bdf-120">Determines whether two <see cref="T:System.Fabric.NodeId" /> objects have different values.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="86bdf-121">返します、<see cref="T:System.Boolean" />値が<languageKeyword>true</languageKeyword>のオブジェクトが別の値です。 それ以外の場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="86bdf-121">Returns a <see cref="T:System.Boolean" /> value that is <languageKeyword>true</languageKeyword> if the objects have different values; otherwise <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeId.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="86bdf-122">作成し、現在のノード ID の文字列表現を返します</span><span class="sxs-lookup"><span data-stu-id="86bdf-122">Creates and returns a string representation of the current node ID.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="86bdf-123"><see cref="T:System.String" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="86bdf-123">Returns <see cref="T:System.String" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryParse">
      <MemberSignature Language="C#" Value="public static bool TryParse (string from, out System.Fabric.NodeId parsedNodeId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryParse(string from, [out] class System.Fabric.NodeId&amp; parsedNodeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.TryParse(System.String,System.Fabric.NodeId@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryParse (from As String, ByRef parsedNodeId As NodeId) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryParse : string *  -&gt; bool" Usage="System.Fabric.NodeId.TryParse (from, parsedNodeId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.String" />
        <Parameter Name="parsedNodeId" Type="System.Fabric.NodeId&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="from">
          <para><span data-ttu-id="86bdf-124">変換するノード ID を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="86bdf-124">A string containing the node ID to convert.</span></span></para>
        </param>
        <param name="parsedNodeId">
          <para><span data-ttu-id="86bdf-125">このメソッドが戻るときに、新しい格納<see cref="T:System.Fabric.NodeId" />に ID が含まれているノードに同等のオブジェクト<paramref name="from" />変換が成功した場合、または<languageKeyword>null</languageKeyword>変換に失敗した場合。</span><span class="sxs-lookup"><span data-stu-id="86bdf-125">When this method returns, contains a new <see cref="T:System.Fabric.NodeId" /> object equivalent to the node ID contained in <paramref name="from" />, if the conversion succeeded, or <languageKeyword>null</languageKeyword> if the conversion failed.</span></span> <span data-ttu-id="86bdf-126">このパラメーターは初期化せずに渡されます。</span><span class="sxs-lookup"><span data-stu-id="86bdf-126">This parameter is passed uninitialized.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="86bdf-127">ノード ID との文字列形式に変換、<see cref="T:System.Fabric.NodeId" />同等のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="86bdf-127">Converts the string representation of a node ID to its <see cref="T:System.Fabric.NodeId" /> object equivalent.</span></span> <span data-ttu-id="86bdf-128">戻り値は、演算が成功したかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="86bdf-128">A return value indicates whether the operation succeeded.</span></span></para>
        </summary>
        <returns>
          <returns><span data-ttu-id="86bdf-129">解析が成功したかどうかを示すブール値</span><span class="sxs-lookup"><span data-stu-id="86bdf-129">A boolean indicating if the parse was successful</span></span></returns>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>