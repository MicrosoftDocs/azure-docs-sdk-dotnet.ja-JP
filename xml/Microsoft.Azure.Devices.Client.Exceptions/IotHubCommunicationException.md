<Type Name="IotHubCommunicationException" FullName="Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException">
  <TypeSignature Language="C#" Value="public sealed class IotHubCommunicationException : Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit IotHubCommunicationException extends Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class IotHubCommunicationException&#xA;Inherits IotHubException" />
  <TypeSignature Language="F#" Value="type IotHubCommunicationException = class&#xA;    inherit IotHubException" />
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
            <span data-ttu-id="5b154-101">IoT Hub サービスとの通信に失敗したときにスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="5b154-101">The exception that is thrown when an attempt to communicate with the IoT Hub service fails.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubCommunicationException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException : string -&gt; Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="5b154-102">エラーの説明。</span><span class="sxs-lookup"><span data-stu-id="5b154-102">A description of the error.</span></span> <span data-ttu-id="5b154-103">メッセージの内容は、ユーザーが理解できる内容にします。</span><span class="sxs-lookup"><span data-stu-id="5b154-103">The content of message is intended to be understood by humans.</span></span> <span data-ttu-id="5b154-104">このコンストラクターの呼び出し元は、この文字列が現在のシステムのカルチャに合わせてローカライズ済みであることを確認しておく必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b154-104">The caller of this constructor is required to ensure that this string has been localized for the current system culture.</span></span></param>
        <summary>
            <span data-ttu-id="5b154-105">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException" />メッセージ文字列をメッセージのパラメーターに設定しています。</span><span class="sxs-lookup"><span data-stu-id="5b154-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException" /> class with the message string set to the message parameter.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubCommunicationException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException : string * Exception -&gt; Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="5b154-106">エラーの説明。</span><span class="sxs-lookup"><span data-stu-id="5b154-106">A description of the error.</span></span> <span data-ttu-id="5b154-107">メッセージの内容は、ユーザーが理解できる内容にします。</span><span class="sxs-lookup"><span data-stu-id="5b154-107">The content of message is intended to be understood by humans.</span></span> <span data-ttu-id="5b154-108">このコンストラクターの呼び出し元は、この文字列が現在のシステムのカルチャに合わせてローカライズ済みであることを確認しておく必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b154-108">The caller of this constructor is required to ensure that this string has been localized for the current system culture.</span></span></param>
        <param name="innerException"><span data-ttu-id="5b154-109">現在の例外の原因となった例外</span><span class="sxs-lookup"><span data-stu-id="5b154-109">The exception that is the cause of the current exception</span></span></param>
        <summary>
            <span data-ttu-id="5b154-110">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException" />メッセージ文字列をメッセージ パラメーターおよびこの例外の原因となった内部例外への参照に設定しています。</span><span class="sxs-lookup"><span data-stu-id="5b154-110">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.IotHubCommunicationException" /> class with the message string set to the message parameter and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>