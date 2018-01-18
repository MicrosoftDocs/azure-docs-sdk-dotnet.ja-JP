<Type Name="ServerBusyException" FullName="Microsoft.ServiceBus.Messaging.ServerBusyException">
  <TypeSignature Language="C#" Value="public sealed class ServerBusyException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit ServerBusyException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.ServerBusyException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServerBusyException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type ServerBusyException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="f38a6-101">サーバーは論理操作でオーバー ロードされる場合にスローされる例外を表します。</span><span class="sxs-lookup"><span data-stu-id="f38a6-101">Represents the exception that is thrown when a server is overloaded with logical operations.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerBusyException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ServerBusyException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.ServerBusyException : string -&gt; Microsoft.ServiceBus.Messaging.ServerBusyException" Usage="new Microsoft.ServiceBus.Messaging.ServerBusyException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f38a6-102">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="f38a6-102">The error message that explains the reason for the exception.</span></span></param>
        <summary><span data-ttu-id="f38a6-103">指定したエラー メッセージを使用して、<see cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f38a6-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException" /> class with a specified error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerBusyException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ServerBusyException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.ServerBusyException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.ServerBusyException" Usage="new Microsoft.ServiceBus.Messaging.ServerBusyException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="f38a6-104">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="f38a6-104">The error message that describes the cause of the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="f38a6-105">現在の例外の原因となった内部例外。</span><span class="sxs-lookup"><span data-stu-id="f38a6-105">The inner exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="f38a6-106">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException" />指定したエラー メッセージと内部例外への参照を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="f38a6-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException" /> class with a specified error message and a reference to the inner exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>