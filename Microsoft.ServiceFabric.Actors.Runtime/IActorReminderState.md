<Type Name="IActorReminderState" FullName="Microsoft.ServiceFabric.Actors.Runtime.IActorReminderState">
  <TypeSignature Language="C#" Value="public interface IActorReminderState : Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorReminderState implements class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.IActorReminderState" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorReminderState&#xA;Implements IActorReminder" />
  <TypeSignature Language="F#" Value="type IActorReminderState = interface&#xA;    interface IActorReminder" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Actors.Runtime.IActorReminder</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="2ed30-101">アクターの関連語句の内部状態を表します。</span><span class="sxs-lookup"><span data-stu-id="2ed30-101">Represents internal state of Actor Reminder.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="RemainingDueTime">
      <MemberSignature Language="C#" Value="public TimeSpan RemainingDueTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RemainingDueTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminderState.RemainingDueTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemainingDueTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RemainingDueTime : TimeSpan" Usage="Microsoft.ServiceFabric.Actors.Runtime.IActorReminderState.RemainingDueTime" />
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
            <span data-ttu-id="2ed30-102">アラームが次の支払時刻。</span><span class="sxs-lookup"><span data-stu-id="2ed30-102">Time when Reminder is next due.</span></span>
            </summary>
        <value><span data-ttu-id="2ed30-103">期限の時刻として<see cref="T:System.TimeSpan" />アラームが次の支払場合。</span><span class="sxs-lookup"><span data-stu-id="2ed30-103">Due time as <see cref="T:System.TimeSpan" /> when the reminder is next due.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>