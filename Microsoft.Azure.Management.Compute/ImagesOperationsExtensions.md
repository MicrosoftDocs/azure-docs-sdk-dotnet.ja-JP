<Type Name="ImagesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ImagesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ImagesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ImagesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ImagesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="84d60-101">ImagesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="84d60-101">Extension methods for ImagesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Image BeginCreateOrUpdate (this Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName, Microsoft.Azure.Management.Compute.Models.Image parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Image BeginCreateOrUpdate(class Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName, class Microsoft.Azure.Management.Compute.Models.Image parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Compute.IImagesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Image)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IImagesOperations, resourceGroupName As String, imageName As String, parameters As Image) As Image" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Compute.IImagesOperations * string * string * Microsoft.Azure.Management.Compute.Models.Image -&gt; Microsoft.Azure.Management.Compute.Models.Image" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, imageName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Image</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.Image" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="84d60-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="84d60-103">The name of the resource group.</span></span>
            </param>
        <param name="imageName">
            <span data-ttu-id="84d60-104">イメージの名前です。</span><span class="sxs-lookup"><span data-stu-id="84d60-104">The name of the image.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="84d60-105">パラメーターは、イメージの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="84d60-105">Parameters supplied to the Create Image operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-106">作成またはイメージを更新します。</span><span class="sxs-lookup"><span data-stu-id="84d60-106">Create or update an image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Image&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName, Microsoft.Azure.Management.Compute.Models.Image parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Image&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName, class Microsoft.Azure.Management.Compute.Models.Image parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IImagesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Image,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IImagesOperations * string * string * Microsoft.Azure.Management.Compute.Models.Image * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, imageName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ImagesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.Image" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="84d60-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="84d60-108">The name of the resource group.</span></span>
            </param>
        <param name="imageName">
            <span data-ttu-id="84d60-109">イメージの名前です。</span><span class="sxs-lookup"><span data-stu-id="84d60-109">The name of the image.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="84d60-110">パラメーターは、イメージの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="84d60-110">Parameters supplied to the Create Image operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="84d60-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="84d60-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-112">作成またはイメージを更新します。</span><span class="sxs-lookup"><span data-stu-id="84d60-112">Create or update an image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete (this Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete(class Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Compute.IImagesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IImagesOperations, resourceGroupName As String, imageName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Compute.IImagesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.BeginDelete (operations, resourceGroupName, imageName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="imageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="84d60-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="84d60-114">The name of the resource group.</span></span>
            </param>
        <param name="imageName">
            <span data-ttu-id="84d60-115">イメージの名前です。</span><span class="sxs-lookup"><span data-stu-id="84d60-115">The name of the image.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-116">イメージを削除します。</span><span class="sxs-lookup"><span data-stu-id="84d60-116">Deletes an Image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.IImagesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.IImagesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, imageName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ImagesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="84d60-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="84d60-118">The name of the resource group.</span></span>
            </param>
        <param name="imageName">
            <span data-ttu-id="84d60-119">イメージの名前です。</span><span class="sxs-lookup"><span data-stu-id="84d60-119">The name of the image.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="84d60-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="84d60-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-121">イメージを削除します。</span><span class="sxs-lookup"><span data-stu-id="84d60-121">Deletes an Image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Image CreateOrUpdate (this Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName, Microsoft.Azure.Management.Compute.Models.Image parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Image CreateOrUpdate(class Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName, class Microsoft.Azure.Management.Compute.Models.Image parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Compute.IImagesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Image)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IImagesOperations, resourceGroupName As String, imageName As String, parameters As Image) As Image" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Compute.IImagesOperations * string * string * Microsoft.Azure.Management.Compute.Models.Image -&gt; Microsoft.Azure.Management.Compute.Models.Image" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, imageName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Image</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.Image" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="84d60-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="84d60-123">The name of the resource group.</span></span>
            </param>
        <param name="imageName">
            <span data-ttu-id="84d60-124">イメージの名前です。</span><span class="sxs-lookup"><span data-stu-id="84d60-124">The name of the image.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="84d60-125">パラメーターは、イメージの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="84d60-125">Parameters supplied to the Create Image operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-126">作成またはイメージを更新します。</span><span class="sxs-lookup"><span data-stu-id="84d60-126">Create or update an image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Image&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName, Microsoft.Azure.Management.Compute.Models.Image parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Image&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName, class Microsoft.Azure.Management.Compute.Models.Image parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IImagesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Image,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IImagesOperations * string * string * Microsoft.Azure.Management.Compute.Models.Image * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, imageName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ImagesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.Image" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="84d60-128">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="84d60-128">The name of the resource group.</span></span>
            </param>
        <param name="imageName">
            <span data-ttu-id="84d60-129">イメージの名前です。</span><span class="sxs-lookup"><span data-stu-id="84d60-129">The name of the image.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="84d60-130">パラメーターは、イメージの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="84d60-130">Parameters supplied to the Create Image operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="84d60-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="84d60-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-132">作成またはイメージを更新します。</span><span class="sxs-lookup"><span data-stu-id="84d60-132">Create or update an image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete (this Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete(class Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.Delete(Microsoft.Azure.Management.Compute.IImagesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IImagesOperations, resourceGroupName As String, imageName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Compute.IImagesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.Delete (operations, resourceGroupName, imageName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="imageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="84d60-134">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="84d60-134">The name of the resource group.</span></span>
            </param>
        <param name="imageName">
            <span data-ttu-id="84d60-135">イメージの名前です。</span><span class="sxs-lookup"><span data-stu-id="84d60-135">The name of the image.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-136">イメージを削除します。</span><span class="sxs-lookup"><span data-stu-id="84d60-136">Deletes an Image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.IImagesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.IImagesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.DeleteAsync (operations, resourceGroupName, imageName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ImagesOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="84d60-138">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="84d60-138">The name of the resource group.</span></span>
            </param>
        <param name="imageName">
            <span data-ttu-id="84d60-139">イメージの名前です。</span><span class="sxs-lookup"><span data-stu-id="84d60-139">The name of the image.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="84d60-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="84d60-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-141">イメージを削除します。</span><span class="sxs-lookup"><span data-stu-id="84d60-141">Deletes an Image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Image Get (this Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Image Get(class Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IImagesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IImagesOperations, resourceGroupName As String, imageName As String, Optional expand As String = null) As Image" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IImagesOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.Image" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.Get (operations, resourceGroupName, imageName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Image</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="84d60-143">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="84d60-143">The name of the resource group.</span></span>
            </param>
        <param name="imageName">
            <span data-ttu-id="84d60-144">イメージの名前です。</span><span class="sxs-lookup"><span data-stu-id="84d60-144">The name of the image.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="84d60-145">操作に適用する展開式です。</span><span class="sxs-lookup"><span data-stu-id="84d60-145">The expand expression to apply on the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-146">イメージを取得します。</span><span class="sxs-lookup"><span data-stu-id="84d60-146">Gets an image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Image&gt; GetAsync (this Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Image&gt; GetAsync(class Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, string imageName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IImagesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IImagesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.GetAsync (operations, resourceGroupName, imageName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ImagesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-147">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="84d60-148">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="84d60-148">The name of the resource group.</span></span>
            </param>
        <param name="imageName">
            <span data-ttu-id="84d60-149">イメージの名前です。</span><span class="sxs-lookup"><span data-stu-id="84d60-149">The name of the image.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="84d60-150">操作に適用する展開式です。</span><span class="sxs-lookup"><span data-stu-id="84d60-150">The expand expression to apply on the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="84d60-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="84d60-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-152">イメージを取得します。</span><span class="sxs-lookup"><span data-stu-id="84d60-152">Gets an image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt; List (this Microsoft.Azure.Management.Compute.IImagesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Image&gt; List(class Microsoft.Azure.Management.Compute.IImagesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.List(Microsoft.Azure.Management.Compute.IImagesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IImagesOperations) As IPage(Of Image)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.IImagesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-153">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-154">サブスクリプションでのイメージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="84d60-154">Gets the list of Images in the subscription.</span></span> <span data-ttu-id="84d60-155">応答で nextLink プロパティを使用して、イメージの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="84d60-155">Use nextLink property in the response to get the next page of Images.</span></span> <span data-ttu-id="84d60-156">NextLink が null をすべてのイメージを取得するまで、この操作を行います。</span><span class="sxs-lookup"><span data-stu-id="84d60-156">Do this till nextLink is null to fetch all the Images.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.IImagesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Image&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.IImagesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.IImagesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.IImagesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ImagesOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-157">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="84d60-158">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="84d60-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-159">サブスクリプションでのイメージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="84d60-159">Gets the list of Images in the subscription.</span></span> <span data-ttu-id="84d60-160">応答で nextLink プロパティを使用して、イメージの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="84d60-160">Use nextLink property in the response to get the next page of Images.</span></span> <span data-ttu-id="84d60-161">NextLink が null をすべてのイメージを取得するまで、この操作を行います。</span><span class="sxs-lookup"><span data-stu-id="84d60-161">Do this till nextLink is null to fetch all the Images.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt; ListByResourceGroup (this Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Image&gt; ListByResourceGroup(class Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Compute.IImagesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IImagesOperations, resourceGroupName As String) As IPage(Of Image)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Compute.IImagesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-162">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="84d60-163">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="84d60-163">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-164">リソース グループの下のイメージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="84d60-164">Gets the list of images under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Image&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Compute.IImagesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Compute.IImagesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Compute.IImagesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ImagesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-165">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="84d60-166">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="84d60-166">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="84d60-167">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="84d60-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-168">リソース グループの下のイメージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="84d60-168">Gets the list of images under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Compute.IImagesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Image&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Compute.IImagesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Compute.IImagesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IImagesOperations, nextPageLink As String) As IPage(Of Image)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Compute.IImagesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-169">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-169">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="84d60-170">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="84d60-170">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-171">リソース グループの下のイメージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="84d60-171">Gets the list of images under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Compute.IImagesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Image&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Compute.IImagesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Compute.IImagesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Compute.IImagesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ImagesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-172">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="84d60-173">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="84d60-173">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="84d60-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="84d60-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-175">リソース グループの下のイメージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="84d60-175">Gets the list of images under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt; ListNext (this Microsoft.Azure.Management.Compute.IImagesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Image&gt; ListNext(class Microsoft.Azure.Management.Compute.IImagesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.ListNext(Microsoft.Azure.Management.Compute.IImagesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IImagesOperations, nextPageLink As String) As IPage(Of Image)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Compute.IImagesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-176">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-176">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="84d60-177">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="84d60-177">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-178">サブスクリプションでのイメージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="84d60-178">Gets the list of Images in the subscription.</span></span> <span data-ttu-id="84d60-179">応答で nextLink プロパティを使用して、イメージの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="84d60-179">Use nextLink property in the response to get the next page of Images.</span></span> <span data-ttu-id="84d60-180">NextLink が null をすべてのイメージを取得するまで、この操作を行います。</span><span class="sxs-lookup"><span data-stu-id="84d60-180">Do this till nextLink is null to fetch all the Images.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.IImagesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Image&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.IImagesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.IImagesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.IImagesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ImagesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ImagesOperationsExtensions/&lt;ListNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Image&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IImagesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="84d60-181">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="84d60-181">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="84d60-182">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="84d60-182">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="84d60-183">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="84d60-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="84d60-184">サブスクリプションでのイメージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="84d60-184">Gets the list of Images in the subscription.</span></span> <span data-ttu-id="84d60-185">応答で nextLink プロパティを使用して、イメージの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="84d60-185">Use nextLink property in the response to get the next page of Images.</span></span> <span data-ttu-id="84d60-186">NextLink が null をすべてのイメージを取得するまで、この操作を行います。</span><span class="sxs-lookup"><span data-stu-id="84d60-186">Do this till nextLink is null to fetch all the Images.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>