<Type Name="FunctionCallNode" FullName="Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode">
  <TypeSignature Language="C#" Value="public sealed class FunctionCallNode : Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FunctionCallNode extends Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FunctionCallNode&#xA;Inherits QueryNode" />
  <TypeSignature Language="F#" Value="type FunctionCallNode = class&#xA;    inherit QueryNode" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.MobileServices.Query.QueryNode</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a3823-101">関数呼び出しを表すノードです。</span><span class="sxs-lookup"><span data-stu-id="a3823-101">Node representing a function call.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FunctionCallNode (string name, System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.MobileServices.Query.QueryNode&gt; arguments);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.MobileServices.Query.QueryNode&gt; arguments) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode.#ctor(System.String,System.Collections.Generic.IList{Microsoft.WindowsAzure.MobileServices.Query.QueryNode})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, arguments As IList(Of QueryNode))" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode : string * System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.MobileServices.Query.QueryNode&gt; -&gt; Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode" Usage="new Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode (name, arguments)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="arguments" Type="System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.MobileServices.Query.QueryNode&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a3823-102">呼び出す関数の名前。</span><span class="sxs-lookup"><span data-stu-id="a3823-102">The name of the function to call.</span></span></param>
        <param name="arguments"><span data-ttu-id="a3823-103">この関数呼び出しに対する引数のリスト。</span><span class="sxs-lookup"><span data-stu-id="a3823-103">The list of arguments to this function call.</span></span></param>
        <summary>
            <span data-ttu-id="a3823-104">インスタンスを初期化します。<see cref="T:Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode" /></span><span class="sxs-lookup"><span data-stu-id="a3823-104">Initializes an instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Accept&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T Accept&lt;T&gt; (Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;T&gt; visitor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T Accept&lt;T&gt;(class Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1&lt;!!T&gt; visitor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode.Accept``1(Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Accept(Of T) (visitor As QueryNodeVisitor(Of T)) As T" />
      <MemberSignature Language="F#" Value="override this.Accept : Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;'T&gt; -&gt; 'T" Usage="functionCallNode.Accept visitor" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="visitor" Type="Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="a3823-105">ビジターがこのトークンにアクセスした後に戻る型。</span><span class="sxs-lookup"><span data-stu-id="a3823-105">Type that the visitor will return after visiting this token.</span></span></typeparam>
        <param name="visitor"><span data-ttu-id="a3823-106">ビジター インターフェイスの実装。</span><span class="sxs-lookup"><span data-stu-id="a3823-106">An implementation of the visitor interface.</span></span></param>
        <summary>
            <span data-ttu-id="a3823-107"><see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1" /> ツリーをたどる <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNode" /> を受け入れます。</span><span class="sxs-lookup"><span data-stu-id="a3823-107">Accept a <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1" /> to walk a tree of <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />s.</span></span>
            </summary>
        <returns><span data-ttu-id="a3823-108">ビジターのパラメーターの型によって型が決まるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a3823-108">An object whose type is determined by the type parameter of the visitor.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Arguments">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.MobileServices.Query.QueryNode&gt; Arguments { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.MobileServices.Query.QueryNode&gt; Arguments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode.Arguments" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Arguments As IList(Of QueryNode)" />
      <MemberSignature Language="F#" Value="member this.Arguments : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.MobileServices.Query.QueryNode&gt;" Usage="Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode.Arguments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.MobileServices.Query.QueryNode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a3823-109">この関数呼び出しに対する引数のリストを取得します。</span><span class="sxs-lookup"><span data-stu-id="a3823-109">Gets the list of arguments to this function call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public override Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Kind As QueryNodeKind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind" Usage="Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a3823-110">クエリ ノードの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="a3823-110">Gets the kind of the query node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a3823-111">呼び出す関数の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="a3823-111">Gets the name of the function to call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>