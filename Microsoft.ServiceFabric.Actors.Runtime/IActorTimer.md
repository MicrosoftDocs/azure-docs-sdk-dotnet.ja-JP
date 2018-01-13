<Type Name="IActorTimer" FullName="Microsoft.ServiceFabric.Actors.Runtime.IActorTimer">
  <TypeSignature Language="C#" Value="public interface IActorTimer : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorTimer implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.IActorTimer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorTimer&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IActorTimer = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            タイマーのアクターのセットを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DueTime">
      <MemberSignature Language="C#" Value="public TimeSpan DueTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DueTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.IActorTimer.DueTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DueTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DueTime : TimeSpan" Usage="Microsoft.ServiceFabric.Actors.Runtime.IActorTimer.DueTime" />
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
            タイマーの期限最初の時刻を取得します。
            </summary>
        <value>時刻<see cref="T:System.TimeSpan" />タイマーが期限最初の場合。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Period">
      <MemberSignature Language="C#" Value="public TimeSpan Period { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Period" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.IActorTimer.Period" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Period As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Period : TimeSpan" Usage="Microsoft.ServiceFabric.Actors.Runtime.IActorTimer.Period" />
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
            タイマーが呼び出されるときに定期的な時刻を取得します。
            </summary>
        <value>として周期の時間<see cref="T:System.TimeSpan" />タイマーが呼び出されるとします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>