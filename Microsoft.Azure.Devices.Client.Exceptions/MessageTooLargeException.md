<Type Name="MessageTooLargeException" FullName="Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException">
  <TypeSignature Language="C#" Value="public sealed class MessageTooLargeException : Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessageTooLargeException extends Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessageTooLargeException&#xA;Inherits IotHubException" />
  <TypeSignature Language="F#" Value="type MessageTooLargeException = class&#xA;    inherit IotHubException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Devices.Client.Exceptions.IotHubException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c5520-101">失敗した場合、メッセージを送信するメッセージの長さが許容される最大サイズを超えているためにスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="c5520-101">The exception that is thrown when an attempt to send a message fails because the length of the message exceeds the maximum size allowed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageTooLargeException (int maximumMessageSizeInBytes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 maximumMessageSizeInBytes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException.#ctor(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maximumMessageSizeInBytes As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException : int -&gt; Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException maximumMessageSizeInBytes" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maximumMessageSizeInBytes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maximumMessageSizeInBytes"><span data-ttu-id="c5520-102">既に存在するデバイスの識別子です。</span><span class="sxs-lookup"><span data-stu-id="c5520-102">Device identifier that already exists.</span></span></param>
        <summary>
            <span data-ttu-id="c5520-103">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" /> (バイト単位)、メッセージの最大サイズを含むメッセージの文字列でクラスを使用します。</span><span class="sxs-lookup"><span data-stu-id="c5520-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" /> class with the message string containing the maximum sized allowed for a message, in bytes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageTooLargeException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException : string -&gt; Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="c5520-104">エラーの説明。</span><span class="sxs-lookup"><span data-stu-id="c5520-104">A description of the error.</span></span> <span data-ttu-id="c5520-105">メッセージの内容は、ユーザーが理解できる内容にします。</span><span class="sxs-lookup"><span data-stu-id="c5520-105">The content of message is intended to be understood by humans.</span></span> <span data-ttu-id="c5520-106">このコンストラクターの呼び出し元は、この文字列が現在のシステムのカルチャに合わせてローカライズ済みであることを確認しておく必要があります。</span><span class="sxs-lookup"><span data-stu-id="c5520-106">The caller of this constructor is required to ensure that this string has been localized for the current system culture.</span></span></param>
        <summary>
            <span data-ttu-id="c5520-107">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" />メッセージ文字列をメッセージのパラメーターに設定しています。</span><span class="sxs-lookup"><span data-stu-id="c5520-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" /> class with the message string set to the message parameter.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageTooLargeException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException : string * Exception -&gt; Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="c5520-108">エラーの説明。</span><span class="sxs-lookup"><span data-stu-id="c5520-108">A description of the error.</span></span> <span data-ttu-id="c5520-109">メッセージの内容は、ユーザーが理解できる内容にします。</span><span class="sxs-lookup"><span data-stu-id="c5520-109">The content of message is intended to be understood by humans.</span></span> <span data-ttu-id="c5520-110">このコンストラクターの呼び出し元は、この文字列が現在のシステムのカルチャに合わせてローカライズ済みであることを確認しておく必要があります。</span><span class="sxs-lookup"><span data-stu-id="c5520-110">The caller of this constructor is required to ensure that this string has been localized for the current system culture.</span></span></param>
        <param name="innerException"><span data-ttu-id="c5520-111">現在の例外の原因となった例外</span><span class="sxs-lookup"><span data-stu-id="c5520-111">The exception that is the cause of the current exception</span></span></param>
        <summary>
            <span data-ttu-id="c5520-112">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" />メッセージ文字列をメッセージ パラメーターおよびこの例外の原因となった内部例外への参照に設定しています。</span><span class="sxs-lookup"><span data-stu-id="c5520-112">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.MessageTooLargeException" /> class with the message string set to the message parameter and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>