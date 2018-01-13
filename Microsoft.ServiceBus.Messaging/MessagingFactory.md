<Type Name="MessagingFactory" FullName="Microsoft.ServiceBus.Messaging.MessagingFactory">
  <TypeSignature Language="C#" Value="public abstract class MessagingFactory : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MessagingFactory extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MessagingFactory&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type MessagingFactory = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary> MessagingFactory クラスは、送受信するようにして、キュー、トピック、またはサブスクリプションからの実行時の操作に使用するアンカー クラスです。 </summary>
    <remarks>CreateQueueClient などの CreateXXXClient でメンバー メソッドが、名前空間に新しいエンティティを作成しないことに注意してください。 It 以前を使用して作成された既存のエンティティへのハンドルをのみを取得、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />です。 これらのエンティティが、名前空間に存在しない場合、例外が表示されます。</remarks>
    <altmember cref="T:Microsoft.ServiceBus.NamespaceManager" />
    <example>
      <code>
            文字列のアドレス ="sb://myapp.WindowsAzure.com/"です。名前空間は、接続先のベース アドレス。
            MessagingFactorySettings MsgFactorySettings = 新しい MessagingFactorySettings() です。操作のタイムアウトを指定 (省略可能) MessagingFactory MsgFactory = MessagingFactory.Create (アドレス、MsgFactorySettings) です。
            </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.AcceptMessageSession" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession () As MessageSession" />
      <MemberSignature Language="F#" Value="member this.AcceptMessageSession : unit -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.AcceptMessageSession " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>すべてのセッションが有効なサブスクリプションとサービスの名前空間のキューで利用可能なセッションを返します。</summary>
        <returns>A<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.AcceptMessageSession(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="member this.AcceptMessageSession : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.AcceptMessageSession serverWaitTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime">処理のタイムアウトです。</param>
        <summary>すべてのセッションが有効なサブスクリプションとサービスの名前空間のキューで利用可能なセッションを返します。</summary>
        <returns>A<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="member this.AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="messagingFactory.AcceptMessageSessionAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>すべてのセッションが有効なサブスクリプションとサービスの名前空間のキューで利用可能なセッションが非同期に返します。</summary>
        <returns>Accept メッセージ セッションの非同期操作を表すタスク インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="member this.AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="messagingFactory.AcceptMessageSessionAsync serverWaitTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime">処理のタイムアウトです。</param>
        <summary>すべてのセッションが有効なサブスクリプションとサービスの名前空間のキューで利用可能なセッションが非同期に返します。</summary>
        <returns>Accept メッセージ セッションの非同期操作を表すタスク インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactory.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージング ファクトリのベース アドレスを取得します。</summary>
        <value>メッセージング ファクトリのベース アドレスを表す URI。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create () As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : unit -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>新しいメッセージング ファクトリ オブジェクトを作成します。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;string&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (addresses As IEnumerable(Of String)) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;string&gt; -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create addresses" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses">ベース アドレスの列挙です。</param>
        <summary>新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (addresses As IEnumerable(Of Uri)) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;Uri&gt; -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create addresses" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses">アドレスの列挙です。</param>
        <summary>新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (address As String) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address">サービスの名前空間のベース アドレス。</param>
        <summary>新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (address As Uri) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : Uri -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address">名前空間のベース アドレス。</param>
        <summary>新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (addresses As IEnumerable(Of String), factorySettings As MessagingFactorySettings) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;string&gt; * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (addresses, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="addresses">ベース アドレスの列挙です。</param>
        <param name="factorySettings">工場出荷時設定します。</param>
        <summary>新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;string&gt; * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (addresses, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses">ベース アドレスの列挙です。</param>
        <param name="tokenProvider">トークン プロバイダー。</param>
        <summary>新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (addresses As IEnumerable(Of Uri), factorySettings As MessagingFactorySettings) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;Uri&gt; * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (addresses, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="addresses">アドレスの列挙です。</param>
        <param name="factorySettings">工場出荷時設定します。</param>
        <summary>新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;Uri&gt; * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (addresses, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses">アドレスの列挙です。</param>
        <param name="tokenProvider">トークン プロバイダー。</param>
        <summary>新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (string address, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(string address, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.String,Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (address As String, factorySettings As MessagingFactorySettings) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (address, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="address">サービスの名前空間のベース アドレス。</param>
        <param name="factorySettings"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />設定します。</param>
        <summary>新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.UriFormatException">場合にスローされる<paramref name="address" />が空です。</exception>
        <exception cref="T:System.ArgumentNullException">場合にスローされる<paramref name="factorySettings" />または<paramref name="address" />が null です。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</exception>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (string address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(string address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.String,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (address, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">名前空間のベース アドレス。</param>
        <param name="tokenProvider">トークン プロバイダー。</param>
        <summary>新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</exception>
        <exception cref="T:System.UriFormatException">場合にスローされる<paramref name="address" />が空です。</exception>
        <exception cref="T:System.ArgumentNullException">場合にスローされる<paramref name="tokenProvider" />または<paramref name="address" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (Uri address, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Uri address, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Uri,Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (address As Uri, factorySettings As MessagingFactorySettings) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (address, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="address">名前空間のベース アドレス。</param>
        <param name="factorySettings"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />設定します。</param>
        <summary>新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">場合にスローされる<paramref name="address" />または<paramref name="factorySettings" />が null です。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</exception>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (Uri address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Uri address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Uri,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (address, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">名前空間のベース アドレス。</param>
        <param name="tokenProvider">トークン プロバイダー。</param>
        <summary>新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</exception>
        <exception cref="T:System.ArgumentNullException">場合にスローされる<paramref name="tokenProvider" />または<paramref name="address" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;string&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (addresses As IEnumerable(Of String)) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync addresses" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses">ベース アドレスの列挙です。</param>
        <summary>新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</summary>
        <returns>非同期を表すタスク インスタンスは、操作を作成します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (addresses As IEnumerable(Of Uri)) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;Uri&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync addresses" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses">アドレスの列挙です。</param>
        <summary>新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</summary>
        <returns>非同期を表すタスク インスタンスは、操作を作成します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (address As String) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address">サービスの名前空間のベース アドレス。</param>
        <summary>新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</summary>
        <returns>非同期を表すタスク インスタンスは、操作を作成します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (address As Uri) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Uri -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address">名前空間のベース アドレス。</param>
        <summary>新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</summary>
        <returns>非同期を表すタスク インスタンスは、操作を作成します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (addresses As IEnumerable(Of String), factorySettings As MessagingFactorySettings) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;string&gt; * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (addresses, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="addresses">ベース アドレスの列挙です。</param>
        <param name="factorySettings"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />設定します。</param>
        <summary>新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</summary>
        <returns>非同期を表すタスク インスタンスは、操作を作成します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;string&gt; * Microsoft.ServiceBus.TokenProvider -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (addresses, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses">ベース アドレスの列挙です。</param>
        <param name="tokenProvider">トークン プロバイダー。</param>
        <summary>新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</summary>
        <returns>非同期を表すタスク インスタンスは、操作を作成します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (addresses As IEnumerable(Of Uri), factorySettings As MessagingFactorySettings) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;Uri&gt; * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (addresses, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="addresses">アドレスの列挙です。</param>
        <param name="factorySettings"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />設定します。</param>
        <summary>新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</summary>
        <returns>非同期を表すタスク インスタンスは、操作を作成します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;Uri&gt; * Microsoft.ServiceBus.TokenProvider -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (addresses, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses">アドレスの列挙です。</param>
        <param name="tokenProvider">トークン プロバイダー。</param>
        <summary>新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</summary>
        <returns>非同期を表すタスク インスタンスは、操作を作成します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (string address, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(string address, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.String,Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (address As String, factorySettings As MessagingFactorySettings) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : string * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (address, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="address">サービスの名前空間のベース アドレス。</param>
        <param name="factorySettings"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />設定します。</param>
        <summary>新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</summary>
        <returns>非同期を表すタスク インスタンスは、操作を作成します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (string address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(string address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.String,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : string * Microsoft.ServiceBus.TokenProvider -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (address, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">サービスの名前空間のベース アドレス。</param>
        <param name="tokenProvider">トークン プロバイダー。</param>
        <summary>新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</summary>
        <returns>非同期を表すタスク インスタンスは、操作を作成します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (Uri address, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Uri address, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Uri,Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (address As Uri, factorySettings As MessagingFactorySettings) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Uri * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (address, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="address">名前空間のベース アドレス。</param>
        <param name="factorySettings"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />設定します。</param>
        <summary>新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</summary>
        <returns>非同期を表すタスク インスタンスは、操作を作成します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (Uri address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Uri address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Uri,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Uri * Microsoft.ServiceBus.TokenProvider -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (address, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">名前空間のベース アドレス。</param>
        <param name="tokenProvider">トークン プロバイダー。</param>
        <summary>新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</summary>
        <returns>非同期を表すタスク インスタンスは、操作を作成します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubClient CreateEventHubClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubClient CreateEventHubClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateEventHubClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubClient (path As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubClient : string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="messagingFactory.CreateEventHubClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Event Hub へのパス。</param>
        <summary>新たに作成<see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />オブジェクトの指定のパスを使用します。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">場合にスロー<paramref name="path" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">接続文字列。</param>
        <summary>新たに作成<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />接続文字列からオブジェクト。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageReceiver CreateMessageReceiver (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageReceiver CreateMessageReceiver(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageReceiver(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageReceiver (entityPath As String) As MessageReceiver" />
      <MemberSignature Language="F#" Value="member this.CreateMessageReceiver : string -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="messagingFactory.CreateMessageReceiver entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">エンティティのパス。</param>
        <summary>メッセージの受信者を作成します。</summary>
        <returns>新しく作成されたメッセージの受信者です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageReceiver CreateMessageReceiver (string entityPath, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageReceiver CreateMessageReceiver(string entityPath, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="messagingFactory.CreateMessageReceiver (entityPath, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="entityPath">エンティティのパス。</param>
        <param name="receiveMode">受信モードです。</param>
        <summary>メッセージの受信者を作成します。</summary>
        <returns>新しく作成されたメッセージの受信者です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt; CreateMessageReceiverAsync (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageReceiver&gt; CreateMessageReceiverAsync(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageReceiverAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageReceiverAsync (entityPath As String) As Task(Of MessageReceiver)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageReceiverAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt;" Usage="messagingFactory.CreateMessageReceiverAsync entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">エンティティのパス。</param>
        <summary>非同期的にメッセージの受信者を作成します。</summary>
        <returns>非同期の作成メッセージ受信側の操作を表すタスク インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt; CreateMessageReceiverAsync (string entityPath, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageReceiver&gt; CreateMessageReceiverAsync(string entityPath, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageReceiverAsync(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageReceiverAsync : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt;" Usage="messagingFactory.CreateMessageReceiverAsync (entityPath, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="entityPath">エンティティのパス。</param>
        <param name="receiveMode">受信モードです。</param>
        <summary>非同期的にメッセージの受信者を作成します。</summary>
        <returns>非同期の作成メッセージ受信側の操作を表すタスク インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSender">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSender CreateMessageSender (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageSender CreateMessageSender(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageSender(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageSender (entityPath As String) As MessageSender" />
      <MemberSignature Language="F#" Value="member this.CreateMessageSender : string -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.CreateMessageSender entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">エンティティのパス。</param>
        <summary>メッセージの送信者を作成します。</summary>
        <returns>新しく作成されたメッセージの送信者。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSender">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSender CreateMessageSender (string transferDestinationEntityPath, string viaEntityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageSender CreateMessageSender(string transferDestinationEntityPath, string viaEntityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageSender(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageSender (transferDestinationEntityPath As String, viaEntityPath As String) As MessageSender" />
      <MemberSignature Language="F#" Value="member this.CreateMessageSender : string * string -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.CreateMessageSender (transferDestinationEntityPath, viaEntityPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transferDestinationEntityPath" Type="System.String" />
        <Parameter Name="viaEntityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transferDestinationEntityPath">転送先エンティティのパス。</param>
        <param name="viaEntityPath">エンティティを使用してパスです。</param>
        <summary>メッセージの送信者を作成します。</summary>
        <returns>作成された <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSenderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateMessageSenderAsync (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateMessageSenderAsync(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageSenderAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageSenderAsync (entityPath As String) As Task(Of MessageSender)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageSenderAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;" Usage="messagingFactory.CreateMessageSenderAsync entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">エンティティのパス。</param>
        <summary>メッセージの送信者を非同期に作成します。</summary>
        <returns>非同期の作成メッセージ送信者の操作を表すタスク インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSenderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateMessageSenderAsync (string transferDestinationEntityPath, string viaEntityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateMessageSenderAsync(string transferDestinationEntityPath, string viaEntityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageSenderAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageSenderAsync (transferDestinationEntityPath As String, viaEntityPath As String) As Task(Of MessageSender)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageSenderAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;" Usage="messagingFactory.CreateMessageSenderAsync (transferDestinationEntityPath, viaEntityPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transferDestinationEntityPath" Type="System.String" />
        <Parameter Name="viaEntityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transferDestinationEntityPath">転送先エンティティのパス。</param>
        <param name="viaEntityPath">エンティティを使用してパスです。</param>
        <summary>メッセージの送信者を非同期に作成します。</summary>
        <returns>非同期の作成メッセージ送信者の操作を表すタスク インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQueueClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueClient CreateQueueClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueClient CreateQueueClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateQueueClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQueueClient (path As String) As QueueClient" />
      <MemberSignature Language="F#" Value="member this.CreateQueueClient : string -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="messagingFactory.CreateQueueClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスに対して、このキューのパス。</param>
        <summary>新しいキュー クライアントを作成します。</summary>
        <returns>新しく作成されたキュー クライアントです。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="path" />null または空です。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <paramref name="path" />長さがより大きい<see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />です。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />オブジェクト。 値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">内部エラーまたは予期しない例外が発生します。</exception>
        <exception cref="T:System.OperationCanceledException">ファクトリが閉じているか、中止されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateQueueClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueClient CreateQueueClient (string path, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueClient CreateQueueClient(string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateQueueClient(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="member this.CreateQueueClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="messagingFactory.CreateQueueClient (path, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスに対して、このキューのパス。</param>
        <param name="receiveMode">受信モードです。</param>
        <summary>新しいキュー クライアントを作成します。</summary>
        <returns>新しく作成されたキュー クライアントです。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="path" />null または空です。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <paramref name="path" />長さがより大きい<see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />です。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />オブジェクト。 値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">内部エラーまたは予期しない例外が発生します。</exception>
        <exception cref="T:System.OperationCanceledException">ファクトリが閉じているか、中止されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionClient CreateSubscriptionClient (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateSubscriptionClient(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateSubscriptionClient(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSubscriptionClient (topicPath As String, name As String) As SubscriptionClient" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionClient : string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="messagingFactory.CreateSubscriptionClient (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービスの名前空間の基準としたトピック パス。</param>
        <param name="name">サブスクリプションの名前。</param>
        <summary>サブスクリプション クライアントを作成します。</summary>
        <returns>新しく作成されたサブスクリプション クライアントです。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">指定された<paramref name="topicPath" />が null または空です。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">長さ<paramref name="topicPath" />がより大きい<see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />です。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />オブジェクト。 値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">内部エラーまたは予期しない例外が発生します。</exception>
        <exception cref="T:System.OperationCanceledException">ファクトリが閉じているか、中止されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionClient CreateSubscriptionClient (string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateSubscriptionClient(string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateSubscriptionClient(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionClient : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="messagingFactory.CreateSubscriptionClient (topicPath, name, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービスの名前空間の基準としたトピック パス。</param>
        <param name="name">サブスクリプションの名前。</param>
        <param name="receiveMode">受信モードです。</param>
        <summary>新しいサブスクリプション クライアントを作成します。</summary>
        <returns>新しく作成されたサブスクリプション クライアントです。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">指定された<paramref name="topicPath" />が null または空です。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">長さ<paramref name="topicPath" />がより大きい<see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />です。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />オブジェクト。 値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">内部エラーまたは予期しない例外が発生します。</exception>
        <exception cref="T:System.OperationCanceledException">ファクトリが閉じているか、中止されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateTopicClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicClient CreateTopicClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicClient CreateTopicClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateTopicClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTopicClient (path As String) As TopicClient" />
      <MemberSignature Language="F#" Value="member this.CreateTopicClient : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="messagingFactory.CreateTopicClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスの基準としたトピック パス。</param>
        <summary>新しいトピック クライアントを作成します。</summary>
        <returns>新しく作成されたトピック クライアントです。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">指定された<paramref name="path" />が null です。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />オブジェクト。 値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">内部エラーまたは予期しない例外が発生します。</exception>
        <exception cref="T:System.OperationCanceledException">ファクトリが閉じているか、中止されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingFactorySettings GetSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessagingFactorySettings GetSettings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.GetSettings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSettings () As MessagingFactorySettings" />
      <MemberSignature Language="F#" Value="member this.GetSettings : unit -&gt; Microsoft.ServiceBus.Messaging.MessagingFactorySettings" Usage="messagingFactory.GetSettings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactorySettings</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>メッセージング ファクトリの設定のコピーを取得します。</summary>
        <returns>メッセージングの工場出荷時設定のコピー。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncrementConnectionResetCount">
      <MemberSignature Language="C#" Value="protected void IncrementConnectionResetCount (Uri endpoint);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void IncrementConnectionResetCount(class System.Uri endpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.IncrementConnectionResetCount(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub IncrementConnectionResetCount (endpoint As Uri)" />
      <MemberSignature Language="F#" Value="member this.IncrementConnectionResetCount : Uri -&gt; unit" Usage="messagingFactory.IncrementConnectionResetCount endpoint" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="endpoint"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NamespaceEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Uri&gt; NamespaceEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; NamespaceEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactory.NamespaceEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NamespaceEndpoints As IEnumerable(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.NamespaceEndpoints : seq&lt;Uri&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.NamespaceEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>名前空間のエンドポイントの一覧を取得します。</summary>
        <value>名前空間のエンドポイントの一覧です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="messagingFactory.OnAbort " />
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
        <summary>中断アクションを実行します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageSession OnAcceptMessageSession (Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan serverWaitTime, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnAcceptMessageSession(valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan serverWaitTime, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnAcceptMessageSession(Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnAcceptMessageSession : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.OnAcceptMessageSession : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.OnAcceptMessageSession (receiveMode, serverWaitTime, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="receiveMode">メッセージは受信モードです。</param>
        <param name="serverWaitTime">サーバーは、時間を待機します。</param>
        <param name="timeout">操作タイムアウト。</param>
        <summary>Accept メッセージ セッションを実行します。</summary>
        <returns>メッセージが実行されるセッションです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAcceptSessionReceiver">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageSession OnAcceptSessionReceiver (string entityName, string sessionId, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnAcceptSessionReceiver(string entityName, string sessionId, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnAcceptSessionReceiver(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnAcceptSessionReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.OnAcceptSessionReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.OnAcceptSessionReceiver (entityName, sessionId, receiveMode, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="entityName">エンティティの名前。</param>
        <param name="sessionId">セッション識別子。</param>
        <param name="receiveMode">メッセージは受信モードです。</param>
        <param name="timeout">操作の前に、待機時間がタイムアウトになりました。</param>
        <summary>Accept セッション受信側のアクションを実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />非同期の参照オブジェクトがセッションの受信側のアクションをそのまま使用します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAcceptMessageSession (Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan serverWaitTime, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAcceptMessageSession(valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan serverWaitTime, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginAcceptMessageSession(Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAcceptMessageSession : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginAcceptMessageSession (receiveMode, serverWaitTime, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="receiveMode">受信モードです。</param>
        <param name="serverWaitTime">サーバーは、時間を待機します。</param>
        <param name="timeout">操作タイムアウト。</param>
        <param name="callback">非同期コールバック。</param>
        <param name="state">セッション状態。</param>
        <summary>実行開始メッセージのセッションのアクションをそのまま使用します。</summary>
        <returns>操作の非同期の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAcceptSessionReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAcceptSessionReceiver (string entityName, string sessionId, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAcceptSessionReceiver(string entityName, string sessionId, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginAcceptSessionReceiver(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAcceptSessionReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginAcceptSessionReceiver (entityName, sessionId, receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entityName">エンティティの名前。</param>
        <param name="sessionId">セッション識別子。</param>
        <param name="receiveMode">メッセージは受信モードです。</param>
        <param name="timeout">操作の前に、待機時間がタイムアウトになりました。</param>
        <param name="callback">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state">受信操作に関する情報を格納するユーザー定義のオブジェクト。</param>
        <summary>実行開始セッション受信側のアクションをそのまま使用します。</summary>
        <returns><see cref="T:System.IAsyncResult" />非同期の参照オブジェクトがセッションの受信側のアクションをそのまま使用します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginClose (timeout, callback, state)" />
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
        <param name="timeout">タイムアウト期間。</param>
        <param name="callback">コールバック。</param>
        <param name="state">状態。</param>
        <summary>開始の閉じる操作を実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />非同期の閉じる操作を参照するオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateMessageReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateMessageReceiver (string entityName, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateMessageReceiver(string entityName, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginCreateMessageReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateMessageReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginCreateMessageReceiver (entityName, receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entityName">エンティティの名前。</param>
        <param name="receiveMode">メッセージは受信モードです。</param>
        <param name="timeout">操作の前に、待機時間がタイムアウトになりました。</param>
        <param name="callback">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state">受信操作に関する情報を格納するユーザー定義のオブジェクト。</param>
        <summary>実行開始メッセージの受信側のアクションを作成します。</summary>
        <returns><see cref="T:System.IAsyncResult" />非同期作成メッセージ受信側のアクションを参照するオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateMessageSender">
      <MemberSignature Language="C#" Value="protected virtual IAsyncResult OnBeginCreateMessageSender (string entityName, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateMessageSender(string entityName, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginCreateMessageSender(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnBeginCreateMessageSender (entityName As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateMessageSender : string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult&#xA;override this.OnBeginCreateMessageSender : string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginCreateMessageSender (entityName, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entityName">エンティティの名前。</param>
        <param name="timeout">タイムアウト期間。</param>
        <param name="callback">コールバック。</param>
        <param name="state">状態。</param>
        <summary>実行開始メッセージの送信者のアクションを作成します。</summary>
        <returns><see cref="T:System.IAsyncResult" />非同期作成メッセージ送信者のアクションを参照するオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateMessageSender">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateMessageSender (string transferDestinationEntityName, string viaEntityName, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateMessageSender(string transferDestinationEntityName, string viaEntityName, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginCreateMessageSender(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginCreateMessageSender (transferDestinationEntityName As String, viaEntityName As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateMessageSender : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginCreateMessageSender (transferDestinationEntityName, viaEntityName, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transferDestinationEntityName" Type="System.String" />
        <Parameter Name="viaEntityName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="transferDestinationEntityName">転送先エンティティの名前。</param>
        <param name="viaEntityName">エンティティを使用して名前です。</param>
        <param name="timeout">タイムアウト期間。</param>
        <param name="callback">コールバック メッセージです。</param>
        <param name="state">状態。</param>
        <summary>実行開始メッセージの送信者のアクションを作成します。</summary>
        <returns><see cref="T:System.IAsyncResult" />非同期作成メッセージ送信者のアクションを参照するオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="messagingFactory.OnClose timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout">タイムアウト期間。</param>
        <summary>閉じる操作を実行します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateEventHubClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.EventHubClient OnCreateEventHubClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.EventHubClient OnCreateEventHubClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateEventHubClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCreateEventHubClient (path As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="abstract member OnCreateEventHubClient : string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient&#xA;override this.OnCreateEventHubClient : string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="messagingFactory.OnCreateEventHubClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">イベント ハブ クライアントのパス。</param>
        <summary>イベント ハブ クライアントの作成の操作を実行します。</summary>
        <returns>作成された <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateMessageReceiver">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageReceiver OnCreateMessageReceiver (string entityName, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageReceiver OnCreateMessageReceiver(string entityName, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateMessageReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateMessageReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver&#xA;override this.OnCreateMessageReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="messagingFactory.OnCreateMessageReceiver (entityName, receiveMode, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="entityName">エンティティの名前。</param>
        <param name="receiveMode">メッセージは受信モードです。</param>
        <param name="timeout">タイムアウト期間。</param>
        <summary>Create メッセージ受信側のアクションを実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />非同期作成メッセージ受信側のアクションを参照するオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateMessageSender">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageSender OnCreateMessageSender (string entityName, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnCreateMessageSender(string entityName, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateMessageSender(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCreateMessageSender (entityName As String, timeout As TimeSpan) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnCreateMessageSender : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSender&#xA;override this.OnCreateMessageSender : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.OnCreateMessageSender (entityName, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="entityName">エンティティの名前。</param>
        <param name="timeout">タイムアウト期間。</param>
        <summary>Create メッセージ送信者のアクションを実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />非同期作成メッセージ送信者のアクションを参照するオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateMessageSender">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageSender OnCreateMessageSender (string transferDestinationEntityName, string viaEntityName, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnCreateMessageSender(string transferDestinationEntityName, string viaEntityName, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateMessageSender(System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCreateMessageSender (transferDestinationEntityName As String, viaEntityName As String, timeout As TimeSpan) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnCreateMessageSender : string * string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSender&#xA;override this.OnCreateMessageSender : string * string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.OnCreateMessageSender (transferDestinationEntityName, viaEntityName, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transferDestinationEntityName" Type="System.String" />
        <Parameter Name="viaEntityName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="transferDestinationEntityName">転送先エンティティの名前。</param>
        <param name="viaEntityName">エンティティを使用して名前です。</param>
        <param name="timeout">メッセージのタイムアウト。</param>
        <summary>Create メッセージ送信者のアクションを実行します。</summary>
        <returns>実行された<see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" />アクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateQueueClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.QueueClient OnCreateQueueClient (string path, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.QueueClient OnCreateQueueClient(string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateQueueClient(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateQueueClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient&#xA;override this.OnCreateQueueClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="messagingFactory.OnCreateQueueClient (path, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスに対して、このキューのパス。</param>
        <param name="receiveMode">受信モードです。</param>
        <summary>キュー クライアントの作成の操作を実行します。</summary>
        <returns>新しく作成されたキュー クライアントです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateSubscriptionClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.SubscriptionClient OnCreateSubscriptionClient (string subscriptionPath, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.SubscriptionClient OnCreateSubscriptionClient(string subscriptionPath, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateSubscriptionClient(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateSubscriptionClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient&#xA;override this.OnCreateSubscriptionClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="messagingFactory.OnCreateSubscriptionClient (subscriptionPath, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subscriptionPath" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="subscriptionPath">サブスクリプションのパスです。</param>
        <param name="receiveMode">受信モードです。</param>
        <summary>作成するサブスクリプション クライアントの操作を実行します。</summary>
        <returns>新しく作成されたサブスクリプション クライアント。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateSubscriptionClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.SubscriptionClient OnCreateSubscriptionClient (string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.SubscriptionClient OnCreateSubscriptionClient(string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateSubscriptionClient(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateSubscriptionClient : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient&#xA;override this.OnCreateSubscriptionClient : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="messagingFactory.OnCreateSubscriptionClient (topicPath, name, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスを基準としたサブスクリプションのパス。</param>
        <param name="name">サブスクリプションの名前。</param>
        <param name="receiveMode">受信モードです。</param>
        <summary>作成するサブスクリプション クライアントの操作を実行します。</summary>
        <returns>新しく作成されたサブスクリプション クライアント。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateTopicClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.TopicClient OnCreateTopicClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.TopicClient OnCreateTopicClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateTopicClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCreateTopicClient (path As String) As TopicClient" />
      <MemberSignature Language="F#" Value="abstract member OnCreateTopicClient : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient&#xA;override this.OnCreateTopicClient : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="messagingFactory.OnCreateTopicClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <summary>トピック クライアントの作成の操作を実行します。</summary>
        <returns>新しく作成されたトピック クライアントです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndAcceptMessageSession(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndAcceptMessageSession (result As IAsyncResult) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member OnEndAcceptMessageSession : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.OnEndAcceptMessageSession result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">操作の結果。</param>
        <summary>最後に実行されるメッセージのセッションのアクションをそのまま使用します。</summary>
        <returns>実行された<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />アクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAcceptSessionReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptSessionReceiver (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptSessionReceiver(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndAcceptSessionReceiver(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndAcceptSessionReceiver (result As IAsyncResult) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member OnEndAcceptSessionReceiver : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.OnEndAcceptSessionReceiver result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">この非同期操作のステータス情報およびユーザー定義データを格納する <see cref="T:System.IAsyncResult" /> オブジェクト。</param>
        <summary>最後に実行されるセッションの受信側のアクションをそのまま使用します。</summary>
        <returns>実行された<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="messagingFactory.OnEndClose result" />
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
        <param name="result">結果。</param>
        <summary>最後の閉じる操作を実行します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateMessageReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateMessageReceiver (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateMessageReceiver(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndCreateMessageReceiver(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateMessageReceiver (result As IAsyncResult) As MessageReceiver" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateMessageReceiver : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="messagingFactory.OnEndCreateMessageReceiver result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">結果。</param>
        <summary>最後に実行されるメッセージの受信側のアクションを作成します。</summary>
        <returns>実行された<see cref="T:Microsoft.ServiceBus.Messaging.MessageReceiver" />アクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateMessageSender">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateMessageSender (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateMessageSender(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndCreateMessageSender(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateMessageSender (result As IAsyncResult) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateMessageSender : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.OnEndCreateMessageSender result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">結果。</param>
        <summary>最後に実行されるメッセージの送信者のアクションを作成します。</summary>
        <returns>実行された<see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" />アクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PairNamespaceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PairNamespaceAsync (Microsoft.ServiceBus.Messaging.PairedNamespaceOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PairNamespaceAsync(class Microsoft.ServiceBus.Messaging.PairedNamespaceOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.PairNamespaceAsync(Microsoft.ServiceBus.Messaging.PairedNamespaceOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function PairNamespaceAsync (options As PairedNamespaceOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.PairNamespaceAsync : Microsoft.ServiceBus.Messaging.PairedNamespaceOptions -&gt; System.Threading.Tasks.Task" Usage="messagingFactory.PairNamespaceAsync options" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" />
      </Parameters>
      <Docs>
        <param name="options">ペアリング オプション。</param>
        <summary>名前空間のペアを非同期的にします。</summary>
        <returns>操作の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public virtual int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactory.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.PrefetchCount" />
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
        <remarks> サーバーに次の acceptmessagesession 呼び出しで有効になります </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetConnection">
      <MemberSignature Language="C#" Value="public virtual void ResetConnection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ResetConnection() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.ResetConnection" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub ResetConnection ()" />
      <MemberSignature Language="F#" Value="abstract member ResetConnection : unit -&gt; unit&#xA;override this.ResetConnection : unit -&gt; unit" Usage="messagingFactory.ResetConnection " />
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
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>