<Type Name="MessageLockLostException" FullName="Microsoft.Azure.ServiceBus.MessageLockLostException">
  <TypeSignature Language="C#" Value="public sealed class MessageLockLostException : Microsoft.Azure.ServiceBus.ServiceBusException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MessageLockLostException extends Microsoft.Azure.ServiceBus.ServiceBusException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.MessageLockLostException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessageLockLostException&#xA;Inherits ServiceBusException" />
  <TypeSignature Language="F#" Value="type MessageLockLostException = class&#xA;    inherit ServiceBusException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.ServiceBusException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cd365-101">メッセージのロックが失われた場合にスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="cd365-101">The exception that is thrown when the lock on the message is lost.</span></span>  <span data-ttu-id="cd365-102">呼び出し元は、Receive を呼び出すし、メッセージを再処理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="cd365-102">Callers should call Receive and process the message again.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageLockLostException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.MessageLockLostException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.MessageLockLostException : string -&gt; Microsoft.Azure.ServiceBus.MessageLockLostException" Usage="new Microsoft.Azure.ServiceBus.MessageLockLostException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageLockLostException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.MessageLockLostException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.MessageLockLostException : string * Exception -&gt; Microsoft.Azure.ServiceBus.MessageLockLostException" Usage="new Microsoft.Azure.ServiceBus.MessageLockLostException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <param name="innerException">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>