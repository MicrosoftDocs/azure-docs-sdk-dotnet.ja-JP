<Type Name="AccessCondition" FullName="Microsoft.Azure.Search.Models.AccessCondition">
  <TypeSignature Language="C#" Value="public class AccessCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AccessCondition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.AccessCondition" />
  <TypeSignature Language="VB.NET" Value="Public Class AccessCondition" />
  <TypeSignature Language="F#" Value="type AccessCondition = class" />
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
            <span data-ttu-id="54688-101">一連の操作に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="54688-101">Additional parameters for a set of operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.#ctor" />
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
            <span data-ttu-id="54688-102">AccessCondition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="54688-102">Initializes a new instance of the AccessCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessCondition (string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional ifMatch As String = null, Optional ifNoneMatch As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.AccessCondition : string * string -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="new Microsoft.Azure.Search.Models.AccessCondition (ifMatch, ifNoneMatch)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ifMatch"><span data-ttu-id="54688-103">If-match 条件を定義します。</span><span class="sxs-lookup"><span data-stu-id="54688-103">Defines the If-Match condition.</span></span> <span data-ttu-id="54688-104">操作は、サーバー上の ETag がこの値に一致する場合にのみ実行されます。</span><span class="sxs-lookup"><span data-stu-id="54688-104">The operation will be performed only if the ETag on the server matches this value.</span></span></param>
        <param name="ifNoneMatch"><span data-ttu-id="54688-105">None-If-match 条件を定義します。</span><span class="sxs-lookup"><span data-stu-id="54688-105">Defines the If-None-Match condition.</span></span> <span data-ttu-id="54688-106">サーバーの ETag が、この値と一致しない場合にのみ、操作が実行されます。</span><span class="sxs-lookup"><span data-stu-id="54688-106">The operation will be performed only if the ETag on the server does not match this value.</span></span></param>
        <summary>
            <span data-ttu-id="54688-107">AccessCondition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="54688-107">Initializes a new instance of the AccessCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateEmptyCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition GenerateEmptyCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition GenerateEmptyCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.GenerateEmptyCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateEmptyCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateEmptyCondition : unit -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.GenerateEmptyCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="54688-108">空のアクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="54688-108">Constructs an empty access condition.</span></span>
            </summary>
        <returns><span data-ttu-id="54688-109">空の <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="54688-109">An empty <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfExistsCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition GenerateIfExistsCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition GenerateIfExistsCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.GenerateIfExistsCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfExistsCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfExistsCondition : unit -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.GenerateIfExistsCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="54688-110">リソースが存在する場合にのみ操作が実行されるように、アクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="54688-110">Constructs an access condition such that an operation will be performed only if the resource exists.</span></span>
            </summary>
        <returns><span data-ttu-id="54688-111"><see cref="T:Microsoft.Azure.Search.Models.AccessCondition" />リソースが存在する条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="54688-111">An <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> object that represents a condition where a resource exists.</span></span></returns>
        <remarks><span data-ttu-id="54688-112">このアクセス条件を設定を含める HTTP 要求を変更<i>If-match</i>条件付きのヘッダーに設定されて<c>"\*"</c>です。</span><span class="sxs-lookup"><span data-stu-id="54688-112">Setting this access condition modifies the request to include the HTTP <i>If-Match</i> conditional header set to <c>"\*"</c>.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfMatchCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition GenerateIfMatchCondition (string eTag);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition GenerateIfMatchCondition(string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.GenerateIfMatchCondition(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfMatchCondition (eTag As String) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfMatchCondition : string -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.GenerateIfMatchCondition eTag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eTag"><span data-ttu-id="54688-113">リソースの ETag と照合する ETag 値です。</span><span class="sxs-lookup"><span data-stu-id="54688-113">The ETag value to check against the resource's ETag.</span></span></param>
        <summary>
            <span data-ttu-id="54688-114">リソースの現在の ETag 値が指定された ETag 値と一致する場合にのみ操作が実行されるように、アクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="54688-114">Constructs an access condition such that an operation will be performed only if the resource's current ETag value matches the specified ETag value.</span></span>
            </summary>
        <returns><span data-ttu-id="54688-115"><see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> If-match 条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="54688-115">An <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> object that represents the If-Match condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfNoneMatchCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition GenerateIfNoneMatchCondition (string eTag);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition GenerateIfNoneMatchCondition(string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.GenerateIfNoneMatchCondition(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfNoneMatchCondition (eTag As String) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfNoneMatchCondition : string -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.GenerateIfNoneMatchCondition eTag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eTag"><span data-ttu-id="54688-116">リソースの ETag と照合する ETag 値です。</span><span class="sxs-lookup"><span data-stu-id="54688-116">The ETag value to check against the resource's ETag.</span></span></param>
        <summary>
            <span data-ttu-id="54688-117">リソースの現在の ETag 値が指定された ETag 値に一致しない場合にのみ操作が実行されるように、アクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="54688-117">Constructs an access condition such that an operation will be performed only if the resource's current ETag value does not match the specified ETag value.</span></span>
            </summary>
        <returns><span data-ttu-id="54688-118"><see cref="T:Microsoft.Azure.Search.Models.AccessCondition" />なし-If-match 条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="54688-118">An <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> object that represents the If-None-Match condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfNotExistsCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition GenerateIfNotExistsCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition GenerateIfNotExistsCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.GenerateIfNotExistsCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfNotExistsCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfNotExistsCondition : unit -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.GenerateIfNotExistsCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="54688-119">リソースが存在しない場合にのみ操作が実行されるように、アクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="54688-119">Constructs an access condition such that an operation will be performed only if the resource does not exist.</span></span>
            </summary>
        <returns><span data-ttu-id="54688-120"><see cref="T:Microsoft.Azure.Search.Models.AccessCondition" />リソースが存在しない場合、条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="54688-120">An <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> object that represents a condition where a resource does not exist.</span></span></returns>
        <remarks><span data-ttu-id="54688-121">このアクセス条件を設定を含める HTTP 要求を変更<i>なし-If-match</i>条件付きのヘッダーに設定されて<c>"\*"</c>です。</span><span class="sxs-lookup"><span data-stu-id="54688-121">Setting this access condition modifies the request to include the HTTP <i>If-None-Match</i> conditional header set to <c>"\*"</c>.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="IfMatch">
      <MemberSignature Language="C#" Value="public string IfMatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IfMatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AccessCondition.IfMatch" />
      <MemberSignature Language="VB.NET" Value="Public Property IfMatch As String" />
      <MemberSignature Language="F#" Value="member this.IfMatch : string with get, set" Usage="Microsoft.Azure.Search.Models.AccessCondition.IfMatch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="54688-122">取得または設定は、If-match 条件を定義します。</span><span class="sxs-lookup"><span data-stu-id="54688-122">Gets or sets defines the If-Match condition.</span></span> <span data-ttu-id="54688-123">操作は、サーバー上の ETag がこの値に一致する場合にのみ実行されます。</span><span class="sxs-lookup"><span data-stu-id="54688-123">The operation will be performed only if the ETag on the server matches this value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfNoneMatch">
      <MemberSignature Language="C#" Value="public string IfNoneMatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IfNoneMatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AccessCondition.IfNoneMatch" />
      <MemberSignature Language="VB.NET" Value="Public Property IfNoneMatch As String" />
      <MemberSignature Language="F#" Value="member this.IfNoneMatch : string with get, set" Usage="Microsoft.Azure.Search.Models.AccessCondition.IfNoneMatch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="54688-124">取得または設定は、[なし]-If-match 条件を定義します。</span><span class="sxs-lookup"><span data-stu-id="54688-124">Gets or sets defines the If-None-Match condition.</span></span> <span data-ttu-id="54688-125">サーバーの ETag が、この値と一致しない場合にのみ、操作が実行されます。</span><span class="sxs-lookup"><span data-stu-id="54688-125">The operation will be performed only if the ETag on the server does not match this value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfNotChanged">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition IfNotChanged (Microsoft.Azure.Search.Models.IResourceWithETag resource);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition IfNotChanged(class Microsoft.Azure.Search.Models.IResourceWithETag resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.IfNotChanged(Microsoft.Azure.Search.Models.IResourceWithETag)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IfNotChanged (resource As IResourceWithETag) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member IfNotChanged : Microsoft.Azure.Search.Models.IResourceWithETag -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.IfNotChanged resource" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="Microsoft.Azure.Search.Models.IResourceWithETag" />
      </Parameters>
      <Docs>
        <param name="resource"><span data-ttu-id="54688-126">使用したリソース、リソースの ETag と照合する ETag 値です。</span><span class="sxs-lookup"><span data-stu-id="54688-126">A resource with an ETag value to check against the resource's ETag.</span></span></param>
        <summary>
            <span data-ttu-id="54688-127">リソースの現在の ETag 値が指定されたリソースの ETag 値と一致する場合にのみ操作が実行されるように、アクセス条件を構築します。</span><span class="sxs-lookup"><span data-stu-id="54688-127">Constructs an access condition such that an operation will be performed only if the resource's current ETag value matches the specified resource's ETag value.</span></span>
            </summary>
        <returns><span data-ttu-id="54688-128"><see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> If-match 条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="54688-128">An <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> object that represents the If-Match condition.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>