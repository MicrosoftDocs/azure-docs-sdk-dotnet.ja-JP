<Type Name="PartitionNotOwnedException" FullName="Microsoft.ServiceBus.Messaging.PartitionNotOwnedException">
  <TypeSignature Language="C#" Value="public sealed class PartitionNotOwnedException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit PartitionNotOwnedException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.PartitionNotOwnedException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionNotOwnedException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type PartitionNotOwnedException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>シグナルを発生するエラーを所有していないパーティションにスローされる例外を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionNotOwnedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PartitionNotOwnedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.PartitionNotOwnedException : string -&gt; Microsoft.ServiceBus.Messaging.PartitionNotOwnedException" Usage="new Microsoft.ServiceBus.Messaging.PartitionNotOwnedException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外の原因を説明するエラー メッセージ。</param>
        <summary>指定したエラー メッセージを使用して、<see cref="T:Microsoft.ServiceBus.Messaging.PartitionNotOwnedException" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionNotOwnedException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PartitionNotOwnedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.PartitionNotOwnedException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.PartitionNotOwnedException" Usage="new Microsoft.ServiceBus.Messaging.PartitionNotOwnedException (message, innerException)" />
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
        <param name="message">例外の原因を説明するエラー メッセージ。</param>
        <param name="innerException">現在の例外の原因となった内部例外。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.PartitionNotOwnedException" />指定したエラー メッセージと内部例外への参照を持つクラス。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>