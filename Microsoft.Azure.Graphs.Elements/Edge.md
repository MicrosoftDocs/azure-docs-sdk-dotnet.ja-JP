<Type Name="Edge" FullName="Microsoft.Azure.Graphs.Elements.Edge">
  <TypeSignature Language="C#" Value="public class Edge" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Edge extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.Elements.Edge" />
  <TypeSignature Language="VB.NET" Value="Public Class Edge" />
  <TypeSignature Language="F#" Value="type Edge = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
    <AssemblyVersion>1.14.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Graphs.Elements.EdgeConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5b4bd-101">エッジのデータのストレージ コンテナーです。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-101">Storage container for edge data.</span></span>
            <span data-ttu-id="5b4bd-102">GraphSON 形式から逆シリアル化をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-102">Supports deserialization from GraphSON format.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Edge ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Edge.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5b4bd-103"><see cref="T:Microsoft.Azure.Graphs.Elements.Edge" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Graphs.Elements.Edge" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.Property&gt; GetProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Graphs.Elements.Property&gt; GetProperties() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Edge.GetProperties" />
      <MemberSignature Language="VB.NET" Value="Public Iterator Function GetProperties () As IEnumerable(Of Property)" />
      <MemberSignature Language="F#" Value="member this.GetProperties : unit -&gt; seq&lt;Microsoft.Azure.Graphs.Elements.Property&gt;" Usage="edge.GetProperties " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.IteratorStateMachine(typeof(Microsoft.Azure.Graphs.Elements.Edge/&lt;GetProperties&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.Property&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5b4bd-104">エッジのすべてのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-104">Gets all the propeties on the edge.</span></span>
            </summary>
        <returns><span data-ttu-id="5b4bd-105">端のプロパティの列挙可能です。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-105">Enumerable of the edges properties.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Graphs.Elements.Property GetProperty (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Graphs.Elements.Property GetProperty(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Edge.GetProperty(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProperty (key As String) As Property" />
      <MemberSignature Language="F#" Value="member this.GetProperty : string -&gt; Microsoft.Azure.Graphs.Elements.Property" Usage="edge.GetProperty key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.Elements.Property</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="5b4bd-106">プロパティのキー。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-106">The key of the property.</span></span></param>
        <summary>
            <span data-ttu-id="5b4bd-107">プロパティ キーが指定されたエッジのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-107">Gets a property on the edge, given the property key.</span></span>
            </summary>
        <returns><span data-ttu-id="5b4bd-108">プロパティに一致する<paramref name="key" />です。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-108">Property that matches to <paramref name="key" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public object Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As Object" />
      <MemberSignature Language="F#" Value="member this.Id : obj" Usage="Microsoft.Azure.Graphs.Elements.Edge.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b4bd-109">取得または識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-109">Gets or sets the identifier.</span></span>
            </summary>
        <value>
            <span data-ttu-id="5b4bd-110">識別子。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-110">The identifier.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InVertexId">
      <MemberSignature Language="C#" Value="public object InVertexId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object InVertexId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.InVertexId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InVertexId As Object" />
      <MemberSignature Language="F#" Value="member this.InVertexId : obj" Usage="Microsoft.Azure.Graphs.Elements.Edge.InVertexId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b4bd-111">取得または設定の頂点の識別子。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-111">Gets or sets the in vertex identifier.</span></span>
            </summary>
        <value>
            <span data-ttu-id="5b4bd-112">頂点の識別子。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-112">The in vertex identifier.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InVertexLabel">
      <MemberSignature Language="C#" Value="public string InVertexLabel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InVertexLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.InVertexLabel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InVertexLabel As String" />
      <MemberSignature Language="F#" Value="member this.InVertexLabel : string" Usage="Microsoft.Azure.Graphs.Elements.Edge.InVertexLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b4bd-113">取得または設定の頂点のラベル。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-113">Gets or sets the in vertex label.</span></span>
            </summary>
        <value>
            <span data-ttu-id="5b4bd-114">頂点のラベルにします。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-114">The in vertex label.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.Label" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string" Usage="Microsoft.Azure.Graphs.Elements.Edge.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b4bd-115">ラベルを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-115">Gets or sets the label.</span></span>
            </summary>
        <value>
            <span data-ttu-id="5b4bd-116">ラベル。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-116">The label.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutVertexId">
      <MemberSignature Language="C#" Value="public object OutVertexId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object OutVertexId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.OutVertexId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutVertexId As Object" />
      <MemberSignature Language="F#" Value="member this.OutVertexId : obj" Usage="Microsoft.Azure.Graphs.Elements.Edge.OutVertexId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b4bd-117">取得または設定を頂点の識別子。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-117">Gets or sets the out vertex identifier.</span></span>
            </summary>
        <value>
            <span data-ttu-id="5b4bd-118">頂点の識別子。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-118">The out vertex identifier.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutVertexLabel">
      <MemberSignature Language="C#" Value="public string OutVertexLabel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutVertexLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.OutVertexLabel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutVertexLabel As String" />
      <MemberSignature Language="F#" Value="member this.OutVertexLabel : string" Usage="Microsoft.Azure.Graphs.Elements.Edge.OutVertexLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b4bd-119">取得または設定を頂点ラベル。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-119">Gets or sets the out vertex label.</span></span>
            </summary>
        <value>
            <span data-ttu-id="5b4bd-120">Out 頂点のラベル。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-120">The out vertex label.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Edge.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="edge.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5b4bd-121">このインスタンスを検証します。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-121">Validates this instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="5b4bd-122">エッジには有効な id が必要です。 または、エッジは有効なラベルが必要です。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-122">Edge must have a valid Id. or Edge must have a valid Label.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="5b4bd-123">エッジは、InVertexId を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-123">Edge must specify InVertexId.</span></span>
            <span data-ttu-id="5b4bd-124">または、エッジが OutVertexId を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-124">or Edge must specify OutVertexId.</span></span>
            <span data-ttu-id="5b4bd-125">または、エッジが InVertexLabel を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-125">or Edge must specify InVertexLabel.</span></span>
            <span data-ttu-id="5b4bd-126">または、エッジが OutVertexLabel を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b4bd-126">or Edge must specify OutVertexLabel.</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>