<Type Name="MessagingEntityDisabledException" FullName="Microsoft.ServiceBus.Messaging.MessagingEntityDisabledException">
  <TypeSignature Language="C#" Value="public sealed class MessagingEntityDisabledException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessagingEntityDisabledException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessagingEntityDisabledException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessagingEntityDisabledException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type MessagingEntityDisabledException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>メッセージング エンティティのシグナルを発生する例外には、エラーが無効になります。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityDisabledException (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingEntityDisabledException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (entityName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessagingEntityDisabledException : string -&gt; Microsoft.ServiceBus.Messaging.MessagingEntityDisabledException" Usage="new Microsoft.ServiceBus.Messaging.MessagingEntityDisabledException entityName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName">例外を担当するエンティティの名前。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityDisabledException" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityDisabledException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingEntityDisabledException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessagingEntityDisabledException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.MessagingEntityDisabledException" Usage="new Microsoft.ServiceBus.Messaging.MessagingEntityDisabledException (message, innerException)" />
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
        <param name="message">例外に関するエラー メッセージ。</param>
        <param name="innerException">現在の例外の原因となった内部例外。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityDisabledException" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>