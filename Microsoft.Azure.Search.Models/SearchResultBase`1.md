<Type Name="SearchResultBase&lt;T&gt;" FullName="Microsoft.Azure.Search.Models.SearchResultBase&lt;T&gt;">
  <TypeSignature Language="C#" Value="public abstract class SearchResultBase&lt;T&gt; where T : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit SearchResultBase`1&lt;class T&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SearchResultBase`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class SearchResultBase(Of T)" />
  <TypeSignature Language="F#" Value="type SearchResultBase&lt;'T (requires 'T : null)&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">
            <span data-ttu-id="94535-101">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="94535-101">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="94535-102">この型のインスタンスは、インデックス内のドキュメントとして格納できます。</span><span class="sxs-lookup"><span data-stu-id="94535-102">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
    <summary>
            <span data-ttu-id="94535-103">ドキュメントを含む結果の抽象基本クラスは、検索クエリにより見つけし、関連メタデータ。</span><span class="sxs-lookup"><span data-stu-id="94535-103">Abstract base class for a result containing a document found by a search query, plus associated metadata.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected SearchResultBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SearchResultBase`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="94535-104">SearchResultBase クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="94535-104">Initializes a new instance of the SearchResultBase class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Document">
      <MemberSignature Language="C#" Value="public T Document { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Document" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchResultBase`1.Document" />
      <MemberSignature Language="VB.NET" Value="Public Property Document As T" />
      <MemberSignature Language="F#" Value="member this.Document : 'T with get, set" Usage="Microsoft.Azure.Search.Models.SearchResultBase&lt;'T (requires 'T : null)&gt;.Document" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94535-105">検索クエリによって検出されたドキュメントを取得します。</span><span class="sxs-lookup"><span data-stu-id="94535-105">Gets the document found by the search query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Highlights">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.HitHighlights Highlights { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.HitHighlights Highlights" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchResultBase`1.Highlights" />
      <MemberSignature Language="VB.NET" Value="Public Property Highlights As HitHighlights" />
      <MemberSignature Language="F#" Value="member this.Highlights : Microsoft.Azure.Search.Models.HitHighlights with get, set" Usage="Microsoft.Azure.Search.Models.SearchResultBase&lt;'T (requires 'T : null)&gt;.Highlights" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.HitHighlights</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94535-106">一致する語句を示す、ドキュメントからテキストのスニペットを取得します。ヒット ハイライト機能が有効になっていないクエリの場合は null です。</span><span class="sxs-lookup"><span data-stu-id="94535-106">Gets text snippets from the document that indicate the matching search terms; null if hit highlighting was not enabled for the query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Score">
      <MemberSignature Language="C#" Value="public double Score { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Score" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchResultBase`1.Score" />
      <MemberSignature Language="VB.NET" Value="Public Property Score As Double" />
      <MemberSignature Language="F#" Value="member this.Score : double with get, set" Usage="Microsoft.Azure.Search.Models.SearchResultBase&lt;'T (requires 'T : null)&gt;.Score" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94535-107">クエリによって返されるその他のドキュメントと比較されたドキュメントの関連性スコアを取得します。</span><span class="sxs-lookup"><span data-stu-id="94535-107">Gets the relevance score of the document compared to other documents returned by the query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>