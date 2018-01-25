<Type Name="GeometryOperationExtensions" FullName="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions">
  <TypeSignature Language="C#" Value="public static class GeometryOperationExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit GeometryOperationExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module GeometryOperationExtensions" />
  <TypeSignature Language="F#" Value="type GeometryOperationExtensions = class" />
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
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a6db4-101">サポートされる操作<see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />Azure Cosmos DB サービスの種類。</span><span class="sxs-lookup"><span data-stu-id="a6db4-101">Operations supported on <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> type in the Azure Cosmos DB service.</span></span> <span data-ttu-id="a6db4-102">これらの操作は LINQ 式のみで使用されるされ、サーバーで評価されます。</span><span class="sxs-lookup"><span data-stu-id="a6db4-102">These operations are to be used in LINQ expressions only and will be evaluated on server.</span></span> <span data-ttu-id="a6db4-103">クライアント ライブラリで提供される実装はありません。</span><span class="sxs-lookup"><span data-stu-id="a6db4-103">There's no implementation provided in the client library.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Distance">
      <MemberSignature Language="C#" Value="public static double Distance (this Microsoft.Azure.Documents.Spatial.Geometry from, Microsoft.Azure.Documents.Spatial.Geometry to);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig float64 Distance(class Microsoft.Azure.Documents.Spatial.Geometry from, class Microsoft.Azure.Documents.Spatial.Geometry to) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Distance(Microsoft.Azure.Documents.Spatial.Geometry,Microsoft.Azure.Documents.Spatial.Geometry)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Distance (from As Geometry, to As Geometry) As Double" />
      <MemberSignature Language="F#" Value="static member Distance : Microsoft.Azure.Documents.Spatial.Geometry * Microsoft.Azure.Documents.Spatial.Geometry -&gt; double" Usage="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Distance (from, to)" />
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
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="Microsoft.Azure.Documents.Spatial.Geometry" RefType="this" />
        <Parameter Name="to" Type="Microsoft.Azure.Documents.Spatial.Geometry" />
      </Parameters>
      <Docs>
        <param name="from"><span data-ttu-id="a6db4-104">最初<see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />です。</span><span class="sxs-lookup"><span data-stu-id="a6db4-104">First <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span></span></param>
        <param name="to"><span data-ttu-id="a6db4-105">2 番目<see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />です。</span><span class="sxs-lookup"><span data-stu-id="a6db4-105">Second <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span></span></param>
        <summary>
            <span data-ttu-id="a6db4-106">Azure Cosmos DB サービスの 2 つのジオメトリ間メートル単位で距離です。</span><span class="sxs-lookup"><span data-stu-id="a6db4-106">Distance in meters between two geometries in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="a6db4-107">メートル単位で 2 つのジオメトリの間の距離を返します。</span><span class="sxs-lookup"><span data-stu-id="a6db4-107">Returns distance in meters between two geometries.</span></span></returns>
        <remarks>
            <span data-ttu-id="a6db4-108">この関数がのジオメトリのみをサポートする今日<see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" />型です。</span><span class="sxs-lookup"><span data-stu-id="a6db4-108">Today this function support only geometries of <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" /> type.</span></span>
            </remarks>
        <example>
          <code><![CDATA[
            var distanceQuery = documents.Where(document => document.Location.Distance(new Point(20.1, 20)) < 20000);
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="Intersects">
      <MemberSignature Language="C#" Value="public static bool Intersects (this Microsoft.Azure.Documents.Spatial.Geometry geometry1, Microsoft.Azure.Documents.Spatial.Geometry geometry2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Intersects(class Microsoft.Azure.Documents.Spatial.Geometry geometry1, class Microsoft.Azure.Documents.Spatial.Geometry geometry2) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Intersects(Microsoft.Azure.Documents.Spatial.Geometry,Microsoft.Azure.Documents.Spatial.Geometry)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Intersects (geometry1 As Geometry, geometry2 As Geometry) As Boolean" />
      <MemberSignature Language="F#" Value="static member Intersects : Microsoft.Azure.Documents.Spatial.Geometry * Microsoft.Azure.Documents.Spatial.Geometry -&gt; bool" Usage="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Intersects (geometry1, geometry2)" />
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
        <Parameter Name="geometry1" Type="Microsoft.Azure.Documents.Spatial.Geometry" RefType="this" />
        <Parameter Name="geometry2" Type="Microsoft.Azure.Documents.Spatial.Geometry" />
      </Parameters>
      <Docs>
        <param name="geometry1"><span data-ttu-id="a6db4-109">最初<see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />です。</span><span class="sxs-lookup"><span data-stu-id="a6db4-109">First <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span></span></param>
        <param name="geometry2"><span data-ttu-id="a6db4-110">2 番目<see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />です。</span><span class="sxs-lookup"><span data-stu-id="a6db4-110">Second <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span></span></param>
        <summary>
            <span data-ttu-id="a6db4-111">Geometry1 が geometry2 と交差するかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="a6db4-111">Checks if geometry1 intersects with geometry2.</span></span>
            </summary>
        <returns><span data-ttu-id="a6db4-112">True geometry2、geometry1 と交差するそれ以外の場合は false を返しますを返します。</span><span class="sxs-lookup"><span data-stu-id="a6db4-112">Returns true if geometry1 intersects with geometry2, otherwise returns false.</span></span></returns>
        <remarks>To be added.</remarks>
        <example>
          <code><![CDATA[
            var distanceQuery = documents.Where(document => document.Location.Intersects(new Point(20.1, 20)));
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="IsValid">
      <MemberSignature Language="C#" Value="public static bool IsValid (this Microsoft.Azure.Documents.Spatial.Geometry geometry);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsValid(class Microsoft.Azure.Documents.Spatial.Geometry geometry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValid(Microsoft.Azure.Documents.Spatial.Geometry)" />
      <MemberSignature Language="F#" Value="static member IsValid : Microsoft.Azure.Documents.Spatial.Geometry -&gt; bool" Usage="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValid geometry" />
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
        <Parameter Name="geometry" Type="Microsoft.Azure.Documents.Spatial.Geometry" RefType="this" />
      </Parameters>
      <Docs>
        <param name="geometry"><span data-ttu-id="a6db4-113">有効性を確認するジオメトリ。</span><span class="sxs-lookup"><span data-stu-id="a6db4-113">The geometry to check for validity.</span></span></param>
        <summary>
          <para>
            <span data-ttu-id="a6db4-114">かどうかを<paramref name="geometry" />が有効では指定され、Azure Cosmos DB サービスによってインデックス付きで使用されるクエリを指定できます。</span><span class="sxs-lookup"><span data-stu-id="a6db4-114">Determines if the <paramref name="geometry" /> specified is valid and can be indexed or used in queries by Azure Cosmos DB service.</span></span>
            </para>
          <para>
            <span data-ttu-id="a6db4-115">Geometry が有効でない場合にいないインデックスが作成されます。</span><span class="sxs-lookup"><span data-stu-id="a6db4-115">If a geometry is not valid, it will not be indexed.</span></span> <span data-ttu-id="a6db4-116">またクエリ時に無効なジオメトリに相当する<c>未定義</c>です。</span><span class="sxs-lookup"><span data-stu-id="a6db4-116">Also during query time invalid geometries are equivalent to <c>undefined</c>.</span></span>
            </para>
        </summary>
        <returns>
          <span data-ttu-id="a6db4-117"><c>true</c>形状は無効な場合です。</span><span class="sxs-lookup"><span data-stu-id="a6db4-117"><c>true</c> if geometry is valid.</span></span> <span data-ttu-id="a6db4-118"><c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="a6db4-118"><c>false</c> otherwise.</span></span></returns>
        <remarks>
            <span data-ttu-id="a6db4-119">この関数では、現在<paramref name="geometry" />型の<see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" />と<see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />です。</span><span class="sxs-lookup"><span data-stu-id="a6db4-119">Currently this function supports <paramref name="geometry" /> of type <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" /> and <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />.</span></span>
            </remarks>
        <example>
          <para>
            <span data-ttu-id="a6db4-120">この例では、インデックスが作成されなかったが無効なジオメトリを含むすべてのドキュメントを選択します。</span><span class="sxs-lookup"><span data-stu-id="a6db4-120">This example select all the documents which contain invalid geometries which were not indexed.</span></span>
            </para>
          <code><![CDATA[
            var invalidDocuments = documents.Where(document => !document.Location.IsValid());
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="IsValidDetailed">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.GeometryValidationResult IsValidDetailed (this Microsoft.Azure.Documents.Spatial.Geometry geometry);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Spatial.GeometryValidationResult IsValidDetailed(class Microsoft.Azure.Documents.Spatial.Geometry geometry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValidDetailed(Microsoft.Azure.Documents.Spatial.Geometry)" />
      <MemberSignature Language="F#" Value="static member IsValidDetailed : Microsoft.Azure.Documents.Spatial.Geometry -&gt; Microsoft.Azure.Documents.Spatial.GeometryValidationResult" Usage="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValidDetailed geometry" />
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
        <ReturnType>Microsoft.Azure.Documents.Spatial.GeometryValidationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="geometry" Type="Microsoft.Azure.Documents.Spatial.Geometry" RefType="this" />
      </Parameters>
      <Docs>
        <param name="geometry"><span data-ttu-id="a6db4-121">有効性を確認するジオメトリ。</span><span class="sxs-lookup"><span data-stu-id="a6db4-121">The geometry to check for validity.</span></span></param>
        <summary>
          <para>
            <span data-ttu-id="a6db4-122">かどうかを<paramref name="geometry" />が有効では指定され、Azure Cosmos DB サービスによってインデックス付きで使用されるクエリを指定できます。</span><span class="sxs-lookup"><span data-stu-id="a6db4-122">Determines if the <paramref name="geometry" /> specified is valid and can be indexed or used in queries by Azure Cosmos DB service.</span></span>
            </para>
          <para>
            <span data-ttu-id="a6db4-123">Geometry が有効でない場合にいないインデックスが作成されます。</span><span class="sxs-lookup"><span data-stu-id="a6db4-123">If a geometry is not valid, it will not be indexed.</span></span> <span data-ttu-id="a6db4-124">またクエリ時に無効なジオメトリに相当する<c>未定義</c>です。</span><span class="sxs-lookup"><span data-stu-id="a6db4-124">Also during query time invalid geometries are equivalent to <c>undefined</c>.</span></span>
            </para>
        </summary>
        <returns><span data-ttu-id="a6db4-125">インスタンス<see cref="T:Microsoft.Azure.Documents.Spatial.GeometryValidationResult" />です。</span><span class="sxs-lookup"><span data-stu-id="a6db4-125">Instance of <see cref="T:Microsoft.Azure.Documents.Spatial.GeometryValidationResult" />.</span></span></returns>
        <remarks>
            <span data-ttu-id="a6db4-126">この関数では、現在<paramref name="geometry" />型の<see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" />と<see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />です。</span><span class="sxs-lookup"><span data-stu-id="a6db4-126">Currently this function supports <paramref name="geometry" /> of type <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" /> and <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />.</span></span>
            </remarks>
        <example>
          <para>
            <span data-ttu-id="a6db4-127">この例では、インデックスが作成されなかったが無効なジオメトリを含むすべてのドキュメントを選択します。</span><span class="sxs-lookup"><span data-stu-id="a6db4-127">This example select all the documents which contain invalid geometries which were not indexed.</span></span>
            </para>
          <code><![CDATA[
            var invalidReason = documents.Where(document => !document.Location.IsValid()).Select(document => document.Location.IsValidDetailed());
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="Within">
      <MemberSignature Language="C#" Value="public static bool Within (this Microsoft.Azure.Documents.Spatial.Geometry inner, Microsoft.Azure.Documents.Spatial.Geometry outer);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Within(class Microsoft.Azure.Documents.Spatial.Geometry inner, class Microsoft.Azure.Documents.Spatial.Geometry outer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Within(Microsoft.Azure.Documents.Spatial.Geometry,Microsoft.Azure.Documents.Spatial.Geometry)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Within (inner As Geometry, outer As Geometry) As Boolean" />
      <MemberSignature Language="F#" Value="static member Within : Microsoft.Azure.Documents.Spatial.Geometry * Microsoft.Azure.Documents.Spatial.Geometry -&gt; bool" Usage="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Within (inner, outer)" />
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
        <Parameter Name="inner" Type="Microsoft.Azure.Documents.Spatial.Geometry" RefType="this" />
        <Parameter Name="outer" Type="Microsoft.Azure.Documents.Spatial.Geometry" />
      </Parameters>
      <Docs>
        <param name="inner"><span data-ttu-id="a6db4-128">内部<see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />です。</span><span class="sxs-lookup"><span data-stu-id="a6db4-128">Inner <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span></span></param>
        <param name="outer"><span data-ttu-id="a6db4-129">外部<see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />です。</span><span class="sxs-lookup"><span data-stu-id="a6db4-129">Outer <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span></span></param>
        <summary>
            <span data-ttu-id="a6db4-130">かどうかを<paramref name="inner" /><see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />完全に含まれている<paramref name="outer" /> <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> Cosmos DB の Azure サービスにします。</span><span class="sxs-lookup"><span data-stu-id="a6db4-130">Determines if <paramref name="inner" /><see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> is fully contained inside <paramref name="outer" /><see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="a6db4-131"><c>true</c>場合<paramref name="inner" /><see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />完全に含まれている<paramref name="outer" /><see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />です。</span><span class="sxs-lookup"><span data-stu-id="a6db4-131"><c>true</c> if <paramref name="inner" /><see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> is fully contained inside <paramref name="outer" /><see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span></span>
            <span data-ttu-id="a6db4-132"><c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="a6db4-132"><c>false</c> otherwise.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="a6db4-133">この関数では、現在<paramref name="inner" />型の geometry<see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" />と型の外部のジオメトリ<see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />です。</span><span class="sxs-lookup"><span data-stu-id="a6db4-133">Currently this function supports <paramref name="inner" /> geometry of type <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" /> and outer geometry of type <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />.</span></span>
            </remarks>
        <example>
          <code><![CDATA[
            Polygon polygon = new Polygon(
                   new[]
                   {
                        new Position(10, 10),
                        new Position(30, 10),
                        new Position(30, 30),
                        new Position(10, 30),
                        new Position(10, 10)
                   });
            var withinQuery = documents.Where(document => document.Location.Within(polygon));
            ]]></code>
        </example>
      </Docs>
    </Member>
  </Members>
</Type>