<Type Name="DataFactoryOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataFactoryOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataFactoryOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataFactoryOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataFactoryOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse BeginCreateOrUpdate (this Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName, Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse BeginCreateOrUpdate(class Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName, class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.DataFactories.IDataFactoryOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IDataFactoryOperations, resourceGroupName As String, parameters As DataFactoryCreateOrUpdateParameters) As DataFactoryCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.DataFactories.IDataFactoryOperations * string * Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0354-101">Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0354-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0354-102">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-102">Required.</span></span> <span data-ttu-id="c0354-103">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0354-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0354-104">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-104">Required.</span></span> <span data-ttu-id="c0354-105">作成または更新、データ ファクトリに必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c0354-105">The parameters required to create or update a data factory.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0354-106">作成またはデータ ファクトリを更新します。</span><span class="sxs-lookup"><span data-stu-id="c0354-106">Create or update a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0354-107">作成または更新データ ファクトリ操作応答です。</span><span class="sxs-lookup"><span data-stu-id="c0354-107">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName, Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName, class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.IDataFactoryOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateAsync (operations As IDataFactoryOperations, resourceGroupName As String, parameters As DataFactoryCreateOrUpdateParameters) As Task(Of DataFactoryCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.IDataFactoryOperations * string * Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0354-108">Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0354-108">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0354-109">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-109">Required.</span></span> <span data-ttu-id="c0354-110">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0354-110">The resource group name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0354-111">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-111">Required.</span></span> <span data-ttu-id="c0354-112">作成または更新、データ ファクトリに必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c0354-112">The parameters required to create or update a data factory.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0354-113">作成またはデータ ファクトリを更新します。</span><span class="sxs-lookup"><span data-stu-id="c0354-113">Create or update a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0354-114">作成または更新データ ファクトリ操作応答です。</span><span class="sxs-lookup"><span data-stu-id="c0354-114">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName, Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName, class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.IDataFactoryOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDataFactoryOperations, resourceGroupName As String, parameters As DataFactoryCreateOrUpdateParameters) As DataFactoryCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.IDataFactoryOperations * string * Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0354-115">Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0354-115">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0354-116">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-116">Required.</span></span> <span data-ttu-id="c0354-117">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0354-117">The resource group name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0354-118">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-118">Required.</span></span> <span data-ttu-id="c0354-119">作成または更新、データ ファクトリに必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c0354-119">The parameters required to create or update a data factory.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0354-120">作成またはデータ ファクトリを更新します。</span><span class="sxs-lookup"><span data-stu-id="c0354-120">Create or update a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0354-121">作成または更新データ ファクトリ操作応答です。</span><span class="sxs-lookup"><span data-stu-id="c0354-121">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName, Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName, class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.IDataFactoryOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IDataFactoryOperations, resourceGroupName As String, parameters As DataFactoryCreateOrUpdateParameters) As Task(Of DataFactoryCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.IDataFactoryOperations * string * Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0354-122">Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0354-122">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0354-123">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-123">Required.</span></span> <span data-ttu-id="c0354-124">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0354-124">The resource group name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0354-125">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-125">Required.</span></span> <span data-ttu-id="c0354-126">作成または更新、データ ファクトリに必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c0354-126">The parameters required to create or update a data factory.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0354-127">作成またはデータ ファクトリを更新します。</span><span class="sxs-lookup"><span data-stu-id="c0354-127">Create or update a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0354-128">作成または更新データ ファクトリ操作応答です。</span><span class="sxs-lookup"><span data-stu-id="c0354-128">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.IDataFactoryOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IDataFactoryOperations, resourceGroupName As String, dataFactoryName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.IDataFactoryOperations * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0354-129">Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0354-129">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0354-130">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-130">Required.</span></span> <span data-ttu-id="c0354-131">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0354-131">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0354-132">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-132">Required.</span></span> <span data-ttu-id="c0354-133">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0354-133">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0354-134">データ ファクトリのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="c0354-134">Delete a data factory instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0354-135">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="c0354-135">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.IDataFactoryOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IDataFactoryOperations, resourceGroupName As String, dataFactoryName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.IDataFactoryOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0354-136">Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0354-136">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0354-137">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-137">Required.</span></span> <span data-ttu-id="c0354-138">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0354-138">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0354-139">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-139">Required.</span></span> <span data-ttu-id="c0354-140">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0354-140">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0354-141">データ ファクトリのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="c0354-141">Delete a data factory instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0354-142">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="c0354-142">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse Get (this Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse Get(class Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.IDataFactoryOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDataFactoryOperations, resourceGroupName As String, dataFactoryName As String) As DataFactoryGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.IDataFactoryOperations * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0354-143">Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0354-143">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0354-144">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-144">Required.</span></span> <span data-ttu-id="c0354-145">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0354-145">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0354-146">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-146">Required.</span></span> <span data-ttu-id="c0354-147">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0354-147">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0354-148">データ ファクトリのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="c0354-148">Gets a data factory instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0354-149">データ ファクトリを取得操作応答します。</span><span class="sxs-lookup"><span data-stu-id="c0354-149">The Get data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.IDataFactoryOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IDataFactoryOperations, resourceGroupName As String, dataFactoryName As String) As Task(Of DataFactoryGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.IDataFactoryOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0354-150">Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0354-150">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0354-151">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-151">Required.</span></span> <span data-ttu-id="c0354-152">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0354-152">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0354-153">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-153">Required.</span></span> <span data-ttu-id="c0354-154">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0354-154">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0354-155">データ ファクトリのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="c0354-155">Gets a data factory instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0354-156">データ ファクトリを取得操作応答します。</span><span class="sxs-lookup"><span data-stu-id="c0354-156">The Get data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse GetCreateOrUpdateStatus (this Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse GetCreateOrUpdateStatus(class Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.GetCreateOrUpdateStatus(Microsoft.Azure.Management.DataFactories.IDataFactoryOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatus (operations As IDataFactoryOperations, operationStatusLink As String) As DataFactoryCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatus : Microsoft.Azure.Management.DataFactories.IDataFactoryOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.GetCreateOrUpdateStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0354-157">Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0354-157">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="c0354-158">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-158">Required.</span></span> <span data-ttu-id="c0354-159">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="c0354-159">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0354-160">Get Operation Status 操作では、指定された操作の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="c0354-160">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="c0354-161">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="c0354-161">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0354-162">作成または更新データ ファクトリ操作応答です。</span><span class="sxs-lookup"><span data-stu-id="c0354-162">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (this Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(class Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.GetCreateOrUpdateStatusAsync(Microsoft.Azure.Management.DataFactories.IDataFactoryOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatusAsync (operations As IDataFactoryOperations, operationStatusLink As String) As Task(Of DataFactoryCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatusAsync : Microsoft.Azure.Management.DataFactories.IDataFactoryOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.GetCreateOrUpdateStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0354-163">Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0354-163">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="c0354-164">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-164">Required.</span></span> <span data-ttu-id="c0354-165">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="c0354-165">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0354-166">Get Operation Status 操作では、指定された操作の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="c0354-166">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="c0354-167">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="c0354-167">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0354-168">作成または更新データ ファクトリ操作応答です。</span><span class="sxs-lookup"><span data-stu-id="c0354-168">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse List (this Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse List(class Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.IDataFactoryOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDataFactoryOperations, resourceGroupName As String) As DataFactoryListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.IDataFactoryOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0354-169">Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0354-169">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0354-170">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-170">Required.</span></span> <span data-ttu-id="c0354-171">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0354-171">The resource group name of the data factories.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0354-172">次のページへのリンクがデータ ファクトリのインスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="c0354-172">Gets the first page of data factory instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0354-173">一覧データ ファクトリ操作応答です。</span><span class="sxs-lookup"><span data-stu-id="c0354-173">The List data factories operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.IDataFactoryOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDataFactoryOperations, resourceGroupName As String) As Task(Of DataFactoryListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.IDataFactoryOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.ListAsync (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0354-174">Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0354-174">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0354-175">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-175">Required.</span></span> <span data-ttu-id="c0354-176">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0354-176">The resource group name of the data factories.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0354-177">次のページへのリンクがデータ ファクトリのインスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="c0354-177">Gets the first page of data factory instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0354-178">一覧データ ファクトリ操作応答です。</span><span class="sxs-lookup"><span data-stu-id="c0354-178">The List data factories operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse ListNext (this Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse ListNext(class Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.IDataFactoryOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDataFactoryOperations, nextLink As String) As DataFactoryListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.IDataFactoryOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0354-179">Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0354-179">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="c0354-180">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-180">Required.</span></span> <span data-ttu-id="c0354-181">次のデータ ファクトリのページの url です。</span><span class="sxs-lookup"><span data-stu-id="c0354-181">The url to the next data factories page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0354-182">次のページへのリンクがデータ ファクトリのインスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="c0354-182">Gets the next page of data factory instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0354-183">一覧データ ファクトリ操作応答です。</span><span class="sxs-lookup"><span data-stu-id="c0354-183">The List data factories operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.IDataFactoryOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.IDataFactoryOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDataFactoryOperations, nextLink As String) As Task(Of DataFactoryListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.IDataFactoryOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DataFactoryOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0354-184">Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0354-184">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="c0354-185">必須。</span><span class="sxs-lookup"><span data-stu-id="c0354-185">Required.</span></span> <span data-ttu-id="c0354-186">次のデータ ファクトリのページの url です。</span><span class="sxs-lookup"><span data-stu-id="c0354-186">The url to the next data factories page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0354-187">次のページへのリンクがデータ ファクトリのインスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="c0354-187">Gets the next page of data factory instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0354-188">一覧データ ファクトリ操作応答です。</span><span class="sxs-lookup"><span data-stu-id="c0354-188">The List data factories operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>