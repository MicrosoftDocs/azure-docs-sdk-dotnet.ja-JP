<Type Name="Document" FullName="Microsoft.Azure.Documents.Document">
  <TypeSignature Language="C#" Value="public class Document : Microsoft.Azure.Documents.Resource, System.Dynamic.IDynamicMetaObjectProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Document extends Microsoft.Azure.Documents.Resource implements class System.Dynamic.IDynamicMetaObjectProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Document" />
  <TypeSignature Language="VB.NET" Value="Public Class Document&#xA;Inherits Resource&#xA;Implements IDynamicMetaObjectProvider" />
  <TypeSignature Language="F#" Value="type Document = class&#xA;    inherit Resource&#xA;    interface IDynamicMetaObjectProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Dynamic.IDynamicMetaObjectProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="834c6-101">Cosmos DB の Azure サービスでドキュメントを表します。</span><span class="sxs-lookup"><span data-stu-id="834c6-101">Represents a document in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks> 
            <span data-ttu-id="834c6-102">ドキュメントは、構造化された JSON ドキュメントです。</span><span class="sxs-lookup"><span data-stu-id="834c6-102">A document is a structured JSON document.</span></span> <span data-ttu-id="834c6-103">JSON ドキュメントのセットのスキーマがないと、ドキュメントは、カスタム プロパティの任意の数との添付ファイルのオプションのリストを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="834c6-103">There is no set schema for the JSON documents, and a document may contain any number of custom properties as well as an optional list of attachments.</span></span> <span data-ttu-id="834c6-104">ドキュメントでは、アプリケーション リソースであるし、マスター _ キーまたはリソース キーを使用して承認することができます。</span><span class="sxs-lookup"><span data-stu-id="834c6-104">Document is an application resource and can be authorized using the master key or resource keys.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Document ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Document.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="834c6-105">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Document" /> Azure Cosmos DB サービスのクラスです。</span><span class="sxs-lookup"><span data-stu-id="834c6-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Document" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AttachmentsLink">
      <MemberSignature Language="C#" Value="public string AttachmentsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AttachmentsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Document.AttachmentsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AttachmentsLink As String" />
      <MemberSignature Language="F#" Value="member this.AttachmentsLink : string" Usage="Microsoft.Azure.Documents.Document.AttachmentsLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="834c6-106">自己リンクに対応するドキュメントの添付ファイル、Azure Cosmos DB サービスから取得します。</span><span class="sxs-lookup"><span data-stu-id="834c6-106">Gets the self-link corresponding to attachments of the document from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="834c6-107">自己リンクに対応するドキュメントの添付ファイルです。</span><span class="sxs-lookup"><span data-stu-id="834c6-107">The self-link corresponding to attachments of the document.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="834c6-108">0 になり、多くの添付ファイルの間のすべてのドキュメントが持つことができます。</span><span class="sxs-lookup"><span data-stu-id="834c6-108">Every document can have between zero and many attachments.</span></span> <span data-ttu-id="834c6-109">添付ファイルのリンクには、ドキュメントに属している添付ファイルのフィードが含まれています。</span><span class="sxs-lookup"><span data-stu-id="834c6-109">The attachments link contains a feed of attachments that belong to the document.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject">
      <MemberSignature Language="C#" Value="System.Dynamic.DynamicMetaObject IDynamicMetaObjectProvider.GetMetaObject (System.Linq.Expressions.Expression parameter);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Dynamic.DynamicMetaObject System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject(class System.Linq.Expressions.Expression parameter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Document.System#Dynamic#IDynamicMetaObjectProvider#GetMetaObject(System.Linq.Expressions.Expression)" />
      <MemberSignature Language="VB.NET" Value="Function GetMetaObject (parameter As Expression) As DynamicMetaObject Implements IDynamicMetaObjectProvider.GetMetaObject" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject(System.Linq.Expressions.Expression)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Dynamic.DynamicMetaObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameter" Type="System.Linq.Expressions.Expression" />
      </Parameters>
      <Docs>
        <param name="parameter">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Document.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.Document.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="ttl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="834c6-110">取得または Azure Cosmos DB サービス内のドキュメントの秒単位で有効期限を設定します。</span><span class="sxs-lookup"><span data-stu-id="834c6-110">Gets or sets the time to live in seconds of the document in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="834c6-111">これは、省略可能なプロパティです。</span><span class="sxs-lookup"><span data-stu-id="834c6-111">It is an optional property.</span></span> <span data-ttu-id="834c6-112">有効な値はどちらかは 0 以外。 正の整数である必要があります '-1'、または<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="834c6-112">A valid value must be either a nonzero positive integer, '-1', or <c>null</c>.</span></span>
            <span data-ttu-id="834c6-113">既定では、TimeToLive が意味を null に設定は、コレクションの継承し、<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />です。</span><span class="sxs-lookup"><span data-stu-id="834c6-113">By default, TimeToLive is set to null meaning the document inherits the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />.</span></span>
            <span data-ttu-id="834c6-114">測定単位は秒です。</span><span class="sxs-lookup"><span data-stu-id="834c6-114">The unit of measurement is seconds.</span></span> <span data-ttu-id="834c6-115">最大値は 2147483647 です。</span><span class="sxs-lookup"><span data-stu-id="834c6-115">The maximum allowed value is 2147483647.</span></span>
            <span data-ttu-id="834c6-116">コレクションに関係なくは無期限にすること、値が-1 の場合は、<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />値。</span><span class="sxs-lookup"><span data-stu-id="834c6-116">When the value is '-1', it means never expire regardless of the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> value.</span></span>
            </value>
        <remarks>
          <para>
            <span data-ttu-id="834c6-117">コレクションを調べた後、ドキュメントの最終的な有効期間ポリシーの評価<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />です。</span><span class="sxs-lookup"><span data-stu-id="834c6-117">The final time-to-live policy of a document is evaluated after consulting the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />.</span></span>
            </para>
          <para>
            <span data-ttu-id="834c6-118">ときに、<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />は<c>null</c>、ドキュメントは、コレクションを継承<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />です。</span><span class="sxs-lookup"><span data-stu-id="834c6-118">When the <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> is <c>null</c>, the document inherits the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />.</span></span>
            <span data-ttu-id="834c6-119">場合、コレクションの<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />とその最終書き込み時刻以降、既定値に有効期限 (秒) の後に期限切れになるドキュメントを秒単位でそのに有効期限としてその値を継承し、0 以外の正の整数がします。</span><span class="sxs-lookup"><span data-stu-id="834c6-119">If the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> is a nonzero positive integer, then the document will inherit that value as its time-to-live in seconds, and will be expired after the default time-to-live in seconds since its last write time.</span></span> <span data-ttu-id="834c6-120">期限切れのドキュメントは、バック グラウンドで削除されます。</span><span class="sxs-lookup"><span data-stu-id="834c6-120">The expired documents will be deleted in background.</span></span>
            <span data-ttu-id="834c6-121">それ以外の場合、ドキュメント無期限になります。</span><span class="sxs-lookup"><span data-stu-id="834c6-121">Otherwise, the document will never expire.</span></span>
            </para>
          <para>
            <span data-ttu-id="834c6-122">ときに、 <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> '-1' で、コレクションに関係なく、ドキュメントが切れない<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />値。</span><span class="sxs-lookup"><span data-stu-id="834c6-122">When the <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> is '-1', the document will never expire regardless of the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> value.</span></span>
            </para>
          <para>
            <span data-ttu-id="834c6-123">ときに、 <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> 0 以外の正の整数は、コレクションを確認する必要があります<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />です。</span><span class="sxs-lookup"><span data-stu-id="834c6-123">When the <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> is a nonzero positive integer, need to check the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />.</span></span>
            <span data-ttu-id="834c6-124">場合、コレクションの<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />は<c>null</c>の有効期限はオフになっているコレクション、およびドキュメントの <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />無視する必要があり、ドキュメントが決して期限切れです。</span><span class="sxs-lookup"><span data-stu-id="834c6-124">If the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> is <c>null</c>, which means the time-to-live has been turned off on the collection, and the document's <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> should be disregarded and the document will never expire.</span></span>
            <span data-ttu-id="834c6-125">それ以外の場合、ドキュメントの<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />が有効であります。</span><span class="sxs-lookup"><span data-stu-id="834c6-125">Otherwise, the document's <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> will be honored.</span></span> <span data-ttu-id="834c6-126">ドキュメントが期限切れになるに有効期限 (秒) の既定の後にその最終書き込み時刻以降</span><span class="sxs-lookup"><span data-stu-id="834c6-126">The document will be expired after the default time-to-live in seconds since its last write time.</span></span> <span data-ttu-id="834c6-127">期限切れのドキュメントは、バック グラウンドで削除されます。</span><span class="sxs-lookup"><span data-stu-id="834c6-127">The expired documents will be deleted in background.</span></span>
            </para>
          <para>
            <span data-ttu-id="834c6-128">次の表は、最終的な有効期間ポリシーを評価するコレクションの指定したマトリックスの例を示します<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />とドキュメントの<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />します。</span><span class="sxs-lookup"><span data-stu-id="834c6-128">The table below shows an example of the matrix to evaluate the final time-to-live policy given a collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> and a document's <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />.</span></span>
            </para>
          <list type="table">
            <listheader>
              <term><span data-ttu-id="834c6-129">コレクション</span><span class="sxs-lookup"><span data-stu-id="834c6-129">Collection</span></span></term>
              <description><span data-ttu-id="834c6-130">[マトリックス]</span><span class="sxs-lookup"><span data-stu-id="834c6-130">Matrix</span></span></description>
            </listheader>
            <item>
              <term><span data-ttu-id="834c6-131">DefaultTimeToLive = null</span><span class="sxs-lookup"><span data-stu-id="834c6-131">DefaultTimeToLive = null</span></span></term>
              <description>
                <list type="table">
                  <listheader>
                    <term><span data-ttu-id="834c6-132">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="834c6-132">Document</span></span></term>
                    <description><span data-ttu-id="834c6-133">結果</span><span class="sxs-lookup"><span data-stu-id="834c6-133">Result</span></span></description>
                  </listheader>
                  <item>
                    <term><span data-ttu-id="834c6-134">TimeToLive = null</span><span class="sxs-lookup"><span data-stu-id="834c6-134">TimeToLive = null</span></span></term>
                    <description><span data-ttu-id="834c6-135">TTL は無効です。</span><span class="sxs-lookup"><span data-stu-id="834c6-135">TTL is disabled.</span></span> <span data-ttu-id="834c6-136">ドキュメントには、(既定値) が決して期限切れです。</span><span class="sxs-lookup"><span data-stu-id="834c6-136">The document will never expire (default).</span></span></description>
                  </item>
                  <item>
                    <term><span data-ttu-id="834c6-137">TimeToLive-1 を =</span><span class="sxs-lookup"><span data-stu-id="834c6-137">TimeToLive = -1</span></span></term>
                    <description><span data-ttu-id="834c6-138">TTL は無効です。</span><span class="sxs-lookup"><span data-stu-id="834c6-138">TTL is disabled.</span></span> <span data-ttu-id="834c6-139">ドキュメントが決して期限切れです。</span><span class="sxs-lookup"><span data-stu-id="834c6-139">The document will never expire.</span></span></description>
                  </item>
                  <item>
                    <term><span data-ttu-id="834c6-140">TimeToLive = 2000</span><span class="sxs-lookup"><span data-stu-id="834c6-140">TimeToLive = 2000</span></span></term>
                    <description><span data-ttu-id="834c6-141">TTL は無効です。</span><span class="sxs-lookup"><span data-stu-id="834c6-141">TTL is disabled.</span></span> <span data-ttu-id="834c6-142">ドキュメントが決して期限切れです。</span><span class="sxs-lookup"><span data-stu-id="834c6-142">The document will never expire.</span></span></description>
                  </item>
                </list>
              </description>
            </item>
            <item>
              <term><span data-ttu-id="834c6-143">DefaultTimeToLive-1 を =</span><span class="sxs-lookup"><span data-stu-id="834c6-143">DefaultTimeToLive = -1</span></span></term>
              <description>
                <list type="table">
                  <listheader>
                    <term><span data-ttu-id="834c6-144">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="834c6-144">Document</span></span></term>
                    <description><span data-ttu-id="834c6-145">結果</span><span class="sxs-lookup"><span data-stu-id="834c6-145">Result</span></span></description>
                  </listheader>
                  <item>
                    <term><span data-ttu-id="834c6-146">TimeToLive = null</span><span class="sxs-lookup"><span data-stu-id="834c6-146">TimeToLive = null</span></span></term>
                    <description><span data-ttu-id="834c6-147">TTL は有効です。</span><span class="sxs-lookup"><span data-stu-id="834c6-147">TTL is enabled.</span></span> <span data-ttu-id="834c6-148">ドキュメントには、(既定値) が決して期限切れです。</span><span class="sxs-lookup"><span data-stu-id="834c6-148">The document will never expire (default).</span></span></description>
                  </item>
                  <item>
                    <term><span data-ttu-id="834c6-149">TimeToLive-1 を =</span><span class="sxs-lookup"><span data-stu-id="834c6-149">TimeToLive = -1</span></span></term>
                    <description><span data-ttu-id="834c6-150">TTL は有効です。</span><span class="sxs-lookup"><span data-stu-id="834c6-150">TTL is enabled.</span></span> <span data-ttu-id="834c6-151">ドキュメントが決して期限切れです。</span><span class="sxs-lookup"><span data-stu-id="834c6-151">The document will never expire.</span></span></description>
                  </item>
                  <item>
                    <term><span data-ttu-id="834c6-152">TimeToLive = 2000</span><span class="sxs-lookup"><span data-stu-id="834c6-152">TimeToLive = 2000</span></span></term>
                    <description><span data-ttu-id="834c6-153">TTL は有効です。</span><span class="sxs-lookup"><span data-stu-id="834c6-153">TTL is enabled.</span></span> <span data-ttu-id="834c6-154">ドキュメントは、2000 秒後に切れます。</span><span class="sxs-lookup"><span data-stu-id="834c6-154">The document will expire after 2000 seconds.</span></span></description>
                  </item>
                </list>
              </description>
            </item>
            <item>
              <term><span data-ttu-id="834c6-155">DefaultTimeToLive = 1000</span><span class="sxs-lookup"><span data-stu-id="834c6-155">DefaultTimeToLive = 1000</span></span></term>
              <description>
                <list type="table">
                  <listheader>
                    <term><span data-ttu-id="834c6-156">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="834c6-156">Document</span></span></term>
                    <description><span data-ttu-id="834c6-157">結果</span><span class="sxs-lookup"><span data-stu-id="834c6-157">Result</span></span></description>
                  </listheader>
                  <item>
                    <term><span data-ttu-id="834c6-158">TimeToLive = null</span><span class="sxs-lookup"><span data-stu-id="834c6-158">TimeToLive = null</span></span></term>
                    <description><span data-ttu-id="834c6-159">TTL は有効です。</span><span class="sxs-lookup"><span data-stu-id="834c6-159">TTL is enabled.</span></span> <span data-ttu-id="834c6-160">ドキュメントは、1000 秒 (既定) 後に切れます。</span><span class="sxs-lookup"><span data-stu-id="834c6-160">The document will expire after 1000 seconds (default).</span></span></description>
                  </item>
                  <item>
                    <term><span data-ttu-id="834c6-161">TimeToLive-1 を =</span><span class="sxs-lookup"><span data-stu-id="834c6-161">TimeToLive = -1</span></span></term>
                    <description><span data-ttu-id="834c6-162">TTL は有効です。</span><span class="sxs-lookup"><span data-stu-id="834c6-162">TTL is enabled.</span></span> <span data-ttu-id="834c6-163">ドキュメントが決して期限切れです。</span><span class="sxs-lookup"><span data-stu-id="834c6-163">The document will never expire.</span></span></description>
                  </item>
                  <item>
                    <term><span data-ttu-id="834c6-164">TimeToLive = 2000</span><span class="sxs-lookup"><span data-stu-id="834c6-164">TimeToLive = 2000</span></span></term>
                    <description><span data-ttu-id="834c6-165">TTL は有効です。</span><span class="sxs-lookup"><span data-stu-id="834c6-165">TTL is enabled.</span></span> <span data-ttu-id="834c6-166">ドキュメントは、2000 秒後に切れます。</span><span class="sxs-lookup"><span data-stu-id="834c6-166">The document will expire after 2000 seconds.</span></span></description>
                  </item>
                </list>
              </description>
            </item>
          </list>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <example>
            <span data-ttu-id="834c6-167">次の例では、ドキュメントの内容から 'ttl' を削除します。</span><span class="sxs-lookup"><span data-stu-id="834c6-167">The example below removes 'ttl' from document content.</span></span>
            <span data-ttu-id="834c6-168">ドキュメントは、コレクションの継承は<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />その有効期間の値として。</span><span class="sxs-lookup"><span data-stu-id="834c6-168">The document will inherit the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> as its time-to-live value.</span></span>
            <code language="c#"><![CDATA[
                document.TimeToLive = null;
            ]]></code></example>
        <example>
            <span data-ttu-id="834c6-169">以下の例では、ドキュメント必要がありますかに関係なく有効期限はありません。</span><span class="sxs-lookup"><span data-stu-id="834c6-169">The example below ensures that the document should never expire regardless.</span></span>
            <code language="c#"><![CDATA[
                document.TimeToLive = -1;
            ]]></code></example>
        <example>
            <span data-ttu-id="834c6-170">次の例はの有効期限を設定、ドキュメントに対する秒単位でします。</span><span class="sxs-lookup"><span data-stu-id="834c6-170">The example below sets the time-to-live in seconds on a document.</span></span>
            <span data-ttu-id="834c6-171">ドキュメント有効期限が切れる時刻以降、最後の書き込み 1000 秒後に、コレクションの<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />は<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="834c6-171">The document will expire after 1000 seconds since its last write time when the collection's <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> is not <c>null</c>.</span></span>
            <code language="c#"><![CDATA[
            document.TimeToLive = 1000;
                ]]></code></example>
      </Docs>
    </Member>
  </Members>
</Type>