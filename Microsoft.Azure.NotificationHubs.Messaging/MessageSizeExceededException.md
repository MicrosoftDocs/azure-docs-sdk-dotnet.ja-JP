<Type Name="MessageSizeExceededException" FullName="Microsoft.Azure.NotificationHubs.Messaging.MessageSizeExceededException">
  <TypeSignature Language="C#" Value="public sealed class MessageSizeExceededException : Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessageSizeExceededException extends Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.MessageSizeExceededException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessageSizeExceededException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type MessageSizeExceededException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="9ef1f-101">メッセージのサイズが最大許容サイズを超えたときに例外を表しますが発生しました。</span><span class="sxs-lookup"><span data-stu-id="9ef1f-101">Represents an exception occurred when the size of the message exceeded the maximum allowed size.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageSizeExceededException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessageSizeExceededException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessageSizeExceededException : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessageSizeExceededException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessageSizeExceededException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="9ef1f-102">例外に関連付けられているメッセージ。</span><span class="sxs-lookup"><span data-stu-id="9ef1f-102">The message associated with the exception.</span></span></param>
        <summary><span data-ttu-id="9ef1f-103">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessageSizeExceededException" />指定した例外メッセージを使用します。</span><span class="sxs-lookup"><span data-stu-id="9ef1f-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessageSizeExceededException" /> class with specified exception message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageSizeExceededException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessageSizeExceededException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessageSizeExceededException : string * Exception -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessageSizeExceededException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessageSizeExceededException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="9ef1f-104">例外に関連付けられているメッセージ。</span><span class="sxs-lookup"><span data-stu-id="9ef1f-104">The message associated with the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="9ef1f-105">現在の例外の発生原因であるエラー。</span><span class="sxs-lookup"><span data-stu-id="9ef1f-105">The error that caused the current exception.</span></span></param>
        <summary><span data-ttu-id="9ef1f-106">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessageSizeExceededException" />した指定した例外メッセージと例外の原因となったエラー。</span><span class="sxs-lookup"><span data-stu-id="9ef1f-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessageSizeExceededException" /> class with specified exception message and the error that caused the exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>