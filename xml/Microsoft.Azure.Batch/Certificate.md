<Type Name="Certificate" FullName="Microsoft.Azure.Batch.Certificate">
  <TypeSignature Language="C#" Value="public class Certificate : Microsoft.Azure.Batch.IInheritedBehaviors, Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Certificate extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors, class Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Certificate" />
  <TypeSignature Language="VB.NET" Value="Public Class Certificate&#xA;Implements IInheritedBehaviors, IRefreshable" />
  <TypeSignature Language="F#" Value="type Certificate = class&#xA;    interface IRefreshable&#xA;    interface ITransportObjectProvider&lt;CertificateAddParameter&gt;&#xA;    interface IInheritedBehaviors&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IRefreshable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="c8495-101">インストールされていることを証明書を使用して、計算ノード、ノードで操作を認証に使用することができます。</span><span class="sxs-lookup"><span data-stu-id="c8495-101">A certificate that can be installed on compute nodes and can be used to authenticate operations on a node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelDelete">
      <MemberSignature Language="C#" Value="public void CancelDelete (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CancelDelete(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Certificate.CancelDelete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CancelDelete (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.CancelDelete : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="certificate.CancelDelete additionalBehaviors" />
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
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="c8495-102">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-102">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="c8495-103">証明書の削除に失敗をキャンセルします。</span><span class="sxs-lookup"><span data-stu-id="c8495-103">Cancels a failed deletion of the certificate.</span></span>  <span data-ttu-id="c8495-104">これは、ため、証明書が、場合にのみ、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />状態、および復元する証明書、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" />状態です。</span><span class="sxs-lookup"><span data-stu-id="c8495-104">This can be done only when the certificate is in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> state, and restores the certificate to the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> state.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="c8495-105">(アクティブなへの返送) ではなく証明書を削除する場合は、失敗した削除をキャンセルする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="c8495-105">If you still wish to delete the certificate (instead of returning it to Active), you do not need to cancel the failed deletion.</span></span> <span data-ttu-id="c8495-106">証明書がすべてのリソースで使用されていないと、し、再度試行できる証明書を削除することを確認する必要があります (を参照してください<see cref="M:Microsoft.Azure.Batch.Certificate.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-106">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate (see <see cref="M:Microsoft.Azure.Batch.Certificate.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></para>
          <para><span data-ttu-id="c8495-107">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="c8495-107">This is a blocking operation.</span></span> <span data-ttu-id="c8495-108">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.Certificate.CancelDeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-108">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.Certificate.CancelDeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelDeleteAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelDeleteAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Certificate.CancelDeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelDeleteAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="certificate.CancelDeleteAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Certificate/&lt;CancelDeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="c8495-109">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-109">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c8495-110">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="c8495-110">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="c8495-111">証明書の削除に失敗をキャンセルします。</span><span class="sxs-lookup"><span data-stu-id="c8495-111">Cancels a failed deletion of the certificate.</span></span>  <span data-ttu-id="c8495-112">これは、ため、証明書が、場合にのみ、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />状態、および復元する証明書、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" />状態です。</span><span class="sxs-lookup"><span data-stu-id="c8495-112">This can be done only when the certificate is in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> state, and restores the certificate to the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> state.</span></span>
            </summary>
        <returns><span data-ttu-id="c8495-113">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c8495-113">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="c8495-114">(アクティブなへの返送) ではなく証明書を削除する場合は、失敗した削除をキャンセルする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="c8495-114">If you still wish to delete the certificate (instead of returning it to Active), you do not need to cancel the failed deletion.</span></span> <span data-ttu-id="c8495-115">証明書がすべてのリソースで使用されていないと、し、再度試行できる証明書を削除することを確認する必要があります (を参照してください<see cref="M:Microsoft.Azure.Batch.Certificate.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-115">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate (see <see cref="M:Microsoft.Azure.Batch.Certificate.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="c8495-116">キャンセルは、非同期的に操作の実行を削除します。</span><span class="sxs-lookup"><span data-stu-id="c8495-116">The cancel delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateFormat">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.CertificateFormat&gt; CertificateFormat { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.CertificateFormat&gt; CertificateFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.CertificateFormat" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CertificateFormat As Nullable(Of CertificateFormat)" />
      <MemberSignature Language="F#" Value="member this.CertificateFormat : Nullable&lt;Microsoft.Azure.Batch.Common.CertificateFormat&gt;" Usage="Microsoft.Azure.Batch.Certificate.CertificateFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.CertificateFormat&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8495-117">証明書のデータの形式を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8495-117">Gets the format of the certificate data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="public void Commit (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Commit(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Certificate.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Commit (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Commit : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="certificate.Commit additionalBehaviors" />
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
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="c8495-118">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-118">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="c8495-119">Batch アカウントに、証明書を追加します。</span><span class="sxs-lookup"><span data-stu-id="c8495-119">Adds the certificate to the Batch account.</span></span>
            </summary>
        <remarks><span data-ttu-id="c8495-120">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="c8495-120">This is a blocking operation.</span></span> <span data-ttu-id="c8495-121">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.Certificate.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-121">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.Certificate.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Certificate.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="certificate.CommitAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Certificate/&lt;CommitAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="c8495-122">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-122">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c8495-123">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="c8495-123">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="c8495-124">Batch アカウントに、証明書を追加します。</span><span class="sxs-lookup"><span data-stu-id="c8495-124">Adds the certificate to the Batch account.</span></span>
            </summary>
        <returns><span data-ttu-id="c8495-125">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="c8495-125">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="c8495-126">コミット操作が非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="c8495-126">The commit operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.Certificate.CustomBehaviors" />
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
            <span data-ttu-id="c8495-127">取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.Certificate" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-127">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.Certificate" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="c8495-128">これらの動作は、子オブジェクトによって継承されます。</span><span class="sxs-lookup"><span data-stu-id="c8495-128">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="c8495-129">変更は、コレクションの順序で適用されます。</span><span class="sxs-lookup"><span data-stu-id="c8495-129">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="c8495-130">最後には、wins を記述します。</span><span class="sxs-lookup"><span data-stu-id="c8495-130">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public string Data { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Data" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.Data" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Data As String" />
      <MemberSignature Language="F#" Value="member this.Data : string" Usage="Microsoft.Azure.Batch.Certificate.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8495-131">未加工の証明書の base64 でエンコードされたデータを取得します (.pfx または .cer ファイルまたは元のデータの内容、<see cref="T:Microsoft.Azure.Batch.Certificate" />が作成された)。</span><span class="sxs-lookup"><span data-stu-id="c8495-131">Gets the base64-encoded raw certificate data (contents of the .pfx or .cer file or data from which the <see cref="T:Microsoft.Azure.Batch.Certificate" /> was created).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="c8495-132">新たに作成するときに、このプロパティは設定<see cref="T:Microsoft.Azure.Batch.Certificate" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-132">This property is set when creating a new <see cref="T:Microsoft.Azure.Batch.Certificate" />.</span></span> <span data-ttu-id="c8495-133">バッチ サービスから取得した証明書が定義されていません。</span><span class="sxs-lookup"><span data-stu-id="c8495-133">It is not defined for certificates retrieved from the Batch service.</span></span></para>
          <para><span data-ttu-id="c8495-134">最大サイズは、10 KB です。</span><span class="sxs-lookup"><span data-stu-id="c8495-134">The maximum size is 10 KB.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Delete(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Certificate.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Delete : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="certificate.Delete additionalBehaviors" />
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
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="c8495-135">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-135">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="c8495-136">Batch アカウントから証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="c8495-136">Deletes the certificate from the Batch account.</span></span>
            </summary>
        <returns><span data-ttu-id="c8495-137">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="c8495-137">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="c8495-138">削除操作は、証明書が削除されることを要求します。</span><span class="sxs-lookup"><span data-stu-id="c8495-138">The delete operation requests that the certificate be deleted.</span></span>  <span data-ttu-id="c8495-139">要求に証明書を格納する、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="c8495-139">The request puts the certificate in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" /> state.</span></span>
            <span data-ttu-id="c8495-140">バッチ サービスでは、その他のクライアント操作しなくても、実際の証明書の削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="c8495-140">The Batch service will perform the actual certificate deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="c8495-141">リソース (プールまたはコンピューティング ノード) が使用されている場合、証明書を削除することはできません。</span><span class="sxs-lookup"><span data-stu-id="c8495-141">You cannot delete a certificate if a resource (pool or compute node) is using it.</span></span> <span data-ttu-id="c8495-142">証明書を削除することができます、前にする必要がありますのでことを確認します。</span><span class="sxs-lookup"><span data-stu-id="c8495-142">Before you can delete a certificate, you must therefore make sure that:</span></span></para>
          <list type="bullet">
            <item>
              <description><span data-ttu-id="c8495-143">証明書は、すべてのプールに関連付けられていません。</span><span class="sxs-lookup"><span data-stu-id="c8495-143">The certificate is not associated with any pools.</span></span></description>
            </item>
            <item>
              <description><span data-ttu-id="c8495-144">証明書は、すべてのコンピューティング ノードにインストールされていません。</span><span class="sxs-lookup"><span data-stu-id="c8495-144">The certificate is not installed on any compute nodes.</span></span>  <span data-ttu-id="c8495-145">(プールから証明書を削除した場合でもは削除されません、プール内の既存のコンピューティング ノードから再起動するまで。)</span><span class="sxs-lookup"><span data-stu-id="c8495-145">(Even if you remove a certificate from a pool, it is not removed from existing compute nodes in that pool until they restart.)</span></span></description>
            </item>
          </list>
          <para><span data-ttu-id="c8495-146">使用されている証明書を削除しようとすると、削除は失敗します。</span><span class="sxs-lookup"><span data-stu-id="c8495-146">If you try to delete a certificate that is in use, the deletion fails.</span></span> <span data-ttu-id="c8495-147">証明書の状態を変更する<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-147">The certificate state changes to <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />.</span></span>
            <span data-ttu-id="c8495-148">使用することができます<see cref="M:Microsoft.Azure.Batch.Certificate.CancelDeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />には、証明書の使用を続行することを決定する場合、アクティブに状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8495-148">You can use <see cref="M:Microsoft.Azure.Batch.Certificate.CancelDeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> to set the status back to Active if you decide that you want to continue using the certificate.</span></span></para>
          <para><span data-ttu-id="c8495-149">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="c8495-149">This is a blocking operation.</span></span> <span data-ttu-id="c8495-150">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.Certificate.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-150">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.Certificate.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Certificate.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="certificate.DeleteAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Certificate/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="c8495-151">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-151">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c8495-152">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="c8495-152">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="c8495-153">Batch アカウントから証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="c8495-153">Deletes the certificate from the Batch account.</span></span>
            </summary>
        <returns><span data-ttu-id="c8495-154">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="c8495-154">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="c8495-155">削除操作は、証明書が削除されることを要求します。</span><span class="sxs-lookup"><span data-stu-id="c8495-155">The delete operation requests that the certificate be deleted.</span></span>  <span data-ttu-id="c8495-156">要求に証明書を格納する、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="c8495-156">The request puts the certificate in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" /> state.</span></span>
            <span data-ttu-id="c8495-157">バッチ サービスでは、その他のクライアント操作しなくても、実際の証明書の削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="c8495-157">The Batch service will perform the actual certificate deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="c8495-158">リソース (プールまたはコンピューティング ノード) が使用されている場合、証明書を削除することはできません。</span><span class="sxs-lookup"><span data-stu-id="c8495-158">You cannot delete a certificate if a resource (pool or compute node) is using it.</span></span> <span data-ttu-id="c8495-159">証明書を削除することができます、前にする必要がありますのでことを確認します。</span><span class="sxs-lookup"><span data-stu-id="c8495-159">Before you can delete a certificate, you must therefore make sure that:</span></span></para>
          <list type="bullet">
            <item>
              <description><span data-ttu-id="c8495-160">証明書は、すべてのプールに関連付けられていません。</span><span class="sxs-lookup"><span data-stu-id="c8495-160">The certificate is not associated with any pools.</span></span></description>
            </item>
            <item>
              <description><span data-ttu-id="c8495-161">証明書は、すべてのコンピューティング ノードにインストールされていません。</span><span class="sxs-lookup"><span data-stu-id="c8495-161">The certificate is not installed on any compute nodes.</span></span>  <span data-ttu-id="c8495-162">(プールから証明書を削除した場合でもは削除されません、プール内の既存のコンピューティング ノードから再起動するまで。)</span><span class="sxs-lookup"><span data-stu-id="c8495-162">(Even if you remove a certificate from a pool, it is not removed from existing compute nodes in that pool until they restart.)</span></span></description>
            </item>
          </list>
          <para><span data-ttu-id="c8495-163">使用されている証明書を削除しようとすると、削除は失敗します。</span><span class="sxs-lookup"><span data-stu-id="c8495-163">If you try to delete a certificate that is in use, the deletion fails.</span></span> <span data-ttu-id="c8495-164">証明書の状態を変更する<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-164">The certificate state changes to <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />.</span></span>
            <span data-ttu-id="c8495-165">使用することができます<see cref="M:Microsoft.Azure.Batch.Certificate.CancelDeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />には、証明書の使用を続行することを決定する場合、アクティブに状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8495-165">You can use <see cref="M:Microsoft.Azure.Batch.Certificate.CancelDeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> to set the status back to Active if you decide that you want to continue using the certificate.</span></span></para>
          <para><span data-ttu-id="c8495-166">削除操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="c8495-166">The delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.DeleteCertificateError DeleteCertificateError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.DeleteCertificateError DeleteCertificateError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.DeleteCertificateError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeleteCertificateError As DeleteCertificateError" />
      <MemberSignature Language="F#" Value="member this.DeleteCertificateError : Microsoft.Azure.Batch.DeleteCertificateError" Usage="Microsoft.Azure.Batch.Certificate.DeleteCertificateError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.DeleteCertificateError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8495-167">この証明書を削除するのには、前回の試行で発生したエラーを取得します。</span><span class="sxs-lookup"><span data-stu-id="c8495-167">Gets the error that occurred on the last attempt to delete this certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8495-168">このプロパティが null で、証明書がない限り、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />状態です。</span><span class="sxs-lookup"><span data-stu-id="c8495-168">This property is null unless the certificate is in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.Password" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string" Usage="Microsoft.Azure.Batch.Certificate.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8495-169">証明書の秘密キーにアクセスするパスワードを取得します。</span><span class="sxs-lookup"><span data-stu-id="c8495-169">Gets the password to access the certificate private key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8495-170">新たに作成するときに、このプロパティは設定<see cref="T:Microsoft.Azure.Batch.Certificate" />.pfx 形式のデータから (を参照してください<see cref="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.Byte[],System.String)" />と<see cref="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.String,System.String)" />)。</span><span class="sxs-lookup"><span data-stu-id="c8495-170">This property is set when creating a new <see cref="T:Microsoft.Azure.Batch.Certificate" /> from .pfx format data (see <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.Byte[],System.String)" /> and <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.String,System.String)" />).</span></span> <span data-ttu-id="c8495-171">バッチ サービスから取得した証明書が定義されていません。</span><span class="sxs-lookup"><span data-stu-id="c8495-171">It is not defined for certificates retrieved from the Batch service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.CertificateState&gt; PreviousState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.CertificateState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousState As Nullable(Of CertificateState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Common.CertificateState&gt;" Usage="Microsoft.Azure.Batch.Certificate.PreviousState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.CertificateState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8495-172">証明書の以前の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8495-172">Gets the previous state of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8495-173">証明書は、初期場合<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" />状態、PreviousState プロパティが定義されていません。</span><span class="sxs-lookup"><span data-stu-id="c8495-173">If the certificate is in its initial <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> state, the PreviousState property is not defined.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.Certificate.PreviousStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8495-174">証明書が以前の状態を入力する時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8495-174">Gets the time at which the certificate entered its previous state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8495-175">証明書は、初期場合<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" />状態、PreviousStateTransitionTime プロパティが定義されていません。</span><span class="sxs-lookup"><span data-stu-id="c8495-175">If the certificate is in its initial <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> state, the PreviousStateTransitionTime property is not defined.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicData">
      <MemberSignature Language="C#" Value="public string PublicData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.PublicData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicData As String" />
      <MemberSignature Language="F#" Value="member this.PublicData : string" Usage="Microsoft.Azure.Batch.Certificate.PublicData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8495-176">証明書のパブリックの部分を base 64 でエンコードされた .cer 形式のデータを含む文字列として取得します。</span><span class="sxs-lookup"><span data-stu-id="c8495-176">Gets the public part of the certificate as a string containing base-64 encoded .cer format data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public void Refresh (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Refresh(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Certificate.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="abstract member Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit&#xA;override this.Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="certificate.Refresh (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="c8495-177">最新の更新の詳細レベルです。</span><span class="sxs-lookup"><span data-stu-id="c8495-177">The detail level for the refresh.</span></span>  <span data-ttu-id="c8495-178">詳細レベルを省略する場合、<see cref="P:Microsoft.Azure.Batch.Certificate.Thumbprint" />または<see cref="P:Microsoft.Azure.Batch.Certificate.ThumbprintAlgorithm" />プロパティを指定すると、更新は失敗します。</span><span class="sxs-lookup"><span data-stu-id="c8495-178">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.Certificate.Thumbprint" /> or <see cref="P:Microsoft.Azure.Batch.Certificate.ThumbprintAlgorithm" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="c8495-179">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-179">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="c8495-180">現在の更新<see cref="T:Microsoft.Azure.Batch.Certificate" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-180">Refreshes the current <see cref="T:Microsoft.Azure.Batch.Certificate" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Certificate.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="certificate.RefreshAsync (detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Certificate/&lt;RefreshAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="c8495-181">最新の更新の詳細レベルです。</span><span class="sxs-lookup"><span data-stu-id="c8495-181">The detail level for the refresh.</span></span>  <span data-ttu-id="c8495-182">詳細レベルを省略する場合、<see cref="P:Microsoft.Azure.Batch.Certificate.Thumbprint" />または<see cref="P:Microsoft.Azure.Batch.Certificate.ThumbprintAlgorithm" />プロパティを指定すると、更新は失敗します。</span><span class="sxs-lookup"><span data-stu-id="c8495-182">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.Certificate.Thumbprint" /> or <see cref="P:Microsoft.Azure.Batch.Certificate.ThumbprintAlgorithm" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="c8495-183">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-183">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c8495-184">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="c8495-184">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="c8495-185">現在の更新<see cref="T:Microsoft.Azure.Batch.Certificate" />です。</span><span class="sxs-lookup"><span data-stu-id="c8495-185">Refreshes the current <see cref="T:Microsoft.Azure.Batch.Certificate" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c8495-186">A<see cref="T:System.Threading.Tasks.Task" />非同期更新操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="c8495-186">A <see cref="T:System.Threading.Tasks.Task" /> representing the asynchronous refresh operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.CertificateState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.CertificateState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of CertificateState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Common.CertificateState&gt;" Usage="Microsoft.Azure.Batch.Certificate.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.CertificateState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8495-187">証明書の現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8495-187">Gets the current state of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.Certificate.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8495-188">証明書が、現在の状態を入力するされた時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8495-188">Gets the time at which the certificate entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string" Usage="Microsoft.Azure.Batch.Certificate.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8495-189">証明書の拇印を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8495-189">Gets the thumbprint of the certificate.</span></span> <span data-ttu-id="c8495-190">これは、最大 40 の 16 進数字のシーケンスです。</span><span class="sxs-lookup"><span data-stu-id="c8495-190">This is a sequence of up to 40 hex digits.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintAlgorithm">
      <MemberSignature Language="C#" Value="public string ThumbprintAlgorithm { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.ThumbprintAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ThumbprintAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintAlgorithm : string" Usage="Microsoft.Azure.Batch.Certificate.ThumbprintAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8495-191">拇印の派生に使用するアルゴリズムを取得します。</span><span class="sxs-lookup"><span data-stu-id="c8495-191">Gets the algorithm used to derive the thumbprint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.Certificate.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8495-192">証明書の URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8495-192">Gets the URL of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>