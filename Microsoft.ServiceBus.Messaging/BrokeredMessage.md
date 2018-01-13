<Type Name="BrokeredMessage" FullName="Microsoft.ServiceBus.Messaging.BrokeredMessage">
  <TypeSignature Language="C#" Value="public sealed class BrokeredMessage : IDisposable, System.Xml.Serialization.IXmlSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BrokeredMessage extends System.Object implements class System.IDisposable, class System.Xml.Serialization.IXmlSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BrokeredMessage&#xA;Implements IDisposable, IXmlSerializable" />
  <TypeSignature Language="F#" Value="type BrokeredMessage = class&#xA;    interface IXmlSerializable&#xA;    interface IDisposable" />
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
    <Interface>
      <InterfaceName>System.Xml.Serialization.IXmlSerializable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Xml.Serialization.XmlRoot("BrokeredMessage", Namespace="http://schemas.microsoft.com/netservices/2011/06/servicebus")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>Service Bus クライアント間の通信の単位を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage (System.IO.Stream messageBodyStream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream messageBodyStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (messageBodyStream As Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.BrokeredMessage : System.IO.Stream -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="new Microsoft.ServiceBus.Messaging.BrokeredMessage messageBodyStream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="messageBodyStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="messageBodyStream">メッセージのボディ ストリーム。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage (object serializableObject);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object serializableObject) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serializableObject As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.BrokeredMessage : obj -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="new Microsoft.ServiceBus.Messaging.BrokeredMessage serializableObject" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serializableObject" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="serializableObject">メッセージ本文にシリアル化されるオブジェクト。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />バイナリ XmlDictionaryWriter に DataContractSerializer を使用して、指定されたオブジェクトからのクラスです。</summary>
        <remarks>既定の<see cref="T:Microsoft.ServiceBus.Messaging.DataContractBinarySerializer" />オブジェクトをシリアル化するために使用します。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage (System.IO.Stream messageBodyStream, bool ownsStream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream messageBodyStream, bool ownsStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor(System.IO.Stream,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (messageBodyStream As Stream, ownsStream As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.BrokeredMessage : System.IO.Stream * bool -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="new Microsoft.ServiceBus.Messaging.BrokeredMessage (messageBodyStream, ownsStream)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="messageBodyStream" Type="System.IO.Stream" />
        <Parameter Name="ownsStream" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="messageBodyStream">メッセージのボディ ストリーム。</param>
        <param name="ownsStream">メッセージの終了時に、ストリームは閉じられますことを指定する場合は trueメッセージが閉じられたときに、ストリームは削除されないことを示すために false になります。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />クラス、本文として提供されたストリームを使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage (object serializableObject, System.Runtime.Serialization.XmlObjectSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object serializableObject, class System.Runtime.Serialization.XmlObjectSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor(System.Object,System.Runtime.Serialization.XmlObjectSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serializableObject As Object, serializer As XmlObjectSerializer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.BrokeredMessage : obj * System.Runtime.Serialization.XmlObjectSerializer -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="new Microsoft.ServiceBus.Messaging.BrokeredMessage (serializableObject, serializer)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serializableObject" Type="System.Object" />
        <Parameter Name="serializer" Type="System.Runtime.Serialization.XmlObjectSerializer" />
      </Parameters>
      <Docs>
        <param name="serializableObject"> シリアル化可能なオブジェクトです。 </param>
        <param name="serializer">         シリアライザー オブジェクトです。 </param>
        <summary> 指定された XmlObjectSerializer を使用して、指定されたオブジェクトから BrokeredMessage を作成するコンス トラクター </summary>
        <remarks> 例外の指定されたシリアライザーがスローおよび適切なアクションを実行できますの注意する必要があります。 参照してください<see href="http://msdn.microsoft.com/en-us/library/ms574055.aspx" />例外とその原因の可能な一覧についてはします。 </remarks>
        <exception cref="T:System.ArgumentNullException">Null のシリアライザーが null でない serializableObject でメソッドに渡された場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Abandon() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Abandon" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon ()" />
      <MemberSignature Language="F#" Value="member this.Abandon : unit -&gt; unit" Usage="brokeredMessage.Abandon " />
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
        <summary>ピーク ロックのメッセージのロックを破棄します。</summary>
        <remarks> この操作は、ピーク ロックのモードで受信したメッセージのみ実行する必要があります。</remarks>
        <exception cref="T:System.ObjectDisposedException">破棄された状態では、メッセージまたはメッセージを受信した受信側が破棄された状態では場合にスローされます。</exception>
        <exception cref="T:System.InvalidOperationException">メッセージ サーバーから受信されていないメッセージで呼び出されるかが、ピーク ロックのモードで受信されていないメッセージで呼び出された場合にスローされます。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたときにスローされます。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />です。 値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">キューまたはメッセージを受信するサブスクリプションは既に存在しないメッセージ サーバーの場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException">Service bus サービスがビジー状態と要求できません。 プロセスは、します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">メッセージング エンティティのメッセージを受信しましたが削除されました。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">ロックに関連付けられているときに、このメッセージが失われたまたはロック トークンが見つかりませんでした。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException">ときにこのメッセージが、セッションとセッションに関連付けられているロックから受け取りました。 が失われました。</exception>
        <exception cref="T:System.UnauthorizedAccessException">ときに、TokenProvider によって提供されるセキュリティ トークンでは、この操作を実行する信頼性情報は含まれません。</exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException">ときにエンティティへの同時接続の数が最大許容値を超えています。</exception>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Abandon(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Abandon(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="member this.Abandon : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="brokeredMessage.Abandon propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify">変更するプロパティのキー/値ペアのコレクション。</param>
        <summary>ピーク ロックのメッセージのロックを破棄します。</summary>
        <remarks> この操作は、ピーク ロックのモードで受信したメッセージのみ実行する必要があります。</remarks>
        <exception cref="T:System.ObjectDisposedException">場合にスローされる<list type="bullet"><item>メッセージは破棄された状態にします</item>。<item>受信側がメッセージを受信しましたが、破棄された状態</item></list></exception>
        <exception cref="T:System.InvalidOperationException">場合にスローされる<list type="bullet"><item>がメッセージ サーバーから受信されていないメッセージで呼び出されます</item>。<item>がピーク ロックのモードで受信されていないメッセージで呼び出されます</item></list></exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたときにスローされます。タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />です。 値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。
                                            <seealso cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></exception>
        <exception cref="T:System.ServiceModel.CommunicationException">キューまたはサブスクリプションから受信したメッセージは既に存在しないメッセージ サーバーの場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AbandonAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.AbandonAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.AbandonAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.AbandonAsync " />
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
        <summary>ピーク ロックのメッセージのロックを非同期的に中止します。</summary>
        <returns>操作の非同期の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AbandonAsync(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.AbandonAsync(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="member this.AbandonAsync : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.AbandonAsync propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify">変更するプロパティのキー/値ペアのコレクション。</param>
        <summary>ピーク ロックのメッセージのロックを非同期的に中止します。</summary>
        <returns>操作の非同期の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="brokeredMessage.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>新しいメッセージとしてメッセージの複製を送信することができるように、メッセージを複製します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />クローンとして作成されたメッセージを格納しています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Complete">
      <MemberSignature Language="C#" Value="public void Complete ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Complete() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Complete" />
      <MemberSignature Language="VB.NET" Value="Public Sub Complete ()" />
      <MemberSignature Language="F#" Value="member this.Complete : unit -&gt; unit" Usage="brokeredMessage.Complete " />
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
        <summary>メッセージの受信操作が完了したことを示し、メッセージは、処理済みとマークする必要があります、削除します。</summary>
        <remarks> このメソッドは、メッセージの確実な配信の受信機と Service Bus との間のハンドシェイクとして使用されます。 このメソッドを呼び出す前に、受信側に失敗した場合、メッセージがキューに保持されます。</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態か、受信側がメッセージを受信したが破棄された状態でスローされます。</exception>
        <exception cref="T:System.InvalidOperationException">メッセージ サーバーから受信されていないメッセージで呼び出されるかが、ピーク ロックのモードで受信されていないメッセージで呼び出された場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">キューまたはメッセージを受信するサブスクリプションは既に存在しないメッセージ サーバーの場合にスローされます。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたときにスローされます。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />です。 値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">メッセージのロックの有効期限が切れた場合にスローされます。 LockDuration、エンティティ全体の設定し、で初期化できます<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />と<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />キューとサブスクリプションのそれぞれします。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException">セッションのロックの有効期限が切れた場合にスローされます。 セッション ロック期間は、LockDuration メッセージと同じはあり、エンティティ全体の設定です。 初期化できます<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />と<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />キューとサブスクリプションのそれぞれします。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException">Service bus サービスがビジー状態と要求できません。 プロセスは、します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">メッセージング エンティティのメッセージを受信しましたが削除されました。</exception>
        <exception cref="T:System.UnauthorizedAccessException">ときに、TokenProvider によって提供されるセキュリティ トークンでは、この操作を実行する信頼性情報は含まれません。</exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException">ときにエンティティへの同時接続の数が最大許容値を超えています。</exception>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CompleteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.CompleteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CompleteAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.CompleteAsync " />
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
        <summary>非同期的にメッセージの受信操作が完了したことを示し、メッセージは、処理済みとマークする必要があります、削除します。</summary>
        <returns>操作の非同期の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはコンテンツの種類を設定します。</summary>
        <value>メッセージ本文のコンテンツの種類。 これは、送信者と受信者のアプリケーション固有のロジックで使用されるコンテンツの種類の識別子です。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定の相関関係の識別子。</summary>
        <value>相関関係の識別子。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeadLetter() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetter" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter ()" />
      <MemberSignature Language="F#" Value="member this.DeadLetter : unit -&gt; unit" Usage="brokeredMessage.DeadLetter " />
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
        <summary>配信不能キューにメッセージを移動します。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態か、受信側がメッセージを受信したが破棄された状態でスローされます。</exception>
        <exception cref="T:System.InvalidOperationException">メッセージ サーバーから受信されていないメッセージで呼び出されるかが、ピーク ロックのモードで受信されていないメッセージで呼び出された場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeadLetter(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetter(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="member this.DeadLetter : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="brokeredMessage.DeadLetter propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify">変更するプロパティのキー/値ペアのコレクション。</param>
        <summary>配信不能キューにメッセージを移動します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeadLetter(string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetter(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (deadLetterReason As String, deadLetterErrorDescription As String)" />
      <MemberSignature Language="F#" Value="member this.DeadLetter : string * string -&gt; unit" Usage="brokeredMessage.DeadLetter (deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deadLetterReason">メッセージの配信不能の理由です。</param>
        <param name="deadLetterErrorDescription">メッセージの配信不能の説明情報。</param>
        <summary>配信不能キューにメッセージを移動します。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態か、受信側がメッセージを受信したが破棄された状態でスローされます。</exception>
        <exception cref="T:System.InvalidOperationException">メッセージ サーバーから受信されていないメッセージで呼び出されるかが、ピーク ロックのモードで受信されていないメッセージで呼び出された場合にスローされます。</exception>
        <exception cref="T:System.ServiceModel.CommunicationException">キューまたはメッセージを受信するサブスクリプションは既に存在しないメッセージ サーバーの場合にスローされます。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたときにスローされます。タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />です。 値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">メッセージのロックの有効期限が切れた場合にスローされます。 LockDuration、エンティティ全体の設定し、で初期化できます<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />と<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />キューとサブスクリプションのそれぞれします。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException">セッションのロックの有効期限が切れた場合にスローされます。 セッション ロック期間は、LockDuration メッセージと同じはあり、エンティティ全体の設定です。 初期化できます<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />と<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />キューとサブスクリプションのそれぞれします。</exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeadLetterAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.DeadLetterAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeadLetterAsync " />
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
        <summary>非同期的にメッセージを配信不能キューに移動します。</summary>
        <returns>操作の非同期の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeadLetterAsync(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterAsync(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="member this.DeadLetterAsync : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeadLetterAsync propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify">変更するプロパティのキー/値ペアのコレクション。</param>
        <summary>非同期的にメッセージを配信不能キューに移動します。</summary>
        <returns>操作の非同期の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeadLetterAsync(string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (deadLetterReason As String, deadLetterErrorDescription As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeadLetterAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeadLetterAsync (deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deadLetterReason">メッセージの配信不能の理由です。</param>
        <param name="deadLetterErrorDescription">メッセージの配信不能の説明情報。</param>
        <summary>非同期的にメッセージを配信不能キューに移動します。</summary>
        <returns>操作の非同期の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterSource">
      <MemberSignature Language="C#" Value="public string DeadLetterSource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeadLetterSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterSource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeadLetterSource As String" />
      <MemberSignature Language="F#" Value="member this.DeadLetterSource : string" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Defer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Defer" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer ()" />
      <MemberSignature Language="F#" Value="member this.Defer : unit -&gt; unit" Usage="brokeredMessage.Defer " />
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
        <summary>受信側がこのメッセージの処理を遅延することを示します。</summary>
        <remarks>メッセージを保留する前にユーザーは、後で検索できるメッセージの受信確認を確保する必要があります。 </remarks>
        <exception cref="T:System.ObjectDisposedException">破棄された状態では、メッセージまたはメッセージを受信した受信側が破棄された状態では場合にスローされます。</exception>
        <exception cref="T:System.InvalidOperationException">メッセージ サーバーから受信されていないメッセージで呼び出されるかが、ピーク ロックのモードで受信されていないメッセージで呼び出された場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">キューまたはメッセージを受信するサブスクリプションは既に存在しないメッセージ サーバーの場合にスローされます。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたときにスローされます。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />です。 値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">メッセージのロックの有効期限が切れた場合にスローされます。 LockDuration、エンティティ全体の設定し、で初期化できます<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />と<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />キューとサブスクリプションのそれぞれします。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException">セッションのロックの有効期限が切れた場合にスローされます。 セッション ロック期間は、LockDuration メッセージと同じはあり、エンティティ全体の設定です。 初期化できます<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />と<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />キューとサブスクリプションのそれぞれします。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException">Service bus サービスがビジー状態と要求できません。 プロセスは、します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">メッセージング エンティティのメッセージを受信しましたが削除されました。</exception>
        <exception cref="T:System.UnauthorizedAccessException">ときに、TokenProvider によって提供されるセキュリティ トークンでは、この操作を実行する信頼性情報は含まれません。</exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException">ときにエンティティへの同時接続の数が最大許容値を超えています。</exception>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Defer(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Defer(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="member this.Defer : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="brokeredMessage.Defer propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify">変更するプロパティのキー/値ペアのコレクション。</param>
        <summary>受信側がこのメッセージの処理を遅延することを示します。</summary>
        <remarks>メッセージを保留する前にユーザーは、後で検索できるメッセージの受信確認を確保する必要があります。 </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeferAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeferAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.DeferAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeferAsync " />
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
        <summary>非同期的に受信側がこのメッセージの処理を遅延することを示します。</summary>
        <returns>操作の非同期の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeferAsync(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeferAsync(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="member this.DeferAsync : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeferAsync propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify">変更するプロパティのキー/値ペアのコレクション。</param>
        <summary>非同期的に受信側がこのメッセージの処理を遅延することを示します。</summary>
        <returns>操作の非同期の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeliveryCount">
      <MemberSignature Language="C#" Value="public int DeliveryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DeliveryCount : int" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.DeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>配信の数を取得します。</summary>
        <value>配信したファイルの数。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
        <exception cref="T:System.InvalidOperationException">ServiceBus によってメッセージが配信されていない場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="brokeredMessage.Dispose " />
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
    <Member MemberName="EnqueuedSequenceNumber">
      <MemberSignature Language="C#" Value="public long EnqueuedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 EnqueuedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.EnqueuedSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージのエンキューされたシーケンス番号を設定します。</summary>
        <value>メッセージのエンキューされたシーケンス番号。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedTimeUtc" />
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
        <value>エンキュー刻 (utc)。 この値は、メッセージをエンキューの実際の時間を表します。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="ExpiresAtUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiresAtUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresAtUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ExpiresAtUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresAtUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresAtUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ExpiresAtUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージが期限切れに設定されている UTC の日付と時刻を取得します。</summary>
        <value>メッセージの有効期限刻 (utc)。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
        <exception cref="T:System.InvalidOperationException">場合は ServerBus によってメッセージが配信されていません。</exception>
      </Docs>
    </Member>
    <Member MemberName="ForcePersistence">
      <MemberSignature Language="C#" Value="public bool ForcePersistence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ForcePersistence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ForcePersistence" />
      <MemberSignature Language="VB.NET" Value="Public Property ForcePersistence As Boolean" />
      <MemberSignature Language="F#" Value="member this.ForcePersistence : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ForcePersistence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージがしばらくの間のメモリ内に保持されているのではなく、すぐに、データベースに永続化されるかどうかを示す値を設定します。 Express 以外のキューまたはトピックにメッセージが送信された場合、このプロパティは無視されます。</summary>
        <value>メッセージが短い時間です。 メモリ内に保持されているのではなく、すぐにデータベースに永続化する場合は trueそれ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBody&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T GetBody&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!T GetBody&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.GetBody``1" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBody(Of T) () As T" />
      <MemberSignature Language="F#" Value="member this.GetBody : unit -&gt; 'T" Usage="brokeredMessage.GetBody " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">メッセージの本文を逆シリアル化する型。</typeparam>
        <summary>使用して、指定した型のオブジェクトに、仲介型メッセージの本文を逆シリアル化、 <see cref="T:System.Runtime.Serialization.DataContractSerializer" /> 、バイナリと<see cref="T:System.Xml.XmlDictionaryReader" />です。</summary>
        <returns>逆シリアル化されたオブジェクト、またはグラフ。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄されている場合状態や、メッセージ ボディ ストリームは既に破棄されています。</exception>
        <exception cref="T:System.InvalidOperationException">ボディ ストリームには、データがないか、メッセージ本文が含まれています。 メッセージには、null のボディ ストリームが含まれている場合は既に使用済みです。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetBody&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T GetBody&lt;T&gt; (System.Runtime.Serialization.XmlObjectSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!T GetBody&lt;T&gt;(class System.Runtime.Serialization.XmlObjectSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.GetBody``1(System.Runtime.Serialization.XmlObjectSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBody(Of T) (serializer As XmlObjectSerializer) As T" />
      <MemberSignature Language="F#" Value="member this.GetBody : System.Runtime.Serialization.XmlObjectSerializer -&gt; 'T" Usage="brokeredMessage.GetBody serializer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="serializer" Type="System.Runtime.Serialization.XmlObjectSerializer" />
      </Parameters>
      <Docs>
        <typeparam name="T"> ジェネリック型パラメーターです。 </typeparam>
        <param name="serializer"> シリアライザー オブジェクトです。 </param>
        <summary>バイナリ XmlObjectSerializer に DataContractSerializer を使用して、指定した型のオブジェクトには、BrokeredMessage の本文を逆シリアル化します。 </summary>
        <returns> 逆シリアル化されたオブジェクト/グラフ</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"> メッセージが破棄された状態である場合にスローされます。 </exception>
        <exception cref="T:System.ArgumentNullException"> Null シリアライザー オブジェクトで呼び出されたときにスローされます。 </exception>
        <exception cref="T:System.InvalidOperationException"> メッセージには、Null 本文ストリームが含まれている場合にスローされます、データが含まれていない、または 1 回 (GetBody() 呼び出し) を介して、ストリームが読み取られた場合。 </exception>
      </Docs>
    </Member>
    <Member MemberName="IsBodyConsumed">
      <MemberSignature Language="C#" Value="public bool IsBodyConsumed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBodyConsumed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.IsBodyConsumed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBodyConsumed As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBodyConsumed : bool" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.IsBodyConsumed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージが使用されているかどうかを指定します。</summary>
        <value>メッセージが使用された場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはアプリケーション固有のラベルを設定します。</summary>
        <value>アプリケーション固有のラベル。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>キュー/サブスクリプションで、メッセージをロックするまで (utc) 日付と時刻を取得します。</summary>
        <value>日時キュー/サブスクリプションになるまで、メッセージがロックされます。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
        <exception cref="T:System.InvalidOperationException">ServiceBus から、メッセージが受信されなかった場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public Guid LockToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockToken As Guid" />
      <MemberSignature Language="F#" Value="member this.LockToken : Guid" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Service Bus によってこのメッセージに割り当てられたロック トークンを取得します。</summary>
        <value>Service Bus によってこのメッセージに割り当てられたロック トークンです。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
        <exception cref="T:System.InvalidOperationException">ServiceBus から、メッセージが受信されなかった場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージの識別子を設定します。 これは、有効になっている場合、Service Bus がメッセージの重複の識別に使用できるユーザー定義の値です。</summary>
        <value>メッセージの識別子。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態の場合にスローされます。</exception>
        <exception cref="T:System.ArgumentException">メッセージ id が null または長さは 128 文字を超える場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定に、キューまたはトピックをセッション対応していないトランザクション メッセージを送信するためのパーティション キー。</summary>
        <value>トランザクション メッセージを送信するためのパーティション キーです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>アプリケーションの特定のメッセージ プロパティを取得します。</summary>
        <value>アプリケーションの特定のメッセージ プロパティ。</value>
        <remarks>プロパティ バッグ内の各プロパティ オブジェクトのサイズは 32 キロバイトを超えることはできません。
            プロパティ バッグの集合的なサイズには、64 キロバイトを超えることはできません。</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="RenewLock">
      <MemberSignature Language="C#" Value="public void RenewLock ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RenewLock() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.RenewLock" />
      <MemberSignature Language="VB.NET" Value="Public Sub RenewLock ()" />
      <MemberSignature Language="F#" Value="member this.RenewLock : unit -&gt; unit" Usage="brokeredMessage.RenewLock " />
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
        <summary>メッセージのロックを更新します。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">場合<see cref="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" />が true の場合、すぐに操作を再試行することができます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">操作をすぐに再試行することができます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">呼び出した場合にスロー<see cref="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.RenewLock" />遅すぎます。 セッションでは、このことはありませんがスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException">代わりにスローされる<see cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException" />場合は、メッセージは、<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewLockAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RenewLockAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.RenewLockAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewLockAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RenewLockAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.RenewLockAsync " />
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
        <summary>非同期的にメッセージのロックを更新します。</summary>
        <returns>操作の非同期の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ReplyTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはに返信するキューのアドレスを設定します。</summary>
        <value>メッセージ キューのアドレスに返信します。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ReplyToSessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定に返信するセッション識別子。</summary>
        <value>返信するセッション識別子です。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="ScheduledEnqueueTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime ScheduledEnqueueTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduledEnqueueTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ScheduledEnqueueTimeUtc : DateTime with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ScheduledEnqueueTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージがエンキューをいるを UTC で日付と時刻を設定します。 このプロパティは、UTC 時刻を返しますプロパティを設定するときに指定された DateTime 値もあります (utc)。</summary>
        <value>スケジュールされたエンキュー刻 (utc)。 この値では、遅延メッセージを送信するためです。 後で、特定の時刻に送信するメッセージを遅延することを利用します。</value>
        <remarks> メッセージ enquing 時間では、メッセージを同時に送信されることは限りません。 にキュー入れられたが取得されますが、実際の送信時間は、キューの作業負荷とその状態によって異なります。 <seealso cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedTimeUtc" /></remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">渡された値が DateTime.MaxValue である場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Service Bus によってメッセージに割り当てられた一意の番号を取得します。</summary>
        <value>Service Bus によってメッセージに割り当てられた一意の番号。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
        <exception cref="T:System.InvalidOperationException">メッセージ サーバーからメッセージを受信したいない場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはセッションの識別子を設定します。</summary>
        <value>セッションの識別子。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public long Size { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.Size" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Size As Long" />
      <MemberSignature Language="F#" Value="member this.Size : int64" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.Size" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージのサイズをバイト単位で取得します。</summary>
        <value>メッセージのサイズ (バイト単位)。</value>
        <remarks>サイズの値を正確なは、BrokeredMessage のインスタンスの送受信後のみです。</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageState State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.MessageState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As MessageState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.ServiceBus.Messaging.MessageState" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージの状態を設定します。</summary>
        <value>メッセージの状態。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Xml.Serialization.IXmlSerializable.GetSchema">
      <MemberSignature Language="C#" Value="System.Xml.Schema.XmlSchema IXmlSerializable.GetSchema ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Xml.Schema.XmlSchema System.Xml.Serialization.IXmlSerializable.GetSchema() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.System#Xml#Serialization#IXmlSerializable#GetSchema" />
      <MemberSignature Language="VB.NET" Value="Function GetSchema () As XmlSchema Implements IXmlSerializable.GetSchema" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.GetSchema</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.Schema.XmlSchema</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>このメソッドは予約されているため、使用できません。 IXmlSerializable インターフェイスを実装する場合は、null (Visual Basic では Nothing) このメソッドから返す、代わりに、カスタム スキーマを指定することが必要な場合、この、XmlSchemaProviderAttribute をクラスに適用します。</summary>
        <returns>WriteXml メソッドで作成され、ReadXml メソッドで使用されるオブジェクトの XML 表現を記述する XmlSchema です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Xml.Serialization.IXmlSerializable.ReadXml">
      <MemberSignature Language="C#" Value="void IXmlSerializable.ReadXml (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Xml.Serialization.IXmlSerializable.ReadXml(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.System#Xml#Serialization#IXmlSerializable#ReadXml(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Sub ReadXml (reader As XmlReader) Implements IXmlSerializable.ReadXml" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.ReadXml(System.Xml.XmlReader)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader">オブジェクトの逆シリアル化元の XmlReader ストリーム。</param>
        <summary>オブジェクトの XML 表現からオブジェクトを生成します。 このメソッドは、内部使用に予約されているを指定しないで直接的または間接的に (たとえば、シリアライザーまたは、フォーマッタを使用して)。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Xml.Serialization.IXmlSerializable.WriteXml">
      <MemberSignature Language="C#" Value="void IXmlSerializable.WriteXml (System.Xml.XmlWriter writer);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Xml.Serialization.IXmlSerializable.WriteXml(class System.Xml.XmlWriter writer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.System#Xml#Serialization#IXmlSerializable#WriteXml(System.Xml.XmlWriter)" />
      <MemberSignature Language="VB.NET" Value="Sub WriteXml (writer As XmlWriter) Implements IXmlSerializable.WriteXml" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.WriteXml(System.Xml.XmlWriter)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
      </Parameters>
      <Docs>
        <param name="writer">オブジェクトがシリアル化の XmlWriter ストリーム。</param>
        <summary>オブジェクトを XML 表現に変換します。 このメソッドは内部で使用するために予約済みであり直接または間接的に使用されません (シリアライザーまたは、フォーマッタを使用してなど)。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または有効期限値、メッセージの時刻を設定します。 これは、その後、メッセージは期限切れ、メッセージが Service Bus に送信されたときから開始期間です。 その TimeToLive の値よりも古いメッセージは、有効期限が切れるし、メッセージ ストアに保持されなくです。 サブスクライバーは期限切れのメッセージを受信することができません。TimeToLive はメッセージを受信できる、最大有効期間が、その値が指定されているエンティティを超えることはできません、<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" />送信先のキューまたはサブスクリプション上の値。 TimeToLive 値が低い方が指定されている場合は、個々 のメッセージに適用されます。 ただし、メッセージで指定されたより大きい値は、エンティティの DefaultMessageTimeToLive 値によってオーバーライドされます。</summary>
        <value>有効期限値、メッセージの時刻。</value>
        <remarks>送信者がメッセージに設定された TTL を超えた場合、変換先の TTL、メッセージの TTL は、遅い方によって上書きされます。
            参照してください<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" />、<see cref="P:Microsoft.ServiceBus.Messaging.TopicDescription.DefaultMessageTimeToLive" />と<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.DefaultMessageTimeToLive" />メッセージ エンティティ レベルで TTL を制御する方法の詳細についてはします。</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">渡された値が TimeSpan.Zero に等しいまたはそれよりも小さい場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または送信をアドレスに設定します。</summary>
        <value>アドレスに送信します。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">メッセージが破棄された状態である場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="brokeredMessage.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>現在のメッセージを表す文字列を返します。</summary>
        <returns>現在のメッセージの文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ViaPartitionKey">
      <MemberSignature Language="C#" Value="public string ViaPartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ViaPartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ViaPartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ViaPartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.ViaPartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ViaPartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはトランザクションがある場合、転送キュー経由のメッセージを送信するために、パーティション キー値を設定します。</summary>
        <value>パーティション キーは、トランザクションがある場合、転送キュー経由のメッセージを送信するために使用する値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>