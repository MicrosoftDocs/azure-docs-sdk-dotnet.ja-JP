<Type Name="MessagingEntityNotFoundException" FullName="Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">
  <TypeSignature Language="C#" Value="public sealed class MessagingEntityNotFoundException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessagingEntityNotFoundException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessagingEntityNotFoundException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type MessagingEntityNotFoundException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="3a88d-101">メッセージング エンティティの信号に対してスローされる例外には、エラーで見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="3a88d-101">The exception that is thrown for signaling messaging entity not found errors.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityNotFoundException (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (entityName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException : string -&gt; Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" Usage="new Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException entityName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="3a88d-102">エンティティの名前。</span><span class="sxs-lookup"><span data-stu-id="3a88d-102">The name of the entity.</span></span></param>
        <summary><span data-ttu-id="3a88d-103">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" />エンティティ名を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="3a88d-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" /> class with the entity name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityNotFoundException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" Usage="new Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="3a88d-104">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="3a88d-104">The error message that explains the reason for the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="3a88d-105">現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="3a88d-105">The exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="3a88d-106">指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3a88d-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="messagingEntityNotFoundException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="3a88d-107">現在の例外の文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="3a88d-107">Returns a string representation of the current exception.</span></span></summary>
        <returns><span data-ttu-id="3a88d-108">現在の例外の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="3a88d-108">A string representation of the current exception.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>