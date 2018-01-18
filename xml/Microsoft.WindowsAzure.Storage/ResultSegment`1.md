<Type Name="ResultSegment&lt;TElement&gt;" FullName="Microsoft.WindowsAzure.Storage.ResultSegment&lt;TElement&gt;">
  <TypeSignature Language="C#" Value="public class ResultSegment&lt;TElement&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResultSegment`1&lt;TElement&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.ResultSegment`1" />
  <TypeSignature Language="VB.NET" Value="Public Class ResultSegment(Of TElement)" />
  <TypeSignature Language="F#" Value="type ResultSegment&lt;'Element&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TElement" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TElement"><span data-ttu-id="d3139-101">結果セグメントとして返される要素の型。</span><span class="sxs-lookup"><span data-stu-id="d3139-101">The type of the element returned in the result segment.</span></span></typeparam>
    <summary>
            <span data-ttu-id="d3139-102">使用可能な結果セット全体から取得された結果セグメントを表します。</span><span class="sxs-lookup"><span data-stu-id="d3139-102">Represents a result segment that was retrieved from the total set of possible results.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.IContinuationToken ContinuationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.IContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.ResultSegment`1.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContinuationToken As IContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.WindowsAzure.Storage.IContinuationToken" Usage="Microsoft.WindowsAzure.Storage.ResultSegment&lt;'Element&gt;.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.IContinuationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3139-103">次の操作に後続の呼び出しで結果セットの取得に使用する継続トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="d3139-103">Gets a continuation token to use to retrieve the next set of results with a subsequent call to the operation.</span></span>
            </summary>
        <value><span data-ttu-id="d3139-104"><see cref="T:Microsoft.WindowsAzure.Storage.IContinuationToken" /> 型のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d3139-104">An object of type <see cref="T:Microsoft.WindowsAzure.Storage.IContinuationToken" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.List&lt;TElement&gt; Results { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.List`1&lt;!TElement&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.ResultSegment`1.Results" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Results As List(Of TElement)" />
      <MemberSignature Language="F#" Value="member this.Results : System.Collections.Generic.List&lt;'Element&gt;" Usage="Microsoft.WindowsAzure.Storage.ResultSegment&lt;'Element&gt;.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3139-105">結果の列挙可能なコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="d3139-105">Gets an enumerable collection of results.</span></span>
            </summary>
        <value><span data-ttu-id="d3139-106">型の結果の列挙可能なコレクション<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="d3139-106">An enumerable collection of results of type <c>TElement</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>