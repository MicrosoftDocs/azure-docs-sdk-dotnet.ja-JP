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
            頂点に含まれるエッジ データのストレージ コンテナーです。
            GraphSON 形式から逆シリアル化をサポートしています。
            </summary>
    <remarks>
            頂点エッジ データはエッジ データよりもよりスパース頂点 in\out ラベルを設定しないことです。
            頂点エッジ データには、その親の頂点に対する相対方向情報も含まれます。
            頂点ではなく、full、依存しない、edge オブジェクトに格納されている境界情報を表すために使用されます。
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
            頂点のエッジの方向を取得します。
            </summary>
        <value>
            頂点エッジ方向です。
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
            このインスタンスを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            VertexEdge には有効な id が必要です。 または、VertexEdge は有効なラベルを持つ必要があります。
            </exception>
        <exception cref="T:System.ArgumentException">VertexEdge には、少なくとも 1 つの InVertexId または OutVertexId を指定する必要があります。</exception>
      </Docs>
    </Member>
  </Members>
</Type>