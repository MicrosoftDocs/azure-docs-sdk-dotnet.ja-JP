<Type Name="AvailableProviderOperationDisplay" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay">
  <TypeSignature Language="C#" Value="public class AvailableProviderOperationDisplay" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AvailableProviderOperationDisplay extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay" />
  <TypeSignature Language="VB.NET" Value="Public Class AvailableProviderOperationDisplay" />
  <TypeSignature Language="F#" Value="type AvailableProviderOperationDisplay = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="addfb-101">この特定の操作/アクションのローカライズされた表示情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="addfb-101">Contains the localized display information for this particular operation/action.</span></span> <span data-ttu-id="addfb-102">これらの値は、(a) は、カスタムのロールの定義では、RBAC イベント サービスと (c) 監査履歴/レコードの管理操作用の (b) 複雑なクエリ フィルターの複数のクライアントによって使用されます。</span><span class="sxs-lookup"><span data-stu-id="addfb-102">These value will be used by several clients for (a) custom role definitions for RBAC, (b) complex query filters for the event service and (c) audit history/records for management operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProviderOperationDisplay ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="addfb-103">AvailableProviderOperationDisplay クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="addfb-103">Initializes a new instance of the AvailableProviderOperationDisplay class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProviderOperationDisplay (string provider = null, string resource = null, string operation = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string provider, string resource, string operation, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional provider As String = null, Optional resource As String = null, Optional operation As String = null, Optional description As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay : string * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay (provider, resource, operation, description)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="provider"><span data-ttu-id="addfb-104">ローカライズされた表示形式、リソース プロバイダー名前のことが期待されても、パブリッシャー/担当会社が含まれます。</span><span class="sxs-lookup"><span data-stu-id="addfb-104">The localized friendly form of the resource provider name - it is expected to also include the publisher/company responsible.</span></span> <span data-ttu-id="addfb-105">タイトルの大文字と小文字を使用して、ファースト パーティのサービスの 'Microsoft' で始まるし、必要があります。</span><span class="sxs-lookup"><span data-stu-id="addfb-105">It should use Title Casing and begin with 'Microsoft' for 1st party services.</span></span></param>
        <param name="resource"><span data-ttu-id="addfb-106">このアクション/操作 - に関連するリソースの種類のローカライズされた表示形式にリソース プロバイダーのパブリックのドキュメントを一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="addfb-106">The localized friendly form of the resource type related to this action/operation - it should match the public documentation for the resource provider.</span></span> <span data-ttu-id="addfb-107">タイトルの大文字と小文字を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="addfb-107">It should use Title Casing</span></span>
            - <span data-ttu-id="addfb-108">例については、'name' セクションを参照してください。</span><span class="sxs-lookup"><span data-stu-id="addfb-108">for examples, please refer to the 'name' section.</span></span></param>
        <param name="operation"><span data-ttu-id="addfb-109">操作のローカライズされた表示名は、ユーザーに表示する必要があります。</span><span class="sxs-lookup"><span data-stu-id="addfb-109">The localized friendly name for the operation, as it should be shown to the user.</span></span> <span data-ttu-id="addfb-110">(ドロップダウン リストに収まる) に簡潔なが (つまり自己文書化) がオフになります。</span><span class="sxs-lookup"><span data-stu-id="addfb-110">It should be concise (to fit in drop downs) but clear (i.e. self-documenting).</span></span> <span data-ttu-id="addfb-111">タイトルの大文字と小文字を使用し、それを適用するエンティティ/リソースを含めるか。</span><span class="sxs-lookup"><span data-stu-id="addfb-111">It should use Title Casing and include the entity/resource to which it applies.</span></span></param>
        <param name="description"><span data-ttu-id="addfb-112">操作のローカライズされたわかりやすい説明は、ユーザーを表示する必要があります。</span><span class="sxs-lookup"><span data-stu-id="addfb-112">The localized friendly description for the operation, as it should be shown to the user.</span></span> <span data-ttu-id="addfb-113">で包括的なことがまだ簡潔なのツール ヒントで使用され、詳細なビューです。</span><span class="sxs-lookup"><span data-stu-id="addfb-113">It should be thorough, yet concise - it will be used in tool tips and detailed views.</span></span></param>
        <summary>
            <span data-ttu-id="addfb-114">AvailableProviderOperationDisplay クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="addfb-114">Initializes a new instance of the AvailableProviderOperationDisplay class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="addfb-115">取得またはユーザーに表示するか、操作のローカライズされたわかりやすい説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="addfb-115">Gets or sets the localized friendly description for the operation, as it should be shown to the user.</span></span> <span data-ttu-id="addfb-116">で包括的なことがまだ簡潔なのツール ヒントで使用され、詳細なビューです。</span><span class="sxs-lookup"><span data-stu-id="addfb-116">It should be thorough, yet concise - it will be used in tool tips and detailed views.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public string Operation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Operation" />
      <MemberSignature Language="VB.NET" Value="Public Property Operation As String" />
      <MemberSignature Language="F#" Value="member this.Operation : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="addfb-117">取得またはユーザーに表示するか、操作のローカライズされた表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="addfb-117">Gets or sets the localized friendly name for the operation, as it should be shown to the user.</span></span> <span data-ttu-id="addfb-118">(ドロップダウン リストに収まる) に簡潔なが (つまり自己文書化) がオフになります。</span><span class="sxs-lookup"><span data-stu-id="addfb-118">It should be concise (to fit in drop downs) but clear (i.e. self-documenting).</span></span> <span data-ttu-id="addfb-119">タイトルの大文字と小文字を使用し、それを適用するエンティティ/リソースを含めるか。</span><span class="sxs-lookup"><span data-stu-id="addfb-119">It should use Title Casing and include the entity/resource to which it applies.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="addfb-120">取得またはローカライズされた表示形式を設定、リソース プロバイダー名前のことが期待されても、パブリッシャー/担当会社が含まれます。</span><span class="sxs-lookup"><span data-stu-id="addfb-120">Gets or sets the localized friendly form of the resource provider name - it is expected to also include the publisher/company responsible.</span></span> <span data-ttu-id="addfb-121">タイトルの大文字と小文字を使用して、ファースト パーティのサービスの 'Microsoft' で始まるし、必要があります。</span><span class="sxs-lookup"><span data-stu-id="addfb-121">It should use Title Casing and begin with 'Microsoft' for 1st party services.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resource">
      <MemberSignature Language="C#" Value="public string Resource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Resource" />
      <MemberSignature Language="VB.NET" Value="Public Property Resource As String" />
      <MemberSignature Language="F#" Value="member this.Resource : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Resource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="addfb-122">このアクション/操作 - に関連するリソースの種類のローカライズされた表示形式を取得または設定は、リソース プロバイダーのパブリックのドキュメントに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="addfb-122">Gets or sets the localized friendly form of the resource type related to this action/operation - it should match the public documentation for the resource provider.</span></span> <span data-ttu-id="addfb-123">タイトルの大文字と小文字を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="addfb-123">It should use Title Casing</span></span>
            - <span data-ttu-id="addfb-124">例については、'name' セクションを参照してください。</span><span class="sxs-lookup"><span data-stu-id="addfb-124">for examples, please refer to the 'name' section.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>