<Type Name="DeviceMaximumQueueDepthExceededException" FullName="Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException">
  <TypeSignature Language="C#" Value="public sealed class DeviceMaximumQueueDepthExceededException : Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit DeviceMaximumQueueDepthExceededException extends Microsoft.Azure.Devices.Client.Exceptions.IotHubException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeviceMaximumQueueDepthExceededException&#xA;Inherits IotHubException" />
  <TypeSignature Language="F#" Value="type DeviceMaximumQueueDepthExceededException = class&#xA;    inherit IotHubException" />
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
            <span data-ttu-id="03f92-101">失敗した場合、メッセージをエンキューするデバイス用のメッセージ キューが既にいっぱいのためにスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="03f92-101">The exception that is thrown when an attempt to enqueue a message fails because the message queue for the device is already full.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceMaximumQueueDepthExceededException (int maximumQueueDepth);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 maximumQueueDepth) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException.#ctor(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maximumQueueDepth As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException : int -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException maximumQueueDepth" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maximumQueueDepth" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maximumQueueDepth"><span data-ttu-id="03f92-102">キュー内のメッセージの最大数。</span><span class="sxs-lookup"><span data-stu-id="03f92-102">Maximum number of messages in the queue.</span></span></param>
        <summary>
            <span data-ttu-id="03f92-103">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" />既に既存のデバイスの識別子を含むメッセージ文字列を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="03f92-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" /> class with the message string containing the identifier of the already existing device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceMaximumQueueDepthExceededException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException : string -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="03f92-104">エラーの説明。</span><span class="sxs-lookup"><span data-stu-id="03f92-104">A description of the error.</span></span> <span data-ttu-id="03f92-105">メッセージの内容は、ユーザーが理解できる内容にします。</span><span class="sxs-lookup"><span data-stu-id="03f92-105">The content of message is intended to be understood by humans.</span></span> <span data-ttu-id="03f92-106">このコンストラクターの呼び出し元は、この文字列が現在のシステムのカルチャに合わせてローカライズ済みであることを確認しておく必要があります。</span><span class="sxs-lookup"><span data-stu-id="03f92-106">The caller of this constructor is required to ensure that this string has been localized for the current system culture.</span></span></param>
        <summary>
            <span data-ttu-id="03f92-107">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" />メッセージ文字列をメッセージのパラメーターに設定しています。</span><span class="sxs-lookup"><span data-stu-id="03f92-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" /> class with the message string set to the message parameter.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceMaximumQueueDepthExceededException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException : string * Exception -&gt; Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" Usage="new Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="03f92-108">エラーの説明。</span><span class="sxs-lookup"><span data-stu-id="03f92-108">A description of the error.</span></span> <span data-ttu-id="03f92-109">メッセージの内容は、ユーザーが理解できる内容にします。</span><span class="sxs-lookup"><span data-stu-id="03f92-109">The content of message is intended to be understood by humans.</span></span> <span data-ttu-id="03f92-110">このコンストラクターの呼び出し元は、この文字列が現在のシステムのカルチャに合わせてローカライズ済みであることを確認しておく必要があります。</span><span class="sxs-lookup"><span data-stu-id="03f92-110">The caller of this constructor is required to ensure that this string has been localized for the current system culture.</span></span></param>
        <param name="innerException"><span data-ttu-id="03f92-111">現在の例外の原因となった例外</span><span class="sxs-lookup"><span data-stu-id="03f92-111">The exception that is the cause of the current exception</span></span></param>
        <summary>
            <span data-ttu-id="03f92-112">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" />メッセージ文字列をメッセージ パラメーターおよびこの例外の原因となった内部例外への参照に設定しています。</span><span class="sxs-lookup"><span data-stu-id="03f92-112">Initializes a new instance of the <see cref="T:Microsoft.Azure.Devices.Client.Exceptions.DeviceMaximumQueueDepthExceededException" /> class with the message string set to the message parameter and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>