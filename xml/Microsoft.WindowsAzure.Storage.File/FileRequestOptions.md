<Type Name="FileRequestOptions" FullName="Microsoft.WindowsAzure.Storage.File.FileRequestOptions">
  <TypeSignature Language="C#" Value="public sealed class FileRequestOptions : Microsoft.WindowsAzure.Storage.IRequestOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FileRequestOptions extends System.Object implements class Microsoft.WindowsAzure.Storage.IRequestOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FileRequestOptions&#xA;Implements IRequestOptions" />
  <TypeSignature Language="F#" Value="type FileRequestOptions = class&#xA;    interface IRequestOptions" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.IRequestOptions</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="94f03-101">ファイル サービスに対する要求で指定できるタイムアウトと再試行のポリシーのオプションのセットを表します。</span><span class="sxs-lookup"><span data-stu-id="94f03-101">Represents a set of timeout and retry policy options that may be specified for a request against the File service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileRequestOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.FileRequestOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="94f03-102"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="94f03-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableContentMD5Validation">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DisableContentMD5Validation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DisableContentMD5Validation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileRequestOptions.DisableContentMD5Validation" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableContentMD5Validation As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DisableContentMD5Validation : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.File.FileRequestOptions.DisableContentMD5Validation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94f03-103">取得またはファイルをダウンロードするときに、MD5 検証を無効にすることを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="94f03-103">Gets or sets a value to indicate that MD5 validation will be disabled when downloading files.</span></span>
            </summary>
        <value><span data-ttu-id="94f03-104">True を使用して、MD5 検証を無効にするにはMD5 検証を有効にする場合は false。</span><span class="sxs-lookup"><span data-stu-id="94f03-104">Use true to disable MD5 validation; false to enable MD5 validation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocationMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; LocationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; LocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileRequestOptions.LocationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property LocationMode As Nullable(Of LocationMode)" />
      <MemberSignature Language="F#" Value="member this.LocationMode : Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.File.FileRequestOptions.LocationMode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.LocationMode</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94f03-105">取得または要求の配置モードを設定します。</span><span class="sxs-lookup"><span data-stu-id="94f03-105">Gets or sets the location mode of the request.</span></span>
            </summary>
        <value><span data-ttu-id="94f03-106">要求の配置モードです。</span><span class="sxs-lookup"><span data-stu-id="94f03-106">The location mode of the request.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumExecutionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaximumExecutionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaximumExecutionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileRequestOptions.MaximumExecutionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumExecutionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaximumExecutionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.File.FileRequestOptions.MaximumExecutionTime" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.MaximumExecutionTime</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94f03-107">取得または要求のすべての潜在的な再試行の最大実行時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="94f03-107">Gets or sets the maximum execution time across all potential retries for the request.</span></span> 
            </summary>
        <value><span data-ttu-id="94f03-108">A<see cref="T:System.TimeSpan" />要求の再試行の最大実行時間を表すです。</span><span class="sxs-lookup"><span data-stu-id="94f03-108">A <see cref="T:System.TimeSpan" /> representing the maximum execution time for retries for the request.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParallelOperationThreadCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ParallelOperationThreadCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ParallelOperationThreadCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileRequestOptions.ParallelOperationThreadCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ParallelOperationThreadCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ParallelOperationThreadCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.File.FileRequestOptions.ParallelOperationThreadCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94f03-109">取得またはファイルのアップロード時に同時にアップロードできる範囲の数を設定します。</span><span class="sxs-lookup"><span data-stu-id="94f03-109">Gets or sets the number of ranges that may be simultaneously uploaded when uploading a file.</span></span>
            </summary>
        <value><span data-ttu-id="94f03-110">実行できる並列操作の数。</span><span class="sxs-lookup"><span data-stu-id="94f03-110">The number of parallel operations that may proceed.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireEncryption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequireEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequireEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileRequestOptions.RequireEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireEncryption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequireEncryption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.File.FileRequestOptions.RequireEncryption" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.RequireEncryption</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94f03-111">取得またはクライアント ライブラリによって読み取りし、書き込みのデータを暗号化するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="94f03-111">Gets or sets a value to indicate whether data written and read by the client library should be encrypted.</span></span>
            </summary>
        <value><span data-ttu-id="94f03-112">使用して<c>true</c>すべてのトランザクションの暗号化/暗号化解除、それ以外のデータがする必要がありますを指定する<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="94f03-112">Use <c>true</c> to specify that data should be encrypted/decrypted for all transactions; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileRequestOptions.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As IRetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.File.FileRequestOptions.RetryPolicy" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.RetryPolicy</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94f03-113">取得または再試行ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="94f03-113">Gets or sets the retry policy.</span></span>
            </summary>
        <value><span data-ttu-id="94f03-114">再試行ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="94f03-114">The retry policy.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ServerTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ServerTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileRequestOptions.ServerTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ServerTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.File.FileRequestOptions.ServerTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.ServerTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94f03-115">取得または、サーバーに要求のタイムアウト間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="94f03-115">Gets or sets the server timeout interval for the request.</span></span>
            </summary>
        <value><span data-ttu-id="94f03-116">要求に対するサーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="94f03-116">The server timeout interval for the request.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreFileContentMD5">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; StoreFileContentMD5 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; StoreFileContentMD5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileRequestOptions.StoreFileContentMD5" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreFileContentMD5 As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.StoreFileContentMD5 : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.File.FileRequestOptions.StoreFileContentMD5" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94f03-117">取得または MD5 ハッシュが計算およびファイルのアップロード時に格納されていることを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="94f03-117">Gets or sets a value to indicate that an MD5 hash will be calculated and stored when uploading a file.</span></span>
            </summary>
        <value><span data-ttu-id="94f03-118">True を使用して計算して; ファイルのアップロード時に MD5 ハッシュを保存するにはそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="94f03-118">Use true to calculate and store an MD5 hash when uploading a file; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseTransactionalMD5">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UseTransactionalMD5 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UseTransactionalMD5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileRequestOptions.UseTransactionalMD5" />
      <MemberSignature Language="VB.NET" Value="Public Property UseTransactionalMD5 As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UseTransactionalMD5 : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.File.FileRequestOptions.UseTransactionalMD5" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94f03-119">取得または計算し、トランザクションの content MD5 の送信/検証する値を設定します。</span><span class="sxs-lookup"><span data-stu-id="94f03-119">Gets or sets a value to calculate and send/validate content MD5 for transactions.</span></span>
            </summary>
        <value><span data-ttu-id="94f03-120">使用して<c>true</c>を計算し、トランザクションの content MD5 の送信/検証するそれ以外の場合、 <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="94f03-120">Use <c>true</c> to calculate and send/validate content MD5 for transactions; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>