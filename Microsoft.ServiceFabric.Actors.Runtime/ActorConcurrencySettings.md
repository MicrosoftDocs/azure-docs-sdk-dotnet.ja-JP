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
            アクターをベースにする同時実行のロックを構成する設定を提供します。 アクターで同時実行の詳細については https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-actors-introduction を参照してください。
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
            ActorConcurrencySettings クラスの新しいインスタンスを初期化します。
            
            既定では、<see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.ReentrancyMode" />は<see cref="F:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode.LogicalCallContext" />で、 <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.LockTimeout" /> (60 秒)
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
            取得またはベースを有効にする同時実行のロックのタイムアウトを設定します。 スローする場合は、ランタイムは、メソッドの呼び出しをディスパッチするロックを取得できません、<see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" />例外。 この例外は、論理呼び出しチェーンをアンワインドし、呼び出しは、時間の場合は、構成された最大時間を再試行します。
            </summary>
        <value>同時実行のロックを有効にするためのタイムアウトに基づいています。 これに設定できます<see cref="F:System.Threading.Timeout.InfiniteTimeSpan" />永遠に待機しているを指定します。</value>
        <remarks>
            同時実行のロックの実際のタイムアウト値は、上位のように、ランタイムは、指定された値をランダムな間隔を追加できます。
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
            取得またはアクター メソッドの呼び出しのための再入モードを設定します。
            </summary>
        <value>
          <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode" />アクター メソッドの呼び出しです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>