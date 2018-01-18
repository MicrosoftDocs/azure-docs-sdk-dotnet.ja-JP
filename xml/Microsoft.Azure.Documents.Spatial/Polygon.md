<Type Name="Polygon" FullName="Microsoft.Azure.Documents.Spatial.Polygon">
  <TypeSignature Language="C#" Value="public sealed class Polygon : Microsoft.Azure.Documents.Spatial.Geometry, IEquatable&lt;Microsoft.Azure.Documents.Spatial.Polygon&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Polygon extends Microsoft.Azure.Documents.Spatial.Geometry implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Spatial.Polygon&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.Polygon" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Polygon&#xA;Inherits Geometry&#xA;Implements IEquatable(Of Polygon)" />
  <TypeSignature Language="F#" Value="type Polygon = class&#xA;    inherit Geometry&#xA;    interface IEquatable&lt;Polygon&gt;" />
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
    <BaseTypeName>Microsoft.Azure.Documents.Spatial.Geometry</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Spatial.Polygon&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="b29de-101">Azure Cosmos DB サービスの多角形 geometry クラスです。</span><span class="sxs-lookup"><span data-stu-id="b29de-101">Polygon geometry class in the Azure Cosmos DB service.</span></span>
            </para>
      <para>
            <span data-ttu-id="b29de-102">多角形は、「多角形のリング」のセットで表されます。</span><span class="sxs-lookup"><span data-stu-id="b29de-102">A polygon is represented by the set of "polygon rings".</span></span> <span data-ttu-id="b29de-103">それぞれのリングが閉じているコマンドライン文字列。</span><span class="sxs-lookup"><span data-stu-id="b29de-103">Each ring is closed line string.</span></span>
            <span data-ttu-id="b29de-104">最初のリングでは、外部リングを定義します。</span><span class="sxs-lookup"><span data-stu-id="b29de-104">First ring defines external ring.</span></span> <span data-ttu-id="b29de-105">後続のすべてのリングは、外部リングで「口」を定義します。</span><span class="sxs-lookup"><span data-stu-id="b29de-105">All subsequent rings define "holes" in the external ring.</span></span>
            </para>
      <para>
            <span data-ttu-id="b29de-106">リングは、左側にある規則を使用して指定する必要があります。 そのポイントの順序でリングを走査する内部、多角形領域の左側にされていることになります。</span><span class="sxs-lookup"><span data-stu-id="b29de-106">Rings must be specified using Left Hand Rule: traversing the ring in the order of its points, should result in internal area of the polygon being to the left side.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
    <example>
            <span data-ttu-id="b29de-107">この例では、地球のごく一部の内容を含む多角形を定義する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="b29de-107">This example shows how to define a polygon which covers small portion of the Earth:</span></span>
            <code language="c#"><![CDATA[
            var polygon = new Polygon(
                    new[]
                    {
                        new Position(20.0, 20.0),
                        new Position(30.0, 20.0),
                        new Position(30.0, 30.0),
                        new Position(20.0, 30.0)
                        new Position(20.0, 20.0)
                    });
            ]]></code></example>
    <example>
            <span data-ttu-id="b29de-108">この例は複数の半球に収まらない領域の内容を含む多角形を定義する方法を示します: (座標の注文だけが取り消されたことに注意してください)。</span><span class="sxs-lookup"><span data-stu-id="b29de-108">This example shows how to define a polygon which covers area more than one hemisphere: (Notice that only order of coordinates was reversed).</span></span>
            <code language="c#"><![CDATA[
            var polygon = new Polygon(
            new[]
                    {
                    new Position(20.0, 20.0),
                        new Position(20.0, 30.0),
                        new Position(30.0, 30.0),
                        new Position(30.0, 20.0)
                        new Position(20.0, 20.0)
                        });
                    ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Polygon (System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; rings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.Spatial.LinearRing&gt; rings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Documents.Spatial.LinearRing})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (rings As IList(Of LinearRing))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Polygon : System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; -&gt; Microsoft.Azure.Documents.Spatial.Polygon" Usage="new Microsoft.Azure.Documents.Spatial.Polygon rings" />
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
        <Parameter Name="rings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;" />
      </Parameters>
      <Docs>
        <param name="rings">
          <para>
            <span data-ttu-id="b29de-109">多角形のリングします。</span><span class="sxs-lookup"><span data-stu-id="b29de-109">Polygon rings.</span></span>
            </para>
          <para>
            <span data-ttu-id="b29de-110">最初のリングが外部リングでします。</span><span class="sxs-lookup"><span data-stu-id="b29de-110">First ring is external ring.</span></span> <span data-ttu-id="b29de-111">次のリングは、多角形で '穴' を定義します。</span><span class="sxs-lookup"><span data-stu-id="b29de-111">Following rings define 'holes' in the polygon.</span></span>
            </para>
        </param>
        <summary>
            <span data-ttu-id="b29de-112">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="b29de-112">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> class in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Polygon (System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt; externalRingPositions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.Spatial.Position&gt; externalRingPositions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Documents.Spatial.Position})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (externalRingPositions As IList(Of Position))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Polygon : System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt; -&gt; Microsoft.Azure.Documents.Spatial.Polygon" Usage="new Microsoft.Azure.Documents.Spatial.Polygon externalRingPositions" />
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
        <Parameter Name="externalRingPositions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt;" />
      </Parameters>
      <Docs>
        <param name="externalRingPositions">
            <span data-ttu-id="b29de-113">外部の多角形のリングの座標です。</span><span class="sxs-lookup"><span data-stu-id="b29de-113">External polygon ring coordinates.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b29de-114">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> Cosmos DB の Azure サービスで外部リング (多角形が含まれていない穴には) からのクラスです。</span><span class="sxs-lookup"><span data-stu-id="b29de-114">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> class, from external ring (the polygon contains no holes) in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Polygon (System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; rings, Microsoft.Azure.Documents.Spatial.GeometryParams geometryParams);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.Spatial.LinearRing&gt; rings, class Microsoft.Azure.Documents.Spatial.GeometryParams geometryParams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Documents.Spatial.LinearRing},Microsoft.Azure.Documents.Spatial.GeometryParams)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Polygon : System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; * Microsoft.Azure.Documents.Spatial.GeometryParams -&gt; Microsoft.Azure.Documents.Spatial.Polygon" Usage="new Microsoft.Azure.Documents.Spatial.Polygon (rings, geometryParams)" />
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
        <Parameter Name="rings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;" />
        <Parameter Name="geometryParams" Type="Microsoft.Azure.Documents.Spatial.GeometryParams" />
      </Parameters>
      <Docs>
        <param name="rings">
            <span data-ttu-id="b29de-115">多角形のリングします。</span><span class="sxs-lookup"><span data-stu-id="b29de-115">Polygon rings.</span></span>
            </param>
        <param name="geometryParams">
            <span data-ttu-id="b29de-116">追加のジオメトリのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b29de-116">Additional geometry parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b29de-117">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="b29de-117">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> class in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Spatial.Polygon other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Spatial.Polygon other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.Equals(Microsoft.Azure.Documents.Spatial.Polygon)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Polygon) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Spatial.Polygon -&gt; bool" Usage="polygon.Equals other" />
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
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Spatial.Polygon" />
      </Parameters>
      <Docs>
        <param name="other">
          <span data-ttu-id="b29de-118"><see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />これと比較する<see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />です。</span><span class="sxs-lookup"><span data-stu-id="b29de-118"><see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> to compare to this <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />.</span></span></param>
        <summary>
            <span data-ttu-id="b29de-119">かどうかをこの<see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />と等しい、 <paramref name="other" /> Cosmos DB の Azure サービスにします。</span><span class="sxs-lookup"><span data-stu-id="b29de-119">Determines if this <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> is equal to the <paramref name="other" /> in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="b29de-120"><c>true</c>オブジェクトが等しい場合。</span><span class="sxs-lookup"><span data-stu-id="b29de-120"><c>true</c> if objects are equal.</span></span> <span data-ttu-id="b29de-121"><c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="b29de-121"><c>false</c> otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="polygon.Equals obj" />
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
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="b29de-122">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b29de-122">The object to compare with the current object.</span></span> </param>
        <summary>
            <span data-ttu-id="b29de-123">決定するかどうか、指定した<see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />が現在と等しい<see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />Cosmos DB の Azure サービスで。</span><span class="sxs-lookup"><span data-stu-id="b29de-123">Determines whether the specified <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> is equal to the current <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b29de-124">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="b29de-124">true if the specified object is equal to the current object; otherwise, false.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="polygon.GetHashCode " />
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
            <span data-ttu-id="b29de-125">ハッシュ関数として機能、 <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> Azure Cosmos DB サービスの種類。</span><span class="sxs-lookup"><span data-stu-id="b29de-125">Serves as a hash function for the <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> type in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b29de-126">現在の <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> のハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="b29de-126">A hash code for the current <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rings">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; Rings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class Microsoft.Azure.Documents.Spatial.LinearRing&gt; Rings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Polygon.Rings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Rings As ReadOnlyCollection(Of LinearRing)" />
      <MemberSignature Language="F#" Value="member this.Rings : System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;" Usage="Microsoft.Azure.Documents.Spatial.Polygon.Rings" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("coordinates", Order=1, Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b29de-127">Azure Cosmos DB サービスの多角形のリングを取得します。</span><span class="sxs-lookup"><span data-stu-id="b29de-127">Gets the polygon rings in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b29de-128">多角形のリングします。</span><span class="sxs-lookup"><span data-stu-id="b29de-128">Polygon rings.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>