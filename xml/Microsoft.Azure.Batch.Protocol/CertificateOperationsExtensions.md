<Type Name="CertificateOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CertificateOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CertificateOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CertificateOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CertificateOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1b893-101">CertificateOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="1b893-101">Extension methods for CertificateOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders Add (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter certificate, Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions certificateAddOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders Add(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, class Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter certificate, class Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions certificateAddOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Add(Microsoft.Azure.Batch.Protocol.ICertificateOperations,Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter,Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Batch.Protocol.ICertificateOperations * Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter * Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Add (operations, certificate, certificateAddOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="certificate" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter" />
        <Parameter Name="certificateAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b893-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b893-102">The operations group for this extension method.</span></span>
            </param>
        <param name="certificate">
            <span data-ttu-id="1b893-103">追加する証明書。</span><span class="sxs-lookup"><span data-stu-id="1b893-103">The certificate to be added.</span></span>
            </param>
        <param name="certificateAddOptions">
            <span data-ttu-id="1b893-104">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b893-104">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b893-105">指定されたアカウントに証明書を追加します。</span><span class="sxs-lookup"><span data-stu-id="1b893-105">Adds a certificate to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt; AddAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter certificate, Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions certificateAddOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt; AddAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, class Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter certificate, class Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions certificateAddOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.AddAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter,Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter * Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.AddAsync (operations, certificate, certificateAddOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;AddAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="certificate" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter" />
        <Parameter Name="certificateAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b893-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b893-106">The operations group for this extension method.</span></span>
            </param>
        <param name="certificate">
            <span data-ttu-id="1b893-107">追加する証明書。</span><span class="sxs-lookup"><span data-stu-id="1b893-107">The certificate to be added.</span></span>
            </param>
        <param name="certificateAddOptions">
            <span data-ttu-id="1b893-108">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b893-108">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b893-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b893-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b893-110">指定されたアカウントに証明書を追加します。</span><span class="sxs-lookup"><span data-stu-id="1b893-110">Adds a certificate to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletion">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders CancelDeletion (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions certificateCancelDeletionOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders CancelDeletion(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions certificateCancelDeletionOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.CancelDeletion(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions)" />
      <MemberSignature Language="F#" Value="static member CancelDeletion : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.CancelDeletion (operations, thumbprintAlgorithm, thumbprint, certificateCancelDeletionOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateCancelDeletionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b893-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b893-111">The operations group for this extension method.</span></span>
            </param>
        <param name="thumbprintAlgorithm">
            <span data-ttu-id="1b893-112">サムプリントのパラメーターを派生させるために使用されるアルゴリズム。</span><span class="sxs-lookup"><span data-stu-id="1b893-112">The algorithm used to derive the thumbprint parameter.</span></span> <span data-ttu-id="1b893-113">これには、sha1 があります。</span><span class="sxs-lookup"><span data-stu-id="1b893-113">This must be sha1.</span></span>
            </param>
        <param name="thumbprint">
            <span data-ttu-id="1b893-114">削除されている証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="1b893-114">The thumbprint of the certificate being deleted.</span></span>
            </param>
        <param name="certificateCancelDeletionOptions">
            <span data-ttu-id="1b893-115">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b893-115">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b893-116">指定されたアカウントからの証明書の削除に失敗をキャンセルします。</span><span class="sxs-lookup"><span data-stu-id="1b893-116">Cancels a failed deletion of a certificate from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b893-117">プールで使用されている証明書を削除またはコンピューティング ノードしようとすると、証明書の状態は deleteFailed に変更します。</span><span class="sxs-lookup"><span data-stu-id="1b893-117">If you try to delete a certificate that is being used by a pool or compute node, the status of the certificate changes to deleteFailed.</span></span> <span data-ttu-id="1b893-118">証明書の使用を続行することを決定する場合をアクティブに証明書の状態を設定します。 この操作を使用できます。</span><span class="sxs-lookup"><span data-stu-id="1b893-118">If you decide that you want to continue using the certificate, you can use this operation to set the status of the certificate back to active.</span></span> <span data-ttu-id="1b893-119">証明書を削除する場合は、削除が失敗した後、この操作を実行する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="1b893-119">If you intend to delete the certificate, you do not need to run this operation after the deletion failed.</span></span> <span data-ttu-id="1b893-120">証明書がすべてのリソースで使用されていないと、し、再度試行できる証明書を削除することを確認する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b893-120">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt; CancelDeletionAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions certificateCancelDeletionOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt; CancelDeletionAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions certificateCancelDeletionOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.CancelDeletionAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelDeletionAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.CancelDeletionAsync (operations, thumbprintAlgorithm, thumbprint, certificateCancelDeletionOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;CancelDeletionAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateCancelDeletionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b893-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b893-121">The operations group for this extension method.</span></span>
            </param>
        <param name="thumbprintAlgorithm">
            <span data-ttu-id="1b893-122">サムプリントのパラメーターを派生させるために使用されるアルゴリズム。</span><span class="sxs-lookup"><span data-stu-id="1b893-122">The algorithm used to derive the thumbprint parameter.</span></span> <span data-ttu-id="1b893-123">これには、sha1 があります。</span><span class="sxs-lookup"><span data-stu-id="1b893-123">This must be sha1.</span></span>
            </param>
        <param name="thumbprint">
            <span data-ttu-id="1b893-124">削除されている証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="1b893-124">The thumbprint of the certificate being deleted.</span></span>
            </param>
        <param name="certificateCancelDeletionOptions">
            <span data-ttu-id="1b893-125">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b893-125">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b893-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b893-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b893-127">指定されたアカウントからの証明書の削除に失敗をキャンセルします。</span><span class="sxs-lookup"><span data-stu-id="1b893-127">Cancels a failed deletion of a certificate from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b893-128">プールで使用されている証明書を削除またはコンピューティング ノードしようとすると、証明書の状態は deleteFailed に変更します。</span><span class="sxs-lookup"><span data-stu-id="1b893-128">If you try to delete a certificate that is being used by a pool or compute node, the status of the certificate changes to deleteFailed.</span></span> <span data-ttu-id="1b893-129">証明書の使用を続行することを決定する場合をアクティブに証明書の状態を設定します。 この操作を使用できます。</span><span class="sxs-lookup"><span data-stu-id="1b893-129">If you decide that you want to continue using the certificate, you can use this operation to set the status of the certificate back to active.</span></span> <span data-ttu-id="1b893-130">証明書を削除する場合は、削除が失敗した後、この操作を実行する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="1b893-130">If you intend to delete the certificate, you do not need to run this operation after the deletion failed.</span></span> <span data-ttu-id="1b893-131">証明書がすべてのリソースで使用されていないと、し、再度試行できる証明書を削除することを確認する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b893-131">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders Delete (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions certificateDeleteOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders Delete(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions certificateDeleteOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Delete(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Delete (operations, thumbprintAlgorithm, thumbprint, certificateDeleteOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b893-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b893-132">The operations group for this extension method.</span></span>
            </param>
        <param name="thumbprintAlgorithm">
            <span data-ttu-id="1b893-133">サムプリントのパラメーターを派生させるために使用されるアルゴリズム。</span><span class="sxs-lookup"><span data-stu-id="1b893-133">The algorithm used to derive the thumbprint parameter.</span></span> <span data-ttu-id="1b893-134">これには、sha1 があります。</span><span class="sxs-lookup"><span data-stu-id="1b893-134">This must be sha1.</span></span>
            </param>
        <param name="thumbprint">
            <span data-ttu-id="1b893-135">削除する証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="1b893-135">The thumbprint of the certificate to be deleted.</span></span>
            </param>
        <param name="certificateDeleteOptions">
            <span data-ttu-id="1b893-136">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b893-136">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b893-137">指定されたアカウントから証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="1b893-137">Deletes a certificate from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b893-138">リソース (プールまたはコンピューティング ノード) が使用されている場合、証明書を削除することはできません。</span><span class="sxs-lookup"><span data-stu-id="1b893-138">You cannot delete a certificate if a resource (pool or compute node) is using it.</span></span> <span data-ttu-id="1b893-139">証明書を削除することができます、前にする必要がありますので、証明書に関連付けられていない既存のプールのコンピューティング ノードであっても、プールから証明書を削除する場合は削除されません、プール内の既存のコンピューティング ノードから再起動するまで)、証明書がインストールされていないことを確認して、証明書の実行中のタスクが依存していません。</span><span class="sxs-lookup"><span data-stu-id="1b893-139">Before you can delete a certificate, you must therefore make sure that the certificate is not associated with any existing pools, the certificate is not installed on any compute nodes (even if you remove a certificate from a pool, it is not removed from existing compute nodes in that pool until they restart), and no running tasks depend on the certificate.</span></span> <span data-ttu-id="1b893-140">使用されている証明書を削除しようとすると、削除は失敗します。</span><span class="sxs-lookup"><span data-stu-id="1b893-140">If you try to delete a certificate that is in use, the deletion fails.</span></span> <span data-ttu-id="1b893-141">証明書の状態は、deleteFailed に変更します。</span><span class="sxs-lookup"><span data-stu-id="1b893-141">The certificate status changes to deleteFailed.</span></span> <span data-ttu-id="1b893-142">取り消す証明書の削除を使用して、証明書の使用を続行することを決定する場合にアクティブな状態を設定することができます。</span><span class="sxs-lookup"><span data-stu-id="1b893-142">You can use Cancel Delete Certificate to set the status back to active if you decide that you want to continue using the certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions certificateDeleteOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions certificateDeleteOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.DeleteAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.DeleteAsync (operations, thumbprintAlgorithm, thumbprint, certificateDeleteOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b893-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b893-143">The operations group for this extension method.</span></span>
            </param>
        <param name="thumbprintAlgorithm">
            <span data-ttu-id="1b893-144">サムプリントのパラメーターを派生させるために使用されるアルゴリズム。</span><span class="sxs-lookup"><span data-stu-id="1b893-144">The algorithm used to derive the thumbprint parameter.</span></span> <span data-ttu-id="1b893-145">これには、sha1 があります。</span><span class="sxs-lookup"><span data-stu-id="1b893-145">This must be sha1.</span></span>
            </param>
        <param name="thumbprint">
            <span data-ttu-id="1b893-146">削除する証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="1b893-146">The thumbprint of the certificate to be deleted.</span></span>
            </param>
        <param name="certificateDeleteOptions">
            <span data-ttu-id="1b893-147">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b893-147">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b893-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b893-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b893-149">指定されたアカウントから証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="1b893-149">Deletes a certificate from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b893-150">リソース (プールまたはコンピューティング ノード) が使用されている場合、証明書を削除することはできません。</span><span class="sxs-lookup"><span data-stu-id="1b893-150">You cannot delete a certificate if a resource (pool or compute node) is using it.</span></span> <span data-ttu-id="1b893-151">証明書を削除することができます、前にする必要がありますので、証明書に関連付けられていない既存のプールのコンピューティング ノードであっても、プールから証明書を削除する場合は削除されません、プール内の既存のコンピューティング ノードから再起動するまで)、証明書がインストールされていないことを確認して、証明書の実行中のタスクが依存していません。</span><span class="sxs-lookup"><span data-stu-id="1b893-151">Before you can delete a certificate, you must therefore make sure that the certificate is not associated with any existing pools, the certificate is not installed on any compute nodes (even if you remove a certificate from a pool, it is not removed from existing compute nodes in that pool until they restart), and no running tasks depend on the certificate.</span></span> <span data-ttu-id="1b893-152">使用されている証明書を削除しようとすると、削除は失敗します。</span><span class="sxs-lookup"><span data-stu-id="1b893-152">If you try to delete a certificate that is in use, the deletion fails.</span></span> <span data-ttu-id="1b893-153">証明書の状態は、deleteFailed に変更します。</span><span class="sxs-lookup"><span data-stu-id="1b893-153">The certificate status changes to deleteFailed.</span></span> <span data-ttu-id="1b893-154">取り消す証明書の削除を使用して、証明書の使用を続行することを決定する場合にアクティブな状態を設定することができます。</span><span class="sxs-lookup"><span data-stu-id="1b893-154">You can use Cancel Delete Certificate to set the status back to active if you decide that you want to continue using the certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.Certificate Get (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions certificateGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.Certificate Get(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions certificateGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.Certificate" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Get (operations, thumbprintAlgorithm, thumbprint, certificateGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b893-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b893-155">The operations group for this extension method.</span></span>
            </param>
        <param name="thumbprintAlgorithm">
            <span data-ttu-id="1b893-156">サムプリントのパラメーターを派生させるために使用されるアルゴリズム。</span><span class="sxs-lookup"><span data-stu-id="1b893-156">The algorithm used to derive the thumbprint parameter.</span></span> <span data-ttu-id="1b893-157">これには、sha1 があります。</span><span class="sxs-lookup"><span data-stu-id="1b893-157">This must be sha1.</span></span>
            </param>
        <param name="thumbprint">
            <span data-ttu-id="1b893-158">取得する証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="1b893-158">The thumbprint of the certificate to get.</span></span>
            </param>
        <param name="certificateGetOptions">
            <span data-ttu-id="1b893-159">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b893-159">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b893-160">指定された証明書に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b893-160">Gets information about the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions certificateGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions certificateGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.GetAsync (operations, thumbprintAlgorithm, thumbprint, certificateGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b893-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b893-161">The operations group for this extension method.</span></span>
            </param>
        <param name="thumbprintAlgorithm">
            <span data-ttu-id="1b893-162">サムプリントのパラメーターを派生させるために使用されるアルゴリズム。</span><span class="sxs-lookup"><span data-stu-id="1b893-162">The algorithm used to derive the thumbprint parameter.</span></span> <span data-ttu-id="1b893-163">これには、sha1 があります。</span><span class="sxs-lookup"><span data-stu-id="1b893-163">This must be sha1.</span></span>
            </param>
        <param name="thumbprint">
            <span data-ttu-id="1b893-164">取得する証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="1b893-164">The thumbprint of the certificate to get.</span></span>
            </param>
        <param name="certificateGetOptions">
            <span data-ttu-id="1b893-165">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b893-165">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b893-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b893-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b893-167">指定された証明書に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b893-167">Gets information about the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; List (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions certificateListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; List(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, class Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions certificateListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.ICertificateOperations,Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.ICertificateOperations * Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.List (operations, certificateListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="certificateListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b893-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b893-168">The operations group for this extension method.</span></span>
            </param>
        <param name="certificateListOptions">
            <span data-ttu-id="1b893-169">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b893-169">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b893-170">すべての指定したアカウントに追加されている証明書の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="1b893-170">Lists all of the certificates that have been added to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions certificateListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, class Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions certificateListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListAsync (operations, certificateListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="certificateListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b893-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b893-171">The operations group for this extension method.</span></span>
            </param>
        <param name="certificateListOptions">
            <span data-ttu-id="1b893-172">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b893-172">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b893-173">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b893-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b893-174">すべての指定したアカウントに追加されている証明書の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="1b893-174">Lists all of the certificates that have been added to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; ListNext (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions certificateListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; ListNext(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions certificateListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListNext (operations, nextPageLink, certificateListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="certificateListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b893-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b893-175">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1b893-176">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b893-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="certificateListNextOptions">
            <span data-ttu-id="1b893-177">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b893-177">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b893-178">すべての指定したアカウントに追加されている証明書の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="1b893-178">Lists all of the certificates that have been added to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions certificateListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions certificateListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListNextAsync (operations, nextPageLink, certificateListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="certificateListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b893-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b893-179">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1b893-180">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b893-180">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="certificateListNextOptions">
            <span data-ttu-id="1b893-181">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b893-181">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b893-182">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b893-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b893-183">すべての指定したアカウントに追加されている証明書の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="1b893-183">Lists all of the certificates that have been added to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>