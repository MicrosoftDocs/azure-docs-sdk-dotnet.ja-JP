<Type Name="ExceptionReceivedContext" FullName="Microsoft.Azure.ServiceBus.ExceptionReceivedContext">
  <TypeSignature Language="C#" Value="public class ExceptionReceivedContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExceptionReceivedContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ExceptionReceivedContext" />
  <TypeSignature Language="VB.NET" Value="Public Class ExceptionReceivedContext" />
  <TypeSignature Language="F#" Value="type ExceptionReceivedContext = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="4d147-101">指定したコンテキスト<see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />クライアントで発生する例外。</span><span class="sxs-lookup"><span data-stu-id="4d147-101">Context provided for <see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" /> exception raised by the client.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionReceivedContext (string action, string endpoint, string entityPath, string clientId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string action, string endpoint, string entityPath, string clientId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ExceptionReceivedContext.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (action As String, endpoint As String, entityPath As String, clientId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ExceptionReceivedContext : string * string * string * string -&gt; Microsoft.Azure.ServiceBus.ExceptionReceivedContext" Usage="new Microsoft.Azure.ServiceBus.ExceptionReceivedContext (action, endpoint, entityPath, clientId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="action"><span data-ttu-id="4d147-102">例外に関連付けられたアクション。</span><span class="sxs-lookup"><span data-stu-id="4d147-102">The action associated with the exception.</span></span></param>
        <param name="endpoint"><span data-ttu-id="4d147-103">例外に関連付けられているエンドポイントです。</span><span class="sxs-lookup"><span data-stu-id="4d147-103">The endpoint associated with the exception.</span></span></param>
        <param name="entityPath"><span data-ttu-id="4d147-104">例外に関連付けられているエンティティのパス。</span><span class="sxs-lookup"><span data-stu-id="4d147-104">The entity path associated with the exception.</span></span></param>
        <param name="clientId"><span data-ttu-id="4d147-105">クライアント Id に関連付けるために使用できる、 <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" />、 <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />、<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageSender" />または<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="4d147-105">The Client Id can be used to associate with the <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" />, <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />, <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageSender" /> or <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> that encountered the exception.</span></span></param>
        <summary><span data-ttu-id="4d147-106"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedContext" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4d147-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedContext" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public string Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ExceptionReceivedContext.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As String" />
      <MemberSignature Language="F#" Value="member this.Action : string" Usage="Microsoft.Azure.ServiceBus.ExceptionReceivedContext.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4d147-107">イベントに関連付けられたアクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="4d147-107">Gets the action associated with the event.</span></span></summary>
        <value><span data-ttu-id="4d147-108">イベントに関連付けられたアクション。</span><span class="sxs-lookup"><span data-stu-id="4d147-108">The action associated with the event.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ExceptionReceivedContext.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string" Usage="Microsoft.Azure.ServiceBus.ExceptionReceivedContext.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4d147-109">送信者、受信者、またはこの例外が発生したセッションに関連付けられているクライアント Id。</span><span class="sxs-lookup"><span data-stu-id="4d147-109">The Client Id associated with the sender, receiver or session when this exception occurred.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ExceptionReceivedContext.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string" Usage="Microsoft.Azure.ServiceBus.ExceptionReceivedContext.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4d147-110">この例外が発生したときに使用する名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="4d147-110">The namespace name used when this exception occurred.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ExceptionReceivedContext.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string" Usage="Microsoft.Azure.ServiceBus.ExceptionReceivedContext.EntityPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4d147-111">この例外が発生したときに使用するエンティティのパス。</span><span class="sxs-lookup"><span data-stu-id="4d147-111">The entity path used when this exception occurred.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>