<Type Name="NoRetry" FullName="Microsoft.Azure.ServiceBus.NoRetry">
  <TypeSignature Language="C#" Value="public sealed class NoRetry : Microsoft.Azure.ServiceBus.RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NoRetry extends Microsoft.Azure.ServiceBus.RetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.NoRetry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NoRetry&#xA;Inherits RetryPolicy" />
  <TypeSignature Language="F#" Value="type NoRetry = class&#xA;    inherit RetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.RetryPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ddbc6-101">実際には再試行しない再試行ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="ddbc6-101">A retry policy, which does not actually retry.</span></span>
            </summary>
    <remarks><span data-ttu-id="ddbc6-102">ユーザー コードで処理するすべての Service Bus 例外の場合は、これを使用します。</span><span class="sxs-lookup"><span data-stu-id="ddbc6-102">Use this if you want all Service Bus exceptions to be handled by user code.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NoRetry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.NoRetry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnShouldRetry">
      <MemberSignature Language="C#" Value="protected override bool OnShouldRetry (TimeSpan remainingTime, int currentRetryCount, out TimeSpan retryInterval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnShouldRetry(valuetype System.TimeSpan remainingTime, int32 currentRetryCount, [out] valuetype System.TimeSpan&amp; retryInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.NoRetry.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnShouldRetry (remainingTime As TimeSpan, currentRetryCount As Integer, ByRef retryInterval As TimeSpan) As Boolean" />
      <MemberSignature Language="F#" Value="override this.OnShouldRetry : TimeSpan * int *  -&gt; bool" Usage="noRetry.OnShouldRetry (remainingTime, currentRetryCount, retryInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="remainingTime" Type="System.TimeSpan" />
        <Parameter Name="currentRetryCount" Type="System.Int32" />
        <Parameter Name="retryInterval" Type="System.TimeSpan&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="remainingTime"><span data-ttu-id="ddbc6-103">タイムアウトになるまでの残り時間です。</span><span class="sxs-lookup"><span data-stu-id="ddbc6-103">The remaining time before the timeout expires.</span></span></param>
        <param name="currentRetryCount"><span data-ttu-id="ddbc6-104">処理された回数です。</span><span class="sxs-lookup"><span data-stu-id="ddbc6-104">The number of attempts that have been processed.</span></span></param>
        <param name="retryInterval"><span data-ttu-id="ddbc6-105">再試行の前に遅延時間の量。</span><span class="sxs-lookup"><span data-stu-id="ddbc6-105">The amount of time to delay before retry.</span></span></param>
        <summary>
            <span data-ttu-id="ddbc6-106">再試行を実行するかどうかに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="ddbc6-106">Called to see if a retry should be performed.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>