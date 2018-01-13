<Type Name="CorrelationFilter" FullName="Microsoft.Azure.ServiceBus.CorrelationFilter">
  <TypeSignature Language="C#" Value="public sealed class CorrelationFilter : Microsoft.Azure.ServiceBus.Filter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CorrelationFilter extends Microsoft.Azure.ServiceBus.Filter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.CorrelationFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CorrelationFilter&#xA;Inherits Filter" />
  <TypeSignature Language="F#" Value="type CorrelationFilter = class&#xA;    inherit Filter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.Filter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ab602-101">相関関係のフィルター式を表します。</span><span class="sxs-lookup"><span data-stu-id="ab602-101">Represents the correlation filter expression.</span></span>
            </summary>
    <remarks>
      <para>
            <span data-ttu-id="ab602-102">CorrelationFilter では、一連の条件は到着したメッセージのユーザー アカウントとシステム プロパティのいずれかと一致するが保持されます。</span><span class="sxs-lookup"><span data-stu-id="ab602-102">A CorrelationFilter holds a set of conditions that are matched against one of more of an arriving message's user and system properties.</span></span>
            <span data-ttu-id="ab602-103">一般的な用途は、一致する、<see cref="P:Microsoft.Azure.ServiceBus.Message.CorrelationId" />プロパティがアプリケーションにもと照合することができます<see cref="P:Microsoft.Azure.ServiceBus.Message.ContentType" />、 <see cref="P:Microsoft.Azure.ServiceBus.Message.Label" />、 <see cref="P:Microsoft.Azure.ServiceBus.Message.MessageId" />、 <see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyTo" />、 <see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyToSessionId" />、 <see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" />、 <see cref="P:Microsoft.Azure.ServiceBus.Message.To" />、いずれかユーザー定義のプロパティ。</span><span class="sxs-lookup"><span data-stu-id="ab602-103">A common use is a match against the <see cref="P:Microsoft.Azure.ServiceBus.Message.CorrelationId" /> property, but the application can also choose to match against <see cref="P:Microsoft.Azure.ServiceBus.Message.ContentType" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.Label" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.MessageId" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyTo" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyToSessionId" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" />, <see cref="P:Microsoft.Azure.ServiceBus.Message.To" />, and any user-defined properties.</span></span>
            <span data-ttu-id="ab602-104">受信メッセージのプロパティ値が相関関係フィルターに指定された値と等しいときに、一致するものが存在すると判断されます。</span><span class="sxs-lookup"><span data-stu-id="ab602-104">A match exists when an arriving message's value for a property is equal to the value specified in the correlation filter.</span></span> <span data-ttu-id="ab602-105">文字列式の比較では大文字と小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="ab602-105">For string expressions, the comparison is case-sensitive.</span></span> <span data-ttu-id="ab602-106">複数の一致するプロパティを指定する場合、フィルターは論理 AND 条件として、つまり、すべての条件が一致するフィルターの一致する必要がありますそれらを結合します。</span><span class="sxs-lookup"><span data-stu-id="ab602-106">When specifying multiple match properties, the filter combines them as a logical AND condition, meaning all conditions must match for the filter to match.</span></span>
            </para>
      <para>
            <span data-ttu-id="ab602-107">CorrelationFilter は、相関関係の等値のみを処理するフィルターの宣言の効率的なショートカットを提供します。</span><span class="sxs-lookup"><span data-stu-id="ab602-107">The CorrelationFilter provides an efficient shortcut for declarations of filters that deal only with correlation equality.</span></span>
            <span data-ttu-id="ab602-108">ここでは、式の lexigraphical 分析のコストを回避できます。</span><span class="sxs-lookup"><span data-stu-id="ab602-108">In this case the cost of the lexigraphical analysis of the expression can be avoided.</span></span>
            <span data-ttu-id="ab602-109">だけでなくが相関関係のフィルターは、宣言時に最適化されますが、実行時にも最適化されます。</span><span class="sxs-lookup"><span data-stu-id="ab602-109">Not only will correlation filters be optimized at declaration time, but they will also be optimized at runtime.</span></span>
            <span data-ttu-id="ab602-110">関連付けフィルターの一致は、o (1) に定義されている相関関係のフィルターのセットの複雑さを集計、ハッシュ テーブルの検索を削減できます。</span><span class="sxs-lookup"><span data-stu-id="ab602-110">Correlation filter matching can be reduced to a hashtable lookup, which aggregates the complexity of the set of defined correlation filters to O(1).</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorrelationFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.CorrelationFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ab602-111"><see cref="T:Microsoft.Azure.ServiceBus.CorrelationFilter" /> クラスの新しいインスタンスを既定値で初期化します。</span><span class="sxs-lookup"><span data-stu-id="ab602-111">Initializes a new instance of the <see cref="T:Microsoft.Azure.ServiceBus.CorrelationFilter" /> class with default values.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorrelationFilter (string correlationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string correlationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.CorrelationFilter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (correlationId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.CorrelationFilter : string -&gt; Microsoft.Azure.ServiceBus.CorrelationFilter" Usage="new Microsoft.Azure.ServiceBus.CorrelationFilter correlationId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="correlationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="correlationId"><span data-ttu-id="ab602-112">相関関係の識別子です。</span><span class="sxs-lookup"><span data-stu-id="ab602-112">The identifier for the correlation.</span></span></param>
        <summary>
            <span data-ttu-id="ab602-113">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.ServiceBus.CorrelationFilter" />指定された関連付け識別子を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="ab602-113">Initializes a new instance of the <see cref="T:Microsoft.Azure.ServiceBus.CorrelationFilter" /> class with the specified correlation identifier.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="ab602-114">場合にスローされる、<paramref name="correlationId" />が null または空です。</span><span class="sxs-lookup"><span data-stu-id="ab602-114">Thrown when the <paramref name="correlationId" /> is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ab602-115">メッセージのコンテンツの種類。</span><span class="sxs-lookup"><span data-stu-id="ab602-115">Content type of the message.</span></span>
            </summary>
        <value><span data-ttu-id="ab602-116">メッセージのコンテンツ タイプ。</span><span class="sxs-lookup"><span data-stu-id="ab602-116">The content type of the message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ab602-117">関連付けの識別子</span><span class="sxs-lookup"><span data-stu-id="ab602-117">Identifier of the correlation.</span></span>
            </summary>
        <value><span data-ttu-id="ab602-118">相関関係の識別子。</span><span class="sxs-lookup"><span data-stu-id="ab602-118">The identifier of the correlation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ab602-119">アプリケーション固有のラベル。</span><span class="sxs-lookup"><span data-stu-id="ab602-119">Application specific label.</span></span>
            </summary>
        <value><span data-ttu-id="ab602-120">アプリケーション固有のラベル。</span><span class="sxs-lookup"><span data-stu-id="ab602-120">The application specific label.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ab602-121">メッセージの識別子。</span><span class="sxs-lookup"><span data-stu-id="ab602-121">Identifier of the message.</span></span>
            </summary>
        <value><span data-ttu-id="ab602-122">メッセージの識別子。</span><span class="sxs-lookup"><span data-stu-id="ab602-122">The identifier of the message.</span></span></value>
        <remarks><span data-ttu-id="ab602-123">MessageId の最大サイズとは、128 文字です。</span><span class="sxs-lookup"><span data-stu-id="ab602-123">Max MessageId size is 128 chars.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ab602-124">メッセージのアプリケーション固有のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="ab602-124">Application specific properties of the message.</span></span>
            </summary>
        <value><span data-ttu-id="ab602-125">メッセージのアプリケーションの特定プロパティです。</span><span class="sxs-lookup"><span data-stu-id="ab602-125">The application specific properties of the message.</span></span></value>
        <remarks>
            <span data-ttu-id="ab602-126">次の値のみの種類がサポートされて: byte、sbyte、char、short、ushort、int、uint、long、ulong、float、double、decimal、bool、Guid、文字列、Uri、DateTime、DateTimeOffset、TimeSpan、ストリーム、byte[]、および IList の IDictionary には、種類がサポートされています。</span><span class="sxs-lookup"><span data-stu-id="ab602-126">Only following value types are supported: byte, sbyte, char, short, ushort, int, uint, long, ulong, float, double, decimal, bool, Guid, string, Uri, DateTime, DateTimeOffset, TimeSpan, Stream, byte[], and IList / IDictionary of supported types</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.ReplyTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ab602-127">返信するキューのアドレス</span><span class="sxs-lookup"><span data-stu-id="ab602-127">Address of the queue to reply to.</span></span>
            </summary>
        <value><span data-ttu-id="ab602-128">返信するキューのアドレス。</span><span class="sxs-lookup"><span data-stu-id="ab602-128">The address of the queue to reply to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.ReplyToSessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ab602-129">返信するセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="ab602-129">Session identifier to reply to.</span></span>
            </summary>
        <value><span data-ttu-id="ab602-130">返信するセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="ab602-130">The session identifier to reply to.</span></span></value>
        <remarks><span data-ttu-id="ab602-131">ReplyToSessionId の最大サイズは 128 です。</span><span class="sxs-lookup"><span data-stu-id="ab602-131">Max size of ReplyToSessionId is 128.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ab602-132">セッションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="ab602-132">Session identifier.</span></span>
            </summary>
        <value><span data-ttu-id="ab602-133">セッション識別子。</span><span class="sxs-lookup"><span data-stu-id="ab602-133">The session identifier.</span></span></value>
        <remarks><span data-ttu-id="ab602-134">SessionId の最大サイズは、128 文字です。</span><span class="sxs-lookup"><span data-stu-id="ab602-134">Max size of sessionId is 128 chars.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ab602-135">送信先アドレス</span><span class="sxs-lookup"><span data-stu-id="ab602-135">Address to send to.</span></span>
            </summary>
        <value><span data-ttu-id="ab602-136">送信するアドレス。</span><span class="sxs-lookup"><span data-stu-id="ab602-136">The address to send to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.CorrelationFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="correlationFilter.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ab602-137">現在のインスタンスの値を等価の文字列形式に変換します。</span><span class="sxs-lookup"><span data-stu-id="ab602-137">Converts the value of the current instance to its equivalent string representation.</span></span>
            </summary>
        <returns><span data-ttu-id="ab602-138">現在のインスタンスの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="ab602-138">A string representation of the current instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>