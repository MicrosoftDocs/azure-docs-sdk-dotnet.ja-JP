<Type Name="ActivityPolicy" FullName="Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy">
  <TypeSignature Language="C#" Value="public class ActivityPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActivityPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ActivityPolicy" />
  <TypeSignature Language="F#" Value="type ActivityPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9f2c2-101">アクティビティ ポリシー。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-101">Activity policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9f2c2-102">ActivityPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-102">Initializes a new instance of the ActivityPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Concurrency">
      <MemberSignature Language="C#" Value="public Nullable&lt;uint&gt; Concurrency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;unsigned int32&gt; Concurrency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy.Concurrency" />
      <MemberSignature Language="VB.NET" Value="Public Property Concurrency As Nullable(Of UInteger)" />
      <MemberSignature Language="F#" Value="member this.Concurrency : Nullable&lt;uint32&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy.Concurrency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.UInt32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f2c2-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-103">Optional.</span></span> <span data-ttu-id="9f2c2-104">アクティビティの同時実行数の最大数。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-104">The maximum number of concurrent activity executions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delay">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; Delay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; Delay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy.Delay" />
      <MemberSignature Language="VB.NET" Value="Public Property Delay As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.Delay : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy.Delay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f2c2-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-105">Optional.</span></span> <span data-ttu-id="9f2c2-106">アクティビティの実行を遅延できるように、上流の活動は完了までに余分な時間を持つことができます。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-106">Delay activity execution so that upstream activities can have extra time to finish.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionPriorityOrder">
      <MemberSignature Language="C#" Value="public string ExecutionPriorityOrder { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExecutionPriorityOrder" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy.ExecutionPriorityOrder" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutionPriorityOrder As String" />
      <MemberSignature Language="F#" Value="member this.ExecutionPriorityOrder : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy.ExecutionPriorityOrder" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f2c2-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-107">Optional.</span></span> <span data-ttu-id="9f2c2-108">実行の優先順位です。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-108">Execution priority order.</span></span>  <span data-ttu-id="9f2c2-109">OldestFirst newestfirst ですから選択します。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-109">Choose from OldestFirst or NewestFirst.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRetry">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRetry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy.LongRetry" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRetry As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRetry : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy.LongRetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f2c2-110">省略可能。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-110">Optional.</span></span> <span data-ttu-id="9f2c2-111">失敗した短い再試行後に長い再試行の合計数。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-111">Total number of long retries after failed short retries.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRetryInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; LongRetryInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; LongRetryInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy.LongRetryInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRetryInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.LongRetryInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy.LongRetryInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f2c2-112">省略可能。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-112">Optional.</span></span> <span data-ttu-id="9f2c2-113">2 つの長い再試行の間隔。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-113">Interval between two long retries.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retry">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Retry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Retry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy.Retry" />
      <MemberSignature Language="VB.NET" Value="Public Property Retry As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Retry : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy.Retry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f2c2-114">省略可能。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-114">Optional.</span></span> <span data-ttu-id="9f2c2-115">失敗した活動に短い再試行回数の合計です。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-115">Total number of short retries for a failed activity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; Timeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; Timeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy.Timeout" />
      <MemberSignature Language="VB.NET" Value="Public Property Timeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.Timeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.ActivityPolicy.Timeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f2c2-116">省略可能。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-116">Optional.</span></span> <span data-ttu-id="9f2c2-117">アクティビティの実行に関するタイムアウトを指定します。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-117">Specifies the timeout for the activity to run.</span></span> <span data-ttu-id="9f2c2-118">指定された値がある場合、無制限のタイムアウトをつまり TimeSpan.FromMilliseconds(-1) の値を取ります。</span><span class="sxs-lookup"><span data-stu-id="9f2c2-118">If there is value specified, it takes the value of TimeSpan.FromMilliseconds(-1) which means indefinite timeout.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>