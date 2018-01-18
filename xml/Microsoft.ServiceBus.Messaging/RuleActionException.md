<Type Name="RuleActionException" FullName="Microsoft.ServiceBus.Messaging.RuleActionException">
  <TypeSignature Language="C#" Value="public sealed class RuleActionException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit RuleActionException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.RuleActionException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RuleActionException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type RuleActionException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="92b90-101">信号フィルター アクション エラーに対してスローされ、フィルターに関連する操作が失敗する場合にスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="92b90-101">The exception that is thrown for signaling filter action errors and is thrown when a filter related operation fails.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleActionException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleActionException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.RuleActionException : string -&gt; Microsoft.ServiceBus.Messaging.RuleActionException" Usage="new Microsoft.ServiceBus.Messaging.RuleActionException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="92b90-102">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="92b90-102">The error message that explains the reason for the exception.</span></span></param>
        <summary><span data-ttu-id="92b90-103">指定されたエラー メッセージで <see cref="T:Microsoft.ServiceBus.Messaging.RuleActionException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="92b90-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.RuleActionException" /> class with the specified error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleActionException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RuleActionException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.RuleActionException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.RuleActionException" Usage="new Microsoft.ServiceBus.Messaging.RuleActionException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="92b90-104">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="92b90-104">The error message that explains the reason for the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="92b90-105">現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="92b90-105">The exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="92b90-106">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.RuleActionException" />指定されたエラー メッセージおよびこの例外の原因となった内部例外への参照を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="92b90-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.RuleActionException" /> class with the specified error message and a reference to the inner exception that is the cause of this exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>