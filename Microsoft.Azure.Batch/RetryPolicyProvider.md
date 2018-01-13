<Type Name="RetryPolicyProvider" FullName="Microsoft.Azure.Batch.RetryPolicyProvider">
  <TypeSignature Language="C#" Value="public class RetryPolicyProvider : Microsoft.Azure.Batch.Protocol.RequestInterceptor" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RetryPolicyProvider extends Microsoft.Azure.Batch.Protocol.RequestInterceptor" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.RetryPolicyProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class RetryPolicyProvider&#xA;Inherits RequestInterceptor" />
  <TypeSignature Language="F#" Value="type RetryPolicyProvider = class&#xA;    inherit RequestInterceptor" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.RequestInterceptor</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6883c-101">設定、RetryPolicy RequestInterceptor です。</span><span class="sxs-lookup"><span data-stu-id="6883c-101">A RequestInterceptor that sets the RetryPolicy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryPolicyProvider (Microsoft.Azure.Batch.Common.IRetryPolicy retryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Common.IRetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.RetryPolicyProvider.#ctor(Microsoft.Azure.Batch.Common.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (retryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.RetryPolicyProvider : Microsoft.Azure.Batch.Common.IRetryPolicy -&gt; Microsoft.Azure.Batch.RetryPolicyProvider" Usage="new Microsoft.Azure.Batch.RetryPolicyProvider retryPolicy" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.Batch.Common.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="retryPolicy"><span data-ttu-id="6883c-102">設定する再試行ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="6883c-102">The retry policy to set.</span></span></param>
        <summary>
            <span data-ttu-id="6883c-103">再試行ポリシーを設定する新しい動作を初期化します。</span><span class="sxs-lookup"><span data-stu-id="6883c-103">Initializes a new behavior to set the retry policy.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExponentialRetryProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.RetryPolicyProvider ExponentialRetryProvider (TimeSpan deltaBackoff, int maxRetries);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.RetryPolicyProvider ExponentialRetryProvider(valuetype System.TimeSpan deltaBackoff, int32 maxRetries) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.RetryPolicyProvider.ExponentialRetryProvider(System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ExponentialRetryProvider (deltaBackoff As TimeSpan, maxRetries As Integer) As RetryPolicyProvider" />
      <MemberSignature Language="F#" Value="static member ExponentialRetryProvider : TimeSpan * int -&gt; Microsoft.Azure.Batch.RetryPolicyProvider" Usage="Microsoft.Azure.Batch.RetryPolicyProvider.ExponentialRetryProvider (deltaBackoff, maxRetries)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.RetryPolicyProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deltaBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxRetries" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="deltaBackoff"><span data-ttu-id="6883c-104">ここで、結果として得られるバックオフは 2、再試行のバックオフ間隔 ^ n \* deltaBackoff (n は再試行の回数)</span><span class="sxs-lookup"><span data-stu-id="6883c-104">The backoff interval between retries, where the resulting backoff is 2^n \* deltaBackoff (where n is the number of retries)</span></span></param>
        <param name="maxRetries"><span data-ttu-id="6883c-105">再試行の最大数。</span><span class="sxs-lookup"><span data-stu-id="6883c-105">The maximum number of retry attempts.</span></span></param>
        <summary>
            <span data-ttu-id="6883c-106">新たに作成<see cref="T:Microsoft.Azure.Batch.RetryPolicyProvider" />を使用して、<see cref="T:Microsoft.Azure.Batch.Common.ExponentialRetry" />ポリシー。</span><span class="sxs-lookup"><span data-stu-id="6883c-106">Creates a new <see cref="T:Microsoft.Azure.Batch.RetryPolicyProvider" /> using the <see cref="T:Microsoft.Azure.Batch.Common.ExponentialRetry" /> policy.</span></span>
            </summary>
        <returns><span data-ttu-id="6883c-107">指定したバックオフと最大再試行回数を使用して指数の再試行を実行するように構成するプロバイダーです。</span><span class="sxs-lookup"><span data-stu-id="6883c-107">A provider configured to perform exponential retries using the specified backoff and max retries.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinearRetryProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.RetryPolicyProvider LinearRetryProvider (TimeSpan deltaBackoff, int maxRetries);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.RetryPolicyProvider LinearRetryProvider(valuetype System.TimeSpan deltaBackoff, int32 maxRetries) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.RetryPolicyProvider.LinearRetryProvider(System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function LinearRetryProvider (deltaBackoff As TimeSpan, maxRetries As Integer) As RetryPolicyProvider" />
      <MemberSignature Language="F#" Value="static member LinearRetryProvider : TimeSpan * int -&gt; Microsoft.Azure.Batch.RetryPolicyProvider" Usage="Microsoft.Azure.Batch.RetryPolicyProvider.LinearRetryProvider (deltaBackoff, maxRetries)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.RetryPolicyProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deltaBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxRetries" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="deltaBackoff"><span data-ttu-id="6883c-108">再試行のバックオフ間隔。</span><span class="sxs-lookup"><span data-stu-id="6883c-108">The backoff interval between retries.</span></span></param>
        <param name="maxRetries"><span data-ttu-id="6883c-109">再試行の最大数。</span><span class="sxs-lookup"><span data-stu-id="6883c-109">The maximum number of retry attempts.</span></span></param>
        <summary>
            <span data-ttu-id="6883c-110">新たに作成<see cref="T:Microsoft.Azure.Batch.RetryPolicyProvider" />を使用して、<see cref="T:Microsoft.Azure.Batch.Common.LinearRetry" />ポリシー。</span><span class="sxs-lookup"><span data-stu-id="6883c-110">Creates a new <see cref="T:Microsoft.Azure.Batch.RetryPolicyProvider" /> using the <see cref="T:Microsoft.Azure.Batch.Common.LinearRetry" /> policy.</span></span>
            </summary>
        <returns><span data-ttu-id="6883c-111">指定したバックオフと最大再試行回数を使用して線形の再試行を実行するように構成するプロバイダーです。</span><span class="sxs-lookup"><span data-stu-id="6883c-111">A provider configured to perform linear retries using the specified backoff and max retries.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NoRetryProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.RetryPolicyProvider NoRetryProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.RetryPolicyProvider NoRetryProvider() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.RetryPolicyProvider.NoRetryProvider" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function NoRetryProvider () As RetryPolicyProvider" />
      <MemberSignature Language="F#" Value="static member NoRetryProvider : unit -&gt; Microsoft.Azure.Batch.RetryPolicyProvider" Usage="Microsoft.Azure.Batch.RetryPolicyProvider.NoRetryProvider " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.RetryPolicyProvider</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6883c-112">新たに作成<see cref="T:Microsoft.Azure.Batch.RetryPolicyProvider" />を使用して、<see cref="T:Microsoft.Azure.Batch.Common.NoRetry" />ポリシー。</span><span class="sxs-lookup"><span data-stu-id="6883c-112">Creates a new <see cref="T:Microsoft.Azure.Batch.RetryPolicyProvider" /> using the <see cref="T:Microsoft.Azure.Batch.Common.NoRetry" /> policy.</span></span>
            </summary>
        <returns><span data-ttu-id="6883c-113">再試行を実行しないするように構成するプロバイダーです。</span><span class="sxs-lookup"><span data-stu-id="6883c-113">A provider configured to perform no retries.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Policy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.IRetryPolicy Policy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Common.IRetryPolicy Policy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.RetryPolicyProvider.Policy" />
      <MemberSignature Language="VB.NET" Value="Public Property Policy As IRetryPolicy" />
      <MemberSignature Language="F#" Value="member this.Policy : Microsoft.Azure.Batch.Common.IRetryPolicy with get, set" Usage="Microsoft.Azure.Batch.RetryPolicyProvider.Policy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.IRetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6883c-114">取得または使用する再試行ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="6883c-114">Gets or sets the retry policy to use.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>