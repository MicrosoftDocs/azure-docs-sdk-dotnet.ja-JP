<Type Name="SessionCannotBeLockedException" FullName="Microsoft.Azure.NotificationHubs.Messaging.SessionCannotBeLockedException">
  <TypeSignature Language="C#" Value="public sealed class SessionCannotBeLockedException : Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit SessionCannotBeLockedException extends Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.SessionCannotBeLockedException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SessionCannotBeLockedException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type SessionCannotBeLockedException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="083c7-101">メッセージ セッションでロックの取得できない場合にスローされる例外を表します。</span><span class="sxs-lookup"><span data-stu-id="083c7-101">Represents the exception that is thrown when a message cannot acquire lock on a session.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionCannotBeLockedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.SessionCannotBeLockedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.SessionCannotBeLockedException : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.SessionCannotBeLockedException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.SessionCannotBeLockedException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="083c7-102">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="083c7-102">The error message that describes the cause of the exception.</span></span></param>
        <summary><span data-ttu-id="083c7-103">指定したエラー メッセージを使用して、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.SessionCannotBeLockedException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="083c7-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.SessionCannotBeLockedException" /> class with a specified error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionCannotBeLockedException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.SessionCannotBeLockedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.SessionCannotBeLockedException : string * Exception -&gt; Microsoft.Azure.NotificationHubs.Messaging.SessionCannotBeLockedException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.SessionCannotBeLockedException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="083c7-104">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="083c7-104">The error message that describes the cause of the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="083c7-105">現在の例外の原因となった内部例外。</span><span class="sxs-lookup"><span data-stu-id="083c7-105">The inner exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="083c7-106">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.SessionCannotBeLockedException" />指定したエラー メッセージと内部への参照を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="083c7-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.SessionCannotBeLockedException" /> class with a specified error message and a reference to the inner.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>