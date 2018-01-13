<Type Name="Message+SystemPropertiesCollection" FullName="Microsoft.Azure.ServiceBus.Message+SystemPropertiesCollection">
  <TypeSignature Language="C#" Value="public sealed class Message.SystemPropertiesCollection" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit Message/SystemPropertiesCollection extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Message.SystemPropertiesCollection" />
  <TypeSignature Language="F#" Value="type Message.SystemPropertiesCollection = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Service Bus サービスによって設定されるプロパティの保存に使用されるコレクション。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SystemPropertiesCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterSource">
      <MemberSignature Language="C#" Value="public string DeadLetterSource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeadLetterSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeadLetterSource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeadLetterSource As String" />
      <MemberSignature Language="F#" Value="member this.DeadLetterSource : string" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeadLetterSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このメッセージがエンキューされた、配信不能になりましたが、前に、キューまたはサブスクリプションの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
                Only set in messages that have been dead-lettered and subsequently auto-forwarded from the dead-letter queue 
                別のエンティティです。 メッセージが配信不能になったエンティティを示します。 このプロパティは読み取り専用です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeliveryCount">
      <MemberSignature Language="C#" Value="public int DeliveryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DeliveryCount : int" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在の配信回数を取得します。
            </summary>
        <value>この値は、1 から始まります。</value>
        <remarks>
               このメッセージに対して試行された配信の数です。 このカウントは、メッセージのロックが有効期限切れになった場合、またはメッセージが受信者によって明示的に破棄された場合に増分されます。 このプロパティは読み取り専用です。
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedSequenceNumber">
      <MemberSignature Language="C#" Value="public long EnqueuedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 EnqueuedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.EnqueuedSequenceNumber : int64" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージの元のシーケンス番号を設定します。</summary>
        <value>メッセージのエンキューされたシーケンス番号。</value>
        <remarks>
            このプロパティは、自動転送されたメッセージの場合に、元の送信地点で最初にメッセージに割り当てられたシーケンス番号を示します。 このプロパティは読み取り専用です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または送信時刻の日時を UTC に設定します。</summary>
        <value>エンキュー刻 (utc)。 </value>
        <remarks>
               メッセージがエンティティで受け入れおよび格納された UTC 時刻。 この値は、受信者が送信者の時計を信頼したくない場合に、信頼できる中立的な到着時間インジケーターとして使用できます。 このプロパティは読み取り専用です。
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsLockTokenSet">
      <MemberSignature Language="C#" Value="public bool IsLockTokenSet { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsLockTokenSet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.IsLockTokenSet" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsLockTokenSet As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsLockTokenSet : bool" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.IsLockTokenSet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在のメッセージの設定のロック トークンがあるかどうかを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>ロック トークンにのみを使用してメッセージを受信したかどうかの指定<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReceived">
      <MemberSignature Language="C#" Value="public bool IsReceived { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReceived" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.IsReceived" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReceived As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReceived : bool" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.IsReceived" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージがブローカーから取得されたかどうかを指定します。</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>キュー/サブスクリプションで、メッセージをロックするまで (utc) 日付と時刻を取得します。</summary>
        <value>日時キュー/サブスクリプションになるまで、メッセージがロックされます。</value>
        <remarks>
                For messages retrieved under a lock (peek-lock receive mode, not pre-settled) this property reflects the UTC 
                インスタント メッセージを保持するまでは、キューまたはサブスクリプションでロックされています。 ロックの有効期限、<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeliveryCount" />がインクリメントされます、メッセージが再び取得するために使用できます。 このプロパティは読み取り専用です。
                </remarks>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public string LockToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockToken As String" />
      <MemberSignature Language="F#" Value="member this.LockToken : string" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在のメッセージのロック トークンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
              ロック トークンは、ブローカーによって保持されているロックへの参照を<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />モード。 説明したようにメッセージを明示的に決済するロックは使用、<a href="https://docs.microsoft.com/azure/service-bus-messaging/message-transfers-locks-settlement">製品ドキュメントで詳しく</a>です。
              完全にロックをピン留めするトークンを使用することができますも、<a href="https://docs.microsoft.com/azure/service-bus-messaging/message-deferral">遅延 API</a>と、正規の配信状態フローからメッセージを受け取る、します。 このプロパティは読み取り専用です。
              </remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Service Bus によってメッセージに割り当てられた一意の番号を取得します。</summary>
        <value>To be added.</value>
        <remarks>
                このシーケンス番号は、メッセージがブローカーおよび関数によって受け入れおよび格納されるときに真の識別子として割り当てられる 64 ビットの整数です。 パーティション分割されたエンティティの場合、最上位の 16 ビットはパーティション識別子を表します。 シーケンス番号は単調に増加します。 48 - 64 ビット範囲が使い果たされると、0 にロールオーバーされます。 このプロパティは読み取り専用です。
                </remarks>
      </Docs>
    </Member>
  </Members>
</Type>