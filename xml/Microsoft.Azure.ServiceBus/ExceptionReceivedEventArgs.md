<Type Name="ExceptionReceivedEventArgs" FullName="Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs">
  <TypeSignature Language="C#" Value="public sealed class ExceptionReceivedEventArgs : EventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExceptionReceivedEventArgs extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExceptionReceivedEventArgs&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type ExceptionReceivedEventArgs = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="516e2-101"><see cref="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.ExceptionReceivedHandler" /> イベントのデータを提供します。</span><span class="sxs-lookup"><span data-stu-id="516e2-101">Provides data for the <see cref="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.ExceptionReceivedHandler" /> event.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionReceivedEventArgs (Exception exception, string action, string endpoint, string entityName, string clientId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Exception exception, string action, string endpoint, string entityName, string clientId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs.#ctor(System.Exception,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs : Exception * string * string * string * string -&gt; Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" Usage="new Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs (exception, action, endpoint, entityName, clientId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="516e2-102">このイベント データが属する例外。</span><span class="sxs-lookup"><span data-stu-id="516e2-102">The exception that this event data belongs to.</span></span></param>
        <param name="action"><span data-ttu-id="516e2-103">イベントに関連付けられたアクション。</span><span class="sxs-lookup"><span data-stu-id="516e2-103">The action associated with the event.</span></span></param>
        <param name="endpoint"><span data-ttu-id="516e2-104">この例外が発生したときに使用されるエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="516e2-104">The endpoint used when this exception occurred.</span></span></param>
        <param name="entityName"><span data-ttu-id="516e2-105">この例外が発生したときに使用するエンティティのパス。</span><span class="sxs-lookup"><span data-stu-id="516e2-105">The entity path used when this exception occurred.</span></span></param>
        <param name="clientId"><span data-ttu-id="516e2-106">クライアント Id に関連付けるために使用できる、 <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" />、 <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />、<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageSender" />または<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="516e2-106">The Client Id can be used to associate with the <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" />, <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />, <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageSender" /> or <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />that encountered the exception.</span></span></param>
        <summary><span data-ttu-id="516e2-107"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="516e2-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="516e2-108">親クラスがこのイベント データが属している例外を取得します。</span><span class="sxs-lookup"><span data-stu-id="516e2-108">Gets the parent class exception to which this event data belongs.</span></span></summary>
        <value><span data-ttu-id="516e2-109">例外、親クラスによって生成されたこのイベント データが属しています。</span><span class="sxs-lookup"><span data-stu-id="516e2-109">The exception, generated by the parent class, to which this event data belongs.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionReceivedContext">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.ExceptionReceivedContext ExceptionReceivedContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.ServiceBus.ExceptionReceivedContext ExceptionReceivedContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs.ExceptionReceivedContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExceptionReceivedContext As ExceptionReceivedContext" />
      <MemberSignature Language="F#" Value="member this.ExceptionReceivedContext : Microsoft.Azure.ServiceBus.ExceptionReceivedContext" Usage="Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs.ExceptionReceivedContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.ExceptionReceivedContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="516e2-110">例外 (アクション、名前空間名、およびエンティティ パス) のコンテキストを取得します。</span><span class="sxs-lookup"><span data-stu-id="516e2-110">Gets the context of the exception (action, namespace name, and entity path).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>