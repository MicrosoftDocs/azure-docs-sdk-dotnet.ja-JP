<Type Name="RetryContext" FullName="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext">
  <TypeSignature Language="C#" Value="public sealed class RetryContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RetryContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RetryContext" />
  <TypeSignature Language="F#" Value="type RetryContext = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d9101-101">要求に対して行われた回数、前回の要求記憶域の場所と以降の再試行の配置モードの結果を含む、Microsoft Azure ストレージ サービスに対して行われた要求の 1 つ以上の再試行のコンテキストを表します。</span><span class="sxs-lookup"><span data-stu-id="d9101-101">Represents the context for one or more retries of a request made against the Microsoft Azure storage services, including the number of retries made for the request, the results of the last request, and the storage location and location mode for subsequent retries.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CurrentRetryCount">
      <MemberSignature Language="C#" Value="public int CurrentRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CurrentRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext.CurrentRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.CurrentRetryCount : int" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext.CurrentRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d9101-102">指定された操作の再試行の回数を取得します。</span><span class="sxs-lookup"><span data-stu-id="d9101-102">Gets the number of retries for the given operation.</span></span>
            </summary>
        <value><span data-ttu-id="d9101-103">指定された操作の再試行の回数を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="d9101-103">An integer specifying the number of retries for the given operation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRequestResult">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RequestResult LastRequestResult { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RequestResult LastRequestResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext.LastRequestResult" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastRequestResult As RequestResult" />
      <MemberSignature Language="F#" Value="member this.LastRequestResult : Microsoft.WindowsAzure.Storage.RequestResult" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext.LastRequestResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RequestResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d9101-104">最後の要求の結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="d9101-104">Gets the results of the last request.</span></span>
            </summary>
        <value><span data-ttu-id="d9101-105"><see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d9101-105">A <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocationMode">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode LocationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode LocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext.LocationMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocationMode As LocationMode" />
      <MemberSignature Language="F#" Value="member this.LocationMode : Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext.LocationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d9101-106">以降の再試行の配置モードを取得します。</span><span class="sxs-lookup"><span data-stu-id="d9101-106">Gets the location mode for subsequent retries.</span></span>
            </summary>
        <value><span data-ttu-id="d9101-107"><see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="d9101-107">A <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" /> enumeration value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLocation">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageLocation NextLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.StorageLocation NextLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext.NextLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextLocation As StorageLocation" />
      <MemberSignature Language="F#" Value="member this.NextLocation : Microsoft.WindowsAzure.Storage.StorageLocation" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext.NextLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d9101-108">次の再試行のターゲットの場所を取得します。</span><span class="sxs-lookup"><span data-stu-id="d9101-108">Gets the target location for the next retry.</span></span>
            </summary>
        <value><span data-ttu-id="d9101-109"><see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="d9101-109">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> enumeration value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="retryContext.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d9101-110">現在の <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" /> インスタンスを表す文字列を返します。</span><span class="sxs-lookup"><span data-stu-id="d9101-110">Returns a string that represents the current <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" /> instance.</span></span>
            </summary>
        <returns><span data-ttu-id="d9101-111">現在を表す文字列<see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="d9101-111">A string that represents the current <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" /> instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>