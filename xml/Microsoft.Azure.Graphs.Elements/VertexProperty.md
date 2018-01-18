<Type Name="VertexProperty" FullName="Microsoft.Azure.Graphs.Elements.VertexProperty">
  <TypeSignature Language="C#" Value="public sealed class VertexProperty" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit VertexProperty extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.Elements.VertexProperty" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class VertexProperty" />
  <TypeSignature Language="F#" Value="type VertexProperty = class" />
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
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Graphs.Elements.VertexPropertyConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c097d-101">頂点プロパティ データのストレージ コンテナーです。</span><span class="sxs-lookup"><span data-stu-id="c097d-101">Storage container for vertex property data.</span></span>
            <span data-ttu-id="c097d-102">GraphSON 形式から逆シリアル化をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="c097d-102">Supports deserialization from GraphSON format.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.Property&gt; GetProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Graphs.Elements.Property&gt; GetProperties() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.VertexProperty.GetProperties" />
      <MemberSignature Language="VB.NET" Value="Public Iterator Function GetProperties () As IEnumerable(Of Property)" />
      <MemberSignature Language="F#" Value="member this.GetProperties : unit -&gt; seq&lt;Microsoft.Azure.Graphs.Elements.Property&gt;" Usage="vertexProperty.GetProperties " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.IteratorStateMachine(typeof(Microsoft.Azure.Graphs.Elements.VertexProperty/&lt;GetProperties&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.Property&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Graphs.Elements.Property GetProperty (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Graphs.Elements.Property GetProperty(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.VertexProperty.GetProperty(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProperty (key As String) As Property" />
      <MemberSignature Language="F#" Value="member this.GetProperty : string -&gt; Microsoft.Azure.Graphs.Elements.Property" Usage="vertexProperty.GetProperty key" />
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
        <param name="key"></param>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public object Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.VertexProperty.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As Object" />
      <MemberSignature Language="F#" Value="member this.Id : obj" Usage="Microsoft.Azure.Graphs.Elements.VertexProperty.Id" />
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
            <span data-ttu-id="c097d-103">取得または識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="c097d-103">Gets or sets the identifier.</span></span>
            </summary>
        <value>
            <span data-ttu-id="c097d-104">識別子。</span><span class="sxs-lookup"><span data-stu-id="c097d-104">The identifier.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public string Key { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.VertexProperty.Key" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string" Usage="Microsoft.Azure.Graphs.Elements.VertexProperty.Key" />
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
            <span data-ttu-id="c097d-105">取得またはキーを設定します。</span><span class="sxs-lookup"><span data-stu-id="c097d-105">Gets or sets the key.</span></span>
            </summary>
        <value>
            <span data-ttu-id="c097d-106">キー。</span><span class="sxs-lookup"><span data-stu-id="c097d-106">The key.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.VertexProperty.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Sub Validate ()" />
      <MemberSignature Language="F#" Value="member this.Validate : unit -&gt; unit" Usage="vertexProperty.Validate " />
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
            <span data-ttu-id="c097d-107">このインスタンスを検証します。</span><span class="sxs-lookup"><span data-stu-id="c097d-107">Validates this instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="c097d-108">VertexProperty、有効なキーが必要です。</span><span class="sxs-lookup"><span data-stu-id="c097d-108">VertexProperty must have a valid Key.</span></span>
            <span data-ttu-id="c097d-109">または、VertexProperty では、null 値が必要ありません。</span><span class="sxs-lookup"><span data-stu-id="c097d-109">or VertexProperty must not have a null Value.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public object Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.VertexProperty.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As Object" />
      <MemberSignature Language="F#" Value="member this.Value : obj" Usage="Microsoft.Azure.Graphs.Elements.VertexProperty.Value" />
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
            <span data-ttu-id="c097d-110">取得または値を設定します。</span><span class="sxs-lookup"><span data-stu-id="c097d-110">Gets or sets the value.</span></span>
            </summary>
        <value>
            <span data-ttu-id="c097d-111">値。</span><span class="sxs-lookup"><span data-stu-id="c097d-111">The value.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>