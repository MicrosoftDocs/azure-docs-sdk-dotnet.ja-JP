<Type Name="SessionLockLostException" FullName="Microsoft.ServiceBus.Messaging.SessionLockLostException">
  <TypeSignature Language="C#" Value="public sealed class SessionLockLostException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit SessionLockLostException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SessionLockLostException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SessionLockLostException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type SessionLockLostException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>セッションを通知するためにスローされる例外は、失われるエラーをロックします。パーティション分割されたメッセージング エンティティの場合のパーティションも移動 Service Bus のノード間の負荷分散を実現するためにたとえば、新しいノードまたはノードが再起動するときに、負荷を共有に追加されます。 そのような場合は、セッションのロックは失われることができますが、メッセージが失われない。 パーティションが移動する場合、セッションがロックされると、受信確認/完了メッセージの処理の呼び出しが失敗すると、そのロックが失われるためです。 ただし、メッセージは残ります、再度読み取るしようとすることができます。 したがって、表示される、<see cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException" />例外は、メッセージが失われない場合でもです。 この場合、メッセージの処理の操作を再試行できます。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionLockLostException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SessionLockLostException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SessionLockLostException : string -&gt; Microsoft.ServiceBus.Messaging.SessionLockLostException" Usage="new Microsoft.ServiceBus.Messaging.SessionLockLostException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外の原因を説明するエラー メッセージ。</param>
        <summary>指定したエラー メッセージで SessionLockLostException クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionLockLostException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SessionLockLostException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SessionLockLostException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.SessionLockLostException" Usage="new Microsoft.ServiceBus.Messaging.SessionLockLostException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">例外の原因を説明するエラー メッセージ。</param>
        <param name="innerException">現在の例外の原因となった例外。</param>
        <summary>指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つ SessionLockLostException クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>