<Type Name="FacetResult" FullName="Microsoft.Azure.Search.Models.FacetResult">
  <TypeSignature Language="C#" Value="public class FacetResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FacetResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.FacetResult" />
  <TypeSignature Language="VB.NET" Value="Public Class FacetResult" />
  <TypeSignature Language="F#" Value="type FacetResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="73727-101">特定の範囲内か、特定の値または間隔を持つフィールドを持つドキュメントの数を報告するファセット クエリ結果の単一バケット。</span><span class="sxs-lookup"><span data-stu-id="73727-101">A single bucket of a facet query result that reports the number of documents with a field falling within a particular range or having a particular value or interval.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FacetResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FacetResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="73727-102">Facet クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="73727-102">Initializes a new instance of the Facet class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AsRangeFacetResult&lt;T&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.RangeFacetResult&lt;T&gt; AsRangeFacetResult&lt;T&gt; () where T : struct;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Search.Models.RangeFacetResult`1&lt;!!T&gt; AsRangeFacetResult&lt;struct .ctor (class System.ValueType) T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FacetResult.AsRangeFacetResult``1" />
      <MemberSignature Language="VB.NET" Value="Public Function AsRangeFacetResult(Of T As Structure) () As RangeFacetResult(Of T)" />
      <MemberSignature Language="F#" Value="member this.AsRangeFacetResult : unit -&gt; Microsoft.Azure.Search.Models.RangeFacetResult&lt;'T (requires 'T : struct)&gt; (requires 'T : struct)" Usage="facetResult.AsRangeFacetResult " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RangeFacetResult&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <ParameterAttribute>NotNullableValueTypeConstraint</ParameterAttribute>
            <BaseTypeName>System.ValueType</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="73727-103">ファセットが適用されているフィールドの種類に対応する型。</span><span class="sxs-lookup"><span data-stu-id="73727-103">A type that matches the type of the field to which the facet was applied.</span></span> <span data-ttu-id="73727-104">有効な型は<c cref="T:System.DateTimeOffset">DateTimeOffset</c>、<c cref="T:System.Double">二重</c>、および<c cref="T:System.Int64">Int64</c> (c# の long 型)。</span><span class="sxs-lookup"><span data-stu-id="73727-104">Valid types include <c cref="T:System.DateTimeOffset">DateTimeOffset</c>, <c cref="T:System.Double">Double</c>, and <c cref="T:System.Int64">Int64</c> (long in C#).</span></span>
            </typeparam>
        <summary>
            <span data-ttu-id="73727-105">指定された型の範囲ファセットにファセットを変換しようとしています。</span><span class="sxs-lookup"><span data-stu-id="73727-105">Attempts to convert the facet to a range facet of the given type.</span></span>
            </summary>
        <returns><span data-ttu-id="73727-106">新しい厳密に型指定された範囲ファセット インスタンス。</span><span class="sxs-lookup"><span data-stu-id="73727-106">A new strongly-typed range facet instance.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidCastException"><span data-ttu-id="73727-107">このインスタンスは、指定された型の範囲ファセットではありません。</span><span class="sxs-lookup"><span data-stu-id="73727-107">This instance is not a range facet of the given type.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AsValueFacetResult&lt;T&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.ValueFacetResult&lt;T&gt; AsValueFacetResult&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Search.Models.ValueFacetResult`1&lt;!!T&gt; AsValueFacetResult&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FacetResult.AsValueFacetResult``1" />
      <MemberSignature Language="VB.NET" Value="Public Function AsValueFacetResult(Of T) () As ValueFacetResult(Of T)" />
      <MemberSignature Language="F#" Value="member this.AsValueFacetResult : unit -&gt; Microsoft.Azure.Search.Models.ValueFacetResult&lt;'T&gt;" Usage="facetResult.AsValueFacetResult " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.ValueFacetResult&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="73727-108">ファセットが適用されているフィールドの種類に対応する型。</span><span class="sxs-lookup"><span data-stu-id="73727-108">A type that matches the type of the field to which the facet was applied.</span></span>
            </typeparam>
        <summary>
            <span data-ttu-id="73727-109">指定された型の値ファセットにファセットを変換しようとしています。</span><span class="sxs-lookup"><span data-stu-id="73727-109">Attempts to convert the facet to a value facet of the given type.</span></span>
            </summary>
        <returns><span data-ttu-id="73727-110">新しい値の厳密に型指定されたファセット インスタンス。</span><span class="sxs-lookup"><span data-stu-id="73727-110">A new strongly-typed value facet instance.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidCastException"><span data-ttu-id="73727-111">このインスタンスは、指定された型の値ファセットではありません。</span><span class="sxs-lookup"><span data-stu-id="73727-111">This instance is not a value facet of the given type.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FacetResult.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Search.Models.FacetResult.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73727-112">このファセットにより説明されるバケット内のドキュメントのおおよその数を取得します。</span><span class="sxs-lookup"><span data-stu-id="73727-112">Gets the approximate count of documents falling within the bucket described by this facet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="From">
      <MemberSignature Language="C#" Value="public object From { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object From" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FacetResult.From" />
      <MemberSignature Language="VB.NET" Value="Public Property From As Object" />
      <MemberSignature Language="F#" Value="member this.From : obj with get, set" Usage="Microsoft.Azure.Search.Models.FacetResult.From" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("from")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73727-113">ファセットの範囲、または (つまり--最初のバケット) の下限がないことを示すために null の下限を示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="73727-113">Gets a value indicating the inclusive lower bound of the facet's range, or null to indicate that there is no lower bound (i.e. -- for the first bucket).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public object To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FacetResult.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As Object" />
      <MemberSignature Language="F#" Value="member this.To : obj with get, set" Usage="Microsoft.Azure.Search.Models.FacetResult.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("to")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73727-114">ファセットの範囲、または (つまり--最後のバケット) の上限がないことを示すために null の上限を示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="73727-114">Gets a value indicating the exclusive upper bound of the facet's range, or null to indicate that there is no upper bound (i.e. -- for the last bucket).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.FacetType Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Search.Models.FacetType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FacetResult.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As FacetType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Search.Models.FacetType" Usage="Microsoft.Azure.Search.Models.FacetResult.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.FacetType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73727-115">このファセットの種類を示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="73727-115">Gets a value indicating the type of this facet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public object Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FacetResult.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As Object" />
      <MemberSignature Language="F#" Value="member this.Value : obj with get, set" Usage="Microsoft.Azure.Search.Models.FacetResult.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73727-116">間隔ファセットである場合は、ファセット、または下限の値を取得します。</span><span class="sxs-lookup"><span data-stu-id="73727-116">Gets the value of the facet, or the inclusive lower bound if it's an interval facet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>