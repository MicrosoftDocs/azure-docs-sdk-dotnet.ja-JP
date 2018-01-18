<Type Name="IMessageSessionAsyncHandler" FullName="Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler">
  <TypeSignature Language="C#" Value="public interface IMessageSessionAsyncHandler" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMessageSessionAsyncHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMessageSessionAsyncHandler" />
  <TypeSignature Language="F#" Value="type IMessageSessionAsyncHandler = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="e9e66-101">メッセージ セッションの非同期のハンドラーのインターフェイスを表します。</span><span class="sxs-lookup"><span data-stu-id="e9e66-101">Represents an interface for the asynchronous handler for the message session.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="OnCloseSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OnCloseSessionAsync (Microsoft.ServiceBus.Messaging.MessageSession session);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseSessionAsync(class Microsoft.ServiceBus.Messaging.MessageSession session) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnCloseSessionAsync(Microsoft.ServiceBus.Messaging.MessageSession)" />
      <MemberSignature Language="VB.NET" Value="Public Function OnCloseSessionAsync (session As MessageSession) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnCloseSessionAsync : Microsoft.ServiceBus.Messaging.MessageSession -&gt; System.Threading.Tasks.Task" Usage="iMessageSessionAsyncHandler.OnCloseSessionAsync session" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="session" Type="Microsoft.ServiceBus.Messaging.MessageSession" />
      </Parameters>
      <Docs>
        <param name="session"><span data-ttu-id="e9e66-102">閉じているセッションです。</span><span class="sxs-lookup"><span data-stu-id="e9e66-102">The closed session.</span></span></param>
        <summary><span data-ttu-id="e9e66-103">セッションが非同期に閉じられたときに発生するイベントを発生させます。</span><span class="sxs-lookup"><span data-stu-id="e9e66-103">Raises an event that occurs when the session has been asynchronously closed.</span></span></summary>
        <returns><span data-ttu-id="e9e66-104">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e9e66-104">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OnMessageAsync (Microsoft.ServiceBus.Messaging.MessageSession session, Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OnMessageAsync(class Microsoft.ServiceBus.Messaging.MessageSession session, class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnMessageAsync(Microsoft.ServiceBus.Messaging.MessageSession,Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Function OnMessageAsync (session As MessageSession, message As BrokeredMessage) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnMessageAsync : Microsoft.ServiceBus.Messaging.MessageSession * Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task" Usage="iMessageSessionAsyncHandler.OnMessageAsync (session, message)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="session" Type="Microsoft.ServiceBus.Messaging.MessageSession" />
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="session"><span data-ttu-id="e9e66-105">メッセージ セッションです。</span><span class="sxs-lookup"><span data-stu-id="e9e66-105">The message session.</span></span></param>
        <param name="message"><span data-ttu-id="e9e66-106">仲介型メッセージです。</span><span class="sxs-lookup"><span data-stu-id="e9e66-106">The brokered message.</span></span></param>
        <summary><span data-ttu-id="e9e66-107">メッセージが仲介型されたときに発生するイベントを発生させます。</span><span class="sxs-lookup"><span data-stu-id="e9e66-107">Raises an event that occurs when a message has been brokered.</span></span></summary>
        <returns><span data-ttu-id="e9e66-108">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e9e66-108">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnSessionLostAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OnSessionLostAsync (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OnSessionLostAsync(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnSessionLostAsync(System.Exception)" />
      <MemberSignature Language="F#" Value="abstract member OnSessionLostAsync : Exception -&gt; System.Threading.Tasks.Task" Usage="iMessageSessionAsyncHandler.OnSessionLostAsync exception" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="e9e66-109">失われたセッションに発生する例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="e9e66-109">The exception that occurred that caused the lost session.</span></span></param>
        <summary><span data-ttu-id="e9e66-110">セッションが失われたときに発生するイベントを発生させます。</span><span class="sxs-lookup"><span data-stu-id="e9e66-110">Raises an event that occurs when the session has been lost.</span></span></summary>
        <returns><span data-ttu-id="e9e66-111">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e9e66-111">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>