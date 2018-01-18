<Type Name="SessionLockLostException" FullName="Microsoft.Azure.ServiceBus.SessionLockLostException">
  <TypeSignature Language="C#" Value="public sealed class SessionLockLostException : Microsoft.Azure.ServiceBus.ServiceBusException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SessionLockLostException extends Microsoft.Azure.ServiceBus.ServiceBusException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.SessionLockLostException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SessionLockLostException&#xA;Inherits ServiceBusException" />
  <TypeSignature Language="F#" Value="type SessionLockLostException = class&#xA;    inherit ServiceBusException" />
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
            <span data-ttu-id="3d7b8-101">セッションのロックの有効期限が切れた場合にスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="3d7b8-101">The exception that is thrown when the lock on the Session has expired.</span></span>  <span data-ttu-id="3d7b8-102">呼び出し元は、もう一度セッションを受け取ります必要があります。</span><span class="sxs-lookup"><span data-stu-id="3d7b8-102">Callers should receive the Session again.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionLockLostException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionLockLostException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SessionLockLostException : string -&gt; Microsoft.Azure.ServiceBus.SessionLockLostException" Usage="new Microsoft.Azure.ServiceBus.SessionLockLostException message" />
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
      <MemberSignature Language="C#" Value="public SessionLockLostException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionLockLostException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SessionLockLostException : string * Exception -&gt; Microsoft.Azure.ServiceBus.SessionLockLostException" Usage="new Microsoft.Azure.ServiceBus.SessionLockLostException (message, innerException)" />
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