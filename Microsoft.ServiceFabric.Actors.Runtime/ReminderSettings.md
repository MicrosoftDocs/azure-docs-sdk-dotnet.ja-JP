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
            このクラスは、通知の動作を構成する設定を提供します。 Https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-reliable-actors-timers-reminders を参照してください。
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
            ReminderSettings クラスの新しいインスタンスを初期化します。
            
            既定では、<see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings.AutoDeleteOneTimeReminders" />に設定されている<c>true</c>です。
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
            取得または ActorRuntime 必要がありますを自動的に削除アラームを 1 回だけ発生し、さらに、このコールバックを正常に完了した後を示す値を設定します。 1 回限りのアラームを参照してくださいアラームが<see cref="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.Period" />が負の値に設定します。
            </summary>
        <value>
            ActorRuntime 必要がありますを自動的に削除 1 回限りのアラームが発生した、そのコールバックを正常に完了した後を示すブール値。
            </value>
        <remarks>
            アラームと見なされる注完了される場合にのみ正常にアラーム コールバック<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />が正常に完了します。
            通知コールバックの実行中に、フェールオーバーが発生した場合、新しいプライマリ レプリカでアラームが再び起動されます。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>