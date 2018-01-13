<Type Name="IndexActionBase&lt;T&gt;" FullName="Microsoft.Azure.Search.Models.IndexActionBase&lt;T&gt;">
  <TypeSignature Language="C#" Value="public abstract class IndexActionBase&lt;T&gt; where T : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit IndexActionBase`1&lt;class T&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexActionBase`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class IndexActionBase(Of T)" />
  <TypeSignature Language="F#" Value="type IndexActionBase&lt;'T (requires 'T : null)&gt; = class" />
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
            <span data-ttu-id="4001f-101">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="4001f-101">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="4001f-102">この型のインスタンスは、インデックス内のドキュメントとして格納できます。</span><span class="sxs-lookup"><span data-stu-id="4001f-102">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
    <summary>
            <span data-ttu-id="4001f-103">ドキュメントを操作するインデックス アクションの抽象基本クラス。</span><span class="sxs-lookup"><span data-stu-id="4001f-103">Abstract base class for index actions that operate on a document.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected IndexActionBase (Microsoft.Azure.Search.Models.IndexActionType actionType, T document);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Search.Models.IndexActionType actionType, !T document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexActionBase`1.#ctor(Microsoft.Azure.Search.Models.IndexActionType,`0)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (actionType As IndexActionType, document As T)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexActionBase&lt;'T (requires 'T : null)&gt; : Microsoft.Azure.Search.Models.IndexActionType * 'T -&gt; Microsoft.Azure.Search.Models.IndexActionBase&lt;'T (requires 'T : null)&gt;" Usage="new Microsoft.Azure.Search.Models.IndexActionBase&lt;'T (requires 'T : null)&gt; (actionType, document)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actionType" Type="Microsoft.Azure.Search.Models.IndexActionType" />
        <Parameter Name="document" Type="T" />
      </Parameters>
      <Docs>
        <param name="actionType"><span data-ttu-id="4001f-104">ドキュメントに対して実行するアクションの種類。</span><span class="sxs-lookup"><span data-stu-id="4001f-104">The type of action to perform on the document.</span></span></param>
        <param name="document"><span data-ttu-id="4001f-105">アクションを実行するドキュメントです。</span><span class="sxs-lookup"><span data-stu-id="4001f-105">The document on which the action will be performed.</span></span></param>
        <summary>
            <span data-ttu-id="4001f-106">指定されたアクションの種類は使用して IndexActionBase クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4001f-106">Initializes a new instance of the IndexActionBase class with the given action type.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.IndexActionType ActionType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Search.Models.IndexActionType ActionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexActionBase`1.ActionType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActionType As IndexActionType" />
      <MemberSignature Language="F#" Value="member this.ActionType : Microsoft.Azure.Search.Models.IndexActionType" Usage="Microsoft.Azure.Search.Models.IndexActionBase&lt;'T (requires 'T : null)&gt;.ActionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexActionType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4001f-107">インデックスのバッチ内のドキュメントに対して実行するアクションを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="4001f-107">Gets a value indicating the action to perform on a document in an indexing batch.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Document">
      <MemberSignature Language="C#" Value="public T Document { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Document" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexActionBase`1.Document" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Document As T" />
      <MemberSignature Language="F#" Value="member this.Document : 'T" Usage="Microsoft.Azure.Search.Models.IndexActionBase&lt;'T (requires 'T : null)&gt;.Document" />
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
            <span data-ttu-id="4001f-108">ドキュメントを取得しますが、アクションが実行されます。キー以外のフィールドには、削除操作は無視されます。</span><span class="sxs-lookup"><span data-stu-id="4001f-108">Gets the document on which the action will be performed; Fields other than the key are ignored for delete actions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>