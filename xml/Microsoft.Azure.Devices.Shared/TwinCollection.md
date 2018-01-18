<Type Name="TwinCollection" FullName="Microsoft.Azure.Devices.Shared.TwinCollection">
  <TypeSignature Language="C#" Value="public class TwinCollection : System.Collections.IEnumerable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TwinCollection extends System.Object implements class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Shared.TwinCollection" />
  <TypeSignature Language="VB.NET" Value="Public Class TwinCollection&#xA;Implements IEnumerable" />
  <TypeSignature Language="F#" Value="type TwinCollection = class&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.IEnumerable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Devices.Shared.TwinCollectionJsonConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c4de4-101">プロパティのコレクションを表します<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="c4de4-101">Represents a collection of properties for <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TwinCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinCollection.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c4de4-102">インスタンスを作成<see cref="T:Microsoft.Azure.Devices.Shared.TwinCollection" />です。</span><span class="sxs-lookup"><span data-stu-id="c4de4-102">Creates instance of <see cref="T:Microsoft.Azure.Devices.Shared.TwinCollection" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TwinCollection (string twinJson);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string twinJson) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinCollection.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (twinJson As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Shared.TwinCollection : string -&gt; Microsoft.Azure.Devices.Shared.TwinCollection" Usage="new Microsoft.Azure.Devices.Shared.TwinCollection twinJson" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="twinJson" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="twinJson"><span data-ttu-id="c4de4-103">JSON フラグメントが対になったデータを格納します。</span><span class="sxs-lookup"><span data-stu-id="c4de4-103">JSON fragment containing the twin data.</span></span></param>
        <summary>
            <span data-ttu-id="c4de4-104">作成、<see cref="T:Microsoft.Azure.Devices.Shared.TwinCollection" />は JSON フラグメントを本文として使用します。</span><span class="sxs-lookup"><span data-stu-id="c4de4-104">Creates a <see cref="T:Microsoft.Azure.Devices.Shared.TwinCollection" /> using a JSON fragment as the body.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TwinCollection (Newtonsoft.Json.Linq.JObject twinJson, Newtonsoft.Json.Linq.JObject metadataJson);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Newtonsoft.Json.Linq.JObject twinJson, class Newtonsoft.Json.Linq.JObject metadataJson) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinCollection.#ctor(Newtonsoft.Json.Linq.JObject,Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (twinJson As JObject, metadataJson As JObject)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Shared.TwinCollection : Newtonsoft.Json.Linq.JObject * Newtonsoft.Json.Linq.JObject -&gt; Microsoft.Azure.Devices.Shared.TwinCollection" Usage="new Microsoft.Azure.Devices.Shared.TwinCollection (twinJson, metadataJson)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="twinJson" Type="Newtonsoft.Json.Linq.JObject" />
        <Parameter Name="metadataJson" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="twinJson"><span data-ttu-id="c4de4-105">JSON フラグメントが対になったデータを格納します。</span><span class="sxs-lookup"><span data-stu-id="c4de4-105">JSON fragment containing the twin data.</span></span></param>
        <param name="metadataJson"><span data-ttu-id="c4de4-106">メタデータを含む JSON フラグメントです。</span><span class="sxs-lookup"><span data-stu-id="c4de4-106">JSON fragment containing the metadata.</span></span></param>
        <summary>
            <span data-ttu-id="c4de4-107">作成、<see cref="T:Microsoft.Azure.Devices.Shared.TwinCollection" />本文とメタデータのフラグメントによって指定された JSON を使用します。</span><span class="sxs-lookup"><span data-stu-id="c4de4-107">Creates a <see cref="T:Microsoft.Azure.Devices.Shared.TwinCollection" /> using the given JSON fragments for the body and metadata.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TwinCollection (string twinJson, string metadataJson);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string twinJson, string metadataJson) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinCollection.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (twinJson As String, metadataJson As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Shared.TwinCollection : string * string -&gt; Microsoft.Azure.Devices.Shared.TwinCollection" Usage="new Microsoft.Azure.Devices.Shared.TwinCollection (twinJson, metadataJson)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="twinJson" Type="System.String" />
        <Parameter Name="metadataJson" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="twinJson"><span data-ttu-id="c4de4-108">JSON フラグメントが対になったデータを格納します。</span><span class="sxs-lookup"><span data-stu-id="c4de4-108">JSON fragment containing the twin data.</span></span></param>
        <param name="metadataJson"><span data-ttu-id="c4de4-109">メタデータを含む JSON フラグメントです。</span><span class="sxs-lookup"><span data-stu-id="c4de4-109">JSON fragment containing the metadata.</span></span></param>
        <summary>
            <span data-ttu-id="c4de4-110">作成、<see cref="T:Microsoft.Azure.Devices.Shared.TwinCollection" />本文とメタデータのフラグメントによって指定された JSON を使用します。</span><span class="sxs-lookup"><span data-stu-id="c4de4-110">Creates a <see cref="T:Microsoft.Azure.Devices.Shared.TwinCollection" /> using the given JSON fragments for the body and metadata.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearMetadata">
      <MemberSignature Language="C#" Value="public void ClearMetadata ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ClearMetadata() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinCollection.ClearMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Sub ClearMetadata ()" />
      <MemberSignature Language="F#" Value="member this.ClearMetadata : unit -&gt; unit" Usage="twinCollection.ClearMetadata " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c4de4-111">コレクションのクリアのメタデータ</span><span class="sxs-lookup"><span data-stu-id="c4de4-111">Clear metadata out of the collection</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Contains(string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinCollection.Contains(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (propertyName As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.Contains : string -&gt; bool" Usage="twinCollection.Contains propertyName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName"><span data-ttu-id="c4de4-112">検索するプロパティ</span><span class="sxs-lookup"><span data-stu-id="c4de4-112">The property to locate</span></span></param>
        <summary>
            <span data-ttu-id="c4de4-113">指定したプロパティが存在するかどうかを決定します。</span><span class="sxs-lookup"><span data-stu-id="c4de4-113">Determines whether the specified property is present</span></span>
            </summary>
        <returns><span data-ttu-id="c4de4-114">指定したプロパティが存在する場合は trueそれ以外の場合は false</span><span class="sxs-lookup"><span data-stu-id="c4de4-114">true if the specified property is present; otherwise, false</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.TwinCollection.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.Azure.Devices.Shared.TwinCollection.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4de4-115">コレクション内のプロパティの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="c4de4-115">Gets the count of properties in the Collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.IEnumerator GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.IEnumerator GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinCollection.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Iterator Overridable NotOverridable Function GetEnumerator () As IEnumerator" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.IEnumerator&#xA;override this.GetEnumerator : unit -&gt; System.Collections.IEnumerator" Usage="twinCollection.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.IteratorStateMachine(typeof(Microsoft.Azure.Devices.Shared.TwinCollection/&lt;GetEnumerator&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="GetLastUpdated">
      <MemberSignature Language="C#" Value="public DateTime GetLastUpdated ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.DateTime GetLastUpdated() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinCollection.GetLastUpdated" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLastUpdated () As DateTime" />
      <MemberSignature Language="F#" Value="member this.GetLastUpdated : unit -&gt; DateTime" Usage="twinCollection.GetLastUpdated " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c4de4-116">このプロパティの LastUpdated の時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="c4de4-116">Gets the LastUpdated time for this property</span></span>
            </summary>
        <returns><span data-ttu-id="c4de4-117">このプロパティの LastUpdated の時刻を表す DateTime インスタンス</span><span class="sxs-lookup"><span data-stu-id="c4de4-117">DateTime instance representing the LastUpdated time for this property</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLastUpdatedVersion">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; GetLastUpdatedVersion ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.Nullable`1&lt;int64&gt; GetLastUpdatedVersion() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinCollection.GetLastUpdatedVersion" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLastUpdatedVersion () As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.GetLastUpdatedVersion : unit -&gt; Nullable&lt;int64&gt;" Usage="twinCollection.GetLastUpdatedVersion " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c4de4-118">このプロパティの LastUpdatedVersion を取得します。</span><span class="sxs-lookup"><span data-stu-id="c4de4-118">Gets the LastUpdatedVersion for this property</span></span>
            </summary>
        <returns><span data-ttu-id="c4de4-119">LastUpdatdVersion 存在する場合は null それ以外の場合</span><span class="sxs-lookup"><span data-stu-id="c4de4-119">LastUpdatdVersion if present, null otherwise</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Shared.Metadata GetMetadata ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Devices.Shared.Metadata GetMetadata() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinCollection.GetMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMetadata () As Metadata" />
      <MemberSignature Language="F#" Value="member this.GetMetadata : unit -&gt; Microsoft.Azure.Devices.Shared.Metadata" Usage="twinCollection.GetMetadata " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Shared.Metadata</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c4de4-120">このプロパティのメタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="c4de4-120">Gets the Metadata for this property</span></span>
            </summary>
        <returns><span data-ttu-id="c4de4-121">このプロパティのメタデータを表すメタデータ インスタンス</span><span class="sxs-lookup"><span data-stu-id="c4de4-121">Metadata instance representing the metadata for this property</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public dynamic this[string propertyName] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.TwinCollection.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(propertyName As String) As Object" />
      <MemberSignature Language="F#" Value="member this.Item(string) : obj with get, set" Usage="Microsoft.Azure.Devices.Shared.TwinCollection.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName"><span data-ttu-id="c4de4-122">取得するプロパティの名前</span><span class="sxs-lookup"><span data-stu-id="c4de4-122">Name of the property to get</span></span></param>
        <summary>
            <span data-ttu-id="c4de4-123">プロパティのインデクサー</span><span class="sxs-lookup"><span data-stu-id="c4de4-123">Property Indexer</span></span>
            </summary>
        <value><span data-ttu-id="c4de4-124">指定されたプロパティ名の値</span><span class="sxs-lookup"><span data-stu-id="c4de4-124">Value for the given proprety name</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToJson">
      <MemberSignature Language="C#" Value="public string ToJson (Newtonsoft.Json.Formatting formatting = Newtonsoft.Json.Formatting.None);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ToJson(valuetype Newtonsoft.Json.Formatting formatting) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinCollection.ToJson(Newtonsoft.Json.Formatting)" />
      <MemberSignature Language="F#" Value="member this.ToJson : Newtonsoft.Json.Formatting -&gt; string" Usage="twinCollection.ToJson formatting" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="formatting" Type="Newtonsoft.Json.Formatting" />
      </Parameters>
      <Docs>
        <param name="formatting"><span data-ttu-id="c4de4-125">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c4de4-125">Optional.</span></span> <span data-ttu-id="c4de4-126">出力の JSON 文字列の書式設定します。</span><span class="sxs-lookup"><span data-stu-id="c4de4-126">Formatting for the output JSON string.</span></span></param>
        <summary>
            <span data-ttu-id="c4de4-127">JSON 文字列として、TwinProperties を取得します。</span><span class="sxs-lookup"><span data-stu-id="c4de4-127">Gets the TwinProperties as a JSON string</span></span>
            </summary>
        <returns><span data-ttu-id="c4de4-128">JSON 文字列</span><span class="sxs-lookup"><span data-stu-id="c4de4-128">JSON string</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinCollection.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="twinCollection.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public long Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.TwinCollection.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As Long" />
      <MemberSignature Language="F#" Value="member this.Version : int64" Usage="Microsoft.Azure.Devices.Shared.TwinCollection.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4de4-129">バージョンを取得します<see cref="T:Microsoft.Azure.Devices.Shared.TwinCollection" /></span><span class="sxs-lookup"><span data-stu-id="c4de4-129">Gets the version of the <see cref="T:Microsoft.Azure.Devices.Shared.TwinCollection" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>