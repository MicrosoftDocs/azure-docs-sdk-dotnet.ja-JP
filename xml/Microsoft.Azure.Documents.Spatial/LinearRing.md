<Type Name="LinearRing" FullName="Microsoft.Azure.Documents.Spatial.LinearRing">
  <TypeSignature Language="C#" Value="public sealed class LinearRing : IEquatable&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit LinearRing extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Spatial.LinearRing&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.LinearRing" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LinearRing&#xA;Implements IEquatable(Of LinearRing)" />
  <TypeSignature Language="F#" Value="type LinearRing = class&#xA;    interface IEquatable&lt;LinearRing&gt;" />
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
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Documents.Spatial.Converters.LinearRingJsonConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ba03b-101">A<see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" />は 4 つ以上の位置の LineString を終了します。</span><span class="sxs-lookup"><span data-stu-id="ba03b-101">A <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> is closed LineString with 4 or more positions.</span></span> <span data-ttu-id="ba03b-102">最初と最後の位置は同等です (同等のポイントを表します)。</span><span class="sxs-lookup"><span data-stu-id="ba03b-102">The first and last positions are equivalent (they represent equivalent points).</span></span>
            <span data-ttu-id="ba03b-103"><see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" />は明示的には表されません GeoJSON の geometry 型で呼ばれる、 <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> Azure Cosmos DB サービスの geometry 型の定義。</span><span class="sxs-lookup"><span data-stu-id="ba03b-103">Though a <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> is not explicitly represented as a GeoJSON geometry type, it is referred to in the <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> geometry type definition in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinearRing (System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt; coordinates);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.Spatial.Position&gt; coordinates) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LinearRing.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Documents.Spatial.Position})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (coordinates As IList(Of Position))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.LinearRing : System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt; -&gt; Microsoft.Azure.Documents.Spatial.LinearRing" Usage="new Microsoft.Azure.Documents.Spatial.LinearRing coordinates" />
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
        <Parameter Name="coordinates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt;" />
      </Parameters>
      <Docs>
        <param name="coordinates">
            <span data-ttu-id="ba03b-104">座標です。</span><span class="sxs-lookup"><span data-stu-id="ba03b-104">The coordinates.</span></span> <span data-ttu-id="ba03b-105">4 つ以上の位置。</span><span class="sxs-lookup"><span data-stu-id="ba03b-105">4 or more positions.</span></span> <span data-ttu-id="ba03b-106">最初と最後の位置は同等です (同等のポイントを表します)。</span><span class="sxs-lookup"><span data-stu-id="ba03b-106">The first and last positions are equivalent (they represent equivalent points).</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba03b-107">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="ba03b-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> class in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Spatial.LinearRing other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Spatial.LinearRing other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LinearRing.Equals(Microsoft.Azure.Documents.Spatial.LinearRing)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As LinearRing) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Spatial.LinearRing -&gt; bool" Usage="linearRing.Equals other" />
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
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Spatial.LinearRing" />
      </Parameters>
      <Docs>
        <param name="other">
          <span data-ttu-id="ba03b-108"><see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" />この 1 つを比較します。</span><span class="sxs-lookup"><span data-stu-id="ba03b-108"><see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> to compare to this one.</span></span></param>
        <summary>
            <span data-ttu-id="ba03b-109">かどうかをこの<see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" />と等しい、 <paramref name="other" /> Cosmos DB の Azure サービスにします。</span><span class="sxs-lookup"><span data-stu-id="ba03b-109">Determines if this <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> is equal to the <paramref name="other" /> in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="ba03b-110"><c>true</c>線形リングが等しい場合は。</span><span class="sxs-lookup"><span data-stu-id="ba03b-110"><c>true</c> if linear rings are equal.</span></span> <span data-ttu-id="ba03b-111"><c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="ba03b-111"><c>false</c> otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LinearRing.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="linearRing.Equals obj" />
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
        <param name="obj"><span data-ttu-id="ba03b-112">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ba03b-112">The object to compare with the current object.</span></span> </param>
        <summary>
            <span data-ttu-id="ba03b-113">決定するかどうか、指定した<see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" />が現在と等しい<see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" />Cosmos DB の Azure サービスで。</span><span class="sxs-lookup"><span data-stu-id="ba03b-113">Determines whether the specified <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> is equal to the current <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ba03b-114">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="ba03b-114">true if the specified object  is equal to the current object; otherwise, false.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LinearRing.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="linearRing.GetHashCode " />
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
            <span data-ttu-id="ba03b-115">ハッシュ関数として機能、 <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> Cosmos DB の Azure サービス内の位置。</span><span class="sxs-lookup"><span data-stu-id="ba03b-115">Serves as a hash function for the <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> positions in the Azure Cosmos DB service.</span></span> 
            </summary>
        <returns>
            <span data-ttu-id="ba03b-116">現在の <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> のハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="ba03b-116">A hash code for the current <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Positions">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.Position&gt; Positions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class Microsoft.Azure.Documents.Spatial.Position&gt; Positions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.LinearRing.Positions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Positions As ReadOnlyCollection(Of Position)" />
      <MemberSignature Language="F#" Value="member this.Positions : System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.Position&gt;" Usage="Microsoft.Azure.Documents.Spatial.LinearRing.Positions" />
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
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.Position&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba03b-117">取得、 <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> Cosmos DB の Azure サービス内の位置。</span><span class="sxs-lookup"><span data-stu-id="ba03b-117">Gets the <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> positions in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="ba03b-118">位置、<see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" />です。</span><span class="sxs-lookup"><span data-stu-id="ba03b-118">Positions of the <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" />.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>