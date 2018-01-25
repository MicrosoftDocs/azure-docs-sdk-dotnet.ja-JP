<Type Name="ActorConcurrencySettings" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings">
  <TypeSignature Language="C#" Value="public sealed class ActorConcurrencySettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorConcurrencySettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorConcurrencySettings" />
  <TypeSignature Language="F#" Value="type ActorConcurrencySettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e9d6a-101">アクターをベースにする同時実行のロックを構成する設定を提供します。</span><span class="sxs-lookup"><span data-stu-id="e9d6a-101">Provides the settings to configure the turn based concurrency lock for actors.</span></span> <span data-ttu-id="e9d6a-102">アクターで同時実行の詳細については https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-actors-introduction を参照してください。</span><span class="sxs-lookup"><span data-stu-id="e9d6a-102">See https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-actors-introduction for a description of concurrency in actors.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorConcurrencySettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e9d6a-103">ActorConcurrencySettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e9d6a-103">Initializes a new instance of the ActorConcurrencySettings class.</span></span>
            
            <span data-ttu-id="e9d6a-104">既定では、<see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.ReentrancyMode" />は<see cref="F:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode.LogicalCallContext" />で、 <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.LockTimeout" /> (60 秒)</span><span class="sxs-lookup"><span data-stu-id="e9d6a-104">By default the <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.ReentrancyMode" /> is <see cref="F:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode.LogicalCallContext" /> with a <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.LockTimeout" /> of 60 seconds</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan LockTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LockTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.LockTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LockTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LockTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.LockTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e9d6a-105">取得またはベースを有効にする同時実行のロックのタイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="e9d6a-105">Gets or sets the timeout for the turn based concurrency lock.</span></span> <span data-ttu-id="e9d6a-106">スローする場合は、ランタイムは、メソッドの呼び出しをディスパッチするロックを取得できません、<see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" />例外。</span><span class="sxs-lookup"><span data-stu-id="e9d6a-106">If the runtime cannot acquire the lock to dispatch the method call, it will throw the <see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" /> exception.</span></span> <span data-ttu-id="e9d6a-107">この例外は、論理呼び出しチェーンをアンワインドし、呼び出しは、時間の場合は、構成された最大時間を再試行します。</span><span class="sxs-lookup"><span data-stu-id="e9d6a-107">This exception will unwind the logical call chain and the call will retried up to a configured maximum amount of times.</span></span>
            </summary>
        <value><span data-ttu-id="e9d6a-108">同時実行のロックを有効にするためのタイムアウトに基づいています。</span><span class="sxs-lookup"><span data-stu-id="e9d6a-108">Timeout for the turn based concurrency lock.</span></span> <span data-ttu-id="e9d6a-109">これに設定できます<see cref="F:System.Threading.Timeout.InfiniteTimeSpan" />永遠に待機しているを指定します。</span><span class="sxs-lookup"><span data-stu-id="e9d6a-109">This can be set to <see cref="F:System.Threading.Timeout.InfiniteTimeSpan" /> to specify waiting forever.</span></span></value>
        <remarks>
            <span data-ttu-id="e9d6a-110">同時実行のロックの実際のタイムアウト値は、上位のように、ランタイムは、指定された値をランダムな間隔を追加できます。</span><span class="sxs-lookup"><span data-stu-id="e9d6a-110">The actual timeout value for the concurrency lock can be higher as the runtime will add a random interval to the supplied value.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReentrancyMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode ReentrancyMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode ReentrancyMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.ReentrancyMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ReentrancyMode As ActorReentrancyMode" />
      <MemberSignature Language="F#" Value="member this.ReentrancyMode : Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode with get, set" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.ReentrancyMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e9d6a-111">取得またはアクター メソッドの呼び出しのための再入モードを設定します。</span><span class="sxs-lookup"><span data-stu-id="e9d6a-111">Gets or sets Reentrancy mode for actor method calls.</span></span>
            </summary>
        <value>
          <span data-ttu-id="e9d6a-112"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode" />アクター メソッドの呼び出しです。</span><span class="sxs-lookup"><span data-stu-id="e9d6a-112"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode" /> for the actor method calls.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>