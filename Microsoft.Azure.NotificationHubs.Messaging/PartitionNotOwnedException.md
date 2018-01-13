<Type Name="PartitionNotOwnedException" FullName="Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException">
  <TypeSignature Language="C#" Value="public sealed class PartitionNotOwnedException : Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit PartitionNotOwnedException extends Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionNotOwnedException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type PartitionNotOwnedException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="39cea-101">シグナルを発生するエラーを所有していないパーティションにスローされる例外を表します。</span><span class="sxs-lookup"><span data-stu-id="39cea-101">Represents the exception that is thrown for signaling partition not owned errors.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionNotOwnedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="39cea-102">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="39cea-102">The error message that describes the cause of the exception.</span></span></param>
        <summary><span data-ttu-id="39cea-103">指定したエラー メッセージを使用して、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="39cea-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException" /> class with a specified error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionNotOwnedException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException : string * Exception -&gt; Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="39cea-104">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="39cea-104">The error message that describes the cause of the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="39cea-105">現在の例外の原因となった内部例外。</span><span class="sxs-lookup"><span data-stu-id="39cea-105">The inner exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="39cea-106">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException" />指定したエラー メッセージと内部例外への参照を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="39cea-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.PartitionNotOwnedException" /> class with a specified error message and a reference to the inner exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>