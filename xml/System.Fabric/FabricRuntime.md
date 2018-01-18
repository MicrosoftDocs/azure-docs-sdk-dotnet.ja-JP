<Type Name="FabricRuntime" FullName="System.Fabric.FabricRuntime">
  <TypeSignature Language="C#" Value="public sealed class FabricRuntime : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed FabricRuntime extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricRuntime" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricRuntime&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type FabricRuntime = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="48022-101">により、ユーザーが作成したホストを取得する、 <see cref="T:System.Fabric.CodePackageActivationContext" />、必要なサービス ファクトリを登録したり、[ <see cref="T:System.Fabric.IStatelessServiceFactory" />、 <see cref="T:System.Fabric.IStatefulServiceFactory" />、または<see cref="T:System.Fabric.ServiceGroupFactory" />] または直接のサービスの種類。</span><span class="sxs-lookup"><span data-stu-id="48022-101">Allows user created hosts to obtain their <see cref="T:System.Fabric.CodePackageActivationContext" />, well as to register the necessary service factories [ <see cref="T:System.Fabric.IStatelessServiceFactory" />, <see cref="T:System.Fabric.IStatefulServiceFactory" />, or <see cref="T:System.Fabric.ServiceGroupFactory" />] or service types directly.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Fabric.FabricRuntime Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.FabricRuntime Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.Create" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create () As FabricRuntime" />
      <MemberSignature Language="F#" Value="static member Create : unit -&gt; System.Fabric.FabricRuntime" Usage="System.Fabric.FabricRuntime.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricRuntime</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="48022-102">作成、<see cref="T:System.Fabric.FabricRuntime" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="48022-102">Creates the <see cref="T:System.Fabric.FabricRuntime" /> object.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="48022-103">新しく作成した<see cref="T:System.Fabric.FabricRuntime" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="48022-103">A newly created <see cref="T:System.Fabric.FabricRuntime" /> object.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Fabric.FabricRuntime Create (Action fabricExitCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.FabricRuntime Create(class System.Action fabricExitCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.Create(System.Action)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (fabricExitCallback As Action) As FabricRuntime" />
      <MemberSignature Language="F#" Value="static member Create : Action -&gt; System.Fabric.FabricRuntime" Usage="System.Fabric.FabricRuntime.Create fabricExitCallback" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricRuntime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fabricExitCallback" Type="System.Action" />
      </Parameters>
      <Docs>
        <param name="fabricExitCallback">
          <para><span data-ttu-id="48022-104">ランタイムが終了または終了するときに実行されるアクション。</span><span class="sxs-lookup"><span data-stu-id="48022-104">The Action to be executed when the runtime exits or terminates.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="48022-105">作成、<see cref="T:System.Fabric.FabricRuntime" />基になるランタイムが終了または何らかの理由が終了した場合に実行される、指定されたコールバック関数を持つオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="48022-105">Creates the <see cref="T:System.Fabric.FabricRuntime" /> object with a specified callback function which will be executed if the underlying runtime terminates or exits for any reason.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="48022-106">新しく作成した<see cref="T:System.Fabric.FabricRuntime" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="48022-106">A newly created <see cref="T:System.Fabric.FabricRuntime" />object.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt; CreateAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricRuntime&gt; CreateAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.CreateAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt;" Usage="System.Fabric.FabricRuntime.CreateAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="48022-107">Service Fabric は、TimeoutException を返す前に続行するには、この操作を許可する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="48022-107">The maximum amount of time Service Fabric will allow this operation to continue before returning a TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="48022-108"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="48022-108">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>  <span data-ttu-id="48022-109">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="48022-109">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="48022-110">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="48022-110">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="48022-111">作成、<see cref="T:System.Fabric.FabricRuntime" />に非同期で、指定したオブジェクト<paramref name="timeout" />と<paramref name="cancellationToken" />です。</span><span class="sxs-lookup"><span data-stu-id="48022-111">Creates the <see cref="T:System.Fabric.FabricRuntime" /> object asynchronously with the specified <paramref name="timeout" /> and <paramref name="cancellationToken" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="48022-112">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="48022-112">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt; CreateAsync (Action fabricExitCallback, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricRuntime&gt; CreateAsync(class System.Action fabricExitCallback, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.CreateAsync(System.Action,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Action * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt;" Usage="System.Fabric.FabricRuntime.CreateAsync (fabricExitCallback, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fabricExitCallback" Type="System.Action" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="fabricExitCallback">
          <para><span data-ttu-id="48022-113">ランタイムが終了または終了するときに実行されるアクション。</span><span class="sxs-lookup"><span data-stu-id="48022-113">The Action to be executed when the runtime exits or terminates.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="48022-114">Service Fabric は、TimeoutException を返す前に続行するには、この操作を許可する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="48022-114">The maximum amount of time Service Fabric will allow this operation to continue before returning a TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="48022-115"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="48022-115">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>  <span data-ttu-id="48022-116">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="48022-116">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="48022-117">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="48022-117">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="48022-118">作成、<see cref="T:System.Fabric.FabricRuntime" />オブジェクト、基になるランタイムが終了または何らかの理由で終了する場合に実行される、指定されたコールバック関数を非同期的に<paramref name="timeout" />、および<paramref name="cancellationToken" />です。</span><span class="sxs-lookup"><span data-stu-id="48022-118">Creates the <see cref="T:System.Fabric.FabricRuntime" /> object asynchronously with the specified callback function which will be executed if the underlying runtime terminates or exits for any reason, <paramref name="timeout" />, and <paramref name="cancellationToken" />.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="48022-119">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="48022-119">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="fabricRuntime.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="48022-120">破棄、<see cref="T:System.Fabric.FabricRuntime" />です。</span><span class="sxs-lookup"><span data-stu-id="48022-120">Disposes of the <see cref="T:System.Fabric.FabricRuntime" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetActivationContext">
      <MemberSignature Language="C#" Value="public static System.Fabric.CodePackageActivationContext GetActivationContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.CodePackageActivationContext GetActivationContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.GetActivationContext" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetActivationContext () As CodePackageActivationContext" />
      <MemberSignature Language="F#" Value="static member GetActivationContext : unit -&gt; System.Fabric.CodePackageActivationContext" Usage="System.Fabric.FabricRuntime.GetActivationContext " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CodePackageActivationContext</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="48022-121">現在取得<see cref="T:System.Fabric.FabricRuntime" />の<see cref="T:System.Fabric.CodePackageActivationContext" />します。</span><span class="sxs-lookup"><span data-stu-id="48022-121">Retrieves the current <see cref="T:System.Fabric.FabricRuntime" />’s <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="48022-122">アクティベーション コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="48022-122">The activation context.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetActivationContextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.CodePackageActivationContext&gt; GetActivationContextAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.CodePackageActivationContext&gt; GetActivationContextAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.GetActivationContextAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetActivationContextAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.CodePackageActivationContext&gt;" Usage="System.Fabric.FabricRuntime.GetActivationContextAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.CodePackageActivationContext&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="48022-123">Service Fabric は、TimeoutException を返す前に続行するには、この操作を許可する最長時間</span><span class="sxs-lookup"><span data-stu-id="48022-123">The maximum amount of time Service Fabric will allow this operation to continue before returning a TimeoutException</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="48022-124"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="48022-124">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>  <span data-ttu-id="48022-125">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="48022-125">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="48022-126">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="48022-126">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="48022-127">現在取得<see cref="T:System.Fabric.FabricRuntime" />の<see cref="T:System.Fabric.CodePackageActivationContext" />に非同期で、指定した<paramref name="timeout" />と<paramref name="cancellationToken" />です。</span><span class="sxs-lookup"><span data-stu-id="48022-127">Retrieves the current <see cref="T:System.Fabric.FabricRuntime" />’s <see cref="T:System.Fabric.CodePackageActivationContext" /> asynchronously with the specified <paramref name="timeout" /> and <paramref name="cancellationToken" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="48022-128">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="48022-128">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeContext">
      <MemberSignature Language="C#" Value="public static System.Fabric.NodeContext GetNodeContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.NodeContext GetNodeContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.GetNodeContext" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetNodeContext () As NodeContext" />
      <MemberSignature Language="F#" Value="static member GetNodeContext : unit -&gt; System.Fabric.NodeContext" Usage="System.Fabric.FabricRuntime.GetNodeContext " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeContext</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="48022-129">Fabric ノードに関する情報を含むノードのコンテキスト オブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="48022-129">Gets the Node Context object that contains information about Fabric Node.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="48022-130">ノードのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="48022-130">The node context.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeContextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.NodeContext&gt; GetNodeContextAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.NodeContext&gt; GetNodeContextAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.GetNodeContextAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetNodeContextAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NodeContext&gt;" Usage="System.Fabric.FabricRuntime.GetNodeContextAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NodeContext&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="48022-131">Service Fabric は、TimeoutException を返す前に続行するには、この操作を許可する最長時間</span><span class="sxs-lookup"><span data-stu-id="48022-131">The maximum amount of time Service Fabric will allow this operation to continue before returning a TimeoutException</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="48022-132"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="48022-132">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="48022-133">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="48022-133">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="48022-134">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="48022-134">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="48022-135">ノードのコンテキスト Fabric ノードから非同期的にタイムアウトとキャンセル トークン取得します。</span><span class="sxs-lookup"><span data-stu-id="48022-135">Gets Node Context from Fabric Node asynchronously with timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="48022-136">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="48022-136">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceGroupFactory">
      <MemberSignature Language="C#" Value="public void RegisterServiceGroupFactory (string serviceGroupTypeName, System.Fabric.ServiceGroupFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterServiceGroupFactory(string serviceGroupTypeName, class System.Fabric.ServiceGroupFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterServiceGroupFactory(System.String,System.Fabric.ServiceGroupFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterServiceGroupFactory (serviceGroupTypeName As String, factory As ServiceGroupFactory)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceGroupFactory : string * System.Fabric.ServiceGroupFactory -&gt; unit" Usage="fabricRuntime.RegisterServiceGroupFactory (serviceGroupTypeName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.ServiceGroupFactory" />
      </Parameters>
      <Docs>
        <param name="serviceGroupTypeName">
          <para><span data-ttu-id="48022-137">(文字列) と ServiceGroup サービス型の型名。</span><span class="sxs-lookup"><span data-stu-id="48022-137">The type name of the ServiceGroup service type (as a string).</span></span>  <span data-ttu-id="48022-138">これは、マニフェストや CreateServiceGroup コマンドで指定されているサービス グループの種類の型と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="48022-138">This should match the type of the service group type as specified in the manifests and/or the CreateServiceGroup command.</span></span></para>
        </param>
        <param name="factory">
          <para><span data-ttu-id="48022-139"><see cref="T:System.Fabric.ServiceGroupFactory" />指定したサービス グループの種類を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="48022-139">The <see cref="T:System.Fabric.ServiceGroupFactory" /> which can create the specified service group type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="48022-140">指定した登録<see cref="T:System.Fabric.ServiceGroupFactory" />指定の種類。</span><span class="sxs-lookup"><span data-stu-id="48022-140">Registers the specified <see cref="T:System.Fabric.ServiceGroupFactory" /> for the specified type.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceGroupFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterServiceGroupFactoryAsync (string serviceGroupTypeName, System.Fabric.ServiceGroupFactory factory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterServiceGroupFactoryAsync(string serviceGroupTypeName, class System.Fabric.ServiceGroupFactory factory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterServiceGroupFactoryAsync(System.String,System.Fabric.ServiceGroupFactory,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceGroupFactoryAsync : string * System.Fabric.ServiceGroupFactory * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricRuntime.RegisterServiceGroupFactoryAsync (serviceGroupTypeName, factory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.ServiceGroupFactory" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceGroupTypeName">
          <para><span data-ttu-id="48022-141">(文字列) と ServiceGroup サービス型の型名。</span><span class="sxs-lookup"><span data-stu-id="48022-141">The type name of the ServiceGroup service type (as a string).</span></span>  <span data-ttu-id="48022-142">これは、マニフェストや CreateServiceGroup コマンドで指定されているサービス グループの種類の型と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="48022-142">This should match the type of the service group type as specified in the manifests and/or the CreateServiceGroup command.</span></span></para>
        </param>
        <param name="factory">
          <para><span data-ttu-id="48022-143"><see cref="T:System.Fabric.ServiceGroupFactory" />指定したサービス グループの種類を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="48022-143">The <see cref="T:System.Fabric.ServiceGroupFactory" /> which can create the specified service group type.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="48022-144">Service Fabric は、TimeoutException を返す前に続行するには、この操作を許可する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="48022-144">The maximum amount of time Service Fabric will allow this operation to continue before returning a TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="48022-145"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="48022-145">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="48022-146">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="48022-146">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="48022-147">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="48022-147">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="48022-148">非同期的に、指定した登録<see cref="T:System.Fabric.ServiceGroupFactory" />、指定したサービス グループの種類の指定した<paramref name="timeout" />と<paramref name="cancellationToken" />です。</span><span class="sxs-lookup"><span data-stu-id="48022-148">Asynchronously registers the specified <see cref="T:System.Fabric.ServiceGroupFactory" /> for the specified service group type with the specified <paramref name="timeout" /> and <paramref name="cancellationToken" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="48022-149">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="48022-149">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceType">
      <MemberSignature Language="C#" Value="public void RegisterServiceType (string serviceTypeName, Type serviceTypeImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterServiceType(string serviceTypeName, class System.Type serviceTypeImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterServiceType(System.String,System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterServiceType (serviceTypeName As String, serviceTypeImplementation As Type)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceType : string * Type -&gt; unit" Usage="fabricRuntime.RegisterServiceType (serviceTypeName, serviceTypeImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceTypeImplementation" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="48022-150">(文字列) としてサービスの種類の型名。</span><span class="sxs-lookup"><span data-stu-id="48022-150">The type name of the service type (as a string).</span></span>  <span data-ttu-id="48022-151">これは、マニフェストや CreateService コマンドで指定されているサービス グループの種類の型と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="48022-151">This should match the type of the service group type as specified in the manifests and/or the CreateService command.</span></span></para>
        </param>
        <param name="serviceTypeImplementation">
          <para><span data-ttu-id="48022-152">指定されたを実装する型の修飾サービス<paramref name="serviceTypeName" />です。</span><span class="sxs-lookup"><span data-stu-id="48022-152">The qualified service Type that implements the specified <paramref name="serviceTypeName" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="48022-153">指定したに関連付けます<paramref name="serviceTypeName" />実際にそれを実装する型を管理します。</span><span class="sxs-lookup"><span data-stu-id="48022-153">Associates the specified <paramref name="serviceTypeName" /> with the actual managed Type that implements it.</span></span> </para>
        </summary>
        <remarks>
          <para><span data-ttu-id="48022-154">サービスの種類の登録のためには、このメカニズムは、カスタムを必要とされません<see cref="T:System.Fabric.IStatelessServiceFactory" />または<see cref="T:System.Fabric.IStatefulServiceFactory" />登録時に提供されます。</span><span class="sxs-lookup"><span data-stu-id="48022-154">Note that this mechanism for service type registration does not require a custom <see cref="T:System.Fabric.IStatelessServiceFactory" /> or <see cref="T:System.Fabric.IStatefulServiceFactory" /> to be provided at registration time.</span></span>  <span data-ttu-id="48022-155">Service Fabric では、実行時に 1 つを生成し、それを自動的に利用します。</span><span class="sxs-lookup"><span data-stu-id="48022-155">Service Fabric will generate one at runtime and utilize it automatically.</span></span>  <span data-ttu-id="48022-156">工場出荷時のカスタム実装の必要性がある場合は、実装<see cref="T:System.Fabric.IStatelessServiceFactory" />または<see cref="T:System.Fabric.IStatefulServiceFactory" />うえで、対応するファクトリを使用している登録メソッド (<see cref="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactoryAsync(System.String,System.Fabric.IStatelessServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />または<see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactoryAsync(System.String,System.Fabric.IStatefulServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />)</span><span class="sxs-lookup"><span data-stu-id="48022-156">If there is a need for a custom implementation of the factory, you can implement <see cref="T:System.Fabric.IStatelessServiceFactory" /> or <see cref="T:System.Fabric.IStatefulServiceFactory" /> and then provide those via the corresponding factory registration methods (<see cref="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactoryAsync(System.String,System.Fabric.IStatelessServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" /> or <see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactoryAsync(System.String,System.Fabric.IStatefulServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />)</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceTypeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterServiceTypeAsync (string serviceTypeName, Type serviceTypeImplementation, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterServiceTypeAsync(string serviceTypeName, class System.Type serviceTypeImplementation, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterServiceTypeAsync(System.String,System.Type,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceTypeAsync : string * Type * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricRuntime.RegisterServiceTypeAsync (serviceTypeName, serviceTypeImplementation, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceTypeImplementation" Type="System.Type" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="48022-157">(文字列) としてサービスの種類の型名。</span><span class="sxs-lookup"><span data-stu-id="48022-157">The type name of the service type (as a string).</span></span>  <span data-ttu-id="48022-158">これは、マニフェストや CreateService コマンドで指定されているサービス グループの種類の型と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="48022-158">This should match the type of the service group type as specified in the manifests and/or the CreateService command.</span></span></para>
        </param>
        <param name="serviceTypeImplementation">
          <para><span data-ttu-id="48022-159">指定されたを実装する型の修飾サービス<paramref name="serviceTypeName" />です。</span><span class="sxs-lookup"><span data-stu-id="48022-159">The qualified service Type that implements the specified <paramref name="serviceTypeName" />.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="48022-160">Service Fabric は、TimeoutException を返す前に続行するには、この操作を許可する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="48022-160">The maximum amount of time Service Fabric will allow this operation to continue before returning a TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="48022-161"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="48022-161">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>  <span data-ttu-id="48022-162">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="48022-162">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="48022-163">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="48022-163">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="48022-164">非同期的に指定された serviceTypeName を実装して、指定した実際のマネージ型に関連付けます<paramref name="timeout" />と<paramref name="cancellationToken" /></span><span class="sxs-lookup"><span data-stu-id="48022-164">Asynchronously associates the specified serviceTypeName with the actual managed Type that implements it, with the specified <paramref name="timeout" /> and <paramref name="cancellationToken" /></span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="48022-165">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="48022-165">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterStatefulServiceFactory">
      <MemberSignature Language="C#" Value="public void RegisterStatefulServiceFactory (string serviceTypeName, System.Fabric.IStatefulServiceFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterStatefulServiceFactory(string serviceTypeName, class System.Fabric.IStatefulServiceFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactory(System.String,System.Fabric.IStatefulServiceFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterStatefulServiceFactory (serviceTypeName As String, factory As IStatefulServiceFactory)" />
      <MemberSignature Language="F#" Value="member this.RegisterStatefulServiceFactory : string * System.Fabric.IStatefulServiceFactory -&gt; unit" Usage="fabricRuntime.RegisterStatefulServiceFactory (serviceTypeName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatefulServiceFactory" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="48022-166">(文字列) としてサービスの種類の型名。</span><span class="sxs-lookup"><span data-stu-id="48022-166">The type name of the service type (as a string).</span></span>  <span data-ttu-id="48022-167">これは、マニフェストや CreateService コマンドで指定されているサービス グループの種類の型と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="48022-167">This should match the type of the service group type as specified in the manifests and/or the CreateService command.</span></span></para>
        </param>
        <param name="factory">
          <para><span data-ttu-id="48022-168"><see cref="T:System.Fabric.IStatefulServiceFactory" />指定されたサービス型を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="48022-168">The <see cref="T:System.Fabric.IStatefulServiceFactory" /> which can create the specified service type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="48022-169">指定した登録<see cref="T:System.Fabric.IStatefulServiceFactory" />指定されたサービスの種類。</span><span class="sxs-lookup"><span data-stu-id="48022-169">Registers the specified <see cref="T:System.Fabric.IStatefulServiceFactory" /> for the specified service type.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterStatefulServiceFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterStatefulServiceFactoryAsync (string serviceTypeName, System.Fabric.IStatefulServiceFactory factory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterStatefulServiceFactoryAsync(string serviceTypeName, class System.Fabric.IStatefulServiceFactory factory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactoryAsync(System.String,System.Fabric.IStatefulServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterStatefulServiceFactoryAsync : string * System.Fabric.IStatefulServiceFactory * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricRuntime.RegisterStatefulServiceFactoryAsync (serviceTypeName, factory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatefulServiceFactory" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="48022-170">(文字列) としてサービスの種類の型名。</span><span class="sxs-lookup"><span data-stu-id="48022-170">The type name of the service type (as a string).</span></span>  <span data-ttu-id="48022-171">これは、マニフェストや CreateService コマンドで指定されているサービス グループの種類の型と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="48022-171">This should match the type of the service group type as specified in the manifests and/or the CreateService command.</span></span></para>
        </param>
        <param name="factory">
          <para><span data-ttu-id="48022-172"><see cref="T:System.Fabric.IStatefulServiceFactory" />指定されたサービス型を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="48022-172">The <see cref="T:System.Fabric.IStatefulServiceFactory" /> which can create the specified service type.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="48022-173">Service Fabric は、TimeoutException を返す前に続行するには、この操作を許可する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="48022-173">The maximum amount of time Service Fabric will allow this operation to continue before returning a TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="48022-174"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="48022-174">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>  <span data-ttu-id="48022-175">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="48022-175">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="48022-176">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="48022-176">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="48022-177">指定した登録<see cref="T:System.Fabric.IStatefulServiceFactory" />、指定されたサービスの種類の指定した<paramref name="timeout" />と<paramref name="cancellationToken" />です。</span><span class="sxs-lookup"><span data-stu-id="48022-177">Registers the specified <see cref="T:System.Fabric.IStatefulServiceFactory" /> for the specified service type with the specified <paramref name="timeout" /> and <paramref name="cancellationToken" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="48022-178">操作を表す非同期です。</span><span class="sxs-lookup"><span data-stu-id="48022-178">The representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterStatelessServiceFactory">
      <MemberSignature Language="C#" Value="public void RegisterStatelessServiceFactory (string serviceTypeName, System.Fabric.IStatelessServiceFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterStatelessServiceFactory(string serviceTypeName, class System.Fabric.IStatelessServiceFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactory(System.String,System.Fabric.IStatelessServiceFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterStatelessServiceFactory (serviceTypeName As String, factory As IStatelessServiceFactory)" />
      <MemberSignature Language="F#" Value="member this.RegisterStatelessServiceFactory : string * System.Fabric.IStatelessServiceFactory -&gt; unit" Usage="fabricRuntime.RegisterStatelessServiceFactory (serviceTypeName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatelessServiceFactory" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="48022-179">(文字列) としてサービスの種類の型名。</span><span class="sxs-lookup"><span data-stu-id="48022-179">The type name of the service type (as a string).</span></span>  <span data-ttu-id="48022-180">これは、マニフェストや CreateService コマンドで指定されているサービス グループの種類の型と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="48022-180">This should match the type of the service group type as specified in the manifests and/or the CreateService command.</span></span></para>
        </param>
        <param name="factory">
          <para><span data-ttu-id="48022-181"><see cref="T:System.Fabric.IStatelessServiceFactory" />指定されたサービス型を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="48022-181">The <see cref="T:System.Fabric.IStatelessServiceFactory" /> which can create the specified service type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="48022-182">指定した登録<see cref="T:System.Fabric.IStatelessServiceFactory" />指定されたサービスの種類。</span><span class="sxs-lookup"><span data-stu-id="48022-182">Registers the specified <see cref="T:System.Fabric.IStatelessServiceFactory" /> for the specified service type.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterStatelessServiceFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterStatelessServiceFactoryAsync (string serviceTypeName, System.Fabric.IStatelessServiceFactory factory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterStatelessServiceFactoryAsync(string serviceTypeName, class System.Fabric.IStatelessServiceFactory factory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactoryAsync(System.String,System.Fabric.IStatelessServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterStatelessServiceFactoryAsync : string * System.Fabric.IStatelessServiceFactory * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricRuntime.RegisterStatelessServiceFactoryAsync (serviceTypeName, factory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatelessServiceFactory" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="48022-183">(文字列) としてサービスの種類の型名。</span><span class="sxs-lookup"><span data-stu-id="48022-183">The type name of the service type (as a string).</span></span>  <span data-ttu-id="48022-184">これは、マニフェストや CreateService コマンドで指定されているサービス グループの種類の型と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="48022-184">This should match the type of the service group type as specified in the manifests and/or the CreateService command.</span></span></para>
        </param>
        <param name="factory">
          <para><span data-ttu-id="48022-185"><see cref="T:System.Fabric.IStatelessServiceFactory" />指定されたサービス型を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="48022-185">The <see cref="T:System.Fabric.IStatelessServiceFactory" /> which can create the specified service type.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="48022-186">Service Fabric は、TimeoutException を返す前に続行するには、この操作を許可する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="48022-186">The maximum amount of time Service Fabric will allow this operation to continue before returning a TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="48022-187"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="48022-187">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>  <span data-ttu-id="48022-188">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="48022-188">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="48022-189">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="48022-189">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="48022-190">非同期的に、指定した登録<see cref="T:System.Fabric.IStatelessServiceFactory" />、指定したサービス型を指定した<paramref name="timeout" />と<paramref name="cancellationToken" /></span><span class="sxs-lookup"><span data-stu-id="48022-190">Asynchronously registers the specified <see cref="T:System.Fabric.IStatelessServiceFactory" /> for the specified service type, with the specified <paramref name="timeout" /> and <paramref name="cancellationToken" /></span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="48022-191">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="48022-191">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>