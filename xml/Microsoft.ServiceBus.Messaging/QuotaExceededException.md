<Type Name="QuotaExceededException" FullName="Microsoft.ServiceBus.Messaging.QuotaExceededException">
  <TypeSignature Language="C#" Value="public class QuotaExceededException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit QuotaExceededException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.QuotaExceededException" />
  <TypeSignature Language="VB.NET" Value="Public Class QuotaExceededException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type QuotaExceededException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="3f3e4-101">シグナリング クォータに対してスローされる例外は、エラーを超えています。</span><span class="sxs-lookup"><span data-stu-id="3f3e4-101">The exception that is thrown for signaling quota exceeded errors.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QuotaExceededException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QuotaExceededException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.QuotaExceededException : string -&gt; Microsoft.ServiceBus.Messaging.QuotaExceededException" Usage="new Microsoft.ServiceBus.Messaging.QuotaExceededException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="3f3e4-102">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="3f3e4-102">The error message that explains the reason for the exception.</span></span></param>
        <summary><span data-ttu-id="3f3e4-103">指定したエラー メッセージを使用して、<see cref="T:Microsoft.ServiceBus.Messaging.QuotaExceededException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3f3e4-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.QuotaExceededException" /> class with a specified error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected QuotaExceededException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QuotaExceededException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.QuotaExceededException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.ServiceBus.Messaging.QuotaExceededException" Usage="new Microsoft.ServiceBus.Messaging.QuotaExceededException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="3f3e4-104">例外に関するシリアル化された情報を格納するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f3e4-104">The object that contains the serialized information about the exception.</span></span></param>
        <param name="context"><span data-ttu-id="3f3e4-105">転送元または転送先に関するコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="3f3e4-105">The contextual information about the source or destination.</span></span></param>
        <summary><span data-ttu-id="3f3e4-106">シリアル化したデータを使用して、<see cref="T:Microsoft.ServiceBus.Messaging.QuotaExceededException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3f3e4-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.QuotaExceededException" /> class with serialized data.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QuotaExceededException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QuotaExceededException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.QuotaExceededException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.QuotaExceededException" Usage="new Microsoft.ServiceBus.Messaging.QuotaExceededException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="3f3e4-107">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="3f3e4-107">The error message that explains the reason for the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="3f3e4-108">現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="3f3e4-108">The exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="3f3e4-109">指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:Microsoft.ServiceBus.Messaging.QuotaExceededException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3f3e4-109">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.QuotaExceededException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>