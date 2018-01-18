<Type Name="MessagingCommunicationException" FullName="Microsoft.ServiceBus.Messaging.MessagingCommunicationException">
  <TypeSignature Language="C#" Value="public sealed class MessagingCommunicationException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessagingCommunicationException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessagingCommunicationException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type MessagingCommunicationException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="f98d1-101">メッセージングの通信エラーを通知するためにスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="f98d1-101">The exception that is thrown to signal messaging communication errors.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingCommunicationException (string communicationPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string communicationPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingCommunicationException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (communicationPath As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessagingCommunicationException : string -&gt; Microsoft.ServiceBus.Messaging.MessagingCommunicationException" Usage="new Microsoft.ServiceBus.Messaging.MessagingCommunicationException communicationPath" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="communicationPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="communicationPath"><span data-ttu-id="f98d1-102">通信のパス。</span><span class="sxs-lookup"><span data-stu-id="f98d1-102">The communication path.</span></span></param>
        <summary><span data-ttu-id="f98d1-103"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f98d1-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingCommunicationException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingCommunicationException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessagingCommunicationException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.MessagingCommunicationException" Usage="new Microsoft.ServiceBus.Messaging.MessagingCommunicationException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="f98d1-104">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="f98d1-104">The error message that explains the reason for the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="f98d1-105">現在の例外の原因となった内部例外。</span><span class="sxs-lookup"><span data-stu-id="f98d1-105">The inner exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="f98d1-106"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f98d1-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>