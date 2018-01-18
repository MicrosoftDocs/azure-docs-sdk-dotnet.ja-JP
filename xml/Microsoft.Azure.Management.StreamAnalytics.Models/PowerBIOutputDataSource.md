<Type Name="PowerBIOutputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource">
  <TypeSignature Language="C#" Value="public class PowerBIOutputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PowerBIOutputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class PowerBIOutputDataSource&#xA;Inherits OutputDataSource" />
  <TypeSignature Language="F#" Value="type PowerBIOutputDataSource = class&#xA;    inherit OutputDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("PowerBI")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a4b20-101">Power BI 出力のデータ ソースをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="a4b20-101">Describes a Power BI output data source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PowerBIOutputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a4b20-102">PowerBIOutputDataSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a4b20-102">Initializes a new instance of the PowerBIOutputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PowerBIOutputDataSource (string refreshToken = null, string tokenUserPrincipalName = null, string tokenUserDisplayName = null, string dataset = null, string table = null, string groupId = null, string groupName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string refreshToken, string tokenUserPrincipalName, string tokenUserDisplayName, string dataset, string table, string groupId, string groupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional refreshToken As String = null, Optional tokenUserPrincipalName As String = null, Optional tokenUserDisplayName As String = null, Optional dataset As String = null, Optional table As String = null, Optional groupId As String = null, Optional groupName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource (refreshToken, tokenUserPrincipalName, tokenUserDisplayName, dataset, table, groupId, groupName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="refreshToken" Type="System.String" />
        <Parameter Name="tokenUserPrincipalName" Type="System.String" />
        <Parameter Name="tokenUserDisplayName" Type="System.String" />
        <Parameter Name="dataset" Type="System.String" />
        <Parameter Name="table" Type="System.String" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="groupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="refreshToken"><span data-ttu-id="a4b20-103">データ ソースに認証するために使用する有効なアクセス トークンの取得に使用できる更新トークンです。</span><span class="sxs-lookup"><span data-stu-id="a4b20-103">A refresh token that can be used to obtain a valid access token that can then be used to authenticate with the data source.</span></span> <span data-ttu-id="a4b20-104">有効な更新トークンは、現在、Azure ポータル経由で取得できのみです。</span><span class="sxs-lookup"><span data-stu-id="a4b20-104">A valid refresh token is currently only obtainable via the Azure Portal.</span></span> <span data-ttu-id="a4b20-105">データ ソースと有効な更新トークンを使用してこのプロパティを更新する必要があるデータ ソースの認証に Azure ポータルに、継続を作成するときに、ダミーの文字列値をここに記述することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="a4b20-105">It is recommended to put a dummy string value here when creating the data source and then going to the Azure Portal to authenticate the data source which will update this property with a valid refresh token.</span></span> <span data-ttu-id="a4b20-106">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="a4b20-106">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="tokenUserPrincipalName"><span data-ttu-id="a4b20-107">ユーザー プリンシパル名 (UPN)、更新トークンを取得するために使用されたユーザーのです。</span><span class="sxs-lookup"><span data-stu-id="a4b20-107">The user principal name (UPN) of the user that was used to obtain the refresh token.</span></span> <span data-ttu-id="a4b20-108">このプロパティを使用して、ヘルプのユーザーが更新トークンの取得に使用されたに注意してください。</span><span class="sxs-lookup"><span data-stu-id="a4b20-108">Use this property to help remember which user was used to obtain the refresh token.</span></span></param>
        <param name="tokenUserDisplayName"><span data-ttu-id="a4b20-109">更新トークンを取得するために使用されたユーザーのユーザーの表示名。</span><span class="sxs-lookup"><span data-stu-id="a4b20-109">The user display name of the user that was used to obtain the refresh token.</span></span> <span data-ttu-id="a4b20-110">このプロパティを使用して、ヘルプのユーザーが更新トークンの取得に使用されたに注意してください。</span><span class="sxs-lookup"><span data-stu-id="a4b20-110">Use this property to help remember which user was used to obtain the refresh token.</span></span></param>
        <param name="dataset"><span data-ttu-id="a4b20-111">Power BI データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="a4b20-111">The name of the Power BI dataset.</span></span> <span data-ttu-id="a4b20-112">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="a4b20-112">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="table"><span data-ttu-id="a4b20-113">指定されたデータセットで Power BI テーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="a4b20-113">The name of the Power BI table under the specified dataset.</span></span> <span data-ttu-id="a4b20-114">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="a4b20-114">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="groupId"><span data-ttu-id="a4b20-115">Power BI グループの ID。</span><span class="sxs-lookup"><span data-stu-id="a4b20-115">The ID of the Power BI group.</span></span></param>
        <param name="groupName"><span data-ttu-id="a4b20-116">Power BI グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a4b20-116">The name of the Power BI group.</span></span> <span data-ttu-id="a4b20-117">このプロパティを使用して、支援する特定の Power BI グループ id の使用に注意してください。</span><span class="sxs-lookup"><span data-stu-id="a4b20-117">Use this property to help remember which specific Power BI group id was used.</span></span></param>
        <summary>
            <span data-ttu-id="a4b20-118">PowerBIOutputDataSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a4b20-118">Initializes a new instance of the PowerBIOutputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dataset">
      <MemberSignature Language="C#" Value="public string Dataset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Dataset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.Dataset" />
      <MemberSignature Language="VB.NET" Value="Public Property Dataset As String" />
      <MemberSignature Language="F#" Value="member this.Dataset : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.Dataset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a4b20-119">取得または Power BI のデータセットの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="a4b20-119">Gets or sets the name of the Power BI dataset.</span></span> <span data-ttu-id="a4b20-120">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="a4b20-120">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GroupId">
      <MemberSignature Language="C#" Value="public string GroupId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GroupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.GroupId" />
      <MemberSignature Language="VB.NET" Value="Public Property GroupId As String" />
      <MemberSignature Language="F#" Value="member this.GroupId : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.GroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.groupId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a4b20-121">取得または Power BI グループの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="a4b20-121">Gets or sets the ID of the Power BI group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GroupName">
      <MemberSignature Language="C#" Value="public string GroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.GroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property GroupName As String" />
      <MemberSignature Language="F#" Value="member this.GroupName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.GroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.groupName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a4b20-122">取得または Power BI グループの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="a4b20-122">Gets or sets the name of the Power BI group.</span></span> <span data-ttu-id="a4b20-123">このプロパティを使用して、支援する特定の Power BI グループ id の使用に注意してください。</span><span class="sxs-lookup"><span data-stu-id="a4b20-123">Use this property to help remember which specific Power BI group id was used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshToken">
      <MemberSignature Language="C#" Value="public string RefreshToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RefreshToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.RefreshToken" />
      <MemberSignature Language="VB.NET" Value="Public Property RefreshToken As String" />
      <MemberSignature Language="F#" Value="member this.RefreshToken : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.RefreshToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.refreshToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a4b20-124">取得またはデータ ソースに認証するために使用する有効なアクセス トークンの取得に使用できる更新トークンを設定します。</span><span class="sxs-lookup"><span data-stu-id="a4b20-124">Gets or sets a refresh token that can be used to obtain a valid access token that can then be used to authenticate with the data source.</span></span> <span data-ttu-id="a4b20-125">有効な更新トークンは、現在、Azure ポータル経由で取得できのみです。</span><span class="sxs-lookup"><span data-stu-id="a4b20-125">A valid refresh token is currently only obtainable via the Azure Portal.</span></span> <span data-ttu-id="a4b20-126">データ ソースと有効な更新トークンを使用してこのプロパティを更新する必要があるデータ ソースの認証に Azure ポータルに、継続を作成するときに、ダミーの文字列値をここに記述することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="a4b20-126">It is recommended to put a dummy string value here when creating the data source and then going to the Azure Portal to authenticate the data source which will update this property with a valid refresh token.</span></span> <span data-ttu-id="a4b20-127">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="a4b20-127">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Table">
      <MemberSignature Language="C#" Value="public string Table { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Table" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.Table" />
      <MemberSignature Language="VB.NET" Value="Public Property Table As String" />
      <MemberSignature Language="F#" Value="member this.Table : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.Table" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.table")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a4b20-128">取得または指定されたデータセットで Power BI テーブルの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="a4b20-128">Gets or sets the name of the Power BI table under the specified dataset.</span></span> <span data-ttu-id="a4b20-129">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="a4b20-129">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenUserDisplayName">
      <MemberSignature Language="C#" Value="public string TokenUserDisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenUserDisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.TokenUserDisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenUserDisplayName As String" />
      <MemberSignature Language="F#" Value="member this.TokenUserDisplayName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.TokenUserDisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tokenUserDisplayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a4b20-130">取得または更新トークンを取得するために使用されたユーザーのユーザーの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="a4b20-130">Gets or sets the user display name of the user that was used to obtain the refresh token.</span></span> <span data-ttu-id="a4b20-131">このプロパティを使用して、ヘルプのユーザーが更新トークンの取得に使用されたに注意してください。</span><span class="sxs-lookup"><span data-stu-id="a4b20-131">Use this property to help remember which user was used to obtain the refresh token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenUserPrincipalName">
      <MemberSignature Language="C#" Value="public string TokenUserPrincipalName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenUserPrincipalName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.TokenUserPrincipalName" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenUserPrincipalName As String" />
      <MemberSignature Language="F#" Value="member this.TokenUserPrincipalName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.TokenUserPrincipalName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tokenUserPrincipalName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a4b20-132">取得または更新トークンを取得するために使用されたユーザーのユーザー プリンシパル名 (UPN) を設定します。</span><span class="sxs-lookup"><span data-stu-id="a4b20-132">Gets or sets the user principal name (UPN) of the user that was used to obtain the refresh token.</span></span> <span data-ttu-id="a4b20-133">このプロパティを使用して、ヘルプのユーザーが更新トークンの取得に使用されたに注意してください。</span><span class="sxs-lookup"><span data-stu-id="a4b20-133">Use this property to help remember which user was used to obtain the refresh token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>