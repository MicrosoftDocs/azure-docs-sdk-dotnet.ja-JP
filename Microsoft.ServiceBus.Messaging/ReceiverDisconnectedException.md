<Type Name="ReceiverDisconnectedException" FullName="Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException">
  <TypeSignature Language="C#" Value="public sealed class ReceiverDisconnectedException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit ReceiverDisconnectedException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReceiverDisconnectedException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type ReceiverDisconnectedException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>2 つ以上の場合、この例外がスローされます<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />オブジェクトが異なるエポックの値を持つ同じ Event Hubs のパーティションに接続します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReceiverDisconnectedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException : string -&gt; Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException" Usage="new Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外メッセージ。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException" />指定した例外メッセージを使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReceiverDisconnectedException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException" Usage="new Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException (message, innerException)" />
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
        <param name="message">例外メッセージ。</param>
        <param name="innerException">内部例外テキストです。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException" />クラスを指定した例外メッセージと内部例外のテキストを使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>