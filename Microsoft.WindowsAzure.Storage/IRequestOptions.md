<Type Name="IRequestOptions" FullName="Microsoft.WindowsAzure.Storage.IRequestOptions">
  <TypeSignature Language="C#" Value="public interface IRequestOptions" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRequestOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.IRequestOptions" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRequestOptions" />
  <TypeSignature Language="F#" Value="type IRequestOptions = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="79913-101">要求のオプションの種類に必要なインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="79913-101">An interface required for request option types.</span></span>
            </summary>
    <remarks><span data-ttu-id="79913-102"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />、 <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />、および<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />クラスで実装、<see cref="T:Microsoft.WindowsAzure.Storage.IRequestOptions" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="79913-102">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />, <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />, and <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> classes implement the <see cref="T:Microsoft.WindowsAzure.Storage.IRequestOptions" /> interface.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="LocationMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; LocationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; LocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IRequestOptions.LocationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property LocationMode As Nullable(Of LocationMode)" />
      <MemberSignature Language="F#" Value="member this.LocationMode : Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.IRequestOptions.LocationMode" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="79913-103">取得または要求の配置モードを設定します。</span><span class="sxs-lookup"><span data-stu-id="79913-103">Gets or sets the location mode of the request.</span></span>
            </summary>
        <value><span data-ttu-id="79913-104"><see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="79913-104">A <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" /> enumeration value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumExecutionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaximumExecutionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaximumExecutionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IRequestOptions.MaximumExecutionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumExecutionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaximumExecutionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.IRequestOptions.MaximumExecutionTime" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="79913-105">取得またはすべての潜在的な再試行の最大実行時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="79913-105">Gets or sets the maximum execution time across all potential retries.</span></span>
            </summary>
        <value><span data-ttu-id="79913-106">A<see cref="T:System.TimeSpan" />すべて潜在的な再試行の最大実行時間を格納しています。</span><span class="sxs-lookup"><span data-stu-id="79913-106">A <see cref="T:System.TimeSpan" /> containing the maximum execution time across all potential retries.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireEncryption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequireEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequireEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IRequestOptions.RequireEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireEncryption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequireEncryption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.IRequestOptions.RequireEncryption" />
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
            <span data-ttu-id="79913-107">取得またはクライアント ライブラリによって読み取りし、書き込みのデータを暗号化するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="79913-107">Gets or sets a value to indicate whether data written and read by the client library should be encrypted.</span></span>
            </summary>
        <value><span data-ttu-id="79913-108">使用して<c>true</c>すべてのトランザクションの暗号化/暗号化解除、それ以外のデータがする必要がありますを指定する<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="79913-108">Use <c>true</c> to specify that data should be encrypted/decrypted for all transactions; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IRequestOptions.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As IRetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.IRequestOptions.RetryPolicy" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="79913-109">取得または要求の再試行ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="79913-109">Gets or sets the retry policy for the request.</span></span>
            </summary>
        <value><span data-ttu-id="79913-110"><see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" /> 型のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="79913-110">An object of type <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ServerTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ServerTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IRequestOptions.ServerTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ServerTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.IRequestOptions.ServerTimeout" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="79913-111">取得または要求の既定のサーバー タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="79913-111">Gets or sets the default server timeout for the request.</span></span>
            </summary>
        <value><span data-ttu-id="79913-112">A<see cref="T:System.TimeSpan" />サーバー タイムアウト間隔を表すです。</span><span class="sxs-lookup"><span data-stu-id="79913-112">A <see cref="T:System.TimeSpan" /> containing the server timeout interval.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>