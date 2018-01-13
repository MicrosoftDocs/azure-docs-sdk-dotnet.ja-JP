<Type Name="EventData" FullName="Microsoft.ServiceBus.Messaging.EventData">
  <TypeSignature Language="C#" Value="public sealed class EventData : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventData extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventData" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventData&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type EventData = class&#xA;    interface IDisposable&#xA;    interface IReadOnlyIndicator" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>Event Hubs ストリームから送受信されたイベントを表します。 イベント、ユーザー定義のプロパティ バッグ、およびパーティション内のオフセットやストリーム シーケンスでは、その番号など、イベントを説明するさまざまなメタデータの本文が含まれています。 パーティションには、一連のイベント データが格納されます。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (byte[] byteArray);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] byteArray) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (byteArray As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventData : byte[] -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="new Microsoft.ServiceBus.Messaging.EventData byteArray" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="byteArray" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="byteArray">本文ストリームを形成するために使用、イベントのデータ バイトの配列。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />を本文として指定したバイト配列を使用するクラス。</summary>
        <remarks>EventData を送信するときに、入力バイト配列を変更不可として扱う必要があります。 
            
            データだけでなく、複製操作を送信するときに Service Bus はバイト配列参照によってではなくをしてアクセス バイト配列のディープ コピーです。 EventData インスタンスを破棄しても、配列との関連付けが逆参照がのみです。 ユーザーは、バイト配列自体のライフ サイクルを担当します。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (System.Collections.Generic.IList&lt;ArraySegment&lt;byte&gt;&gt; arraySegments);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; arraySegments) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.Collections.Generic.IList{System.ArraySegment{System.Byte}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (arraySegments As IList(Of ArraySegment(Of Byte)))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventData : System.Collections.Generic.IList&lt;ArraySegment&lt;byte&gt;&gt; -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="new Microsoft.ServiceBus.Messaging.EventData arraySegments" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="arraySegments" Type="System.Collections.Generic.IList&lt;System.ArraySegment&lt;System.Byte&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="arraySegments">本文として送信するには、配列セグメントの IList、<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />です。
            </param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />を本文として指定したバイト配列セグメントの一覧を使用するクラス。</summary>
        <remarks>ユーザーが IList を使用して通常&lt;ArraySegment&lt;バイト&gt;&gt;を使用する場合がバッファー プール メモリの効率的な使用を必要とするシナリオを自分が所有します。
            
            データだけでなく、複製操作を送信するときに Service Bus にアクセスする配列セグメント参照によってではなくをバイトのディープ コピーです。 
            
            EventData インスタンスを破棄しても、リストとの関連付けが解除参照はのみです。 ユーザーは、自分自身配列セグメントのライフ サイクルを担当します。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventData : System.IO.Stream -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="new Microsoft.ServiceBus.Messaging.EventData stream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream">本文ストリームとして使用されるストリーム。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />本文ストリームとして引数のストリームを使用するクラス。</summary>
        <remarks>ユーザーは、このコンス トラクターを使用する場合に、ストリームの破棄を所有すると想定されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (object content, System.Runtime.Serialization.XmlObjectSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object content, class System.Runtime.Serialization.XmlObjectSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.Object,System.Runtime.Serialization.XmlObjectSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (content As Object, serializer As XmlObjectSerializer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventData : obj * System.Runtime.Serialization.XmlObjectSerializer -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="new Microsoft.ServiceBus.Messaging.EventData (content, serializer)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="content" Type="System.Object" />
        <Parameter Name="serializer" Type="System.Runtime.Serialization.XmlObjectSerializer" />
      </Parameters>
      <Docs>
        <param name="content">.Net オブジェクト</param>
        <param name="serializer">シリアル化に使用されるシリアライザー<paramref name="content" /></param>
        <summary>
            入力のコンテンツと本文ストリームを作成するシリアライザーを受け取るコンス トラクターです。
            </summary>
        <remarks>コンテンツがある場合、ストリームと seriazlier が null で使用する時と見なされることが<see cref="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.IO.Stream)" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventData Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventData Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As EventData" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="eventData.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventData</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>このイベント データのディープ コピーを作成します。</summary>
        <returns>このイベント データのコピー。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="eventData.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>アンマネージ リソースの解放またはリセットに関連付けられているアプリケーション定義のタスクを実行します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.EventData.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または送信時刻の日時を UTC に設定します。</summary>
        <value>エンキュー刻 (utc)。 この値は、エンキュー イベント データの実際の時間を表します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBodyStream">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetBodyStream ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IO.Stream GetBodyStream() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.GetBodyStream" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBodyStream () As Stream" />
      <MemberSignature Language="F#" Value="member this.GetBodyStream : unit -&gt; System.IO.Stream" Usage="eventData.GetBodyStream " />
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
        <summary>取得またはイベント データの本体を基になるストリームを設定します。</summary>
        <returns>イベント データの本体を基になるストリーム。</returns>
        <remarks>このメソッドは、1 回のみ呼び出すことができ、メソッドはスロー後<see cref="T:System.InvalidOperationException" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBytes">
      <MemberSignature Language="C#" Value="public byte[] GetBytes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] GetBytes() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.GetBytes" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBytes () As Byte()" />
      <MemberSignature Language="F#" Value="member this.GetBytes : unit -&gt; byte[]" Usage="eventData.GetBytes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>イベント データのバイト数を取得します。</summary>
        <returns>イベントのデータ バイトです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offset">
      <MemberSignature Language="C#" Value="public string Offset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.Offset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Offset As String" />
      <MemberSignature Language="F#" Value="member this.Offset : string" Usage="Microsoft.ServiceBus.Messaging.EventData.Offset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>イベント ハブ パーティション ストリームに対して相対的には、データのオフセットを取得します。 オフセットは、マーカーまたは Event Hubs ストリーム内のイベントの識別子です。 識別子は、Event Hubs ストリームのパーティション内で一意です。</summary>
        <value>イベント データの読み取りのオフセット。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.EventData.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはイベント データを送信するパーティションを決定するために使用するキーを設定します。</summary>
        <value>イベント データを送信するパーティションのパーティション キーです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.EventData.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>ユーザーのプロパティの中に明示的に追加されたユーザーが操作を送信するイベント データを取得します。</summary>
        <value>イベント データのユーザーのプロパティです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.EventData.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Event Hub のパーティションのストリーム内のイベントの論理シーケンス番号を取得します。</summary>
        <value>イベントの論理シーケンス番号。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializedSizeInBytes">
      <MemberSignature Language="C#" Value="public long SerializedSizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SerializedSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializedSizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SerializedSizeInBytes : int64" Usage="Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; SystemProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; SystemProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.SystemProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SystemProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.SystemProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.EventData.SystemProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはイベント データを含む、システムのプロパティを設定します。</summary>
        <value>イベント データを含むシステム プロパティ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>