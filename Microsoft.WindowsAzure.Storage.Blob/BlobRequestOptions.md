<Type Name="BlobRequestOptions" FullName="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions">
  <TypeSignature Language="C#" Value="public sealed class BlobRequestOptions : Microsoft.WindowsAzure.Storage.IRequestOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BlobRequestOptions extends System.Object implements class Microsoft.WindowsAzure.Storage.IRequestOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BlobRequestOptions&#xA;Implements IRequestOptions" />
  <TypeSignature Language="F#" Value="type BlobRequestOptions = class&#xA;    interface IRequestOptions" />
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
            Blob サービスに対する要求で指定できるタイムアウトと再試行のポリシーのオプションのセットを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobRequestOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.#ctor" />
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
            <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbsorbConditionalErrorsOnRetry">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AbsorbConditionalErrorsOnRetry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AbsorbConditionalErrorsOnRetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />
      <MemberSignature Language="VB.NET" Value="Public Property AbsorbConditionalErrorsOnRetry As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AbsorbConditionalErrorsOnRetry : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />
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
            取得または要求の再試行の条件付きの障害を吸収する必要があるかどうかを示す値を設定します。 
            </summary>
        <value>To be added.</value>
        <remarks>
            このオプションのみが使用、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" />内のオブジェクト、 <b>UploadFrom* </b>メソッド、 <b>AppendFrom* </b>メソッド、および<b>BlobWriteStream</b>クラスです。 既定では、その設定は<c>false</c>です。 このオプションを設定<c>true</c>単一ライターのシナリオに対してのみです。 このオプションを設定<c>true</c>マルチ ライターのシナリオで破損した blob データする可能性があります。
            
            追加 blob に対してを呼び出した「UploadFrom *」、ストレージ クライアントは、データ ブロックの数に、入力データを分割し、「追加ブロック操作には、各データ ブロックをアップロードします。
            通常、"IfAppendPositionEqual"アクセス条件は、他のプロセス任意の場所にこのデータ ストリームの途中でのデータが追加される場合、アップロード操作が失敗するので、append block 操作に追加されます。
            ただし、非常に特定の状況で、誤認エラーになります。 追加操作がタイムアウトした場合、サービスで操作が成功した可能性がありますが、「成功」応答でした、クライアントに返送します。
            この場合、クライアントは retry、および、「追加位置が満たされていません」エラーが発生します。
            
            この値を設定<c>true</c>上の考慮事項 アカウンティングの再試行時に「追加位置が満たされていません」エラーを確認した場合の続行アップロード操作の結果します。 ただし、これは失われますマルチ ライターのシナリオでの保護を一度に複数のスレッドを blob にアップロードすると、この値に設定されて<c>true</c>、一部のデータが失われる可能性がありますがそのため、クライアントから見ると、データがアップロードされた、ときに実際にはその他のプロセスのデータです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableContentMD5Validation">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DisableContentMD5Validation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DisableContentMD5Validation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.DisableContentMD5Validation" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableContentMD5Validation As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DisableContentMD5Validation : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.DisableContentMD5Validation" />
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
            取得または blob をダウンロードするときに、MD5 検証を無効にすることを示す値を設定します。
            </summary>
        <value>使用して<c>true</c> MD5 検証を無効にするには<c>false</c> MD5 検証を有効にします。 既定値は <c>false</c>です。</value>
        <remarks>
            Blob に値が既に存在する場合は、blob をダウンロードするとき、ストレージ サービスで全体の blob の MD5 ハッシュがヘッダーとして含まれます。 このオプションは、ストレージ クライアントがダウンロード時にその MD5 ハッシュを検証するかどうかを制御します。
            詳細については、「<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.StoreBlobContentMD5" />」を参照してください。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy EncryptionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy EncryptionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.EncryptionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionPolicy As BlobEncryptionPolicy" />
      <MemberSignature Language="F#" Value="member this.EncryptionPolicy : Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.EncryptionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または要求の暗号化ポリシーを設定します。
            </summary>
        <value><see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.EncryptionPolicy" /> 型のオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocationMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; LocationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; LocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.LocationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property LocationMode As Nullable(Of LocationMode)" />
      <MemberSignature Language="F#" Value="member this.LocationMode : Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.LocationMode" />
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
             取得または要求の配置モードを設定します。
             </summary>
        <value>A<see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" />要求の配置モードを示す列挙値。</value>
        <remarks>LocationMode では、場所、ストレージ クライアントが試みます、要求を行うことを指定します。 これはに対してのみ有効 RA-GRS アカウントのアカウントのプライマリまたはセカンダリ エンドポイントのいずれかからデータを読み取ることができます。
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumExecutionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaximumExecutionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaximumExecutionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.MaximumExecutionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumExecutionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaximumExecutionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.MaximumExecutionTime" />
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
            取得または要求のすべての潜在的な再試行の最大実行時間を設定します。 
            </summary>
        <value>A<see cref="T:System.TimeSpan" />要求の再試行の最大実行時間を表すです。</value>
        <remarks>
            最大実行時間は、単一の API 呼び出しに割り当てられた時間です。
            時間の合計費やされている場合、API のすべての REST 要求でなどの再試行は、この値を超えています。、クライアントがタイムアウトになります。 この値は、クライアントでのみ追跡される、サービスにいない送信されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ParallelOperationThreadCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ParallelOperationThreadCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ParallelOperationThreadCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.ParallelOperationThreadCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ParallelOperationThreadCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ParallelOperationThreadCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.ParallelOperationThreadCount" />
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
             取得または同時にアップロードできるブロックの数を設定します。
             </summary>
        <value>並列 blob の数を示す整数値では、実行できる操作をアップロードします。</value>
        <remarks>
             を blob に UploadFrom のメソッドを使用する場合、blob はブロック分割します。 この未処理 I/O「put ブロック」の要求に対して特定の時点で、ライブラリをインフライト必要がある値の制限を設定します。 既定値は、1 (並列処理) です。 この値を設定すると、クライアントと Azure ストレージ サービスの間のネットワークによって、高速な blob アップロード可能性があります。
             場合、blob は小 (256 MB 未満)、この値を 1 に等しい保持のことをお勧めします。
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireEncryption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequireEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequireEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.RequireEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireEncryption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequireEncryption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.RequireEncryption" />
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
            取得またはクライアント ライブラリによって読み取りし、書き込みのデータを暗号化するかどうかを示す値を設定します。
            </summary>
        <value>使用して<c>true</c>すべてのトランザクションの暗号化/暗号化解除、それ以外のデータがする必要がありますを指定する<c>false</c>です。</value>
        <remarks>
            RequireEncryption ここでは、クライアント側の暗号化を指します。
            この値に設定されている場合<c>true</c>データが暗号化と復号化の暗号化ポリシーを使用していない場合、すべての呼び出しは失敗します。 この値は false (既定)、ダウンロードされたすべてのデータ暗号化されていない場合として返されます-はします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As IRetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.RetryPolicy" />
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
             取得または要求の再試行ポリシーを設定します。
             </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" /> 型のオブジェクト。</value>
        <remarks> 再試行ポリシーでは、ストレージ クライアントの失敗した要求を再試行するように指示します。
             既定では、いくつかのエラーのみが再試行されます。 たとえば、接続の障害と調整エラーを再試行できます。 リソースが (404) が見つかりません。 または、これらは再試行時に成功する可能性がないため、認証エラーは再試行されません。
             指定しない場合、セット、ストレージ クライアントを使用して、指数バックオフの再試行ポリシーを待機時間が指数関数的に要求、合計で約 30 秒までの間隔が長くを取得します。
             ほとんどのシナリオには、既定の再試行ポリシーを使用することをお勧めします。
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ServerTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ServerTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.ServerTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ServerTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.ServerTimeout" />
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
            取得または 1 つの HTTP 要求に対するサーバー タイムアウト間隔を設定します。
            </summary>
        <value>A<see cref="T:System.TimeSpan" />各 HTTP 要求に対するサーバー タイムアウト間隔を表すです。</value>
        <remarks>
            サーバーのタイムアウトは、行われた各 REST 要求の Azure ストレージ サービスに送信されるタイムアウトです。 呼ばれる API は、複数の REST 呼び出しを行う場合 (UploadFromStream、たとえば、または要求を再試行する場合)、このタイムアウトは要求ごとに個別に適用されます。 この値は追跡または検証されていないクライアントで、記憶域サービスにのみ渡されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SingleBlobUploadThresholdInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SingleBlobUploadThresholdInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SingleBlobUploadThresholdInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.SingleBlobUploadThresholdInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property SingleBlobUploadThresholdInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SingleBlobUploadThresholdInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.SingleBlobUploadThresholdInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または 1 つの blob としてアップロードできるをバイト単位で blob の最大サイズを設定します。 
            </summary>
        <value>(バイト単位) を 1 mb ~ 256 MB までの範囲を 1 つの blob としてアップロードできる blob の最大サイズを示す long です。</value>
        <remarks>ParallelOperationThreadCount が 1 より大きい値に設定されている場合、この値は無視されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreBlobContentMD5">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; StoreBlobContentMD5 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; StoreBlobContentMD5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.StoreBlobContentMD5" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreBlobContentMD5 As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.StoreBlobContentMD5 : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.StoreBlobContentMD5" />
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
            取得または MD5 ハッシュが計算および blob のアップロード時に格納されていることを示す値を設定します。
            </summary>
        <value>使用して<c>true</c>計算して; blob のアップロード時に MD5 ハッシュを保存するそれ以外の場合、 <c>false</c>です。 既定値は<c>false</c>です。</value>
        <remarks>このプロパティはサポートされていません、 <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> Append * Api です。
            StoreBlobContentMD5 要求オプションでは、ストレージ クライアント アップロード処理中に、blob コンテンツの MD5 ハッシュを計算するように指示します。 Blob オブジェクトには、この値は content-md5 ヘッダーとして格納されます。 このオプションは、アップロード操作にのみ適用されます。 これは、以降のダウンロード時に、blob の整合性を検証するために役立ちますし、HTTP 仕様で定義されている content-md5 ヘッダーとの互換性。Content-md5 ヘッダーが存在する場合は、ストレージ クライアントあとのダウンロードを使用して場合は、"DisableContentMD5Validation"が設定されていない限り、コンテンツの MD5 ハッシュを検証するされます。
            この値がいずれかのアップロードまたはダウンロード データ; 上の Azure ストレージ サービスで検証しないことに注意してください。格納されているだけであり返されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UseTransactionalMD5">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UseTransactionalMD5 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UseTransactionalMD5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.UseTransactionalMD5" />
      <MemberSignature Language="VB.NET" Value="Public Property UseTransactionalMD5 As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UseTransactionalMD5 : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.UseTransactionalMD5" />
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
            取得または計算し、トランザクションの content MD5 の送信/検証する値を設定します。
            </summary>
        <value>使用して<c>true</c>を計算し、トランザクションの content MD5 の送信/検証するそれ以外の場合、 <c>false</c>です。 既定値は <c>false</c>です。</value>
        <remarks>
            UseTransactionalMD5 オプションでは、ストレージ クライアント計算し、個々 の記憶域の REST 操作の MD5 ハッシュを検証するように指示します。 指定した REST 操作では、この値が設定されている場合、ストレージ クライアントと記憶域サービスの両方、転送されたデータの MD5 ハッシュが計算され、値が一致しない場合は失敗します。
            この値は、サービスまたはクライアントには保存されません。
            このオプションは、アップロードし、ダウンロード操作の両方に適用されます。
            HTTPS の転送中のようなチェックはことに注意してください。 HTTPS を使用してこの機能はオフにすることをお勧めします。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>