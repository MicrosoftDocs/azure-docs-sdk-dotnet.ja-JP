<Type Name="Point" FullName="Microsoft.Azure.Documents.Spatial.Point">
  <TypeSignature Language="C#" Value="public sealed class Point : Microsoft.Azure.Documents.Spatial.Geometry, IEquatable&lt;Microsoft.Azure.Documents.Spatial.Point&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Point extends Microsoft.Azure.Documents.Spatial.Geometry implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Spatial.Point&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.Point" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Point&#xA;Inherits Geometry&#xA;Implements IEquatable(Of Point)" />
  <TypeSignature Language="F#" Value="type Point = class&#xA;    inherit Geometry&#xA;    interface IEquatable&lt;Point&gt;" />
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
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Spatial.Point&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="a02c9-101">Azure Cosmos DB サービスの geometry のクラスをポイントします。</span><span class="sxs-lookup"><span data-stu-id="a02c9-101">Point geometry class in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Point (Microsoft.Azure.Documents.Spatial.Position position);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Documents.Spatial.Position position) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Point.#ctor(Microsoft.Azure.Documents.Spatial.Position)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Point : Microsoft.Azure.Documents.Spatial.Position -&gt; Microsoft.Azure.Documents.Spatial.Point" Usage="new Microsoft.Azure.Documents.Spatial.Point position" />
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
        <Parameter Name="position" Type="Microsoft.Azure.Documents.Spatial.Position" />
      </Parameters>
      <Docs>
        <param name="position">
            <span data-ttu-id="a02c9-102">ポイントの位置。</span><span class="sxs-lookup"><span data-stu-id="a02c9-102">Position of the point.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a02c9-103">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="a02c9-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> class in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Point (Microsoft.Azure.Documents.Spatial.Position position, Microsoft.Azure.Documents.Spatial.GeometryParams geometryParams);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Documents.Spatial.Position position, class Microsoft.Azure.Documents.Spatial.GeometryParams geometryParams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Point.#ctor(Microsoft.Azure.Documents.Spatial.Position,Microsoft.Azure.Documents.Spatial.GeometryParams)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Point : Microsoft.Azure.Documents.Spatial.Position * Microsoft.Azure.Documents.Spatial.GeometryParams -&gt; Microsoft.Azure.Documents.Spatial.Point" Usage="new Microsoft.Azure.Documents.Spatial.Point (position, geometryParams)" />
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
        <Parameter Name="position" Type="Microsoft.Azure.Documents.Spatial.Position" />
        <Parameter Name="geometryParams" Type="Microsoft.Azure.Documents.Spatial.GeometryParams" />
      </Parameters>
      <Docs>
        <param name="position">
            <span data-ttu-id="a02c9-104">座標をポイントします。</span><span class="sxs-lookup"><span data-stu-id="a02c9-104">Point coordinates.</span></span>
            </param>
        <param name="geometryParams">
            <span data-ttu-id="a02c9-105">追加のジオメトリのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="a02c9-105">Additional geometry parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a02c9-106">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="a02c9-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> class in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Point (double longitude, double latitude);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(float64 longitude, float64 latitude) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Point.#ctor(System.Double,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (longitude As Double, latitude As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Point : double * double -&gt; Microsoft.Azure.Documents.Spatial.Point" Usage="new Microsoft.Azure.Documents.Spatial.Point (longitude, latitude)" />
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
        <Parameter Name="longitude" Type="System.Double" />
        <Parameter Name="latitude" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="longitude">
            <span data-ttu-id="a02c9-107">点の経度です。</span><span class="sxs-lookup"><span data-stu-id="a02c9-107">Longitude of the point.</span></span>
            </param>
        <param name="latitude">
            <span data-ttu-id="a02c9-108">点の緯度です。</span><span class="sxs-lookup"><span data-stu-id="a02c9-108">Latitude of the point.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a02c9-109">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> Cosmos DB の Azure サービス内のクラスです。</span><span class="sxs-lookup"><span data-stu-id="a02c9-109">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> class in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Spatial.Point other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Spatial.Point other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Point.Equals(Microsoft.Azure.Documents.Spatial.Point)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Point) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Spatial.Point -&gt; bool" Usage="point.Equals other" />
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
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Spatial.Point" />
      </Parameters>
      <Docs>
        <param name="other">
          <span data-ttu-id="a02c9-110"><see cref="T:Microsoft.Azure.Documents.Spatial.Point" />これと比較する<see cref="T:Microsoft.Azure.Documents.Spatial.Point" />です。</span><span class="sxs-lookup"><span data-stu-id="a02c9-110"><see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> to compare to this <see cref="T:Microsoft.Azure.Documents.Spatial.Point" />.</span></span></param>
        <summary>
            <span data-ttu-id="a02c9-111">かどうかをこの<see cref="T:Microsoft.Azure.Documents.Spatial.Point" />と等しい<paramref name="other" />Cosmos DB の Azure サービスにします。</span><span class="sxs-lookup"><span data-stu-id="a02c9-111">Determines if this <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> is equal to <paramref name="other" /> in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="a02c9-112"><c>true</c>オブジェクトが等しい場合。</span><span class="sxs-lookup"><span data-stu-id="a02c9-112"><c>true</c> if objects are equal.</span></span> <span data-ttu-id="a02c9-113"><c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="a02c9-113"><c>false</c> otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Point.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="point.Equals obj" />
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
        <param name="obj"><span data-ttu-id="a02c9-114">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a02c9-114">The object to compare with the current object.</span></span> </param>
        <summary>
            <span data-ttu-id="a02c9-115">決定するかどうか、指定した<see cref="T:Microsoft.Azure.Documents.Spatial.Point" />が現在と等しい<see cref="T:Microsoft.Azure.Documents.Spatial.Point" />Cosmos DB の Azure サービスで。</span><span class="sxs-lookup"><span data-stu-id="a02c9-115">Determines whether the specified <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> is equal to the current <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="a02c9-116">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="a02c9-116">true if the specified object  is equal to the current object; otherwise, false.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Point.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="point.GetHashCode " />
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
            <span data-ttu-id="a02c9-117">ハッシュ関数として機能、 <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> Azure Cosmos DB サービスの種類。</span><span class="sxs-lookup"><span data-stu-id="a02c9-117">Serves as a hash function for the <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> type in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="a02c9-118">現在のジオメトリのハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="a02c9-118">A hash code for the current geometry.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Position">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Spatial.Position Position { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Spatial.Position Position" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Point.Position" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Position As Position" />
      <MemberSignature Language="F#" Value="member this.Position : Microsoft.Azure.Documents.Spatial.Position" Usage="Microsoft.Azure.Documents.Spatial.Point.Position" />
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
        <ReturnType>Microsoft.Azure.Documents.Spatial.Position</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a02c9-119">座標は、Azure Cosmos DB サービスのポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="a02c9-119">Gets point coordinates in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="a02c9-120">点の座標。</span><span class="sxs-lookup"><span data-stu-id="a02c9-120">Coordinates of the point.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>