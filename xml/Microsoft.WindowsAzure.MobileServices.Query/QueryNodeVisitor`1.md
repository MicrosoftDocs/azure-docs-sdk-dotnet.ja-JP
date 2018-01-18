<Type Name="QueryNodeVisitor&lt;T&gt;" FullName="Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;T&gt;">
  <TypeSignature Language="C#" Value="public abstract class QueryNodeVisitor&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit QueryNodeVisitor`1&lt;T&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class QueryNodeVisitor(Of T)" />
  <TypeSignature Language="F#" Value="type QueryNodeVisitor&lt;'T&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T"><span data-ttu-id="a8e3f-101">ビジターが生成するジェネリック型。</span><span class="sxs-lookup"><span data-stu-id="a8e3f-101">Generic type produced by the visitor.</span></span></typeparam>
    <summary>
            <span data-ttu-id="a8e3f-102">QueryNode ツリーをウォークの訪問者のインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="a8e3f-102">Visitor interface for walking the QueryNode Tree.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected QueryNodeVisitor ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Visit">
      <MemberSignature Language="C#" Value="public virtual T Visit (Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode nodeIn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Visit(class Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode nodeIn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1.Visit(Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Visit (nodeIn As BinaryOperatorNode) As T" />
      <MemberSignature Language="F#" Value="abstract member Visit : Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode -&gt; 'T&#xA;override this.Visit : Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode -&gt; 'T" Usage="queryNodeVisitor.Visit nodeIn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeIn" Type="Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode" />
      </Parameters>
      <Docs>
        <param name="nodeIn"><span data-ttu-id="a8e3f-103">アクセスするノード</span><span class="sxs-lookup"><span data-stu-id="a8e3f-103">the node to visit</span></span></param>
        <summary>
            <span data-ttu-id="a8e3f-104">BinaryOperatorNode にアクセスします</span><span class="sxs-lookup"><span data-stu-id="a8e3f-104">Visit a BinaryOperatorNode</span></span>
            </summary>
        <returns><span data-ttu-id="a8e3f-105">実装者が定義します</span><span class="sxs-lookup"><span data-stu-id="a8e3f-105">Defined by the implementer</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Visit">
      <MemberSignature Language="C#" Value="public virtual T Visit (Microsoft.WindowsAzure.MobileServices.Query.ConstantNode nodeIn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Visit(class Microsoft.WindowsAzure.MobileServices.Query.ConstantNode nodeIn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1.Visit(Microsoft.WindowsAzure.MobileServices.Query.ConstantNode)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Visit (nodeIn As ConstantNode) As T" />
      <MemberSignature Language="F#" Value="abstract member Visit : Microsoft.WindowsAzure.MobileServices.Query.ConstantNode -&gt; 'T&#xA;override this.Visit : Microsoft.WindowsAzure.MobileServices.Query.ConstantNode -&gt; 'T" Usage="queryNodeVisitor.Visit nodeIn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeIn" Type="Microsoft.WindowsAzure.MobileServices.Query.ConstantNode" />
      </Parameters>
      <Docs>
        <param name="nodeIn"><span data-ttu-id="a8e3f-106">アクセスするノード</span><span class="sxs-lookup"><span data-stu-id="a8e3f-106">the node to visit</span></span></param>
        <summary>
            <span data-ttu-id="a8e3f-107">ConstantNode にアクセスします</span><span class="sxs-lookup"><span data-stu-id="a8e3f-107">Visit a ConstantNode</span></span>
            </summary>
        <returns><span data-ttu-id="a8e3f-108">実装者が定義します</span><span class="sxs-lookup"><span data-stu-id="a8e3f-108">Defined by the implementer</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Visit">
      <MemberSignature Language="C#" Value="public virtual T Visit (Microsoft.WindowsAzure.MobileServices.Query.ConvertNode nodeIn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Visit(class Microsoft.WindowsAzure.MobileServices.Query.ConvertNode nodeIn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1.Visit(Microsoft.WindowsAzure.MobileServices.Query.ConvertNode)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Visit (nodeIn As ConvertNode) As T" />
      <MemberSignature Language="F#" Value="abstract member Visit : Microsoft.WindowsAzure.MobileServices.Query.ConvertNode -&gt; 'T&#xA;override this.Visit : Microsoft.WindowsAzure.MobileServices.Query.ConvertNode -&gt; 'T" Usage="queryNodeVisitor.Visit nodeIn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeIn" Type="Microsoft.WindowsAzure.MobileServices.Query.ConvertNode" />
      </Parameters>
      <Docs>
        <param name="nodeIn"><span data-ttu-id="a8e3f-109">アクセスするノード</span><span class="sxs-lookup"><span data-stu-id="a8e3f-109">the node to visit</span></span></param>
        <summary>
            <span data-ttu-id="a8e3f-110">ConvertNode にアクセスします</span><span class="sxs-lookup"><span data-stu-id="a8e3f-110">Visit a ConvertNode</span></span>
            </summary>
        <returns><span data-ttu-id="a8e3f-111">実装者が定義します</span><span class="sxs-lookup"><span data-stu-id="a8e3f-111">Defined by the implementer</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Visit">
      <MemberSignature Language="C#" Value="public virtual T Visit (Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode nodeIn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Visit(class Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode nodeIn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1.Visit(Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Visit (nodeIn As FunctionCallNode) As T" />
      <MemberSignature Language="F#" Value="abstract member Visit : Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode -&gt; 'T&#xA;override this.Visit : Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode -&gt; 'T" Usage="queryNodeVisitor.Visit nodeIn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeIn" Type="Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode" />
      </Parameters>
      <Docs>
        <param name="nodeIn"><span data-ttu-id="a8e3f-112">アクセスするノード</span><span class="sxs-lookup"><span data-stu-id="a8e3f-112">the node to visit</span></span></param>
        <summary>
            <span data-ttu-id="a8e3f-113">ODataMethodCallNode を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a8e3f-113">Visit an ODataMethodCallNode</span></span>
            </summary>
        <returns><span data-ttu-id="a8e3f-114">実装者が定義します</span><span class="sxs-lookup"><span data-stu-id="a8e3f-114">Defined by the implementer</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Visit">
      <MemberSignature Language="C#" Value="public virtual T Visit (Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode nodeIn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Visit(class Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode nodeIn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1.Visit(Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Visit (nodeIn As MemberAccessNode) As T" />
      <MemberSignature Language="F#" Value="abstract member Visit : Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode -&gt; 'T&#xA;override this.Visit : Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode -&gt; 'T" Usage="queryNodeVisitor.Visit nodeIn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeIn" Type="Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode" />
      </Parameters>
      <Docs>
        <param name="nodeIn"><span data-ttu-id="a8e3f-115">アクセスするノード</span><span class="sxs-lookup"><span data-stu-id="a8e3f-115">the node to visit</span></span></param>
        <summary>
            <span data-ttu-id="a8e3f-116">MemberAccessNode を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a8e3f-116">Visit a MemberAccessNode</span></span>
            </summary>
        <returns><span data-ttu-id="a8e3f-117">実装者が定義します</span><span class="sxs-lookup"><span data-stu-id="a8e3f-117">Defined by the implementer</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Visit">
      <MemberSignature Language="C#" Value="public virtual T Visit (Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode nodeIn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Visit(class Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode nodeIn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1.Visit(Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Visit (nodeIn As UnaryOperatorNode) As T" />
      <MemberSignature Language="F#" Value="abstract member Visit : Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode -&gt; 'T&#xA;override this.Visit : Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode -&gt; 'T" Usage="queryNodeVisitor.Visit nodeIn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeIn" Type="Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode" />
      </Parameters>
      <Docs>
        <param name="nodeIn"><span data-ttu-id="a8e3f-118">アクセスするノード</span><span class="sxs-lookup"><span data-stu-id="a8e3f-118">the node to visit</span></span></param>
        <summary>
            <span data-ttu-id="a8e3f-119">UnaryOperatorNode にアクセスします</span><span class="sxs-lookup"><span data-stu-id="a8e3f-119">Visit a UnaryOperatorNode</span></span>
            </summary>
        <returns><span data-ttu-id="a8e3f-120">実装者が定義します</span><span class="sxs-lookup"><span data-stu-id="a8e3f-120">Defined by the implementer</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>