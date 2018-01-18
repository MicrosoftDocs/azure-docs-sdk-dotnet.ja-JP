<Type Name="MessageStoreLockLostException" FullName="Microsoft.Azure.NotificationHubs.Messaging.MessageStoreLockLostException">
  <TypeSignature Language="C#" Value="public sealed class MessageStoreLockLostException : Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessageStoreLockLostException extends Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.MessageStoreLockLostException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessageStoreLockLostException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type MessageStoreLockLostException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="6c4bc-101">表すメッセージ ストアのロックの信号に対してスローされる例外には、エラーが失われました。</span><span class="sxs-lookup"><span data-stu-id="6c4bc-101">Represents the exception that is thrown for signaling message store lock lost errors.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageStoreLockLostException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessageStoreLockLostException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessageStoreLockLostException : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessageStoreLockLostException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessageStoreLockLostException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="6c4bc-102">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="6c4bc-102">The error message that explains the reason for the exception.</span></span></param>
        <summary><span data-ttu-id="6c4bc-103">指定したエラー メッセージを使用して、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessageStoreLockLostException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6c4bc-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessageStoreLockLostException" /> class with a specified error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageStoreLockLostException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessageStoreLockLostException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessageStoreLockLostException : string * Exception -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessageStoreLockLostException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessageStoreLockLostException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="6c4bc-104">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="6c4bc-104">The error message that explains the reason for the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="6c4bc-105">現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="6c4bc-105">The exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="6c4bc-106">指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessageStoreLockLostException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6c4bc-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessageStoreLockLostException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>