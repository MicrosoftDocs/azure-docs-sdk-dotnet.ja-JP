<Type Name="CertificateOperations" FullName="Microsoft.Azure.Batch.CertificateOperations">
  <TypeSignature Language="C#" Value="public class CertificateOperations : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateOperations extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.CertificateOperations" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateOperations&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type CertificateOperations = class&#xA;    interface IInheritedBehaviors" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="744d5-101">Azure Batch アカウントの証明書関連の操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="744d5-101">Performs certificate-related operations on an Azure Batch account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelDeleteCertificate">
      <MemberSignature Language="C#" Value="public void CancelDeleteCertificate (string thumbprintAlgorithm, string thumbprint, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CancelDeleteCertificate(string thumbprintAlgorithm, string thumbprint, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificate(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CancelDeleteCertificate (thumbprintAlgorithm As String, thumbprint As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.CancelDeleteCertificate : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="certificateOperations.CancelDeleteCertificate (thumbprintAlgorithm, thumbprint, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm"><span data-ttu-id="744d5-102">派生に使用するアルゴリズム、<paramref name="thumbprint" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="744d5-102">The algorithm used to derive the <paramref name="thumbprint" /> parameter.</span></span> <span data-ttu-id="744d5-103">これには、sha1 があります。</span><span class="sxs-lookup"><span data-stu-id="744d5-103">This must be sha1.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="744d5-104">削除に失敗した証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="744d5-104">The thumbprint of the certificate that failed to delete.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="744d5-105">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="744d5-105">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="744d5-106">指定された証明書の削除に失敗をキャンセルします。</span><span class="sxs-lookup"><span data-stu-id="744d5-106">Cancels a failed deletion of the specified certificate.</span></span>  <span data-ttu-id="744d5-107">これは、ため、証明書が、場合にのみ、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />状態、および復元する証明書、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" />状態です。</span><span class="sxs-lookup"><span data-stu-id="744d5-107">This can be done only when the certificate is in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> state, and restores the certificate to the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> state.</span></span>
            </summary>
        <returns><span data-ttu-id="744d5-108">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="744d5-108">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="744d5-109">(アクティブなへの返送) ではなく証明書を削除する場合は、失敗した削除をキャンセルする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="744d5-109">If you still wish to delete the certificate (instead of returning it to Active), you do not need to cancel the failed deletion.</span></span> <span data-ttu-id="744d5-110">証明書がすべてのリソースで使用されていないと、し、再度試行できる証明書を削除することを確認する必要があります (を参照してください<see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="744d5-110">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate (see <see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="744d5-111">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="744d5-111">This is a blocking operation.</span></span> <span data-ttu-id="744d5-112">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="744d5-112">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeleteCertificateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelDeleteCertificateAsync (string thumbprintAlgorithm, string thumbprint, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelDeleteCertificateAsync(string thumbprintAlgorithm, string thumbprint, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelDeleteCertificateAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="certificateOperations.CancelDeleteCertificateAsync (thumbprintAlgorithm, thumbprint, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CertificateOperations/&lt;CancelDeleteCertificateAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm"><span data-ttu-id="744d5-113">派生に使用するアルゴリズム、<paramref name="thumbprint" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="744d5-113">The algorithm used to derive the <paramref name="thumbprint" /> parameter.</span></span> <span data-ttu-id="744d5-114">これには、sha1 があります。</span><span class="sxs-lookup"><span data-stu-id="744d5-114">This must be sha1.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="744d5-115">削除に失敗した証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="744d5-115">The thumbprint of the certificate that failed to delete.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="744d5-116">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="744d5-116">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="744d5-117">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="744d5-117">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="744d5-118">指定された証明書の削除に失敗をキャンセルします。</span><span class="sxs-lookup"><span data-stu-id="744d5-118">Cancels a failed deletion of the specified certificate.</span></span>  <span data-ttu-id="744d5-119">これは、ため、証明書が、場合にのみ、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />状態、および復元する証明書、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" />状態です。</span><span class="sxs-lookup"><span data-stu-id="744d5-119">This can be done only when the certificate is in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> state, and restores the certificate to the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> state.</span></span>
            </summary>
        <returns><span data-ttu-id="744d5-120">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="744d5-120">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="744d5-121">(アクティブなへの返送) ではなく証明書を削除する場合は、失敗した削除をキャンセルする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="744d5-121">If you still wish to delete the certificate (instead of returning it to Active), you do not need to cancel the failed deletion.</span></span> <span data-ttu-id="744d5-122">証明書がすべてのリソースで使用されていないと、し、再度試行できる証明書を削除することを確認する必要があります (を参照してください<see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="744d5-122">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate (see <see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="744d5-123">キャンセルは、非同期的に操作の実行を削除します。</span><span class="sxs-lookup"><span data-stu-id="744d5-123">The cancel delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate CreateCertificate (byte[] cerRawData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate CreateCertificate(unsigned int8[] cerRawData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCertificate (cerRawData As Byte()) As Certificate" />
      <MemberSignature Language="F#" Value="member this.CreateCertificate : byte[] -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.CreateCertificate cerRawData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cerRawData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="cerRawData"><span data-ttu-id="744d5-124">.Cer 形式で証明書データです。</span><span class="sxs-lookup"><span data-stu-id="744d5-124">The certificate data in .cer format.</span></span></param>
        <summary>
            <span data-ttu-id="744d5-125">新たに作成<see cref="T:Microsoft.Azure.Batch.Certificate" />.cer 形式のデータをメモリからです。</span><span class="sxs-lookup"><span data-stu-id="744d5-125">Creates a new <see cref="T:Microsoft.Azure.Batch.Certificate" /> from .cer format data in memory.</span></span>
            </summary>
        <returns><span data-ttu-id="744d5-126">A<see cref="T:Microsoft.Azure.Batch.Certificate" />バッチ サービスに追加されていない新しい証明書を表すです。</span><span class="sxs-lookup"><span data-stu-id="744d5-126">A <see cref="T:Microsoft.Azure.Batch.Certificate" /> representing a new certificate that has not been added to the Batch service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate CreateCertificate (string cerFileName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate CreateCertificate(string cerFileName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCertificate (cerFileName As String) As Certificate" />
      <MemberSignature Language="F#" Value="member this.CreateCertificate : string -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.CreateCertificate cerFileName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cerFileName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cerFileName"><span data-ttu-id="744d5-127">.Cer ファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="744d5-127">The path to the .cer file.</span></span></param>
        <summary>
            <span data-ttu-id="744d5-128">新たに作成<see cref="T:Microsoft.Azure.Batch.Certificate" />.cer ファイルからです。</span><span class="sxs-lookup"><span data-stu-id="744d5-128">Creates a new <see cref="T:Microsoft.Azure.Batch.Certificate" /> from a .cer file.</span></span>
            </summary>
        <returns><span data-ttu-id="744d5-129">A<see cref="T:Microsoft.Azure.Batch.Certificate" />バッチ サービスに追加されていない新しい証明書を表すです。</span><span class="sxs-lookup"><span data-stu-id="744d5-129">A <see cref="T:Microsoft.Azure.Batch.Certificate" /> representing a new certificate that has not been added to the Batch service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate CreateCertificate (byte[] pfxRawData, string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate CreateCertificate(unsigned int8[] pfxRawData, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.Byte[],System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCertificate (pfxRawData As Byte(), password As String) As Certificate" />
      <MemberSignature Language="F#" Value="member this.CreateCertificate : byte[] * string -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.CreateCertificate (pfxRawData, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxRawData" Type="System.Byte[]" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pfxRawData"><span data-ttu-id="744d5-130">.Pfx 形式で証明書データです。</span><span class="sxs-lookup"><span data-stu-id="744d5-130">The certificate data in .pfx format.</span></span></param>
        <param name="password"><span data-ttu-id="744d5-131">証明書の秘密キーにアクセスするパスワードです。</span><span class="sxs-lookup"><span data-stu-id="744d5-131">The password to access the certificate private key.</span></span></param>
        <summary>
            <span data-ttu-id="744d5-132">新たに作成<see cref="T:Microsoft.Azure.Batch.Certificate" />.pfx 形式のデータをメモリからです。</span><span class="sxs-lookup"><span data-stu-id="744d5-132">Creates a new <see cref="T:Microsoft.Azure.Batch.Certificate" /> from .pfx format data in memory.</span></span>
            </summary>
        <returns><span data-ttu-id="744d5-133">A<see cref="T:Microsoft.Azure.Batch.Certificate" />バッチ サービスに追加されていない新しい証明書を表すです。</span><span class="sxs-lookup"><span data-stu-id="744d5-133">A <see cref="T:Microsoft.Azure.Batch.Certificate" /> representing a new certificate that has not been added to the Batch service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate CreateCertificate (string pfxFileName, string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate CreateCertificate(string pfxFileName, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCertificate (pfxFileName As String, password As String) As Certificate" />
      <MemberSignature Language="F#" Value="member this.CreateCertificate : string * string -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.CreateCertificate (pfxFileName, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxFileName" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pfxFileName"><span data-ttu-id="744d5-134">.Pfx ファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="744d5-134">The path to the .pfx file.</span></span></param>
        <param name="password"><span data-ttu-id="744d5-135">証明書の秘密キーにアクセスするパスワードです。</span><span class="sxs-lookup"><span data-stu-id="744d5-135">The password to access the certificate private key.</span></span></param>
        <summary>
            <span data-ttu-id="744d5-136">新たに作成<see cref="T:Microsoft.Azure.Batch.Certificate" />.pfx ファイルからです。</span><span class="sxs-lookup"><span data-stu-id="744d5-136">Creates a new <see cref="T:Microsoft.Azure.Batch.Certificate" /> from a .pfx file.</span></span>
            </summary>
        <returns><span data-ttu-id="744d5-137">A<see cref="T:Microsoft.Azure.Batch.Certificate" />バッチ サービスに追加されていない新しい証明書を表すです。</span><span class="sxs-lookup"><span data-stu-id="744d5-137">A <see cref="T:Microsoft.Azure.Batch.Certificate" /> representing a new certificate that has not been added to the Batch service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="744d5-138">取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.CertificateOperations" />です。</span><span class="sxs-lookup"><span data-stu-id="744d5-138">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.CertificateOperations" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="744d5-139">これらの動作は、子オブジェクトによって継承されます。</span><span class="sxs-lookup"><span data-stu-id="744d5-139">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="744d5-140">変更は、コレクションの順序で適用されます。</span><span class="sxs-lookup"><span data-stu-id="744d5-140">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="744d5-141">最後には、wins を記述します。</span><span class="sxs-lookup"><span data-stu-id="744d5-141">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificate">
      <MemberSignature Language="C#" Value="public void DeleteCertificate (string thumbprintAlgorithm, string thumbprint, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteCertificate(string thumbprintAlgorithm, string thumbprint, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificate(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteCertificate (thumbprintAlgorithm As String, thumbprint As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteCertificate : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="certificateOperations.DeleteCertificate (thumbprintAlgorithm, thumbprint, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm"><span data-ttu-id="744d5-142">派生に使用するアルゴリズム、<paramref name="thumbprint" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="744d5-142">The algorithm used to derive the <paramref name="thumbprint" /> parameter.</span></span> <span data-ttu-id="744d5-143">これには、sha1 があります。</span><span class="sxs-lookup"><span data-stu-id="744d5-143">This must be sha1.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="744d5-144">削除する証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="744d5-144">The thumbprint of the certificate to delete.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="744d5-145">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="744d5-145">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="744d5-146">Batch アカウントから証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="744d5-146">Deletes the certificate from the Batch account.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="744d5-147">削除操作は、証明書が削除されることを要求します。</span><span class="sxs-lookup"><span data-stu-id="744d5-147">The delete operation requests that the certificate be deleted.</span></span>  <span data-ttu-id="744d5-148">要求に証明書を格納する、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="744d5-148">The request puts the certificate in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" /> state.</span></span>
            <span data-ttu-id="744d5-149">バッチ サービスでは、その他のクライアント操作しなくても、実際の証明書の削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="744d5-149">The Batch service will perform the actual certificate deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="744d5-150">リソース (プールまたはコンピューティング ノード) が使用されている場合、証明書を削除することはできません。</span><span class="sxs-lookup"><span data-stu-id="744d5-150">You cannot delete a certificate if a resource (pool or compute node) is using it.</span></span> <span data-ttu-id="744d5-151">証明書を削除することができます、前にする必要がありますのでことを確認します。</span><span class="sxs-lookup"><span data-stu-id="744d5-151">Before you can delete a certificate, you must therefore make sure that:</span></span></para>
          <list type="bullet">
            <item>
              <description><span data-ttu-id="744d5-152">証明書は、すべてのプールに関連付けられていません。</span><span class="sxs-lookup"><span data-stu-id="744d5-152">The certificate is not associated with any pools.</span></span></description>
            </item>
            <item>
              <description><span data-ttu-id="744d5-153">証明書は、すべてのコンピューティング ノードにインストールされていません。</span><span class="sxs-lookup"><span data-stu-id="744d5-153">The certificate is not installed on any compute nodes.</span></span>  <span data-ttu-id="744d5-154">(プールから証明書を削除した場合でもは削除されません、プール内の既存のコンピューティング ノードから再起動するまで。)</span><span class="sxs-lookup"><span data-stu-id="744d5-154">(Even if you remove a certificate from a pool, it is not removed from existing compute nodes in that pool until they restart.)</span></span></description>
            </item>
          </list>
          <para><span data-ttu-id="744d5-155">使用されている証明書を削除しようとすると、削除は失敗します。</span><span class="sxs-lookup"><span data-stu-id="744d5-155">If you try to delete a certificate that is in use, the deletion fails.</span></span> <span data-ttu-id="744d5-156">証明書の状態を変更する<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />です。</span><span class="sxs-lookup"><span data-stu-id="744d5-156">The certificate state changes to <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />.</span></span>
            <span data-ttu-id="744d5-157">使用することができます<see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />には、証明書の使用を続行することを決定する場合、アクティブに状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="744d5-157">You can use <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> to set the status back to Active if you decide that you want to continue using the certificate.</span></span></para>
          <para><span data-ttu-id="744d5-158">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="744d5-158">This is a blocking operation.</span></span> <span data-ttu-id="744d5-159">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="744d5-159">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteCertificateAsync (string thumbprintAlgorithm, string thumbprint, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteCertificateAsync(string thumbprintAlgorithm, string thumbprint, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteCertificateAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="certificateOperations.DeleteCertificateAsync (thumbprintAlgorithm, thumbprint, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CertificateOperations/&lt;DeleteCertificateAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm"><span data-ttu-id="744d5-160">派生に使用するアルゴリズム、<paramref name="thumbprint" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="744d5-160">The algorithm used to derive the <paramref name="thumbprint" /> parameter.</span></span> <span data-ttu-id="744d5-161">これには、sha1 があります。</span><span class="sxs-lookup"><span data-stu-id="744d5-161">This must be sha1.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="744d5-162">削除する証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="744d5-162">The thumbprint of the certificate to delete.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="744d5-163">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="744d5-163">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="744d5-164">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="744d5-164">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="744d5-165">Batch アカウントから証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="744d5-165">Deletes the certificate from the Batch account.</span></span>
            </summary>
        <returns><span data-ttu-id="744d5-166">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="744d5-166">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="744d5-167">削除操作は、証明書が削除されることを要求します。</span><span class="sxs-lookup"><span data-stu-id="744d5-167">The delete operation requests that the certificate be deleted.</span></span>  <span data-ttu-id="744d5-168">要求に証明書を格納する、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="744d5-168">The request puts the certificate in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" /> state.</span></span>
            <span data-ttu-id="744d5-169">バッチ サービスでは、その他のクライアント操作しなくても、実際の証明書の削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="744d5-169">The Batch service will perform the actual certificate deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="744d5-170">リソース (プールまたはコンピューティング ノード) が使用されている場合、証明書を削除することはできません。</span><span class="sxs-lookup"><span data-stu-id="744d5-170">You cannot delete a certificate if a resource (pool or compute node) is using it.</span></span> <span data-ttu-id="744d5-171">証明書を削除することができます、前にする必要がありますのでことを確認します。</span><span class="sxs-lookup"><span data-stu-id="744d5-171">Before you can delete a certificate, you must therefore make sure that:</span></span></para>
          <list type="bullet">
            <item>
              <description><span data-ttu-id="744d5-172">証明書は、すべてのプールに関連付けられていません。</span><span class="sxs-lookup"><span data-stu-id="744d5-172">The certificate is not associated with any pools.</span></span></description>
            </item>
            <item>
              <description><span data-ttu-id="744d5-173">証明書は、すべてのコンピューティング ノードにインストールされていません。</span><span class="sxs-lookup"><span data-stu-id="744d5-173">The certificate is not installed on any compute nodes.</span></span>  <span data-ttu-id="744d5-174">(プールから証明書を削除した場合でもは削除されません、プール内の既存のコンピューティング ノードから再起動するまで。)</span><span class="sxs-lookup"><span data-stu-id="744d5-174">(Even if you remove a certificate from a pool, it is not removed from existing compute nodes in that pool until they restart.)</span></span></description>
            </item>
          </list>
          <para><span data-ttu-id="744d5-175">使用されている証明書を削除しようとすると、削除は失敗します。</span><span class="sxs-lookup"><span data-stu-id="744d5-175">If you try to delete a certificate that is in use, the deletion fails.</span></span> <span data-ttu-id="744d5-176">証明書の状態を変更する<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />です。</span><span class="sxs-lookup"><span data-stu-id="744d5-176">The certificate state changes to <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />.</span></span>
            <span data-ttu-id="744d5-177">使用することができます<see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />には、証明書の使用を続行することを決定する場合、アクティブに状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="744d5-177">You can use <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> to set the status back to Active if you decide that you want to continue using the certificate.</span></span></para>
          <para><span data-ttu-id="744d5-178">削除操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="744d5-178">The delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate GetCertificate (string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate GetCertificate(string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.GetCertificate(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetCertificate : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.GetCertificate (thumbprintAlgorithm, thumbprint, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm"><span data-ttu-id="744d5-179">派生に使用するアルゴリズム、<paramref name="thumbprint" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="744d5-179">The algorithm used to derive the <paramref name="thumbprint" /> parameter.</span></span> <span data-ttu-id="744d5-180">これには、sha1 があります。</span><span class="sxs-lookup"><span data-stu-id="744d5-180">This must be sha1.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="744d5-181">取得する証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="744d5-181">The thumbprint of the certificate to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="744d5-182">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="744d5-182">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="744d5-183">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="744d5-183">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="744d5-184">指定した <see cref="T:Microsoft.Azure.Batch.Certificate" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="744d5-184">Gets the specified <see cref="T:Microsoft.Azure.Batch.Certificate" />.</span></span>
            </summary>
        <returns><span data-ttu-id="744d5-185">A <see cref="T:Microsoft.Azure.Batch.Certificate" /> Azure Batch アカウントに指定された証明書に関する情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="744d5-185">A <see cref="T:Microsoft.Azure.Batch.Certificate" /> containing information about the specified certificate in the Azure Batch account.</span></span></returns>
        <remarks><span data-ttu-id="744d5-186">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="744d5-186">This is a blocking operation.</span></span> <span data-ttu-id="744d5-187">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CertificateOperations.GetCertificateAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="744d5-187">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CertificateOperations.GetCertificateAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Certificate&gt; GetCertificateAsync (string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Certificate&gt; GetCertificateAsync(string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.GetCertificateAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetCertificateAsync : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Certificate&gt;" Usage="certificateOperations.GetCertificateAsync (thumbprintAlgorithm, thumbprint, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CertificateOperations/&lt;GetCertificateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm"><span data-ttu-id="744d5-188">派生に使用するアルゴリズム、<paramref name="thumbprint" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="744d5-188">The algorithm used to derive the <paramref name="thumbprint" /> parameter.</span></span> <span data-ttu-id="744d5-189">これには、sha1 があります。</span><span class="sxs-lookup"><span data-stu-id="744d5-189">This must be sha1.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="744d5-190">取得する証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="744d5-190">The thumbprint of the certificate to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="744d5-191">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="744d5-191">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="744d5-192">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="744d5-192">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="744d5-193">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="744d5-193">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="744d5-194">指定した <see cref="T:Microsoft.Azure.Batch.Certificate" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="744d5-194">Gets the specified <see cref="T:Microsoft.Azure.Batch.Certificate" />.</span></span>
            </summary>
        <returns><span data-ttu-id="744d5-195">A <see cref="T:Microsoft.Azure.Batch.Certificate" /> Azure Batch アカウントに指定された証明書に関する情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="744d5-195">A <see cref="T:Microsoft.Azure.Batch.Certificate" /> containing information about the specified certificate in the Azure Batch account.</span></span></returns>
        <remarks><span data-ttu-id="744d5-196">証明書の取得操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="744d5-196">The get certificate operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCertificates">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.Certificate&gt; ListCertificates (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.Certificate&gt; ListCertificates(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.ListCertificates(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListCertificates : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.Certificate&gt;" Usage="certificateOperations.ListCertificates (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="744d5-197">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="744d5-197">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="744d5-198">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="744d5-198">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="744d5-199">列挙、<see cref="T:Microsoft.Azure.Batch.Certificate">証明書</see>Batch アカウントにします。</span><span class="sxs-lookup"><span data-stu-id="744d5-199">Enumerates the <see cref="T:Microsoft.Azure.Batch.Certificate">certificates</see> in the Batch account.</span></span>
            </summary>
        <returns><span data-ttu-id="744d5-200"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を非同期的または同期的に、証明書を列挙を使用できます。</span><span class="sxs-lookup"><span data-stu-id="744d5-200">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate certificates asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="744d5-201">このメソッドがすぐに戻る証明書は、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。</span><span class="sxs-lookup"><span data-stu-id="744d5-201">This method returns immediately; the certificates are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="744d5-202">検索は非アトミックなです。証明書は、コレクションの列挙中にページで取得されます。</span><span class="sxs-lookup"><span data-stu-id="744d5-202">Retrieval is non-atomic; certificates are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>