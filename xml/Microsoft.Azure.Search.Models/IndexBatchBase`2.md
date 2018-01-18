<Type Name="IndexBatchBase&lt;TAction,TDoc&gt;" FullName="Microsoft.Azure.Search.Models.IndexBatchBase&lt;TAction,TDoc&gt;">
  <TypeSignature Language="C#" Value="public abstract class IndexBatchBase&lt;TAction,TDoc&gt; where TAction : IndexActionBase&lt;TDoc&gt; where TDoc : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit IndexBatchBase`2&lt;(class Microsoft.Azure.Search.Models.IndexActionBase`1&lt;!TDoc&gt;) TAction, class TDoc&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexBatchBase`2" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class IndexBatchBase(Of TAction, TDoc)" />
  <TypeSignature Language="F#" Value="type IndexBatchBase&lt;'Action, 'Doc (requires 'Action :&gt; IndexActionBase&lt;'Doc&gt; and 'Doc : null)&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TAction">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.Search.Models.IndexActionBase&lt;TDoc&gt;</BaseTypeName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="TDoc">
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
    <typeparam name="TAction">
            <span data-ttu-id="86952-101">バッチに含まれているアクションの種類。</span><span class="sxs-lookup"><span data-stu-id="86952-101">The type of action to be contained in the batch.</span></span> <span data-ttu-id="86952-102">IndexActionBase から派生しなければなりません。</span><span class="sxs-lookup"><span data-stu-id="86952-102">Must be derived from IndexActionBase.</span></span>
            </typeparam>
    <typeparam name="TDoc">
            <span data-ttu-id="86952-103">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="86952-103">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="86952-104">この型のインスタンスは、インデックス内のドキュメントとして格納できます。</span><span class="sxs-lookup"><span data-stu-id="86952-104">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
    <summary>
            <span data-ttu-id="86952-105">アップロードのバッチの抽象基本クラスは、マージ、や、Azure Search インデックスに送信するアクションを削除します。</span><span class="sxs-lookup"><span data-stu-id="86952-105">Abstract base class for batches of upload, merge, and/or delete actions to send to the Azure Search index.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected IndexBatchBase (System.Collections.Generic.IEnumerable&lt;TAction&gt; actions);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;!TAction&gt; actions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexBatchBase`2.#ctor(System.Collections.Generic.IEnumerable{`0})" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (actions As IEnumerable(Of TAction))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexBatchBase&lt;'Action, 'Doc (requires 'Action :&gt; Microsoft.Azure.Search.Models.IndexActionBase&lt;'Doc&gt; and 'Doc : null)&gt; : seq&lt;'Action (requires 'Action :&gt; Microsoft.Azure.Search.Models.IndexActionBase&lt;'Doc&gt;)&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatchBase&lt;'Action, 'Doc (requires 'Action :&gt; Microsoft.Azure.Search.Models.IndexActionBase&lt;'Doc&gt; and 'Doc : null)&gt;" Usage="new Microsoft.Azure.Search.Models.IndexBatchBase&lt;'Action, 'Doc (requires 'Action :&gt; Microsoft.Azure.Search.Models.IndexActionBase&lt;'Doc&gt; and 'Doc : null)&gt; actions" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actions" Type="System.Collections.Generic.IEnumerable&lt;TAction&gt;" />
      </Parameters>
      <Docs>
        <param name="actions"><span data-ttu-id="86952-106">バッチに含めるインデックス アクションです。</span><span class="sxs-lookup"><span data-stu-id="86952-106">The index actions to include in the batch.</span></span></param>
        <summary>
            <span data-ttu-id="86952-107">IndexBatchBase クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="86952-107">Initializes a new instance of the IndexBatchBase class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Actions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;TAction&gt; Actions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;!TAction&gt; Actions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexBatchBase`2.Actions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Actions As IEnumerable(Of TAction)" />
      <MemberSignature Language="F#" Value="member this.Actions : seq&lt;'Action (requires 'Action :&gt; Microsoft.Azure.Search.Models.IndexActionBase&lt;'Doc&gt;)&gt;" Usage="Microsoft.Azure.Search.Models.IndexBatchBase&lt;'Action, 'Doc (requires 'Action :&gt; Microsoft.Azure.Search.Models.IndexActionBase&lt;'Doc&gt; and 'Doc : null)&gt;.Actions" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86952-108">バッチ内の順序でアクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="86952-108">Gets the sequence of actions in the batch.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>