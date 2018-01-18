<Type Name="ImagesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ImagesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ImagesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ImagesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ImagesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3ed40-101">ImagesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="3ed40-101">Extension methods for ImagesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, string resourceGroupName, string imageName, Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, string resourceGroupName, string imageName, class Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IImagesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IImagesOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, imageName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3ed40-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3ed40-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3ed40-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3ed40-103">The name of the resource group.</span></span>
            </param>
        <param name="imageName">
            <span data-ttu-id="3ed40-104">イメージの名前です。</span><span class="sxs-lookup"><span data-stu-id="3ed40-104">The name of the image.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3ed40-105">パラメーターは、イメージの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="3ed40-105">Parameters supplied to the Create Image operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3ed40-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3ed40-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3ed40-107">作成またはイメージを更新します。</span><span class="sxs-lookup"><span data-stu-id="3ed40-107">Create or update an image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, string resourceGroupName, string imageName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, string resourceGroupName, string imageName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IImagesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IImagesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, imageName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3ed40-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3ed40-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3ed40-109">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3ed40-109">The name of the resource group.</span></span>
            </param>
        <param name="imageName">
            <span data-ttu-id="3ed40-110">イメージの名前です。</span><span class="sxs-lookup"><span data-stu-id="3ed40-110">The name of the image.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3ed40-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3ed40-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3ed40-112">イメージを削除します。</span><span class="sxs-lookup"><span data-stu-id="3ed40-112">Deletes an Image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, string resourceGroupName, string imageName, Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, string resourceGroupName, string imageName, class Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IImagesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IImagesOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, imageName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3ed40-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3ed40-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3ed40-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3ed40-114">The name of the resource group.</span></span>
            </param>
        <param name="imageName">
            <span data-ttu-id="3ed40-115">イメージの名前です。</span><span class="sxs-lookup"><span data-stu-id="3ed40-115">The name of the image.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3ed40-116">パラメーターは、イメージの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="3ed40-116">Parameters supplied to the Create Image operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3ed40-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3ed40-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3ed40-118">作成またはイメージを更新します。</span><span class="sxs-lookup"><span data-stu-id="3ed40-118">Create or update an image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, string resourceGroupName, string imageName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, string resourceGroupName, string imageName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IImagesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IImagesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.DeleteAsync (operations, resourceGroupName, imageName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3ed40-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3ed40-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3ed40-120">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3ed40-120">The name of the resource group.</span></span>
            </param>
        <param name="imageName">
            <span data-ttu-id="3ed40-121">イメージの名前です。</span><span class="sxs-lookup"><span data-stu-id="3ed40-121">The name of the image.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3ed40-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3ed40-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3ed40-123">イメージを削除します。</span><span class="sxs-lookup"><span data-stu-id="3ed40-123">Deletes an Image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, string resourceGroupName, string imageName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, string resourceGroupName, string imageName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.IImagesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.IImagesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.GetAsync (operations, resourceGroupName, imageName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3ed40-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3ed40-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3ed40-125">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3ed40-125">The name of the resource group.</span></span>
            </param>
        <param name="imageName">
            <span data-ttu-id="3ed40-126">イメージの名前です。</span><span class="sxs-lookup"><span data-stu-id="3ed40-126">The name of the image.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="3ed40-127">操作に適用する展開式です。</span><span class="sxs-lookup"><span data-stu-id="3ed40-127">The expand expression to apply on the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3ed40-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3ed40-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3ed40-129">イメージを取得します。</span><span class="sxs-lookup"><span data-stu-id="3ed40-129">Gets an image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.IImagesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.IImagesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions/&lt;ListAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IImagesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3ed40-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3ed40-130">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3ed40-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3ed40-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3ed40-132">サブスクリプションでのイメージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="3ed40-132">Gets the list of Images in the subscription.</span></span> <span data-ttu-id="3ed40-133">応答で nextLink プロパティを使用して、イメージの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="3ed40-133">Use nextLink property in the response to get the next page of Images.</span></span> <span data-ttu-id="3ed40-134">NextLink が null ではすべてのイメージを取得するまで、この操作を行います。</span><span class="sxs-lookup"><span data-stu-id="3ed40-134">Do this till nextLink is not null to fetch all the Images.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Compute.Fluent.IImagesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Compute.Fluent.IImagesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IImagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3ed40-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3ed40-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3ed40-136">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3ed40-136">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3ed40-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3ed40-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3ed40-138">リソース グループの下のイメージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="3ed40-138">Gets the list of images under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Compute.Fluent.IImagesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Compute.Fluent.IImagesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IImagesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3ed40-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3ed40-139">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3ed40-140">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3ed40-140">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3ed40-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3ed40-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3ed40-142">リソース グループの下のイメージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="3ed40-142">Gets the list of images under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IImagesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.Fluent.IImagesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.Fluent.IImagesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ImagesOperationsExtensions/&lt;ListNextAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IImagesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3ed40-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3ed40-143">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3ed40-144">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3ed40-144">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3ed40-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3ed40-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3ed40-146">サブスクリプションでのイメージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="3ed40-146">Gets the list of Images in the subscription.</span></span> <span data-ttu-id="3ed40-147">応答で nextLink プロパティを使用して、イメージの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="3ed40-147">Use nextLink property in the response to get the next page of Images.</span></span> <span data-ttu-id="3ed40-148">NextLink が null ではすべてのイメージを取得するまで、この操作を行います。</span><span class="sxs-lookup"><span data-stu-id="3ed40-148">Do this till nextLink is not null to fetch all the Images.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>