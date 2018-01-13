<Type Name="IMessageSession" FullName="Microsoft.Azure.ServiceBus.IMessageSession">
  <TypeSignature Language="C#" Value="public interface IMessageSession : Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMessageSession implements class Microsoft.Azure.ServiceBus.Core.IMessageReceiver, class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.IMessageSession" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMessageSession&#xA;Implements IMessageReceiver" />
  <TypeSignature Language="F#" Value="type IMessageSession = interface&#xA;    interface IMessageReceiver&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.IMessageReceiver</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            セッション オブジェクトを表します。 セッションでの操作を実行する IMessageSession を使用できます。
            </summary>
    <remarks>
      <para>
            サービス バス セッション、AMQP 1.0 プロトコルでは"Groups"とも呼ばれますとは、一連の関連メッセージをバインド解除済みです。 ServiceBus では、セッションでメッセージの順序を保証します。
            </para>
      <para>
            センダは、セッションを作成することができますを設定してトピックまたはキューにメッセージを送信するときに、<see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" />メッセージのプロパティをいくつかのアプリケーションには、一意識別子を定義します。 AMQP 1.0 プロトコル レベルでは、この値は、グループ id プロパティにマップされます。
            </para>
      <para>
            セッションは、キューまたはトピックのサブスクリプションで、セッションのセッション Id で、少なくとも 1 つのメッセージが表示される時に存在するようになります。
            セッションが存在する場合は定義されている時点、またはセッションの有効期限が切れる場合または非表示のジェスチャです。
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; GetStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; GetStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IMessageSession.GetStateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetStateAsync () As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member GetStateAsync : unit -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="iMessageSession.GetStateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            セッション状態を取得します。
            </summary>
        <returns>バイト配列としてセッション状態。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.IMessageSession.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime" Usage="Microsoft.Azure.ServiceBus.IMessageSession.LockedUntilUtc" />
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
        <summary>
            時刻を取得するセッションで識別される<see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />はこのクライアント用になるまでにロックします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewSessionLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewSessionLockAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewSessionLockAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IMessageSession.RenewSessionLockAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewSessionLockAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member RenewSessionLockAsync : unit -&gt; System.Threading.Tasks.Task" Usage="iMessageSession.RenewSessionLockAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            指定されたセッションで、ロックの更新、<see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />です。 ロックは、エンティティに指定された設定に基づいて更新されます。
            </summary>
        <returns>非同期操作</returns>
        <remarks>
          <para>
            セッションを承諾すると、セッションによってロックされてクライアントのインスタンスの指定された期間、サービス キュー/サブスクリプションの作成中に。
            セッションの処理は、この期間を超える必要がある場合、セッション ロックを更新する必要があります。 各更新のエンティティに設定 LockDuration によってセッションがロックされている時間にリセットされます。
            </para>
          <para>
            セッションの更新は、同様のセッションですべてのメッセージを更新します。 各メッセージを更新することがない必要があります。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string" Usage="Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />
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
            セッション Id を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetStateAsync (byte[] sessionState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetStateAsync(unsigned int8[] sessionState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IMessageSession.SetStateAsync(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function SetStateAsync (sessionState As Byte()) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetStateAsync : byte[] -&gt; System.Threading.Tasks.Task" Usage="iMessageSession.SetStateAsync sessionState" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionState" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="sessionState">セッション状態のバイト配列</param>
        <summary>
            使用して後で取得できるセッションでのカスタム状態を設定します。<see cref="M:Microsoft.Azure.ServiceBus.IMessageSession.GetStateAsync" /></summary>
        <returns>To be added.</returns>
        <remarks>空の状態を設定していない場合、この状態は Service Bus に永久に格納されます。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>