<Type Name="Vertex" FullName="Microsoft.Azure.Graphs.Elements.Vertex">
  <TypeSignature Language="C#" Value="public sealed class Vertex" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Vertex extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.Elements.Vertex" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Vertex" />
  <TypeSignature Language="F#" Value="type Vertex = class" />
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
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Graphs.Elements.VertexConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            頂点のデータのストレージ コンテナーです。
            GraphSON 形式から逆シリアル化をサポートしています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetInEdges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.VertexEdge&gt; GetInEdges ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Graphs.Elements.VertexEdge&gt; GetInEdges() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Vertex.GetInEdges" />
      <MemberSignature Language="VB.NET" Value="Public Function GetInEdges () As IEnumerable(Of VertexEdge)" />
      <MemberSignature Language="F#" Value="member this.GetInEdges : unit -&gt; seq&lt;Microsoft.Azure.Graphs.Elements.VertexEdge&gt;" Usage="vertex.GetInEdges " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.VertexEdge&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            頂点へのすべての着信端を取得します。
            </summary>
        <returns>エッジの Enumerable です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInEdges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.VertexEdge&gt; GetInEdges (string label);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Graphs.Elements.VertexEdge&gt; GetInEdges(string label) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Vertex.GetInEdges(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetInEdges (label As String) As IEnumerable(Of VertexEdge)" />
      <MemberSignature Language="F#" Value="member this.GetInEdges : string -&gt; seq&lt;Microsoft.Azure.Graphs.Elements.VertexEdge&gt;" Usage="vertex.GetInEdges label" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.VertexEdge&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="label" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="label">条件に一致するエッジ ラベルです。</param>
        <summary>
            ラベル付きの頂点へのすべての着信端を取得<paramref name="label" />です。
            </summary>
        <returns>列挙可能な入力方向のエッジが含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutEdges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.VertexEdge&gt; GetOutEdges ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Graphs.Elements.VertexEdge&gt; GetOutEdges() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Vertex.GetOutEdges" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOutEdges () As IEnumerable(Of VertexEdge)" />
      <MemberSignature Language="F#" Value="member this.GetOutEdges : unit -&gt; seq&lt;Microsoft.Azure.Graphs.Elements.VertexEdge&gt;" Usage="vertex.GetOutEdges " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.VertexEdge&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            頂点から出力方向のエッジすべてを取得します。
            </summary>
        <returns>列挙可能な出力方向のエッジが含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutEdges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.VertexEdge&gt; GetOutEdges (string label);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Graphs.Elements.VertexEdge&gt; GetOutEdges(string label) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Vertex.GetOutEdges(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOutEdges (label As String) As IEnumerable(Of VertexEdge)" />
      <MemberSignature Language="F#" Value="member this.GetOutEdges : string -&gt; seq&lt;Microsoft.Azure.Graphs.Elements.VertexEdge&gt;" Usage="vertex.GetOutEdges label" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.VertexEdge&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="label" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="label">条件に一致するエッジ ラベルです。</param>
        <summary>
            ラベル付きの頂点から出力方向のエッジすべてを取得<paramref name="label" />です。
            </summary>
        <returns>列挙可能な出力方向のエッジが含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVertexProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.VertexProperty&gt; GetVertexProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Graphs.Elements.VertexProperty&gt; GetVertexProperties() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Vertex.GetVertexProperties" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVertexProperties () As IEnumerable(Of VertexProperty)" />
      <MemberSignature Language="F#" Value="member this.GetVertexProperties : unit -&gt; seq&lt;Microsoft.Azure.Graphs.Elements.VertexProperty&gt;" Usage="vertex.GetVertexProperties " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.VertexProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            頂点のすべての頂点プロパティを取得します。
            </summary>
        <returns>列挙可能なすべての頂点プロパティを格納します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVertexProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.VertexProperty&gt; GetVertexProperties (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Graphs.Elements.VertexProperty&gt; GetVertexProperties(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Vertex.GetVertexProperties(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVertexProperties (key As String) As IEnumerable(Of VertexProperty)" />
      <MemberSignature Language="F#" Value="member this.GetVertexProperties : string -&gt; seq&lt;Microsoft.Azure.Graphs.Elements.VertexProperty&gt;" Usage="vertex.GetVertexProperties key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.VertexProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">クエリにプロパティのキー。</param>
        <summary>
            指定したプロパティのキーに対応する頂点プロパティを取得します。
            </summary>
        <returns>一致する頂点プロパティを含む列挙可能な<paramref name="key" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public object Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Vertex.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As Object" />
      <MemberSignature Language="F#" Value="member this.Id : obj" Usage="Microsoft.Azure.Graphs.Elements.Vertex.Id" />
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
            取得または識別子を設定します。
            </summary>
        <value>
            識別子。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Vertex.Label" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string" Usage="Microsoft.Azure.Graphs.Elements.Vertex.Label" />
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
            ラベルを取得または設定します。
            </summary>
        <value>
            ラベル。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Vertex.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Sub Validate ()" />
      <MemberSignature Language="F#" Value="member this.Validate : unit -&gt; unit" Usage="vertex.Validate " />
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
            頂点には有効な id が必要です。 または、頂点は有効なラベルを持つ必要があります。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>