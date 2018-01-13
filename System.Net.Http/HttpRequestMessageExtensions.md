<Type Name="HttpRequestMessageExtensions" FullName="System.Net.Http.HttpRequestMessageExtensions">
  <TypeSignature Language="C#" Value="public static class HttpRequestMessageExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit HttpRequestMessageExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Net.Http.HttpRequestMessageExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module HttpRequestMessageExtensions" />
  <TypeSignature Language="F#" Value="type HttpRequestMessageExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c1b15-101">拡張メソッドを<see cref="T:System.Net.Http.HttpRequestMessage" />さまざまなユーティリティを提供します。</span><span class="sxs-lookup"><span data-stu-id="c1b15-101">Extension methods for <see cref="T:System.Net.Http.HttpRequestMessage" /> providing various utilities.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateBadRequestResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateBadRequestResponse (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateBadRequestResponse(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateBadRequestResponse(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateBadRequestResponse (request As HttpRequestMessage) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateBadRequestResponse : System.Net.Http.HttpRequestMessage -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateBadRequestResponse request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="c1b15-102">現在の <see cref="T:System.Net.Http.HttpRequestMessage" /> です。</span><span class="sxs-lookup"><span data-stu-id="c1b15-102">The current <see cref="T:System.Net.Http.HttpRequestMessage" />.</span></span></param>
        <summary>
            <span data-ttu-id="c1b15-103">作成、<see cref="T:System.Net.Http.HttpResponseMessage" />で、<see cref="F:System.Net.HttpStatusCode.BadRequest" />ステータス コードと、既定値<see cref="T:System.Web.Http.HttpError" />として HTTP 応答本文です。</span><span class="sxs-lookup"><span data-stu-id="c1b15-103">Creates an <see cref="T:System.Net.Http.HttpResponseMessage" /> with an <see cref="F:System.Net.HttpStatusCode.BadRequest" /> status code and a  default <see cref="T:System.Web.Http.HttpError" /> as HTTP response body.</span></span>
            </summary>
        <returns><span data-ttu-id="c1b15-104">初期化された<see cref="T:System.Net.Http.HttpResponseMessage" />です。</span><span class="sxs-lookup"><span data-stu-id="c1b15-104">An initialized <see cref="T:System.Net.Http.HttpResponseMessage" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBadRequestResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateBadRequestResponse (this System.Net.Http.HttpRequestMessage request, string format, params object[] args);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateBadRequestResponse(class System.Net.Http.HttpRequestMessage request, string format, object[] args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateBadRequestResponse(System.Net.Http.HttpRequestMessage,System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateBadRequestResponse (request As HttpRequestMessage, format As String, ParamArray args As Object()) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateBadRequestResponse : System.Net.Http.HttpRequestMessage * string * obj[] -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateBadRequestResponse (request, format, args)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="args" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="c1b15-105">現在の <see cref="T:System.Net.Http.HttpRequestMessage" /> です。</span><span class="sxs-lookup"><span data-stu-id="c1b15-105">The current <see cref="T:System.Net.Http.HttpRequestMessage" />.</span></span></param>
        <param name="format"><span data-ttu-id="c1b15-106">複合書式設定文字列。</span><span class="sxs-lookup"><span data-stu-id="c1b15-106">A composite format string.</span></span></param>
        <param name="args"><span data-ttu-id="c1b15-107">0 個以上の書式設定対象オブジェクトを含んだオブジェクト配列。</span><span class="sxs-lookup"><span data-stu-id="c1b15-107">An object array that contains zero or more objects to format.</span></span></param>
        <summary>
            <span data-ttu-id="c1b15-108">作成、<see cref="T:System.Net.Http.HttpResponseMessage" />で、<see cref="F:System.Net.HttpStatusCode.BadRequest" />ステータス コードと<see cref="T:System.Web.Http.HttpError" />HTTP 応答の本文として提供されたメッセージを格納しています。</span><span class="sxs-lookup"><span data-stu-id="c1b15-108">Creates an <see cref="T:System.Net.Http.HttpResponseMessage" /> with an <see cref="F:System.Net.HttpStatusCode.BadRequest" /> status code and a <see cref="T:System.Web.Http.HttpError" /> containing the provided message as HTTP response body.</span></span>
            </summary>
        <returns><span data-ttu-id="c1b15-109">初期化された<see cref="T:System.Net.Http.HttpResponseMessage" />です。</span><span class="sxs-lookup"><span data-stu-id="c1b15-109">An initialized <see cref="T:System.Net.Http.HttpResponseMessage" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotFoundResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateNotFoundResponse (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateNotFoundResponse(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateNotFoundResponse(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateNotFoundResponse (request As HttpRequestMessage) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateNotFoundResponse : System.Net.Http.HttpRequestMessage -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateNotFoundResponse request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="c1b15-110">現在の <see cref="T:System.Net.Http.HttpRequestMessage" /> です。</span><span class="sxs-lookup"><span data-stu-id="c1b15-110">The current <see cref="T:System.Net.Http.HttpRequestMessage" />.</span></span></param>
        <summary>
            <span data-ttu-id="c1b15-111">作成、<see cref="T:System.Net.Http.HttpResponseMessage" />で、<see cref="F:System.Net.HttpStatusCode.NotFound" />ステータス コードと、既定値<see cref="T:System.Web.Http.HttpError" />として HTTP 応答本文です。</span><span class="sxs-lookup"><span data-stu-id="c1b15-111">Creates an <see cref="T:System.Net.Http.HttpResponseMessage" /> with an <see cref="F:System.Net.HttpStatusCode.NotFound" /> status code and a default <see cref="T:System.Web.Http.HttpError" /> as HTTP response body.</span></span>
            </summary>
        <returns><span data-ttu-id="c1b15-112">初期化された<see cref="T:System.Net.Http.HttpResponseMessage" />です。</span><span class="sxs-lookup"><span data-stu-id="c1b15-112">An initialized <see cref="T:System.Net.Http.HttpResponseMessage" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotFoundResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateNotFoundResponse (this System.Net.Http.HttpRequestMessage request, string format, params object[] args);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateNotFoundResponse(class System.Net.Http.HttpRequestMessage request, string format, object[] args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateNotFoundResponse(System.Net.Http.HttpRequestMessage,System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateNotFoundResponse (request As HttpRequestMessage, format As String, ParamArray args As Object()) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateNotFoundResponse : System.Net.Http.HttpRequestMessage * string * obj[] -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateNotFoundResponse (request, format, args)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="args" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="c1b15-113">現在の <see cref="T:System.Net.Http.HttpRequestMessage" /> です。</span><span class="sxs-lookup"><span data-stu-id="c1b15-113">The current <see cref="T:System.Net.Http.HttpRequestMessage" />.</span></span></param>
        <param name="format"><span data-ttu-id="c1b15-114">複合書式設定文字列。</span><span class="sxs-lookup"><span data-stu-id="c1b15-114">A composite format string.</span></span></param>
        <param name="args"><span data-ttu-id="c1b15-115">0 個以上の書式設定対象オブジェクトを含んだオブジェクト配列。</span><span class="sxs-lookup"><span data-stu-id="c1b15-115">An object array that contains zero or more objects to format.</span></span></param>
        <summary>
            <span data-ttu-id="c1b15-116">作成、<see cref="T:System.Net.Http.HttpResponseMessage" />で、<see cref="F:System.Net.HttpStatusCode.NotFound" />ステータス コードと<see cref="T:System.Web.Http.HttpError" />HTTP 応答の本文として提供されたメッセージを格納しています。</span><span class="sxs-lookup"><span data-stu-id="c1b15-116">Creates an <see cref="T:System.Net.Http.HttpResponseMessage" /> with an <see cref="F:System.Net.HttpStatusCode.NotFound" /> status code and a <see cref="T:System.Web.Http.HttpError" /> containing the provided message as HTTP response body.</span></span>
            </summary>
        <returns><span data-ttu-id="c1b15-117">初期化された<see cref="T:System.Net.Http.HttpResponseMessage" />です。</span><span class="sxs-lookup"><span data-stu-id="c1b15-117">An initialized <see cref="T:System.Net.Http.HttpResponseMessage" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUnauthorizedResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateUnauthorizedResponse (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateUnauthorizedResponse(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateUnauthorizedResponse(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateUnauthorizedResponse (request As HttpRequestMessage) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateUnauthorizedResponse : System.Net.Http.HttpRequestMessage -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateUnauthorizedResponse request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="c1b15-118">現在の <see cref="T:System.Net.Http.HttpRequestMessage" /> です。</span><span class="sxs-lookup"><span data-stu-id="c1b15-118">The current <see cref="T:System.Net.Http.HttpRequestMessage" />.</span></span></param>
        <summary>
            <span data-ttu-id="c1b15-119">作成、<see cref="T:System.Net.Http.HttpResponseMessage" />で、<see cref="F:System.Net.HttpStatusCode.Unauthorized" />ステータス コードと、既定値<see cref="T:System.Web.Http.HttpError" />として HTTP 応答本文です。</span><span class="sxs-lookup"><span data-stu-id="c1b15-119">Creates an <see cref="T:System.Net.Http.HttpResponseMessage" /> with an <see cref="F:System.Net.HttpStatusCode.Unauthorized" /> status code and a  default <see cref="T:System.Web.Http.HttpError" /> as HTTP response body.</span></span>
            </summary>
        <returns><span data-ttu-id="c1b15-120">初期化された<see cref="T:System.Net.Http.HttpResponseMessage" />です。</span><span class="sxs-lookup"><span data-stu-id="c1b15-120">An initialized <see cref="T:System.Net.Http.HttpResponseMessage" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUnauthorizedResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateUnauthorizedResponse (this System.Net.Http.HttpRequestMessage request, string format, params object[] args);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateUnauthorizedResponse(class System.Net.Http.HttpRequestMessage request, string format, object[] args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateUnauthorizedResponse(System.Net.Http.HttpRequestMessage,System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateUnauthorizedResponse (request As HttpRequestMessage, format As String, ParamArray args As Object()) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateUnauthorizedResponse : System.Net.Http.HttpRequestMessage * string * obj[] -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateUnauthorizedResponse (request, format, args)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="args" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="c1b15-121">現在の <see cref="T:System.Net.Http.HttpRequestMessage" /> です。</span><span class="sxs-lookup"><span data-stu-id="c1b15-121">The current <see cref="T:System.Net.Http.HttpRequestMessage" />.</span></span></param>
        <param name="format"><span data-ttu-id="c1b15-122">複合書式設定文字列。</span><span class="sxs-lookup"><span data-stu-id="c1b15-122">A composite format string.</span></span></param>
        <param name="args"><span data-ttu-id="c1b15-123">0 個以上の書式設定対象オブジェクトを含んだオブジェクト配列。</span><span class="sxs-lookup"><span data-stu-id="c1b15-123">An object array that contains zero or more objects to format.</span></span></param>
        <summary>
            <span data-ttu-id="c1b15-124">作成、<see cref="T:System.Net.Http.HttpResponseMessage" />で、<see cref="F:System.Net.HttpStatusCode.Unauthorized" />ステータス コードと<see cref="T:System.Web.Http.HttpError" />HTTP 応答の本文として提供されたメッセージを格納しています。</span><span class="sxs-lookup"><span data-stu-id="c1b15-124">Creates an <see cref="T:System.Net.Http.HttpResponseMessage" /> with an <see cref="F:System.Net.HttpStatusCode.Unauthorized" /> status code and a <see cref="T:System.Web.Http.HttpError" /> containing the provided message as HTTP response body.</span></span>
            </summary>
        <returns><span data-ttu-id="c1b15-125">初期化された<see cref="T:System.Net.Http.HttpResponseMessage" />です。</span><span class="sxs-lookup"><span data-stu-id="c1b15-125">An initialized <see cref="T:System.Net.Http.HttpResponseMessage" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHeaderOrDefault">
      <MemberSignature Language="C#" Value="public static string GetHeaderOrDefault (this System.Net.Http.HttpRequestMessage request, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetHeaderOrDefault(class System.Net.Http.HttpRequestMessage request, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.GetHeaderOrDefault(System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetHeaderOrDefault (request As HttpRequestMessage, name As String) As String" />
      <MemberSignature Language="F#" Value="static member GetHeaderOrDefault : System.Net.Http.HttpRequestMessage * string -&gt; string" Usage="System.Net.Http.HttpRequestMessageExtensions.GetHeaderOrDefault (request, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="c1b15-126">ヘッダーを検索する場所の要求。</span><span class="sxs-lookup"><span data-stu-id="c1b15-126">The request for where to look for the header.</span></span></param>
        <param name="name"><span data-ttu-id="c1b15-127">ヘッダーの名前。</span><span class="sxs-lookup"><span data-stu-id="c1b15-127">The name of the header.</span></span></param>
        <summary>
            <span data-ttu-id="c1b15-128">単一の値としては、最初の HTTP ヘッダー値を取得または<c>null</c>存在していない場合。</span><span class="sxs-lookup"><span data-stu-id="c1b15-128">Gets the first HTTP header value as a single value or <c>null</c> if not present.</span></span>
            </summary>
        <returns><span data-ttu-id="c1b15-129">最初の HTTP ヘッダーの値または<c>null</c>存在していない場合。</span><span class="sxs-lookup"><span data-stu-id="c1b15-129">The first HTTP header value or <c>null</c> if not present.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsIfNoneMatch">
      <MemberSignature Language="C#" Value="public static bool IsIfNoneMatch (this System.Net.Http.HttpRequestMessage request, System.Net.Http.Headers.EntityTagHeaderValue current);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsIfNoneMatch(class System.Net.Http.HttpRequestMessage request, class System.Net.Http.Headers.EntityTagHeaderValue current) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.IsIfNoneMatch(System.Net.Http.HttpRequestMessage,System.Net.Http.Headers.EntityTagHeaderValue)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsIfNoneMatch (request As HttpRequestMessage, current As EntityTagHeaderValue) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsIfNoneMatch : System.Net.Http.HttpRequestMessage * System.Net.Http.Headers.EntityTagHeaderValue -&gt; bool" Usage="System.Net.Http.HttpRequestMessageExtensions.IsIfNoneMatch (request, current)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="current" Type="System.Net.Http.Headers.EntityTagHeaderValue" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="c1b15-130">一致するように要求します。</span><span class="sxs-lookup"><span data-stu-id="c1b15-130">The request to match.</span></span></param>
        <param name="current"><span data-ttu-id="c1b15-131">リソースの現在の etag。</span><span class="sxs-lookup"><span data-stu-id="c1b15-131">The current etag for the resource.</span></span> <span data-ttu-id="c1b15-132">(つまり、リソースがまだ存在しない) 現在の etag がない場合を使用して<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="c1b15-132">If there is no current etag (i.e. the resource does not yet exist) then use <c>null</c>.</span></span></param>
        <summary>
            <span data-ttu-id="c1b15-133">要求の条件付きのことを確認、<c>なし-If-match</c> HTTP ヘッダー フィールドに一致する値を持つ、<paramref name="current" />値。</span><span class="sxs-lookup"><span data-stu-id="c1b15-133">Checks if the request is conditional having a <c>If-None-Match</c> HTTP header field with a value that matches the <paramref name="current" /> value.</span></span> <span data-ttu-id="c1b15-134">場合、 <c>true</c> 304 (変更なし) または 412 (Precondition Failed) のステータス コードを使用することを示すためにこれを使用することができます。</span><span class="sxs-lookup"><span data-stu-id="c1b15-134">In the case of <c>true</c> this can be used to indicate that a 304 (Not Modified) or a 412 (Precondition Failed) status code should be used.</span></span>
            </summary>
        <returns><span data-ttu-id="c1b15-135">返します<c>true</c>場合の<c>なし-If-match</c>値です。 現在の etag 値と一致または<c>なし-If-match</c>値は"\*"と<paramref name="current" />は null。 それ以外の場合は false。</span><span class="sxs-lookup"><span data-stu-id="c1b15-135">Returns <c>true</c> if one of the <c>If-None-Match</c> values match the current etag; or the <c>If-None-Match</c> value is "\*" and <paramref name="current" /> is not null; otherwise false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>