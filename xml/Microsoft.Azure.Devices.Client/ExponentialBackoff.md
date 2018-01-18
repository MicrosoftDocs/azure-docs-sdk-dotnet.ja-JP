<Type Name="ExponentialBackoff" FullName="Microsoft.Azure.Devices.Client.ExponentialBackoff">
  <TypeSignature Language="C#" Value="public class ExponentialBackoff : Microsoft.Azure.Devices.Client.IRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExponentialBackoff extends System.Object implements class Microsoft.Azure.Devices.Client.IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.ExponentialBackoff" />
  <TypeSignature Language="VB.NET" Value="Public Class ExponentialBackoff&#xA;Implements IRetryPolicy" />
  <TypeSignature Language="F#" Value="type ExponentialBackoff = class&#xA;    interface IRetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Devices.Client.IRetryPolicy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="a27d5-101">指定された数の再試行の間隔を決定する、ランダムな指数バックオフ スキームを使用して、再試行を実行する再試行ポリシーを表します。</span><span class="sxs-lookup"><span data-stu-id="a27d5-101">Represents a retry policy that performs a specified number of retries, using a randomized exponential back off scheme to determine the interval between retries.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExponentialBackoff (int retryCount, TimeSpan minBackoff, TimeSpan maxBackoff, TimeSpan deltaBackoff);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 retryCount, valuetype System.TimeSpan minBackoff, valuetype System.TimeSpan maxBackoff, valuetype System.TimeSpan deltaBackoff) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.ExponentialBackoff.#ctor(System.Int32,System.TimeSpan,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (retryCount As Integer, minBackoff As TimeSpan, maxBackoff As TimeSpan, deltaBackoff As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.ExponentialBackoff : int * TimeSpan * TimeSpan * TimeSpan -&gt; Microsoft.Azure.Devices.Client.ExponentialBackoff" Usage="new Microsoft.Azure.Devices.Client.ExponentialBackoff (retryCount, minBackoff, maxBackoff, deltaBackoff)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retryCount" Type="System.Int32" />
        <Parameter Name="minBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxBackoff" Type="System.TimeSpan" />
        <Parameter Name="deltaBackoff" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="retryCount"><span data-ttu-id="a27d5-102">再試行の最大数。</span><span class="sxs-lookup"><span data-stu-id="a27d5-102">The maximum number of retry attempts.</span></span></param>
        <param name="minBackoff"><span data-ttu-id="a27d5-103">バックオフ時間の最小値</span><span class="sxs-lookup"><span data-stu-id="a27d5-103">The minimum back-off time</span></span></param>
        <param name="maxBackoff"><span data-ttu-id="a27d5-104">最大バックオフ時間。</span><span class="sxs-lookup"><span data-stu-id="a27d5-104">The maximum back-off time.</span></span></param>
        <param name="deltaBackoff"><span data-ttu-id="a27d5-105">再試行の間の指数遅延のランダムな差分の計算に使用される値。</span><span class="sxs-lookup"><span data-stu-id="a27d5-105">The value that will be used to calculate a random delta in the exponential delay between retries.</span></span></param>
        <summary>
            <span data-ttu-id="a27d5-106">ExponentialBackoff のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="a27d5-106">Creates an instance of ExponentialBackoff.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry (int currentRetryCount, Exception lastException, out TimeSpan retryInterval);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ShouldRetry(int32 currentRetryCount, class System.Exception lastException, [out] valuetype System.TimeSpan&amp; retryInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.ExponentialBackoff.ShouldRetry(System.Int32,System.Exception,System.TimeSpan@)" />
      <MemberSignature Language="VB.NET" Value="Public Function ShouldRetry (currentRetryCount As Integer, lastException As Exception, ByRef retryInterval As TimeSpan) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ShouldRetry : int * Exception *  -&gt; bool&#xA;override this.ShouldRetry : int * Exception *  -&gt; bool" Usage="exponentialBackoff.ShouldRetry (currentRetryCount, lastException, retryInterval)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Devices.Client.IRetryPolicy.ShouldRetry(System.Int32,System.Exception,System.TimeSpan@)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentRetryCount" Type="System.Int32" />
        <Parameter Name="lastException" Type="System.Exception" />
        <Parameter Name="retryInterval" Type="System.TimeSpan&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="currentRetryCount"><span data-ttu-id="a27d5-107">操作が再試行された回数。</span><span class="sxs-lookup"><span data-stu-id="a27d5-107">How many times the operation has been retried.</span></span></param>
        <param name="lastException"><span data-ttu-id="a27d5-108">操作の例外。</span><span class="sxs-lookup"><span data-stu-id="a27d5-108">Operation exception.</span></span></param>
        <param name="retryInterval"><span data-ttu-id="a27d5-109">この期間が経過後は、次の再試行を実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a27d5-109">Next retry should be performed after this time interval.</span></span></param>
        <summary>
            <span data-ttu-id="a27d5-110">操作を再試行する必要がありますパラメーターに基づいている場合は、true を返します。</span><span class="sxs-lookup"><span data-stu-id="a27d5-110">Returns true if, based on the parameters the operation should be retried.</span></span>
            </summary>
        <returns><span data-ttu-id="a27d5-111">する場合は true、操作は再試行の場合は false それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="a27d5-111">True if the operation should be retried, false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>