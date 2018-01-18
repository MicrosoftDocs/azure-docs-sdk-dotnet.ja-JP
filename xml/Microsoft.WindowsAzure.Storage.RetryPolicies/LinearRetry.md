<Type Name="LinearRetry" FullName="Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry">
  <TypeSignature Language="C#" Value="public sealed class LinearRetry : Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit LinearRetry extends System.Object implements class Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LinearRetry&#xA;Implements IExtendedRetryPolicy" />
  <TypeSignature Language="F#" Value="type LinearRetry = class&#xA;    interface IExtendedRetryPolicy&#xA;    interface IRetryPolicy" />
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
      <InterfaceName>Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="8856a-101">指定された回数の再試行の間の一定の時間を指定した期間を使用して、再試行を実行する再試行ポリシーを表します。</span><span class="sxs-lookup"><span data-stu-id="8856a-101">Represents a retry policy that performs a specified number of retries, using a specified fixed time interval between retries.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinearRetry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry.#ctor" />
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
            <span data-ttu-id="8856a-102"><see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8856a-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinearRetry (TimeSpan deltaBackoff, int maxAttempts);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan deltaBackoff, int32 maxAttempts) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry.#ctor(System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deltaBackoff As TimeSpan, maxAttempts As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry : TimeSpan * int -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry" Usage="new Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry (deltaBackoff, maxAttempts)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deltaBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxAttempts" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="deltaBackoff"><span data-ttu-id="8856a-103">A<see cref="T:System.TimeSpan" />再試行のバックオフ間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="8856a-103">A <see cref="T:System.TimeSpan" /> specifying the back-off interval between retries.</span></span></param>
        <param name="maxAttempts"><span data-ttu-id="8856a-104">再試行の最大数を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="8856a-104">An integer specifying the maximum number of retry attempts.</span></span></param>
        <summary>
            <span data-ttu-id="8856a-105">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry" />クラスの指定されたデルタと再試行の最大数を使用します。</span><span class="sxs-lookup"><span data-stu-id="8856a-105">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry" /> class using the specified delta and maximum number of retries.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateInstance">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy CreateInstance ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy CreateInstance() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry.CreateInstance" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateInstance () As IRetryPolicy" />
      <MemberSignature Language="F#" Value="abstract member CreateInstance : unit -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy&#xA;override this.CreateInstance : unit -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" Usage="linearRetry.CreateInstance " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy.CreateInstance</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8856a-106">現在試行中の要求の新しい再試行ポリシーを生成します。</span><span class="sxs-lookup"><span data-stu-id="8856a-106">Generates a new retry policy for the current request attempt.</span></span>
            </summary>
        <returns><span data-ttu-id="8856a-107"><see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />を試行中、現在の要求の再試行ポリシーを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8856a-107">An <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" /> object that represents the retry policy for the current request attempt.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Evaluate">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo Evaluate (Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext retryContext, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo Evaluate(class Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext retryContext, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry.Evaluate(Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Evaluate : Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo&#xA;override this.Evaluate : Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" Usage="linearRetry.Evaluate (retryContext, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy.Evaluate(Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="retryContext" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="retryContext"><span data-ttu-id="8856a-108">A<see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" />オブジェクトの数を示す再試行回数、前回の要求の結果と、次の再試行するかどうか、プライマリまたはセカンダリの場所で発生する必要があり、配置モードを指定します。</span><span class="sxs-lookup"><span data-stu-id="8856a-108">A <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" /> object that indicates the number of retries, the results of the last request, and whether the next retry should happen in the primary or secondary location, and specifies the location mode.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8856a-109"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8856a-109">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8856a-110">次の再試行まで、操作を再試行するかどうかと間隔を決定します。</span><span class="sxs-lookup"><span data-stu-id="8856a-110">Determines whether the operation should be retried and the interval until the next retry.</span></span>
            </summary>
        <returns><span data-ttu-id="8856a-111">A<see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" />配置モードを示すオブジェクトのプライマリまたはセカンダリの場所に、次の再試行が発生するかどうかとします。</span><span class="sxs-lookup"><span data-stu-id="8856a-111">A <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" /> object that indicates the location mode, and whether the next retry should happen in the primary or secondary location.</span></span> <span data-ttu-id="8856a-112">場合<c>null</c>操作は再試行されません。</span><span class="sxs-lookup"><span data-stu-id="8856a-112">If <c>null</c>, the operation will not be retried.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry (int currentRetryCount, int statusCode, Exception lastException, out TimeSpan retryInterval, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ShouldRetry(int32 currentRetryCount, int32 statusCode, class System.Exception lastException, [out] valuetype System.TimeSpan&amp; retryInterval, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry.ShouldRetry(System.Int32,System.Int32,System.Exception,System.TimeSpan@,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ShouldRetry : int * int * Exception *  * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.ShouldRetry : int * int * Exception *  * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="linearRetry.ShouldRetry (currentRetryCount, statusCode, lastException, retryInterval, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy.ShouldRetry(System.Int32,System.Int32,System.Exception,System.TimeSpan@,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentRetryCount" Type="System.Int32" />
        <Parameter Name="statusCode" Type="System.Int32" />
        <Parameter Name="lastException" Type="System.Exception" />
        <Parameter Name="retryInterval" Type="System.TimeSpan&amp;" RefType="out" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="currentRetryCount"><span data-ttu-id="8856a-113">指定された操作の再試行の回数を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="8856a-113">An integer specifying the number of retries for the given operation.</span></span> <span data-ttu-id="8856a-114">ゼロの値を示しますこの最初のエラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="8856a-114">A value of zero signifies this is the first error encountered.</span></span></param>
        <param name="statusCode"><span data-ttu-id="8856a-115">最後の操作のステータス コードを格納する整数。</span><span class="sxs-lookup"><span data-stu-id="8856a-115">An integer containing the status code for the last operation.</span></span></param>
        <param name="lastException"><span data-ttu-id="8856a-116"><see cref="T:System.Exception" />を最後に発生した例外を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8856a-116">An <see cref="T:System.Exception" /> object that represents the last exception encountered.</span></span></param>
        <param name="retryInterval"><span data-ttu-id="8856a-117">A<see cref="T:System.TimeSpan" />次の再試行まで待機する間隔を示すです。</span><span class="sxs-lookup"><span data-stu-id="8856a-117">A <see cref="T:System.TimeSpan" /> indicating the interval to wait until the next retry.</span></span></param>
        <param name="operationContext"><span data-ttu-id="8856a-118"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8856a-118">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="8856a-119">次の再試行まで、操作を再試行するかどうかと間隔を決定します。</span><span class="sxs-lookup"><span data-stu-id="8856a-119">Determines whether the operation should be retried and the interval until the next retry.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="8856a-120"><c>true</c>場合は、操作は、それ以外の再試行をする必要があります<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="8856a-120"><c>true</c> if the operation should be retried; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>