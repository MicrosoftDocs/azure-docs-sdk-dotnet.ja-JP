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
    <summary>メッセージのサイズが最大許容サイズを超えたときに例外を表しますが発生しました。</summary>
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
        <param name="message">例外に関連付けられているメッセージ。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessageSizeExceededException" />指定した例外メッセージを使用します。</summary>
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
        <param name="message">例外に関連付けられているメッセージ。</param>
        <param name="innerException">現在の例外の発生原因であるエラー。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessageSizeExceededException" />した指定した例外メッセージと例外の原因となったエラー。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>