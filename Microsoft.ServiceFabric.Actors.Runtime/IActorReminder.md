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
            使用して登録アラームを表す<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />です。
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
            ときにアラームが最初により呼び出される時間を取得します。
            </summary>
        <value>アラームが呼び出されるため最初と時刻。</value>
        <remarks>
            負 (-1) ミリ秒の値と、アラームは呼び出されません。 値のゼロ (0 は、登録後すぐにアラームが呼び出されます。
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
            アラームの名前を取得します。 名前は、アクターごとに一意です。
            </summary>
        <value>アラームの名前。</value>
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
            アラームが定期的に呼び出される時間間隔を取得します。
            </summary>
        <value>アラームが定期的に呼び出される時間間隔。</value>
        <remarks>
            アラームの最初の呼び出しの後に発生<see cref="P:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder.DueTime" />です。 すべての後続の呼び出しは、このプロパティによって定義された間隔で発生します。
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
            アラームの呼び出しに渡されるユーザー状態を取得します。
            </summary>
        <value>アラームの呼び出しに渡されるユーザー状態。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>