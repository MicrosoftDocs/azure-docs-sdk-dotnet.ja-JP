<Type Name="ReminderSettings" FullName="Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings">
  <TypeSignature Language="C#" Value="public sealed class ReminderSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReminderSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReminderSettings" />
  <TypeSignature Language="F#" Value="type ReminderSettings = class" />
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
            <span data-ttu-id="adcf8-101">このクラスは、通知の動作を構成する設定を提供します。</span><span class="sxs-lookup"><span data-stu-id="adcf8-101">This class provides settings to configure the behavior of reminders.</span></span> <span data-ttu-id="adcf8-102">Https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-reliable-actors-timers-reminders を参照してください。</span><span class="sxs-lookup"><span data-stu-id="adcf8-102">See https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-reliable-actors-timers-reminders</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReminderSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="adcf8-103">ReminderSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="adcf8-103">Initializes a new instance of the ReminderSettings class.</span></span>
            
            <span data-ttu-id="adcf8-104">既定では、<see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings.AutoDeleteOneTimeReminders" />に設定されている<c>true</c>です。</span><span class="sxs-lookup"><span data-stu-id="adcf8-104">By default the <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings.AutoDeleteOneTimeReminders" /> is set to <c>true</c>.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOneTimeReminders">
      <MemberSignature Language="C#" Value="public bool AutoDeleteOneTimeReminders { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoDeleteOneTimeReminders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings.AutoDeleteOneTimeReminders" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOneTimeReminders As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOneTimeReminders : bool with get, set" Usage="Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings.AutoDeleteOneTimeReminders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="adcf8-105">取得または ActorRuntime 必要がありますを自動的に削除アラームを 1 回だけ発生し、さらに、このコールバックを正常に完了した後を示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="adcf8-105">Gets or sets value indicating if ActorRuntime should automatically delete one-time reminders after they have fired and completed its callback successfully.</span></span> <span data-ttu-id="adcf8-106">1 回限りのアラームを参照してくださいアラームが<see cref="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.Period" />が負の値に設定します。</span><span class="sxs-lookup"><span data-stu-id="adcf8-106">One-time reminders refer to reminders whose <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.Period" /> is set to negative value.</span></span>
            </summary>
        <value>
            <span data-ttu-id="adcf8-107">ActorRuntime 必要がありますを自動的に削除 1 回限りのアラームが発生した、そのコールバックを正常に完了した後を示すブール値。</span><span class="sxs-lookup"><span data-stu-id="adcf8-107">The bool value indicating if ActorRuntime should automatically delete a one-time reminders after it has fired and completed its callback successfully.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="adcf8-108">アラームと見なされる注完了される場合にのみ正常にアラーム コールバック<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />が正常に完了します。</span><span class="sxs-lookup"><span data-stu-id="adcf8-108">Note that a reminder is considered to completed successfully only when reminder callback <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" /> completes successfully.</span></span>
            <span data-ttu-id="adcf8-109">通知コールバックの実行中に、フェールオーバーが発生した場合、新しいプライマリ レプリカでアラームが再び起動されます。</span><span class="sxs-lookup"><span data-stu-id="adcf8-109">If a failover happens while reminder callback was executing, reminder will fire again on new primary replica.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>