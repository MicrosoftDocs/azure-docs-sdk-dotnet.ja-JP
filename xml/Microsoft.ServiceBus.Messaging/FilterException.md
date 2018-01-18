<Type Name="FilterException" FullName="Microsoft.ServiceBus.Messaging.FilterException">
  <TypeSignature Language="C#" Value="public sealed class FilterException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit FilterException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.FilterException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FilterException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type FilterException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="89613-101">信号フィルター アクション エラーに対してスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="89613-101">The exception that is thrown for signaling filter action errors.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FilterException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FilterException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.FilterException : string -&gt; Microsoft.ServiceBus.Messaging.FilterException" Usage="new Microsoft.ServiceBus.Messaging.FilterException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="89613-102">例外メッセージ。</span><span class="sxs-lookup"><span data-stu-id="89613-102">The exception message.</span></span></param>
        <summary><span data-ttu-id="89613-103">指定したメッセージを使用して、<see cref="T:Microsoft.ServiceBus.Messaging.FilterException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="89613-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.FilterException" /> class using the specified message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FilterException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FilterException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.FilterException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.FilterException" Usage="new Microsoft.ServiceBus.Messaging.FilterException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="89613-104">例外メッセージ。</span><span class="sxs-lookup"><span data-stu-id="89613-104">The exception message.</span></span></param>
        <param name="innerException"><span data-ttu-id="89613-105">内部例外。</span><span class="sxs-lookup"><span data-stu-id="89613-105">The inner exception.</span></span></param>
        <summary><span data-ttu-id="89613-106">指定したメッセージと内部例外を使用して、<see cref="T:Microsoft.ServiceBus.Messaging.FilterException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="89613-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.FilterException" /> class using the specified message and inner exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>