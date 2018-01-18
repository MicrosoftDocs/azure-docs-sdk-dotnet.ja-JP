<Type Name="RetryExponential" FullName="Microsoft.Azure.EventHubs.RetryExponential">
  <TypeSignature Language="C#" Value="public sealed class RetryExponential : Microsoft.Azure.EventHubs.RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RetryExponential extends Microsoft.Azure.EventHubs.RetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.RetryExponential" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RetryExponential&#xA;Inherits RetryPolicy" />
  <TypeSignature Language="F#" Value="type RetryExponential = class&#xA;    inherit RetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.EventHubs.RetryPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="39ca9-101">RetryPolicy 実装が再試行間の遅延が交互の指数的に拡張されます。</span><span class="sxs-lookup"><span data-stu-id="39ca9-101">RetryPolicy implementation where the delay between retries will grow in a staggered exponential manner.</span></span>
            <span data-ttu-id="39ca9-102">RetryPolicy を使用してクライアントに対して設定できる<see cref="T:Microsoft.Azure.EventHubs.EventHubClient" />です。</span><span class="sxs-lookup"><span data-stu-id="39ca9-102">RetryPolicy can be set on the client using <see cref="T:Microsoft.Azure.EventHubs.EventHubClient" />.</span></span>
            <span data-ttu-id="39ca9-103">DeltaBackOff (MaximumBackoff - MinimumBackoff) の関数である retryFactor を使用して計算されます RetryIntervals と MaximumRetryCount</span><span class="sxs-lookup"><span data-stu-id="39ca9-103">RetryIntervals will be computed using a retryFactor which is a function of deltaBackOff (MaximumBackoff - MinimumBackoff) and MaximumRetryCount</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryExponential (TimeSpan minimumBackoff, TimeSpan maximumBackoff, int maximumRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan minimumBackoff, valuetype System.TimeSpan maximumBackoff, int32 maximumRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.RetryExponential.#ctor(System.TimeSpan,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (minimumBackoff As TimeSpan, maximumBackoff As TimeSpan, maximumRetryCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.RetryExponential : TimeSpan * TimeSpan * int -&gt; Microsoft.Azure.EventHubs.RetryExponential" Usage="new Microsoft.Azure.EventHubs.RetryExponential (minimumBackoff, maximumBackoff, maximumRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minimumBackoff" Type="System.TimeSpan" />
        <Parameter Name="maximumBackoff" Type="System.TimeSpan" />
        <Parameter Name="maximumRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minimumBackoff"><span data-ttu-id="39ca9-104">最小バックオフ間隔です。</span><span class="sxs-lookup"><span data-stu-id="39ca9-104">Minimum backoff interval.</span></span></param>
        <param name="maximumBackoff"><span data-ttu-id="39ca9-105">最大バックオフ間隔です。</span><span class="sxs-lookup"><span data-stu-id="39ca9-105">Maximum backoff interval.</span></span></param>
        <param name="maximumRetryCount"><span data-ttu-id="39ca9-106">最大再試行回数です。</span><span class="sxs-lookup"><span data-stu-id="39ca9-106">Maximum retry count.</span></span></param>
        <summary>
            <span data-ttu-id="39ca9-107">新しい構成された RetryExponential 再試行ポリシー オブジェクトを返します。</span><span class="sxs-lookup"><span data-stu-id="39ca9-107">Returns a new RetryExponential retry policy object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.EventHubs.RetryPolicy Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.EventHubs.RetryPolicy Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.RetryExponential.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Clone () As RetryPolicy" />
      <MemberSignature Language="F#" Value="override this.Clone : unit -&gt; Microsoft.Azure.EventHubs.RetryPolicy" Usage="retryExponential.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.RetryPolicy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="39ca9-108">このインスタンスの新しいコピーを作成します。</span><span class="sxs-lookup"><span data-stu-id="39ca9-108">Creates a new copy of this instance.</span></span></summary>
        <returns><span data-ttu-id="39ca9-109">このインスタンスの作成の新しいコピーです。</span><span class="sxs-lookup"><span data-stu-id="39ca9-109">The created new copy of this instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnGetNextRetryInterval">
      <MemberSignature Language="C#" Value="protected override Nullable&lt;TimeSpan&gt; OnGetNextRetryInterval (string clientId, Exception lastException, TimeSpan remainingTime, int baseWaitTimeSecs);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; OnGetNextRetryInterval(string clientId, class System.Exception lastException, valuetype System.TimeSpan remainingTime, int32 baseWaitTimeSecs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.RetryExponential.OnGetNextRetryInterval(System.String,System.Exception,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnGetNextRetryInterval (clientId As String, lastException As Exception, remainingTime As TimeSpan, baseWaitTimeSecs As Integer) As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnGetNextRetryInterval : string * Exception * TimeSpan * int -&gt; Nullable&lt;TimeSpan&gt;" Usage="retryExponential.OnGetNextRetryInterval (clientId, lastException, remainingTime, baseWaitTimeSecs)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="lastException" Type="System.Exception" />
        <Parameter Name="remainingTime" Type="System.TimeSpan" />
        <Parameter Name="baseWaitTimeSecs" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="clientId"></param>
        <param name="lastException"></param>
        <param name="remainingTime"></param>
        <param name="baseWaitTimeSecs"></param>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>