<Type Name="IActorReminder" FullName="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder">
  <TypeSignature Language="C#" Value="public interface IActorReminder" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorReminder" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorReminder" />
  <TypeSignature Language="F#" Value="type IActorReminder = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5a8ea-101">使用して登録アラームを表す<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />です。</span><span class="sxs-lookup"><span data-stu-id="5a8ea-101">Represents a reminder registered using <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DueTime">
      <MemberSignature Language="C#" Value="public TimeSpan DueTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DueTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.DueTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DueTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DueTime : TimeSpan" Usage="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.DueTime" />
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
            <span data-ttu-id="5a8ea-102">ときにアラームが最初により呼び出される時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="5a8ea-102">Gets the time when the reminder is first due to be invoked.</span></span>
            </summary>
        <value><span data-ttu-id="5a8ea-103">アラームが呼び出されるため最初と時刻。</span><span class="sxs-lookup"><span data-stu-id="5a8ea-103">The time when the reminder is first due to be invoked.</span></span></value>
        <remarks>
            <span data-ttu-id="5a8ea-104">負 (-1) ミリ秒の値と、アラームは呼び出されません。</span><span class="sxs-lookup"><span data-stu-id="5a8ea-104">A value of negative one (-1) milliseconds means the reminder is not invoked.</span></span> <span data-ttu-id="5a8ea-105">値のゼロ (0 は、登録後すぐにアラームが呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="5a8ea-105">A value of zero (0) means the reminder is invoked immediately after registration.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a8ea-106">アラームの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="5a8ea-106">Gets the name of the reminder.</span></span> <span data-ttu-id="5a8ea-107">名前は、アクターごとに一意です。</span><span class="sxs-lookup"><span data-stu-id="5a8ea-107">The name is unique per actor.</span></span>
            </summary>
        <value><span data-ttu-id="5a8ea-108">アラームの名前。</span><span class="sxs-lookup"><span data-stu-id="5a8ea-108">The name of the reminder.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Period">
      <MemberSignature Language="C#" Value="public TimeSpan Period { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Period" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.Period" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Period As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Period : TimeSpan" Usage="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.Period" />
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
            <span data-ttu-id="5a8ea-109">アラームが定期的に呼び出される時間間隔を取得します。</span><span class="sxs-lookup"><span data-stu-id="5a8ea-109">Gets the time interval at which the reminder is invoked periodically.</span></span>
            </summary>
        <value><span data-ttu-id="5a8ea-110">アラームが定期的に呼び出される時間間隔。</span><span class="sxs-lookup"><span data-stu-id="5a8ea-110">The time interval at which the reminder is invoked periodically.</span></span></value>
        <remarks>
            <span data-ttu-id="5a8ea-111">アラームの最初の呼び出しの後に発生<see cref="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.DueTime" />です。</span><span class="sxs-lookup"><span data-stu-id="5a8ea-111">The first invocation of the reminder occurs after <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.DueTime" />.</span></span> <span data-ttu-id="5a8ea-112">すべての後続の呼び出しは、このプロパティによって定義された間隔で発生します。</span><span class="sxs-lookup"><span data-stu-id="5a8ea-112">All subsequent invocations occur at intervals defined by this property.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public byte[] State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Byte()" />
      <MemberSignature Language="F#" Value="member this.State : byte[]" Usage="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a8ea-113">アラームの呼び出しに渡されるユーザー状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="5a8ea-113">Gets the user state passed to the reminder invocation.</span></span>
            </summary>
        <value><span data-ttu-id="5a8ea-114">アラームの呼び出しに渡されるユーザー状態。</span><span class="sxs-lookup"><span data-stu-id="5a8ea-114">The user state passed to the reminder invocation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>