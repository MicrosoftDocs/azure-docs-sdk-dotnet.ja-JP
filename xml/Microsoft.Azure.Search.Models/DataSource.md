<Type Name="DataSource" FullName="Microsoft.Azure.Search.Models.DataSource">
  <TypeSignature Language="C#" Value="public class DataSource : Microsoft.Azure.Search.Models.IResourceWithETag" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataSource extends System.Object implements class Microsoft.Azure.Search.Models.IResourceWithETag" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class DataSource&#xA;Implements IResourceWithETag" />
  <TypeSignature Language="F#" Value="type DataSource = class&#xA;    interface IResourceWithETag" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Search.Models.IResourceWithETag</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="d10b0-101">インデクサーの構成に使用できる Azure search データソース定義を表します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-101">Represents a datasource definition in Azure Search, which can be used to configure an indexer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.#ctor" />
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
            <span data-ttu-id="d10b0-102">DataSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-102">Initializes a new instance of the DataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSource (string name, Microsoft.Azure.Search.Models.DataSourceType type, Microsoft.Azure.Search.Models.DataSourceCredentials credentials, Microsoft.Azure.Search.Models.DataContainer container, string description = null, Microsoft.Azure.Search.Models.DataChangeDetectionPolicy dataChangeDetectionPolicy = null, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy dataDeletionDetectionPolicy = null, string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Search.Models.DataSourceType type, class Microsoft.Azure.Search.Models.DataSourceCredentials credentials, class Microsoft.Azure.Search.Models.DataContainer container, string description, class Microsoft.Azure.Search.Models.DataChangeDetectionPolicy dataChangeDetectionPolicy, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy dataDeletionDetectionPolicy, string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.#ctor(System.String,Microsoft.Azure.Search.Models.DataSourceType,Microsoft.Azure.Search.Models.DataSourceCredentials,Microsoft.Azure.Search.Models.DataContainer,System.String,Microsoft.Azure.Search.Models.DataChangeDetectionPolicy,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.DataSource : string * Microsoft.Azure.Search.Models.DataSourceType * Microsoft.Azure.Search.Models.DataSourceCredentials * Microsoft.Azure.Search.Models.DataContainer * string * Microsoft.Azure.Search.Models.DataChangeDetectionPolicy * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="new Microsoft.Azure.Search.Models.DataSource (name, type, credentials, container, description, dataChangeDetectionPolicy, dataDeletionDetectionPolicy, eTag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Search.Models.DataSourceType" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Search.Models.DataSourceCredentials" />
        <Parameter Name="container" Type="Microsoft.Azure.Search.Models.DataContainer" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dataChangeDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataChangeDetectionPolicy" />
        <Parameter Name="dataDeletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d10b0-103">データ ソースの名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-103">The name of the datasource.</span></span></param>
        <param name="type"><span data-ttu-id="d10b0-104">データ ソースの種類。</span><span class="sxs-lookup"><span data-stu-id="d10b0-104">The type of the datasource.</span></span></param>
        <param name="credentials"><span data-ttu-id="d10b0-105">データ ソースの資格情報。</span><span class="sxs-lookup"><span data-stu-id="d10b0-105">Credentials for the datasource.</span></span></param>
        <param name="container"><span data-ttu-id="d10b0-106">データ ソースのデータ コンテナーです。</span><span class="sxs-lookup"><span data-stu-id="d10b0-106">The data container for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="d10b0-107">データ ソースの説明です。</span><span class="sxs-lookup"><span data-stu-id="d10b0-107">The description of the datasource.</span></span></param>
        <param name="dataChangeDetectionPolicy"><span data-ttu-id="d10b0-108">データは、データ ソースの検出ポリシーを変更します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-108">The data change detection policy for the datasource.</span></span></param>
        <param name="dataDeletionDetectionPolicy"><span data-ttu-id="d10b0-109">データ ソースのデータ削除検出ポリシー。</span><span class="sxs-lookup"><span data-stu-id="d10b0-109">The data deletion detection policy for the datasource.</span></span></param>
        <param name="eTag"><span data-ttu-id="d10b0-110">データ ソースの ETag です。</span><span class="sxs-lookup"><span data-stu-id="d10b0-110">The ETag of the DataSource.</span></span></param>
        <summary>
            <span data-ttu-id="d10b0-111">DataSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-111">Initializes a new instance of the DataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureBlobStorage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureBlobStorage (string name, string storageConnectionString, string containerName, string pathPrefix = null, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureBlobStorage(string name, string storageConnectionString, string containerName, string pathPrefix, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureBlobStorage(System.String,System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureBlobStorage (name As String, storageConnectionString As String, containerName As String, Optional pathPrefix As String = null, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureBlobStorage : string * string * string * string * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureBlobStorage (name, storageConnectionString, containerName, pathPrefix, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="pathPrefix" Type="System.String" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d10b0-112">データ ソースの名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-112">The name of the datasource.</span></span></param>
        <param name="storageConnectionString"><span data-ttu-id="d10b0-113">Azure ストレージ アカウントの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="d10b0-113">The connection string for the Azure Storage account.</span></span> <span data-ttu-id="d10b0-114">この形式に従う必要があります:"DefaultEndpointsProtocol = https;AccountName [ストレージ アカウント] を = です。AccountKey [アカウント キー] を = です"。HTTPS が必要なことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="d10b0-114">It must follow this format: "DefaultEndpointsProtocol=https;AccountName=[your storage account];AccountKey=[your account key];" Note that HTTPS is required.</span></span></param>
        <param name="containerName"><span data-ttu-id="d10b0-115">Blob の読み取り元のコンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-115">The name of the container from which to read blobs.</span></span></param>
        <param name="pathPrefix"><span data-ttu-id="d10b0-116">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-116">Optional.</span></span> <span data-ttu-id="d10b0-117">指定した場合、データ ソースはこのプレフィックスで始まる blob のみが含まれます。</span><span class="sxs-lookup"><span data-stu-id="d10b0-117">If specified, the datasource will include only blobs with names starting with this prefix.</span></span> <span data-ttu-id="d10b0-118">これは、機能は、blob はフォルダーで整理"仮想"、たとえばときに便利です。</span><span class="sxs-lookup"><span data-stu-id="d10b0-118">This is useful when blobs are organized into "virtual folders", for example.</span></span></param>
        <param name="deletionDetectionPolicy"><span data-ttu-id="d10b0-119">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-119">Optional.</span></span> <span data-ttu-id="d10b0-120">データ ソースのデータ削除検出ポリシー。</span><span class="sxs-lookup"><span data-stu-id="d10b0-120">The data deletion detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="d10b0-121">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-121">Optional.</span></span> <span data-ttu-id="d10b0-122">データ ソースの説明です。</span><span class="sxs-lookup"><span data-stu-id="d10b0-122">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="d10b0-123">Azure Blob コンテナーへの接続に新しいデータ ソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-123">Creates a new DataSource to connect to an Azure Blob container.</span></span>
            </summary>
        <returns><span data-ttu-id="d10b0-124">新しいデータ ソース インスタンス。</span><span class="sxs-lookup"><span data-stu-id="d10b0-124">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureSql">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureSql (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.DataChangeDetectionPolicy changeDetectionPolicy, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureSql(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.DataChangeDetectionPolicy changeDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureSql(System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataChangeDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureSql (name As String, sqlConnectionString As String, tableOrViewName As String, changeDetectionPolicy As DataChangeDetectionPolicy, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureSql : string * string * string * Microsoft.Azure.Search.Models.DataChangeDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureSql (name, sqlConnectionString, tableOrViewName, changeDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="changeDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataChangeDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d10b0-125">データ ソースの名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-125">The name of the datasource.</span></span></param>
        <param name="sqlConnectionString"><span data-ttu-id="d10b0-126">Azure SQL データベースの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="d10b0-126">The connection string for the Azure SQL database.</span></span></param>
        <param name="tableOrViewName"><span data-ttu-id="d10b0-127">テーブルまたはビューの行を読み取り元の名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-127">The name of the table or view from which to read rows.</span></span></param>
        <param name="changeDetectionPolicy"><span data-ttu-id="d10b0-128">データ ソースの変更検出ポリシー。</span><span class="sxs-lookup"><span data-stu-id="d10b0-128">The change detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="d10b0-129">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-129">Optional.</span></span> <span data-ttu-id="d10b0-130">データ ソースの説明です。</span><span class="sxs-lookup"><span data-stu-id="d10b0-130">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="d10b0-131">変更の検出を有効になっていると、Azure SQL データベースに接続する新しいデータ ソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-131">Creates a new DataSource to connect to an Azure SQL database with change detection enabled.</span></span>
            </summary>
        <returns><span data-ttu-id="d10b0-132">新しいデータ ソース インスタンス。</span><span class="sxs-lookup"><span data-stu-id="d10b0-132">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureSql">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureSql (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureSql(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureSql(System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureSql (name As String, sqlConnectionString As String, tableOrViewName As String, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureSql : string * string * string * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureSql (name, sqlConnectionString, tableOrViewName, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d10b0-133">データ ソースの名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-133">The name of the datasource.</span></span></param>
        <param name="sqlConnectionString"><span data-ttu-id="d10b0-134">Azure SQL データベースの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="d10b0-134">The connection string for the Azure SQL database.</span></span></param>
        <param name="tableOrViewName"><span data-ttu-id="d10b0-135">テーブルまたはビューの行を読み取り元の名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-135">The name of the table or view from which to read rows.</span></span></param>
        <param name="deletionDetectionPolicy"><span data-ttu-id="d10b0-136">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-136">Optional.</span></span> <span data-ttu-id="d10b0-137">データ ソースのデータ削除検出ポリシー。</span><span class="sxs-lookup"><span data-stu-id="d10b0-137">The data deletion detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="d10b0-138">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-138">Optional.</span></span> <span data-ttu-id="d10b0-139">データ ソースの説明です。</span><span class="sxs-lookup"><span data-stu-id="d10b0-139">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="d10b0-140">Azure SQL データベースへの接続に新しいデータ ソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-140">Creates a new DataSource to connect to an Azure SQL database.</span></span>
            </summary>
        <returns><span data-ttu-id="d10b0-141">新しいデータ ソース インスタンス。</span><span class="sxs-lookup"><span data-stu-id="d10b0-141">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureSql">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureSql (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy changeDetectionPolicy, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureSql(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy changeDetectionPolicy, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureSql(System.String,System.String,System.String,Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureSql (name As String, sqlConnectionString As String, tableOrViewName As String, changeDetectionPolicy As HighWaterMarkChangeDetectionPolicy, deletionDetectionPolicy As DataDeletionDetectionPolicy, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureSql : string * string * string * Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureSql (name, sqlConnectionString, tableOrViewName, changeDetectionPolicy, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="changeDetectionPolicy" Type="Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d10b0-142">データ ソースの名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-142">The name of the datasource.</span></span></param>
        <param name="sqlConnectionString"><span data-ttu-id="d10b0-143">Azure SQL データベースの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="d10b0-143">The connection string for the Azure SQL database.</span></span></param>
        <param name="tableOrViewName"><span data-ttu-id="d10b0-144">テーブルまたはビューの行を読み取り元の名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-144">The name of the table or view from which to read rows.</span></span></param>
        <param name="changeDetectionPolicy"><span data-ttu-id="d10b0-145">データ ソースの変更検出ポリシー。</span><span class="sxs-lookup"><span data-stu-id="d10b0-145">The change detection policy for the datasource.</span></span> <span data-ttu-id="d10b0-146">削除の検出が有効になっている場合は、そののみ高基準値変更検出を Azure SQL の許可します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-146">Note that only high watermark change detection is allowed for Azure SQL when deletion detection is enabled.</span></span></param>
        <param name="deletionDetectionPolicy"><span data-ttu-id="d10b0-147">データ ソースのデータ削除検出ポリシー。</span><span class="sxs-lookup"><span data-stu-id="d10b0-147">The data deletion detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="d10b0-148">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-148">Optional.</span></span> <span data-ttu-id="d10b0-149">データ ソースの説明です。</span><span class="sxs-lookup"><span data-stu-id="d10b0-149">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="d10b0-150">変更の検出と削除の検出が有効な Azure SQL データベースへの接続に新しいデータ ソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-150">Creates a new DataSource to connect to an Azure SQL database with change detection and deletion detection enabled.</span></span>
            </summary>
        <returns><span data-ttu-id="d10b0-151">新しいデータ ソース インスタンス。</span><span class="sxs-lookup"><span data-stu-id="d10b0-151">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableStorage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureTableStorage (string name, string storageConnectionString, string tableName, string query = null, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureTableStorage(string name, string storageConnectionString, string tableName, string query, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureTableStorage(System.String,System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureTableStorage (name As String, storageConnectionString As String, tableName As String, Optional query As String = null, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureTableStorage : string * string * string * string * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureTableStorage (name, storageConnectionString, tableName, query, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d10b0-152">データ ソースの名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-152">The name of the datasource.</span></span></param>
        <param name="storageConnectionString"><span data-ttu-id="d10b0-153">Azure ストレージ アカウントの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="d10b0-153">The connection string for the Azure Storage account.</span></span> <span data-ttu-id="d10b0-154">この形式に従う必要があります:"DefaultEndpointsProtocol = https;AccountName [ストレージ アカウント] を = です。AccountKey [アカウント キー] を = です"。HTTPS が必要なことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="d10b0-154">It must follow this format: "DefaultEndpointsProtocol=https;AccountName=[your storage account];AccountKey=[your account key];" Note that HTTPS is required.</span></span></param>
        <param name="tableName"><span data-ttu-id="d10b0-155">行の読み込み元のテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-155">The name of the table from which to read rows.</span></span></param>
        <param name="query"><span data-ttu-id="d10b0-156">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-156">Optional.</span></span> <span data-ttu-id="d10b0-157">行を読み取るときに、テーブルに適用されるクエリ。</span><span class="sxs-lookup"><span data-stu-id="d10b0-157">A query that is applied to the table when reading rows.</span></span></param>
        <param name="deletionDetectionPolicy"><span data-ttu-id="d10b0-158">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-158">Optional.</span></span> <span data-ttu-id="d10b0-159">データ ソースのデータ削除検出ポリシー。</span><span class="sxs-lookup"><span data-stu-id="d10b0-159">The data deletion detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="d10b0-160">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-160">Optional.</span></span> <span data-ttu-id="d10b0-161">データ ソースの説明です。</span><span class="sxs-lookup"><span data-stu-id="d10b0-161">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="d10b0-162">Azure テーブルへの接続に新しいデータ ソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-162">Creates a new DataSource to connect to an Azure Table.</span></span>
            </summary>
        <returns><span data-ttu-id="d10b0-163">新しいデータ ソース インスタンス。</span><span class="sxs-lookup"><span data-stu-id="d10b0-163">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataContainer Container { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataContainer Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Container" />
      <MemberSignature Language="VB.NET" Value="Public Property Container As DataContainer" />
      <MemberSignature Language="F#" Value="member this.Container : Microsoft.Azure.Search.Models.DataContainer with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="container")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataContainer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d10b0-164">取得またはデータ ソースのデータ コンテナーを設定します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-164">Gets or sets the data container for the datasource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataSourceCredentials Credentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataSourceCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public Property Credentials As DataSourceCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.Search.Models.DataSourceCredentials with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="credentials")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSourceCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d10b0-165">取得またはデータ ソースの資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-165">Gets or sets credentials for the datasource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataChangeDetectionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataChangeDetectionPolicy DataChangeDetectionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataChangeDetectionPolicy DataChangeDetectionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.DataChangeDetectionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property DataChangeDetectionPolicy As DataChangeDetectionPolicy" />
      <MemberSignature Language="F#" Value="member this.DataChangeDetectionPolicy : Microsoft.Azure.Search.Models.DataChangeDetectionPolicy with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.DataChangeDetectionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataChangeDetectionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataChangeDetectionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d10b0-166">取得またはデータ ソースのデータ変更検出ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-166">Gets or sets the data change detection policy for the datasource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDeletionDetectionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy DataDeletionDetectionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy DataDeletionDetectionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.DataDeletionDetectionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDeletionDetectionPolicy As DataDeletionDetectionPolicy" />
      <MemberSignature Language="F#" Value="member this.DataDeletionDetectionPolicy : Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.DataDeletionDetectionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataDeletionDetectionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d10b0-167">取得またはデータ ソースのデータ削除検出ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-167">Gets or sets the data deletion detection policy for the datasource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="d10b0-168">取得またはデータ ソースの説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-168">Gets or sets the description of the datasource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DocumentDb">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource DocumentDb (string name, string documentDbConnectionString, string collectionName, string query = null, bool useChangeDetection = true, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource DocumentDb(string name, string documentDbConnectionString, string collectionName, string query, bool useChangeDetection, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.DocumentDb(System.String,System.String,System.String,System.String,System.Boolean,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DocumentDb (name As String, documentDbConnectionString As String, collectionName As String, Optional query As String = null, Optional useChangeDetection As Boolean = true, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member DocumentDb : string * string * string * string * bool * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.DocumentDb (name, documentDbConnectionString, collectionName, query, useChangeDetection, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="documentDbConnectionString" Type="System.String" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="useChangeDetection" Type="System.Boolean" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d10b0-169">データ ソースの名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-169">The name of the datasource.</span></span></param>
        <param name="documentDbConnectionString"><span data-ttu-id="d10b0-170">DocumentDb データベースの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="d10b0-170">The connection string for the DocumentDb database.</span></span> <span data-ttu-id="d10b0-171">この形式に従う必要があります:"AccountName |AccountEndpoint [アカウント名またはエンドポイント] を = です。AccountKey [アカウント キー] を =; Database = [データベース名]"</span><span class="sxs-lookup"><span data-stu-id="d10b0-171">It must follow this format: "AccountName|AccountEndpoint=[your account name or endpoint];AccountKey=[your account key];Database=[your database name]"</span></span></param>
        <param name="collectionName"><span data-ttu-id="d10b0-172">ドキュメントを読み取り元のコレクションの名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-172">The name of the collection from which to read documents.</span></span></param>
        <param name="query"><span data-ttu-id="d10b0-173">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-173">Optional.</span></span> <span data-ttu-id="d10b0-174">ドキュメントを読み取るときに、コレクションに適用されるクエリ。</span><span class="sxs-lookup"><span data-stu-id="d10b0-174">A query that is applied to the collection when reading documents.</span></span></param>
        <param name="useChangeDetection"><span data-ttu-id="d10b0-175">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-175">Optional.</span></span> <span data-ttu-id="d10b0-176">インデックスを作成するときに、変更の検出を使用するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-176">Indicates whether to use change detection when indexing.</span></span> <span data-ttu-id="d10b0-177">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="d10b0-177">Default is true.</span></span></param>
        <param name="deletionDetectionPolicy"><span data-ttu-id="d10b0-178">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-178">Optional.</span></span> <span data-ttu-id="d10b0-179">データ ソースのデータ削除検出ポリシー。</span><span class="sxs-lookup"><span data-stu-id="d10b0-179">The data deletion detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="d10b0-180">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-180">Optional.</span></span> <span data-ttu-id="d10b0-181">データ ソースの説明です。</span><span class="sxs-lookup"><span data-stu-id="d10b0-181">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="d10b0-182">DocumentDb データベースへの接続に新しいデータ ソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-182">Creates a new DataSource to connect to a DocumentDb database.</span></span>
            </summary>
        <returns><span data-ttu-id="d10b0-183">新しいデータ ソース インスタンス。</span><span class="sxs-lookup"><span data-stu-id="d10b0-183">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="@odata.etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d10b0-184">取得またはデータ ソースの ETag を設定します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-184">Gets or sets the ETag of the DataSource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d10b0-185">取得またはデータ ソースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-185">Gets or sets the name of the datasource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerOnAzureVM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.DataChangeDetectionPolicy changeDetectionPolicy, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.DataChangeDetectionPolicy changeDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM(System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataChangeDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlServerOnAzureVM (name As String, sqlConnectionString As String, tableOrViewName As String, changeDetectionPolicy As DataChangeDetectionPolicy, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member SqlServerOnAzureVM : string * string * string * Microsoft.Azure.Search.Models.DataChangeDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM (name, sqlConnectionString, tableOrViewName, changeDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="changeDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataChangeDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d10b0-186">データ ソースの名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-186">The name of the datasource.</span></span></param>
        <param name="sqlConnectionString"><span data-ttu-id="d10b0-187">SQL Server データベースの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="d10b0-187">The connection string for the SQL Server database.</span></span></param>
        <param name="tableOrViewName"><span data-ttu-id="d10b0-188">テーブルまたはビューの行を読み取り元の名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-188">The name of the table or view from which to read rows.</span></span></param>
        <param name="changeDetectionPolicy"><span data-ttu-id="d10b0-189">データ ソースの変更検出ポリシー。</span><span class="sxs-lookup"><span data-stu-id="d10b0-189">The change detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="d10b0-190">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-190">Optional.</span></span> <span data-ttu-id="d10b0-191">データ ソースの説明です。</span><span class="sxs-lookup"><span data-stu-id="d10b0-191">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="d10b0-192">変更の検出を有効になっていると、VM でホストされる SQL Server データベースに接続する新しいデータ ソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-192">Creates a new DataSource to connect to a VM-hosted SQL Server database with change detection enabled.</span></span>
            </summary>
        <returns><span data-ttu-id="d10b0-193">新しいデータ ソース インスタンス。</span><span class="sxs-lookup"><span data-stu-id="d10b0-193">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerOnAzureVM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM(System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlServerOnAzureVM (name As String, sqlConnectionString As String, tableOrViewName As String, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member SqlServerOnAzureVM : string * string * string * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM (name, sqlConnectionString, tableOrViewName, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d10b0-194">データ ソースの名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-194">The name of the datasource.</span></span></param>
        <param name="sqlConnectionString"><span data-ttu-id="d10b0-195">SQL Server データベースの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="d10b0-195">The connection string for the SQL Server database.</span></span></param>
        <param name="tableOrViewName"><span data-ttu-id="d10b0-196">テーブルまたはビューの行を読み取り元の名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-196">The name of the table or view from which to read rows.</span></span></param>
        <param name="deletionDetectionPolicy"><span data-ttu-id="d10b0-197">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-197">Optional.</span></span> <span data-ttu-id="d10b0-198">データ ソースのデータ削除検出ポリシー。</span><span class="sxs-lookup"><span data-stu-id="d10b0-198">The data deletion detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="d10b0-199">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-199">Optional.</span></span> <span data-ttu-id="d10b0-200">データ ソースの説明です。</span><span class="sxs-lookup"><span data-stu-id="d10b0-200">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="d10b0-201">VM でホストされる SQL Server データベースに接続する新しいデータ ソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-201">Creates a new DataSource to connect to a VM-hosted SQL Server database.</span></span>
            </summary>
        <returns><span data-ttu-id="d10b0-202">新しいデータ ソース インスタンス。</span><span class="sxs-lookup"><span data-stu-id="d10b0-202">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerOnAzureVM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy changeDetectionPolicy, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy changeDetectionPolicy, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM(System.String,System.String,System.String,Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlServerOnAzureVM (name As String, sqlConnectionString As String, tableOrViewName As String, changeDetectionPolicy As HighWaterMarkChangeDetectionPolicy, deletionDetectionPolicy As DataDeletionDetectionPolicy, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member SqlServerOnAzureVM : string * string * string * Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM (name, sqlConnectionString, tableOrViewName, changeDetectionPolicy, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="changeDetectionPolicy" Type="Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d10b0-203">データ ソースの名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-203">The name of the datasource.</span></span></param>
        <param name="sqlConnectionString"><span data-ttu-id="d10b0-204">SQL Server データベースの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="d10b0-204">The connection string for the SQL Server database.</span></span></param>
        <param name="tableOrViewName"><span data-ttu-id="d10b0-205">テーブルまたはビューの行を読み取り元の名前。</span><span class="sxs-lookup"><span data-stu-id="d10b0-205">The name of the table or view from which to read rows.</span></span></param>
        <param name="changeDetectionPolicy"><span data-ttu-id="d10b0-206">データ ソースの変更検出ポリシー。</span><span class="sxs-lookup"><span data-stu-id="d10b0-206">The change detection policy for the datasource.</span></span> <span data-ttu-id="d10b0-207">削除の検出が有効になっている場合は、そののみ高基準値変更検出を SQL Server の許可します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-207">Note that only high watermark change detection is allowed for SQL Server when deletion detection is enabled.</span></span></param>
        <param name="deletionDetectionPolicy"><span data-ttu-id="d10b0-208">データ ソースのデータ削除検出ポリシー。</span><span class="sxs-lookup"><span data-stu-id="d10b0-208">The data deletion detection policy for the datasource.</span></span></param>
        <param name="description"><span data-ttu-id="d10b0-209">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d10b0-209">Optional.</span></span> <span data-ttu-id="d10b0-210">データ ソースの説明です。</span><span class="sxs-lookup"><span data-stu-id="d10b0-210">Description of the datasource.</span></span></param>
        <summary>
            <span data-ttu-id="d10b0-211">変更の検出と削除の検出を有効になっている VM でホストされる SQL Server データベースに接続する新しいデータ ソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-211">Creates a new DataSource to connect to a VM-hosted SQL Server database with change detection and deletion detection enabled.</span></span>
            </summary>
        <returns><span data-ttu-id="d10b0-212">新しいデータ ソース インスタンス。</span><span class="sxs-lookup"><span data-stu-id="d10b0-212">A new DataSource instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataSourceType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataSourceType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As DataSourceType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Search.Models.DataSourceType with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSourceType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d10b0-213">取得またはデータ ソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-213">Gets or sets the type of the datasource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataSource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d10b0-214">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="d10b0-214">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d10b0-215">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d10b0-215">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>