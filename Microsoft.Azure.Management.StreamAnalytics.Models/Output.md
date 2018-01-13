<Type Name="Output" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.Output">
  <TypeSignature Language="C#" Value="public class Output : Microsoft.Azure.Management.StreamAnalytics.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Output extends Microsoft.Azure.Management.StreamAnalytics.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
  <TypeSignature Language="VB.NET" Value="Public Class Output&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type Output = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3bbe2-101">名前付きの出力に関連付けられているすべての情報を含む出力オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-101">An output object, containing all information associated with the named output.</span></span> <span data-ttu-id="3bbe2-102">ストリーミング ジョブの下では、すべての出力が含まれています。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-102">All outputs are contained under a streaming job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Output ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Output.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3bbe2-103">出力クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-103">Initializes a new instance of the Output class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Output (string id = null, string name = null, string type = null, Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource datasource = null, Microsoft.Azure.Management.StreamAnalytics.Models.Serialization serialization = null, Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics diagnostics = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource datasource, class Microsoft.Azure.Management.StreamAnalytics.Models.Serialization serialization, class Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics diagnostics, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Output.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource,Microsoft.Azure.Management.StreamAnalytics.Models.Serialization,Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.Output : string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource * Microsoft.Azure.Management.StreamAnalytics.Models.Serialization * Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Output" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.Output (id, name, type, datasource, serialization, diagnostics, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="datasource" Type="Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
        <Parameter Name="serialization" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Serialization" />
        <Parameter Name="diagnostics" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="3bbe2-104">リソース Id</span><span class="sxs-lookup"><span data-stu-id="3bbe2-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="3bbe2-105">リソース名</span><span class="sxs-lookup"><span data-stu-id="3bbe2-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="3bbe2-106">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="3bbe2-106">Resource type</span></span></param>
        <param name="datasource"><span data-ttu-id="3bbe2-107">出力が書き込まれるデータ ソースをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-107">Describes the data source that output will be written to.</span></span> <span data-ttu-id="3bbe2-108">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-108">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="serialization"><span data-ttu-id="3bbe2-109">入力からのデータをシリアル化する方法または出力に書き込まれるときにデータをシリアル化する方法について説明します。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-109">Describes how data from an input is serialized or how data is serialized when written to an output.</span></span>
            <span data-ttu-id="3bbe2-110">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-110">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="diagnostics"><span data-ttu-id="3bbe2-111">顧客のアテンションを正当化する、入力、出力、または、全体的なジョブに適用可能な条件について説明します。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-111">Describes conditions applicable to the Input, Output, or the job overall, that warrant customer attention.</span></span></param>
        <param name="etag"><span data-ttu-id="3bbe2-112">出力の現在のエンティティ タグ。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-112">The current entity tag for the output.</span></span> <span data-ttu-id="3bbe2-113">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-113">This is an opaque string.</span></span> <span data-ttu-id="3bbe2-114">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-114">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="3bbe2-115">使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-115">You can also use it in the If-Match or If-None-Match headers for write operations for optimistic concurrency.</span></span></param>
        <summary>
            <span data-ttu-id="3bbe2-116">出力クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-116">Initializes a new instance of the Output class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Datasource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource Datasource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource Datasource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Output.Datasource" />
      <MemberSignature Language="VB.NET" Value="Public Property Datasource As OutputDataSource" />
      <MemberSignature Language="F#" Value="member this.Datasource : Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Output.Datasource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.datasource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bbe2-117">取得または設定する出力が書き込まれるデータ ソースをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-117">Gets or sets describes the data source that output will be written to.</span></span> <span data-ttu-id="3bbe2-118">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-118">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Diagnostics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics Diagnostics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics Diagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Output.Diagnostics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Diagnostics As Diagnostics" />
      <MemberSignature Language="F#" Value="member this.Diagnostics : Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Output.Diagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.diagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bbe2-119">顧客の注意を保証する取得は、入力、出力、または、ジョブ全体に適用可能な状態を説明します。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-119">Gets describes conditions applicable to the Input, Output, or the job overall, that warrant customer attention.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Output.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Output.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bbe2-120">出力の現在のエンティティ タグを取得します。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-120">Gets the current entity tag for the output.</span></span> <span data-ttu-id="3bbe2-121">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-121">This is an opaque string.</span></span> <span data-ttu-id="3bbe2-122">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-122">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="3bbe2-123">使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-123">You can also use it in the If-Match or If-None-Match headers for write operations for optimistic concurrency.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serialization">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.Serialization Serialization { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.Serialization Serialization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Output.Serialization" />
      <MemberSignature Language="VB.NET" Value="Public Property Serialization As Serialization" />
      <MemberSignature Language="F#" Value="member this.Serialization : Microsoft.Azure.Management.StreamAnalytics.Models.Serialization with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Output.Serialization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serialization")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Serialization</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bbe2-124">取得または設定は、入力からのデータをシリアル化する方法または出力に書き込まれるときにデータをシリアル化する方法について説明します。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-124">Gets or sets describes how data from an input is serialized or how data is serialized when written to an output.</span></span> <span data-ttu-id="3bbe2-125">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="3bbe2-125">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>