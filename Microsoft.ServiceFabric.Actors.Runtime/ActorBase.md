<Type Name="ActorBase" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorBase">
  <TypeSignature Language="C#" Value="public abstract class ActorBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ActorBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ActorBase" />
  <TypeSignature Language="F#" Value="type ActorBase = class" />
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
            アクターの基本クラスを表します。
            </summary>
    <remarks>
            アクターの基本データ型から派生したアクターの共通の機能を提供する<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />です。
            アクターのガベージ コレクションとのフェールオーバーの制限の状態が保持されます。
            状態の取得と格納は、アクター状態プロバイダーによって提供されます。 詳細については、「 <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> 」を参照してください。
            </remarks>
    <altmember cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />
  </Docs>
  <Members>
    <Member MemberName="ActorService">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.ActorService ActorService { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.ActorService ActorService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ActorService" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorService As ActorService" />
      <MemberSignature Language="F#" Value="member this.ActorService : Microsoft.ServiceFabric.Actors.Runtime.ActorService" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ActorService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorService</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アクターをホストしているステートフル サービス レプリカを取得します。
            </summary>
        <value>
            <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ActorService" />ステートフル サービス レプリカをホストしているアクターを表すです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public string ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : string" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ApplicationName" />
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
            このアクターをホストしているアクター サービスが含まれるアプリケーションの名前を取得します。
            </summary>
        <value>このアクターをホストしているアクター サービスが含まれるアプリケーションの名前。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEvent&lt;TEvent&gt;">
      <MemberSignature Language="C#" Value="protected TEvent GetEvent&lt;TEvent&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance !!TEvent GetEvent&lt;TEvent&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.GetEvent``1" />
      <MemberSignature Language="VB.NET" Value="Protected Function GetEvent(Of TEvent) () As TEvent" />
      <MemberSignature Language="F#" Value="member this.GetEvent : unit -&gt; 'Event" Usage="actorBase.GetEvent " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TEvent</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TEvent" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="TEvent">イベント インターフェイスの型。</typeparam>
        <summary>
            指定したイベント インターフェイスのイベントを取得します。
            </summary>
        <returns>指定されたインターフェイスを表すイベントを返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReminder">
      <MemberSignature Language="C#" Value="protected Microsoft.ServiceFabric.Actors.Runtime.IActorReminder GetReminder (string reminderName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder GetReminder(string reminderName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.GetReminder(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Function GetReminder (reminderName As String) As IActorReminder" />
      <MemberSignature Language="F#" Value="member this.GetReminder : string -&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" Usage="actorBase.GetReminder reminderName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.IActorReminder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reminderName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="reminderName">取得するアラームの名前。</param>
        <summary>
            指定された通知の名前を持つアクター アラームを取得します。
            </summary>
        <returns>
            <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />アクター アラームを表すです。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceFabric.Actors.ReminderNotFoundException">アラームのアクターが見つかりません。</exception>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.ActorId Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.ActorId Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As ActorId" />
      <MemberSignature Language="F#" Value="member this.Id : Microsoft.ServiceFabric.Actors.ActorId" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorBase.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アクター サービスとこのアクターの id を取得します。
            </summary>
        <value><see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />アクターのです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnActivateAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnActivateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnActivateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnActivateAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnActivateAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OnActivateAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.OnActivateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="actorBase.OnActivateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            メンバーを初期化、状態を初期化またはタイマーを登録するには、このメソッドをオーバーライドします。 このメソッドは、アクターがアクティブ化後は、メソッドの前に、上の呼び出しやアラームをディスパッチします。 右呼び出されます。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task">タスク</see>OnActivateAsync の未処理の操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeactivateAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnDeactivateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnDeactivateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnDeactivateAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnDeactivateAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OnDeactivateAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.OnDeactivateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="actorBase.OnDeactivateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
             リソースを解放するには、このメソッドをオーバーライドします。 アクターが非アクティブ化された (によるガベージ コレクション実行時のアクター) の場合は、このメソッドが呼び出されます。
             状態の変更などのアクター操作は、このメソッドから呼び出さないようにしてください。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task">タスク</see>OnDeactivateAsync の未処理の操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnPostActorMethodAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnPostActorMethodAsync (Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext actorMethodContext);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnPostActorMethodAsync(valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext actorMethodContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPostActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" />
      <MemberSignature Language="F#" Value="abstract member OnPostActorMethodAsync : Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext -&gt; System.Threading.Tasks.Task&#xA;override this.OnPostActorMethodAsync : Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext -&gt; System.Threading.Tasks.Task" Usage="actorBase.OnPostActorMethodAsync actorMethodContext" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorMethodContext" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" />
      </Parameters>
      <Docs>
        <param name="actorMethodContext">
            <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" />このメソッドの前にアクター ランタイムによって呼び出されたメソッドについて説明します。
            </param>
        <summary>
            アクター メソッドの実行が完了した後、すべてのアクションを実行するためには、このメソッドをオーバーライドします。
            このメソッドが呼び出されるアクター ランタイムによって、アクター メソッドの実行が完了しました。
            </summary>
        <returns>
            返します、<see cref="T:System.Threading.Tasks.Task">タスク</see>actor メソッドの操作を表すです。
            </returns>
        <remarks>
            前のバージョンのアクター ランタイムがこのメソッドを呼び出す: <list type="bullet"> <item><description>クライアント要求が送られたときにアクター インターフェイス メソッドを呼び出すします</description>。</item> <item><description>でメソッドを呼び出す<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" />アラームが発生したときのインターフェイスします</description>。</item> <item><description>タイマーが発生したときに、タイマー コールバックを呼び出します。</description></item></list></remarks>
      </Docs>
    </Member>
    <Member MemberName="OnPreActorMethodAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnPreActorMethodAsync (Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext actorMethodContext);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnPreActorMethodAsync(valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext actorMethodContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPreActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" />
      <MemberSignature Language="F#" Value="abstract member OnPreActorMethodAsync : Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext -&gt; System.Threading.Tasks.Task&#xA;override this.OnPreActorMethodAsync : Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext -&gt; System.Threading.Tasks.Task" Usage="actorBase.OnPreActorMethodAsync actorMethodContext" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorMethodContext" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" />
      </Parameters>
      <Docs>
        <param name="actorMethodContext">
            <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" />このメソッドの完了後にアクター ランタイムによって呼び出されるメソッドを記述します。
            </param>
        <summary>
            前のアクター メソッドが呼び出されるアクションを実行するためには、このメソッドをオーバーライドします。
            このメソッドはアクター メソッドの呼び出しの直前にアクター ランタイムによって呼び出されます。
            </summary>
        <returns>
            返します、<see cref="T:System.Threading.Tasks.Task">タスク</see>前 actor メソッドの操作を表すです。
            </returns>
        <remarks>
            前のバージョンのアクター ランタイムがこのメソッドを呼び出す: <list type="bullet"> <item><description>クライアント要求が送られたときにアクター インターフェイス メソッドを呼び出すします</description>。</item> <item><description>でメソッドを呼び出す<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" />アラームが発生したときのインターフェイスします</description>。</item> <item><description>タイマーが発生したときに、タイマー コールバックを呼び出します。</description></item></list></remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterReminderAsync">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminder&gt; RegisterReminderAsync (string reminderName, byte[] state, TimeSpan dueTime, TimeSpan period);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder&gt; RegisterReminderAsync(string reminderName, unsigned int8[] state, valuetype System.TimeSpan dueTime, valuetype System.TimeSpan period) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Function RegisterReminderAsync (reminderName As String, state As Byte(), dueTime As TimeSpan, period As TimeSpan) As Task(Of IActorReminder)" />
      <MemberSignature Language="F#" Value="member this.RegisterReminderAsync : string * byte[] * TimeSpan * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminder&gt;" Usage="actorBase.RegisterReminderAsync (reminderName, state, dueTime, period)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.ActorBase/&lt;RegisterReminderAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminder&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reminderName" Type="System.String" />
        <Parameter Name="state" Type="System.Byte[]" />
        <Parameter Name="dueTime" Type="System.TimeSpan" />
        <Parameter Name="period" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="reminderName">登録を求めるメッセージの名前。 名前は、アクターごとに一意にする必要があります。</param>
        <param name="state">アラームの呼び出しに渡されるユーザー状態。</param>
        <param name="dueTime">最初にアラームを呼び出す前に遅延時間の量。 負の値は-1 (ミリ秒) の呼び出しを無効にするを指定します。 登録後すぐに通知を起動するゼロ (0) を指定します。
            </param>
        <param name="period">
            最初の呼び出しの後にアラーム呼び出し間の時間間隔。 ミリ秒を指定 (-1) を定期的な呼び出しを無効にします。
            </param>
        <summary>
            アクターは、通知に登録します。
            </summary>
        <returns>
            非同期の登録操作を表すタスク。 タスクの結果は、登録済みの通知に関する情報を提供し、アラームを使用して、登録を解除するために使用<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.UnregisterReminderAsync(Microsoft.ServiceFabric.Actors.Runtime.IActorReminder)" />です。
            </returns>
        <remarks>
          <para>
            派生したクラス<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorBase" />実装する必要があります<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" />アラームの呼び出しを使用します。 複数のアラームは、いつでもによって一意に識別<paramref name="reminderName" />です。 既存の通知は、このメソッドをもう一度呼び出すことによっても更新されます。 アラームの呼び出しは、他のアラームとその他のアクター メソッド コールバックの両方で同期されます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterTimer">
      <MemberSignature Language="C#" Value="protected Microsoft.ServiceFabric.Actors.Runtime.IActorTimer RegisterTimer (Func&lt;object,System.Threading.Tasks.Task&gt; asyncCallback, object state, TimeSpan dueTime, TimeSpan period);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class Microsoft.ServiceFabric.Actors.Runtime.IActorTimer RegisterTimer(class System.Func`2&lt;object, class System.Threading.Tasks.Task&gt; asyncCallback, object state, valuetype System.TimeSpan dueTime, valuetype System.TimeSpan period) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterTimer(System.Func{System.Object,System.Threading.Tasks.Task},System.Object,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Function RegisterTimer (asyncCallback As Func(Of Object, Task), state As Object, dueTime As TimeSpan, period As TimeSpan) As IActorTimer" />
      <MemberSignature Language="F#" Value="member this.RegisterTimer : Func&lt;obj, System.Threading.Tasks.Task&gt; * obj * TimeSpan * TimeSpan -&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorTimer" Usage="actorBase.RegisterTimer (asyncCallback, state, dueTime, period)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.IActorTimer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncCallback" Type="System.Func&lt;System.Object,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="state" Type="System.Object" />
        <Parameter Name="dueTime" Type="System.TimeSpan" />
        <Parameter Name="period" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="asyncCallback">
            タイマーが起動されるときに呼び出されるメソッドを指定するデリゲート。
            1 つのパラメーターを持ち: RegisterTimer に渡される状態オブジェクト。
            返します、<see cref="T:System.Threading.Tasks.Task" />非同期操作を表すです。
            </param>
        <param name="state">コールバック メソッドを使用または null にする情報を含むオブジェクトです。</param>
        <param name="dueTime">非同期のコールバックが最初に呼び出される前に遅延する時間数。 -1 ミリ秒を指定して、タイマーが開始されないようにします。 0 を指定して、タイマーをすぐに開始します。
            </param>
        <param name="period">
            非同期のコールバックの呼び出し間の時間間隔。 -1 ミリ秒を指定して、周期的なシグナル通知を無効にします。</param>
        <summary>
            アクターのタイマーを登録します。
            </summary>
        <returns>IActorTimer オブジェクトを返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceUri">
      <MemberSignature Language="C#" Value="public Uri ServiceUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ServiceUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceUri As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceUri : Uri" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorBase.ServiceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このアクターをホストしているアクター サービスの URI を取得します。
            </summary>
        <value><see cref="T:System.Uri" />このアクターをホストしているアクター サービス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterReminderAsync">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task UnregisterReminderAsync (Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task UnregisterReminderAsync(class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.UnregisterReminderAsync(Microsoft.ServiceFabric.Actors.Runtime.IActorReminder)" />
      <MemberSignature Language="VB.NET" Value="Protected Function UnregisterReminderAsync (reminder As IActorReminder) As Task" />
      <MemberSignature Language="F#" Value="member this.UnregisterReminderAsync : Microsoft.ServiceFabric.Actors.Runtime.IActorReminder -&gt; System.Threading.Tasks.Task" Usage="actorBase.UnregisterReminderAsync reminder" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.ActorBase/&lt;UnregisterReminderAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reminder" Type="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
      </Parameters>
      <Docs>
        <param name="reminder">登録を解除するアクター通知します。</param>
        <summary>
            使用してに登録されていた通知の登録を解除<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.RegisterReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />です。
            </summary>
        <returns>
            登録解除の非同期操作を表すタスクを返します。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
            指定された通知が登録されていません。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UnregisterTimer">
      <MemberSignature Language="C#" Value="protected void UnregisterTimer (Microsoft.ServiceFabric.Actors.Runtime.IActorTimer timer);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void UnregisterTimer(class Microsoft.ServiceFabric.Actors.Runtime.IActorTimer timer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.UnregisterTimer(Microsoft.ServiceFabric.Actors.Runtime.IActorTimer)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub UnregisterTimer (timer As IActorTimer)" />
      <MemberSignature Language="F#" Value="member this.UnregisterTimer : Microsoft.ServiceFabric.Actors.Runtime.IActorTimer -&gt; unit" Usage="actorBase.UnregisterTimer timer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timer" Type="Microsoft.ServiceFabric.Actors.Runtime.IActorTimer" />
      </Parameters>
      <Docs>
        <param name="timer">登録解除する必要があるタイマーを表す IActorTimer です。</param>
        <summary>
            以前にこのアクターの設定、タイマーの登録を解除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>