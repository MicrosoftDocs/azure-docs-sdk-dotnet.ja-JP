<Type Name="MessageSession" FullName="Microsoft.ServiceBus.Messaging.MessageSession">
  <TypeSignature Language="C#" Value="public abstract class MessageSession : Microsoft.ServiceBus.Messaging.MessageReceiver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MessageSession extends Microsoft.ServiceBus.Messaging.MessageReceiver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessageSession" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MessageSession&#xA;Inherits MessageReceiver" />
  <TypeSignature Language="F#" Value="type MessageSession = class&#xA;    inherit MessageReceiver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessageReceiver</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>1 つのトランザクションで処理するための関連メッセージのグループをできるメッセージ セッションを表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetState">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetState ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IO.Stream GetState() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.GetState" />
      <MemberSignature Language="VB.NET" Value="Public Function GetState () As Stream" />
      <MemberSignature Language="F#" Value="member this.GetState : unit -&gt; System.IO.Stream" Usage="messageSession.GetState " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>メッセージ セッションの状態を取得します。</summary>
        <returns>元の状態情報が永続化されるストリーム。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.IO.Stream&gt; GetStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; GetStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.GetStateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetStateAsync () As Task(Of Stream)" />
      <MemberSignature Language="F#" Value="member this.GetStateAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="messageSession.GetStateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>非同期的にメッセージ セッションの状態を取得します。</summary>
        <returns>元の状態情報が永続化されるストリーム。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsExclusiveMode">
      <MemberSignature Language="C#" Value="public bool IsExclusiveMode { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsExclusiveMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.IsExclusiveMode" />
      <MemberSignature Language="VB.NET" Value="Public Property IsExclusiveMode As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsExclusiveMode : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.IsExclusiveMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastPeekedSequenceNumber">
      <MemberSignature Language="C#" Value="public override long LastPeekedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastPeekedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.LastPeekedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property LastPeekedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastPeekedSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.MessageSession.LastPeekedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはセッションで最後のピークのシーケンス番号を設定します。</summary>
        <value>セッションの最後のピークのシーケンス番号。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または日付と時刻をメッセージのセッションがロック解除を設定します。</summary>
        <value>日付とロックするメッセージ セッションの時間。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; LockToken { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public Property LockToken As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.LockToken : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>ロック トークン </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbandon">
      <MemberSignature Language="C#" Value="protected override void OnAbandon (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbandon(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnAbandon(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit" Usage="messageSession.OnAbandon (trackingContext, lockTokens, propertiesToModify, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="lockTokens"> ロック トークン。 </param>
        <param name="propertiesToModify"></param>
        <param name="timeout"> タイムアウト期間。 </param>
        <summary> ピークを排除には、メッセージがロックされています。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="messageSession.OnAbort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>メッセージ セッションを中止します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAbandon">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginAbandon (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginAbandon(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginAbandon(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginAbandon (trackingContext, lockTokens, propertiesToModify, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"></param>
        <param name="lockTokens"> ロック トークン。 </param>
        <param name="propertiesToModify"> 電話放棄呼アクションを追加するプロパティです。</param>
        <param name="fromSync"></param>
        <param name="timeout">    タイムアウト期間。 </param>
        <param name="callback">   コールバック。 </param>
        <param name="state">      状態。 </param>
        <summary>
            Begin 破棄アクションを実行します。 
            </summary>
        <returns> が必要です。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginClose (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout">操作がタイムアウトまでの待機間隔を時間にわたっています。</param>
        <param name="callback">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。 </param>
        <summary>メッセージ セッションの通信オブジェクトを終了する非同期操作を開始します。</summary>
        <returns><see cref="T:System.IAsyncResult" />メッセージ セッションの通信オブジェクトを閉じる非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginComplete">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt; deliveryTags, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; deliveryTags, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.ArraySegment{System.Byte}},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;ArraySegment&lt;byte&gt;&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginComplete (trackingContext, deliveryTags, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="deliveryTags" Type="System.Collections.Generic.IEnumerable&lt;System.ArraySegment&lt;System.Byte&gt;&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</param>
        <param name="deliveryTags"> 配信のタグのコレクション。</param>
        <param name="fromSync"> 同期の開始時刻です。</param>
        <param name="timeout"> 操作がタイムアウトまでの待機間隔を時間にわたっています。</param>
        <param name="callback"> 操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state"> 非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</param>
        <summary>OnComplete または BeginComplete 操作の呼び出し時に実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />メッセージ セッションの通信オブジェクトを閉じる非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginComplete">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginComplete (trackingContext, lockTokens, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</param>
        <param name="lockTokens"> ロックのトークンのコレクションはロックされているメッセージ インスタンスにバインドされます。</param>
        <param name="fromSync"> 同期の開始時刻です。</param>
        <param name="timeout"> 操作がタイムアウトまでの待機間隔を時間にわたっています。</param>
        <param name="callback"> 操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state"> 非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</param>
        <summary>OnComplete または BeginComplete 操作の呼び出し時に実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />メッセージ セッションの通信オブジェクトを閉じる非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginDeadLetter">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginDeadLetter (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginDeadLetter(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginDeadLetter(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginDeadLetter (trackingContext, lockTokens, propertiesToModify, deadLetterReason, deadLetterErrorDescription, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="lockTokens"> ロック トークン。 </param>
        <param name="propertiesToModify"> メッセージを変更するプロパティです。 </param>
        <param name="deadLetterReason">  メッセージの配信不能の理由です。 </param>
        <param name="deadLetterErrorDescription">  メッセージの配信不能の説明情報。 </param>
        <param name="fromSync"> この場合は true、同期メソッドから呼び出されました。</param>
        <param name="timeout">    タイムアウト期間。 </param>
        <param name="callback">   コールバック。 </param>
        <param name="state">      状態。 </param>
        <summary> 配信不能メッセージ キューの操作を開始移動を実行します。 </summary>
        <returns> が必要です。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginDefer">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginDefer (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginDefer(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginDefer(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginDefer (trackingContext, lockTokens, propertiesToModify, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="lockTokens"> ロック トークン。 </param>
        <param name="propertiesToModify"> メッセージを変更するプロパティです。 </param>
        <param name="fromSync"></param>
        <param name="timeout">    タイムアウト期間。 </param>
        <param name="callback">   コールバック。 </param>
        <param name="state">      状態。 </param>
        <summary> 実行開始アクションを延期します。 </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetState">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetState (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetState(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginGetState(Microsoft.ServiceBus.Tracing.TrackingContext,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetState : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginGetState (trackingContext, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">  使用する TrackingContext です。 </param>
        <param name="timeout">  タイムアウト期間。 </param>
        <param name="callback"> コールバック。 </param>
        <param name="state">    状態。 </param>
        <summary> Begin get 状態アクションを実行します。 </summary>
        <returns> が必要です。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginOpen">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginOpen (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginOpen(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginOpen(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginOpen (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginOpen : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginOpen (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout">操作がタイムアウトまでの待機間隔を時間にわたっています。</param>
        <param name="callback">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。 </param>
        <summary>メッセージの受信者の OnOpen 操作の呼び出し時に実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />メッセージ セッションの通信オブジェクトを開く非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginPeek">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginPeek (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, long fromSequenceNumber, int messageCount, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginPeek(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int64 fromSequenceNumber, int32 messageCount, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginPeek(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int64,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginPeek : Microsoft.ServiceBus.Tracing.TrackingContext * int64 * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginPeek (trackingContext, fromSequenceNumber, messageCount, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</param>
        <param name="fromSequenceNumber"> セッションから表示するシーケンス番号。</param>
        <param name="messageCount"> 操作でメッセージの数。</param>
        <param name="timeout"> 操作がタイムアウトまでの待機間隔を時間にわたっています。</param>
        <param name="callback"> 操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state"> 非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</param>
        <summary>OnPeek または BeginPeek の操作の呼び出し時に実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />メッセージ セッションの通信をピークする非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRenewLock">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginRenewLock (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginRenewLock(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginRenewLock(Microsoft.ServiceBus.Tracing.TrackingContext,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginRenewLock : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginRenewLock (trackingContext, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</param>
        <param name="timeout"> 操作がタイムアウトまでの待機間隔を時間にわたっています。</param>
        <param name="callback"> 操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state"> 非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</param>
        <summary>RenewLock または BeginRenewLock 操作の呼び出し時に実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />操作の状態を取得する非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginRenewMessageLocks (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginRenewMessageLocks(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginRenewMessageLocks(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginRenewMessageLocks : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginRenewMessageLocks (trackingContext, lockTokens, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</param>
        <param name="lockTokens"> ロックのトークンのコレクションはロックされているメッセージ インスタンスにバインドされます。</param>
        <param name="fromSync"> 同期の開始時刻です。</param>
        <param name="timeout"> 時間間隔、操作は、タイムアウトになるまで待機します。</param>
        <param name="callback"> 操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state"> 非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</param>
        <summary>メッセージのロックの OnBegin 操作の呼び出し時に実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />ロック メッセージの処理を更新する非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginSetState">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginSetState (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.IO.Stream sessionState, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginSetState(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.IO.Stream sessionState, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginSetState(Microsoft.ServiceBus.Tracing.TrackingContext,System.IO.Stream,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginSetState : Microsoft.ServiceBus.Tracing.TrackingContext * System.IO.Stream * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginSetState (trackingContext, sessionState, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="sessionState" Type="System.IO.Stream" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">  使用する TrackingContext です。 </param>
        <param name="sessionState">   状態。 </param>
        <param name="timeout">  タイムアウト期間。 </param>
        <param name="callback"> コールバック。 </param>
        <param name="state">    状態。 </param>
        <summary> 開始状態の設定のアクションを実行します。 </summary>
        <returns> が必要です。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;long&gt; receipts, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;int64&gt; receipts, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Int64},System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginTryReceive (trackingContext, receipts, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="receipts" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="receipts"> 配信確認メッセージ。 </param>
        <param name="timeout">  タイムアウト期間。 </param>
        <param name="callback"> コールバック。 </param>
        <param name="state">    状態。 </param>
        <summary> Begin try を実行するアクションを受信します。 </summary>
        <returns> が必要です。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginTryReceive (trackingContext, messageCount, serverWaitTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="messageCount"> メッセージの数。 </param>
        <param name="serverWaitTime"> タイムアウト期間。 </param>
        <param name="callback">     コールバック。 </param>
        <param name="state">        状態。 </param>
        <summary> Begin try を実行するアクションを受信します。 </summary>
        <returns> が必要です。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive2">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginTryReceive2 (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginTryReceive2(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginTryReceive2(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginTryReceive2 : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginTryReceive2 (trackingContext, messageCount, serverWaitTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="messageCount"> メッセージの数。 </param>
        <param name="serverWaitTime"> タイムアウト期間。 </param>
        <param name="callback">     コールバック。 </param>
        <param name="state">        状態。 </param>
        <summary> Begin try を実行するアクションを受信します。 </summary>
        <returns> が必要です。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnComplete">
      <MemberSignature Language="C#" Value="protected override void OnComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * TimeSpan -&gt; unit" Usage="messageSession.OnComplete (trackingContext, lockTokens, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="lockTokens"> ロック トークン。 </param>
        <param name="timeout"> タイムアウト期間。 </param>
        <summary> ピーク ロックされているメッセージを完了します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeadLetter">
      <MemberSignature Language="C#" Value="protected override void OnDeadLetter (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnDeadLetter(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnDeadLetter(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * TimeSpan -&gt; unit" Usage="messageSession.OnDeadLetter (trackingContext, lockTokens, propertiesToModify, deadLetterReason, deadLetterErrorDescription, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">To be added.</param>
        <param name="lockTokens">To be added.</param>
        <param name="propertiesToModify">To be added.</param>
        <param name="deadLetterReason">To be added.</param>
        <param name="deadLetterErrorDescription">To be added.</param>
        <param name="timeout">To be added.</param>
        <summary> 配信不能キューにメッセージを移動します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDefer">
      <MemberSignature Language="C#" Value="protected override void OnDefer (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnDefer(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnDefer(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit" Usage="messageSession.OnDefer (trackingContext, lockTokens, propertiesToModify, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="lockTokens"> ロック トークン。 </param>
        <param name="propertiesToModify"> メッセージを変更するプロパティです。 </param>
        <param name="timeout">    タイムアウト期間。 </param>
        <summary> メッセージを延期します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAbandon">
      <MemberSignature Language="C#" Value="protected override void OnEndAbandon (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndAbandon(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndAbandon(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndAbandon (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndAbandon : IAsyncResult -&gt; unit" Usage="messageSession.OnEndAbandon result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />メッセージを破棄し、そのロックを解放する非同期操作を参照します。</param>
        <summary>メッセージを破棄し、そのロックを解放する非同期操作を終了します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="messageSession.OnEndClose result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />メッセージ セッションの通信オブジェクトを閉じる非同期操作を参照します。</param>
        <summary>メッセージ セッションの通信オブジェクトを終了する非同期操作を終了します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndComplete">
      <MemberSignature Language="C#" Value="protected override void OnEndComplete (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndComplete(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndComplete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndComplete (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndComplete : IAsyncResult -&gt; unit" Usage="messageSession.OnEndComplete result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />メッセージの受信を完了する非同期操作を参照します。</param>
        <summary>メッセージの受信者の完了操作の終了を実行します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndDeadLetter">
      <MemberSignature Language="C#" Value="protected override void OnEndDeadLetter (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndDeadLetter(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndDeadLetter(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndDeadLetter (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndDeadLetter : IAsyncResult -&gt; unit" Usage="messageSession.OnEndDeadLetter result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />配信不能キューに配信不能メッセージを移動する非同期操作を参照します。</param>
        <summary>メッセージ受信側の配信不能操作の終了を実行します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndDefer">
      <MemberSignature Language="C#" Value="protected override void OnEndDefer (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndDefer(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndDefer(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndDefer (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndDefer : IAsyncResult -&gt; unit" Usage="messageSession.OnEndDefer result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />メッセージの処理を中断する非同期操作を参照します。</param>
        <summary>最後の実行、メッセージ受信側の操作の保留します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetState">
      <MemberSignature Language="C#" Value="protected abstract System.IO.Stream OnEndGetState (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IO.Stream OnEndGetState(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndGetState(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetState (result As IAsyncResult) As Stream" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetState : IAsyncResult -&gt; System.IO.Stream" Usage="messageSession.OnEndGetState result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />メッセージ セッションの状態を取得する非同期操作を参照します。</param>
        <summary>OnGetState または EndGetState 操作の呼び出し時に実行します。</summary>
        <returns>元の状態情報が永続化されるストリーム。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndOpen">
      <MemberSignature Language="C#" Value="protected override void OnEndOpen (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndOpen(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndOpen(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndOpen (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndOpen : IAsyncResult -&gt; unit" Usage="messageSession.OnEndOpen result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />メッセージ セッションの通信オブジェクトを開く非同期操作を参照します。</param>
        <summary>メッセージ セッションの通信オブジェクトを開く非同期操作を終了します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndPeek">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnEndPeek (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnEndPeek(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndPeek(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndPeek (result As IAsyncResult) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="override this.OnEndPeek : IAsyncResult -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageSession.OnEndPeek result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />メッセージ セッションの通信をピークする非同期操作を参照します。</param>
        <summary>EndPeek 操作の呼び出し時に実行します。</summary>
        <returns>セッションからのメッセージの一覧。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRenewLock">
      <MemberSignature Language="C#" Value="protected abstract DateTime OnEndRenewLock (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance valuetype System.DateTime OnEndRenewLock(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndRenewLock(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndRenewLock (result As IAsyncResult) As DateTime" />
      <MemberSignature Language="F#" Value="abstract member OnEndRenewLock : IAsyncResult -&gt; DateTime" Usage="messageSession.OnEndRenewLock result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />メッセージ セッションの状態を取得する非同期操作を参照します。</param>
        <summary>メッセージの受信者の EndRenewLock 操作を実行します。</summary>
        <returns>日付とロックの更新の終了時刻。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;DateTime&gt; OnEndRenewMessageLocks (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;valuetype System.DateTime&gt; OnEndRenewMessageLocks(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndRenewMessageLocks(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndRenewMessageLocks (result As IAsyncResult) As IEnumerable(Of DateTime)" />
      <MemberSignature Language="F#" Value="override this.OnEndRenewMessageLocks : IAsyncResult -&gt; seq&lt;DateTime&gt;" Usage="messageSession.OnEndRenewMessageLocks result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">操作の結果。</param>
        <summary>メッセージ ロック EndRenew アクションを実行します。</summary>
        <returns><see cref="T:System.Collections.Generic.IEnumerable`1" />ロックされたメッセージの.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndSetState">
      <MemberSignature Language="C#" Value="protected abstract void OnEndSetState (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndSetState(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndSetState(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndSetState (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndSetState : IAsyncResult -&gt; unit" Usage="messageSession.OnEndSetState result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />メッセージ セッションの状態を設定する非同期操作を参照します。</param>
        <summary>メッセージ セッションの状態を設定する非同期操作を終了します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceive">
      <MemberSignature Language="C#" Value="protected override bool OnEndTryReceive (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnEndTryReceive(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndTryReceive(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndTryReceive (result As IAsyncResult, ByRef messages As IEnumerable(Of BrokeredMessage)) As Boolean" />
      <MemberSignature Language="F#" Value="override this.OnEndTryReceive : IAsyncResult *  -&gt; bool" Usage="messageSession.OnEndTryReceive (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />メッセージを受信しようとする非同期操作を参照します。</param>
        <param name="messages">このメソッドが戻るときに、受信したメッセージのコレクションが含まれています。</param>
        <summary>最後に実行される受信メッセージの受信側の操作を再試行してください。</summary>
        <returns>これが成功した場合は true。失敗した場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceive2">
      <MemberSignature Language="C#" Value="protected override bool OnEndTryReceive2 (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnEndTryReceive2(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndTryReceive2(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndTryReceive2 (result As IAsyncResult, ByRef messages As IEnumerable(Of BrokeredMessage)) As Boolean" />
      <MemberSignature Language="F#" Value="override this.OnEndTryReceive2 : IAsyncResult *  -&gt; bool" Usage="messageSession.OnEndTryReceive2 (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />メッセージを受信しようとする非同期操作を参照します。</param>
        <param name="messages">このメソッドが戻るときに、受信したメッセージのコレクションが含まれています。</param>
        <summary>最後に実行される受信メッセージの受信側の操作を再試行してください。</summary>
        <returns>これが成功した場合は true。失敗した場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnGetState">
      <MemberSignature Language="C#" Value="protected virtual System.IO.Stream OnGetState (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IO.Stream OnGetState(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnGetState(Microsoft.ServiceBus.Tracing.TrackingContext,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnGetState : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan -&gt; System.IO.Stream&#xA;override this.OnGetState : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan -&gt; System.IO.Stream" Usage="messageSession.OnGetState (trackingContext, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">  使用する TrackingContext です。 </param>
        <param name="timeout"> タイムアウト期間。 </param>
        <summary> Get 状態アクションを実行します。 </summary>
        <returns> が必要です。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRenewLock">
      <MemberSignature Language="C#" Value="protected virtual DateTime OnRenewLock (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance valuetype System.DateTime OnRenewLock(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnRenewLock(Microsoft.ServiceBus.Tracing.TrackingContext,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnRenewLock : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan -&gt; DateTime&#xA;override this.OnRenewLock : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan -&gt; DateTime" Usage="messageSession.OnRenewLock (trackingContext, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</param>
        <param name="timeout"> 操作がタイムアウトまでの待機間隔を時間にわたっています。</param>
        <summary>メッセージ ロック RenewLock アクションを実行します。</summary>
        <returns>時間間隔、操作は、タイムアウトになるまで待機します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnSetState">
      <MemberSignature Language="C#" Value="protected virtual void OnSetState (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.IO.Stream stream, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnSetState(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.IO.Stream stream, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnSetState(Microsoft.ServiceBus.Tracing.TrackingContext,System.IO.Stream,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnSetState : Microsoft.ServiceBus.Tracing.TrackingContext * System.IO.Stream * TimeSpan -&gt; unit&#xA;override this.OnSetState : Microsoft.ServiceBus.Tracing.TrackingContext * System.IO.Stream * TimeSpan -&gt; unit" Usage="messageSession.OnSetState (trackingContext, stream, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="stream" Type="System.IO.Stream" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">  使用する TrackingContext です。 </param>
        <param name="stream">  ストリーム。 </param>
        <param name="timeout"> タイムアウト期間。 </param>
        <summary> 状態の設定アクションを実行します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTryReceive">
      <MemberSignature Language="C#" Value="protected override bool OnTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;long&gt; receipts, TimeSpan timeout, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;int64&gt; receipts, valuetype System.TimeSpan timeout, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Int64},System.TimeSpan,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="F#" Value="override this.OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan *  -&gt; bool" Usage="messageSession.OnTryReceive (trackingContext, receipts, timeout, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="receipts" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="receipts"> 配信確認メッセージ。 </param>
        <param name="timeout">  タイムアウト期間。 </param>
        <param name="messages"> 出力メッセージ (送信)</param>
        <summary> 再試行を実行するアクションを受信します。 </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTryReceive">
      <MemberSignature Language="C#" Value="protected override bool OnTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="F#" Value="override this.OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan *  -&gt; bool" Usage="messageSession.OnTryReceive (trackingContext, messageCount, serverWaitTime, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="messageCount"> メッセージ数。 </param>
        <param name="serverWaitTime">  サーバーがタイムアウトするまでの時間を待機します。 </param>
        <param name="messages">  返されるメッセージ。 </param>
        <summary> 再試行を実行するアクションを受信します。 </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public override string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.Path" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.MessageSession.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>に対して相対的なキューまたはトピックのパスを取得、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />ベース アドレス。</summary>
        <value>キューまたはトピックのパスを表す文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public override int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージの受信者が同時に要求メッセージの数を設定します。</summary>
        <value>メッセージの受信者が同時に要求メッセージの数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessException">
      <MemberSignature Language="C#" Value="protected Exception ProcessException (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Exception ProcessException(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.ProcessException(System.Exception)" />
      <MemberSignature Language="F#" Value="member this.ProcessException : Exception -&gt; Exception" Usage="messageSession.ProcessException exception" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="exception"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLock">
      <MemberSignature Language="C#" Value="public void RenewLock ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RenewLock() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.RenewLock" />
      <MemberSignature Language="VB.NET" Value="Public Sub RenewLock ()" />
      <MemberSignature Language="F#" Value="member this.RenewLock : unit -&gt; unit" Usage="messageSession.RenewLock " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>ホストがそのメッセージのロックを更新するまでの時間を指定します。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">場合<see cref="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" />が true の場合、すぐに操作を再試行することができます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">操作をすぐに再試行することができます。</exception>
        <exception cref="T:System.TimeoutException">操作をすぐに再試行することができます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException">代わりにスローされる<see cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException" />場合は、メッセージは、<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewLockAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RenewLockAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.RenewLockAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewLockAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RenewLockAsync : unit -&gt; System.Threading.Tasks.Task" Usage="messageSession.RenewLockAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>ホストがそのメッセージのロックを更新するまでの時間を指定します。</summary>
        <returns>ロックされているホスト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public virtual string SessionId { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージのセッション識別子を設定します。</summary>
        <value>メッセージのセッション識別子です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetState">
      <MemberSignature Language="C#" Value="public void SetState (System.IO.Stream sessionState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetState(class System.IO.Stream sessionState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.SetState(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetState (sessionState As Stream)" />
      <MemberSignature Language="F#" Value="member this.SetState : System.IO.Stream -&gt; unit" Usage="messageSession.SetState sessionState" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionState" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="sessionState">状態情報が永続化されるストリーム。</param>
        <summary>メッセージ セッションの状態を設定します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetStateAsync (System.IO.Stream sessionState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SetStateAsync(class System.IO.Stream sessionState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.SetStateAsync(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetStateAsync (sessionState As Stream) As Task" />
      <MemberSignature Language="F#" Value="member this.SetStateAsync : System.IO.Stream -&gt; System.Threading.Tasks.Task" Usage="messageSession.SetStateAsync sessionState" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionState" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="sessionState">状態情報が永続化されるストリーム。</param>
        <summary>メッセージ セッションの状態を非同期に設定します。</summary>
        <returns>メッセージ セッションの状態。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportsGetRuntimeEntityDescription">
      <MemberSignature Language="C#" Value="protected internal override bool SupportsGetRuntimeEntityDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overrides ReadOnly Property SupportsGetRuntimeEntityDescription As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportsGetRuntimeEntityDescription : bool" Usage="Microsoft.ServiceBus.Messaging.MessageSession.SupportsGetRuntimeEntityDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>