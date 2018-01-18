<Type Name="InputProperties" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties">
  <TypeSignature Language="C#" Value="public class InputProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InputProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class InputProperties" />
  <TypeSignature Language="F#" Value="type InputProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cd35d-101">入力に関連付けられているプロパティです。</span><span class="sxs-lookup"><span data-stu-id="cd35d-101">The properties that are associated with an input.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InputProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cd35d-102">InputProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cd35d-102">Initializes a new instance of the InputProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InputProperties (Microsoft.Azure.Management.StreamAnalytics.Models.Serialization serialization = null, Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics diagnostics = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StreamAnalytics.Models.Serialization serialization, class Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics diagnostics, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.#ctor(Microsoft.Azure.Management.StreamAnalytics.Models.Serialization,Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties : Microsoft.Azure.Management.StreamAnalytics.Models.Serialization * Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties (serialization, diagnostics, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serialization" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Serialization" />
        <Parameter Name="diagnostics" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serialization"><span data-ttu-id="cd35d-103">入力からのデータをシリアル化する方法または出力に書き込まれるときにデータをシリアル化する方法について説明します。</span><span class="sxs-lookup"><span data-stu-id="cd35d-103">Describes how data from an input is serialized or how data is serialized when written to an output.</span></span>
            <span data-ttu-id="cd35d-104">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="cd35d-104">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="diagnostics"><span data-ttu-id="cd35d-105">顧客のアテンションを正当化する、入力、出力、または、全体的なジョブに適用可能な条件について説明します。</span><span class="sxs-lookup"><span data-stu-id="cd35d-105">Describes conditions applicable to the Input, Output, or the job overall, that warrant customer attention.</span></span></param>
        <param name="etag"><span data-ttu-id="cd35d-106">入力の現在のエンティティ タグ。</span><span class="sxs-lookup"><span data-stu-id="cd35d-106">The current entity tag for the input.</span></span> <span data-ttu-id="cd35d-107">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="cd35d-107">This is an opaque string.</span></span> <span data-ttu-id="cd35d-108">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="cd35d-108">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="cd35d-109">使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。</span><span class="sxs-lookup"><span data-stu-id="cd35d-109">You can also use it in the If-Match or If-None-Match headers for write operations for optimistic concurrency.</span></span></param>
        <summary>
            <span data-ttu-id="cd35d-110">InputProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cd35d-110">Initializes a new instance of the InputProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Diagnostics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics Diagnostics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics Diagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Diagnostics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Diagnostics As Diagnostics" />
      <MemberSignature Language="F#" Value="member this.Diagnostics : Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Diagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cd35d-111">顧客の注意を保証する取得は、入力、出力、または、ジョブ全体に適用可能な状態を説明します。</span><span class="sxs-lookup"><span data-stu-id="cd35d-111">Gets describes conditions applicable to the Input, Output, or the job overall, that warrant customer attention.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cd35d-112">入力の現在のエンティティ タグを取得します。</span><span class="sxs-lookup"><span data-stu-id="cd35d-112">Gets the current entity tag for the input.</span></span> <span data-ttu-id="cd35d-113">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="cd35d-113">This is an opaque string.</span></span> <span data-ttu-id="cd35d-114">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="cd35d-114">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="cd35d-115">使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。</span><span class="sxs-lookup"><span data-stu-id="cd35d-115">You can also use it in the If-Match or If-None-Match headers for write operations for optimistic concurrency.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serialization">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.Serialization Serialization { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.Serialization Serialization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Serialization" />
      <MemberSignature Language="VB.NET" Value="Public Property Serialization As Serialization" />
      <MemberSignature Language="F#" Value="member this.Serialization : Microsoft.Azure.Management.StreamAnalytics.Models.Serialization with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties.Serialization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serialization")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Serialization</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cd35d-116">取得または設定は、入力からのデータをシリアル化する方法または出力に書き込まれるときにデータをシリアル化する方法について説明します。</span><span class="sxs-lookup"><span data-stu-id="cd35d-116">Gets or sets describes how data from an input is serialized or how data is serialized when written to an output.</span></span> <span data-ttu-id="cd35d-117">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="cd35d-117">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>