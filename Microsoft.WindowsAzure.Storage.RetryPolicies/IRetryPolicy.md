<Type Name="IRetryPolicy" FullName="Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy">
  <TypeSignature Language="C#" Value="public interface IRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRetryPolicy" />
  <TypeSignature Language="F#" Value="type IRetryPolicy = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="aca30-101">再試行ポリシーを表します。</span><span class="sxs-lookup"><span data-stu-id="aca30-101">Represents a retry policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateInstance">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy CreateInstance ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy CreateInstance() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy.CreateInstance" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateInstance () As IRetryPolicy" />
      <MemberSignature Language="F#" Value="abstract member CreateInstance : unit -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" Usage="iRetryPolicy.CreateInstance " />
      <MemberType>Method</MemberType>
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
            <span data-ttu-id="aca30-102">現在試行中の要求の新しい再試行ポリシーを生成します。</span><span class="sxs-lookup"><span data-stu-id="aca30-102">Generates a new retry policy for the current request attempt.</span></span>
            </summary>
        <returns><span data-ttu-id="aca30-103"><see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />を試行中、現在の要求の再試行ポリシーを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="aca30-103">An <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" /> object that represents the retry policy for the current request attempt.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry (int currentRetryCount, int statusCode, Exception lastException, out TimeSpan retryInterval, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ShouldRetry(int32 currentRetryCount, int32 statusCode, class System.Exception lastException, [out] valuetype System.TimeSpan&amp; retryInterval, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy.ShouldRetry(System.Int32,System.Int32,System.Exception,System.TimeSpan@,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ShouldRetry : int * int * Exception *  * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="iRetryPolicy.ShouldRetry (currentRetryCount, statusCode, lastException, retryInterval, operationContext)" />
      <MemberType>Method</MemberType>
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
        <param name="currentRetryCount"><span data-ttu-id="aca30-104">指定された操作の再試行の回数を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="aca30-104">An integer specifying the number of retries for the given operation.</span></span> <span data-ttu-id="aca30-105">ゼロの値を示しますこの最初のエラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="aca30-105">A value of zero signifies this is the first error encountered.</span></span></param>
        <param name="statusCode"><span data-ttu-id="aca30-106">最後の操作のステータス コードを格納する整数。</span><span class="sxs-lookup"><span data-stu-id="aca30-106">An integer containing the status code for the last operation.</span></span></param>
        <param name="lastException"><span data-ttu-id="aca30-107"><see cref="T:System.Exception" />を最後に発生した例外を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="aca30-107">An <see cref="T:System.Exception" /> object that represents the last exception encountered.</span></span></param>
        <param name="retryInterval"><span data-ttu-id="aca30-108">A<see cref="T:System.TimeSpan" />次の再試行まで待機する間隔を示すです。</span><span class="sxs-lookup"><span data-stu-id="aca30-108">A <see cref="T:System.TimeSpan" /> indicating the interval to wait until the next retry.</span></span></param>
        <param name="operationContext"><span data-ttu-id="aca30-109"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="aca30-109">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="aca30-110">次の再試行まで、操作を再試行するかどうかと間隔を決定します。</span><span class="sxs-lookup"><span data-stu-id="aca30-110">Determines whether the operation should be retried and the interval until the next retry.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="aca30-111"><c>true</c>場合は、操作は、それ以外の再試行をする必要があります<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="aca30-111"><c>true</c> if the operation should be retried; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>