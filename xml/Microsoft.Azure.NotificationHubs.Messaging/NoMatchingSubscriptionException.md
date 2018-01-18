<Type Name="NoMatchingSubscriptionException" FullName="Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException">
  <TypeSignature Language="C#" Value="public sealed class NoMatchingSubscriptionException : Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit NoMatchingSubscriptionException extends Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NoMatchingSubscriptionException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type NoMatchingSubscriptionException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="e8fef-101">一致結果なしサブスクリプションと一致する場合にスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="e8fef-101">The exception that is thrown when subscription matching resulted no match.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NoMatchingSubscriptionException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="e8fef-102">例外に関するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e8fef-102">The error message about the exception.</span></span></param>
        <summary><span data-ttu-id="e8fef-103">エラー メッセージを使用して、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e8fef-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException" /> class with error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NoMatchingSubscriptionException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException : string * Exception -&gt; Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="e8fef-104">例外に関するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e8fef-104">The error message about the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="e8fef-105">現在の例外の原因となった内部例外。</span><span class="sxs-lookup"><span data-stu-id="e8fef-105">The inner exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="e8fef-106">エラー メッセージと内部例外を使用して、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e8fef-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException" /> class with error message and inner exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="noMatchingSubscriptionException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="e8fef-107"><see cref="T:Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException" /> の文字列形式を返します。</span><span class="sxs-lookup"><span data-stu-id="e8fef-107">Returns the string representation of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException" />.</span></span></summary>
        <returns><span data-ttu-id="e8fef-108"><see cref="T:Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException" /> の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="e8fef-108">The string representation of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.NoMatchingSubscriptionException" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>