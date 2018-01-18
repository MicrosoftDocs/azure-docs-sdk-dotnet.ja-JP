<Type Name="VertexEdge" FullName="Microsoft.Azure.Graphs.Elements.VertexEdge">
  <TypeSignature Language="C#" Value="public sealed class VertexEdge : Microsoft.Azure.Graphs.Elements.Edge" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit VertexEdge extends Microsoft.Azure.Graphs.Elements.Edge" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.Elements.VertexEdge" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class VertexEdge&#xA;Inherits Edge" />
  <TypeSignature Language="F#" Value="type VertexEdge = class&#xA;    inherit Edge" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
    <AssemblyVersion>1.14.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Graphs.Elements.Edge</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Graphs.Elements.VertexEdgeConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="55791-101">頂点に含まれるエッジ データのストレージ コンテナーです。</span><span class="sxs-lookup"><span data-stu-id="55791-101">Storage container for edge data contained within a vertex.</span></span>
            <span data-ttu-id="55791-102">GraphSON 形式から逆シリアル化をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="55791-102">Supports deserialization from GraphSON format.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="55791-103">頂点エッジ データはエッジ データよりもよりスパース頂点 in\out ラベルを設定しないことです。</span><span class="sxs-lookup"><span data-stu-id="55791-103">Vertex edge data is more sparse than edge data in that it doesn't populate the vertex in\out labels.</span></span>
            <span data-ttu-id="55791-104">頂点エッジ データには、その親の頂点に対する相対方向情報も含まれます。</span><span class="sxs-lookup"><span data-stu-id="55791-104">Vertex edge data also contains direction information relative to its parent vertex.</span></span>
            <span data-ttu-id="55791-105">頂点ではなく、full、依存しない、edge オブジェクトに格納されている境界情報を表すために使用されます。</span><span class="sxs-lookup"><span data-stu-id="55791-105">It is used to represent the edge information that is stored within a vertex rather than the full, independent, edge object.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Direction">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Graphs.Elements.Direction Direction { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Graphs.Elements.Direction Direction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.VertexEdge.Direction" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Direction As Direction" />
      <MemberSignature Language="F#" Value="member this.Direction : Microsoft.Azure.Graphs.Elements.Direction" Usage="Microsoft.Azure.Graphs.Elements.VertexEdge.Direction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.Elements.Direction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55791-106">頂点のエッジの方向を取得します。</span><span class="sxs-lookup"><span data-stu-id="55791-106">Gets the vertex edge direction.</span></span>
            </summary>
        <value>
            <span data-ttu-id="55791-107">頂点エッジ方向です。</span><span class="sxs-lookup"><span data-stu-id="55791-107">The vertex edge direction.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.VertexEdge.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="vertexEdge.Validate " />
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
            <span data-ttu-id="55791-108">このインスタンスを検証します。</span><span class="sxs-lookup"><span data-stu-id="55791-108">Validates this instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="55791-109">VertexEdge には有効な id が必要です。 または、VertexEdge は有効なラベルを持つ必要があります。</span><span class="sxs-lookup"><span data-stu-id="55791-109">VertexEdge must have a valid Id. or VertexEdge must have a valid Label.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="55791-110">VertexEdge には、少なくとも 1 つの InVertexId または OutVertexId を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="55791-110">VertexEdge must specify at least one InVertexId or OutVertexId.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>