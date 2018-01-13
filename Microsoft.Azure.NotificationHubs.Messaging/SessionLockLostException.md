<Type Name="SessionLockLostException" FullName="Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException">
  <TypeSignature Language="C#" Value="public sealed class SessionLockLostException : Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit SessionLockLostException extends Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SessionLockLostException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type SessionLockLostException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="22851-101">セッションを通知するためにスローされる例外は、失われるエラーをロックします。パーティション分割されたメッセージング エンティティの場合のパーティションも移動 Service Bus のノード間の負荷分散を実現するためにたとえば、新しいノードまたはノードが再起動するときに、負荷を共有に追加されます。</span><span class="sxs-lookup"><span data-stu-id="22851-101">The exception that is thrown to signal session lock lost errors.In the case of partitioned messaging entities, partitions sometimes move to achieve load balancing across Service Bus nodes; for example, when a node restarts or new nodes are added to share the load.</span></span> <span data-ttu-id="22851-102">そのような場合は、セッションのロックは失われることができますが、メッセージが失われない。</span><span class="sxs-lookup"><span data-stu-id="22851-102">When that happens, session locks can be lost, but messages are never lost.</span></span> <span data-ttu-id="22851-103">パーティションが移動する場合、セッションがロックされると、受信確認/完了メッセージの処理の呼び出しが失敗すると、そのロックが失われるためです。</span><span class="sxs-lookup"><span data-stu-id="22851-103">If a partition moves after the session is locked, then the acknowledge/complete message processing call fails, because the lock is lost.</span></span> <span data-ttu-id="22851-104">ただし、メッセージは残ります、再度読み取るしようとすることができます。</span><span class="sxs-lookup"><span data-stu-id="22851-104">However, the message remains and you can try to read it again.</span></span> <span data-ttu-id="22851-105">したがって、表示される、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException" />例外は、メッセージが失われない場合でもです。</span><span class="sxs-lookup"><span data-stu-id="22851-105">Thus, you may receive a <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException" /> exception even though the message itself is not lost.</span></span> <span data-ttu-id="22851-106">この場合、メッセージの処理の操作を再試行できます。</span><span class="sxs-lookup"><span data-stu-id="22851-106">In this case, you can retry the message processing operation.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionLockLostException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="22851-107">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="22851-107">The error message that explains the reason for the exception.</span></span></param>
        <summary><span data-ttu-id="22851-108">指定したエラー メッセージで SessionLockLostException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="22851-108">Initializes a new instance of the SessionLockLostException class with a specified error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionLockLostException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException : string * Exception -&gt; Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.SessionLockLostException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="22851-109">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="22851-109">The error message that explains the reason for the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="22851-110">現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="22851-110">The exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="22851-111">指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つ SessionLockLostException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="22851-111">Initializes a new instance of the SessionLockLostException class  with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>