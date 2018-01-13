<Type Name="MessageSessionAsyncHandler" FullName="Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler">
  <TypeSignature Language="C#" Value="public abstract class MessageSessionAsyncHandler : Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MessageSessionAsyncHandler extends System.Object implements class Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MessageSessionAsyncHandler&#xA;Implements IMessageSessionAsyncHandler" />
  <TypeSignature Language="F#" Value="type MessageSessionAsyncHandler = class&#xA;    interface IMessageSessionAsyncHandler" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>メッセージのセッションに関連付けられている非同期のハンドラーを表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MessageSessionAsyncHandler ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnCloseSessionAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IMessageSessionAsyncHandler.OnCloseSessionAsync (Microsoft.ServiceBus.Messaging.MessageSession session);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnCloseSessionAsync(class Microsoft.ServiceBus.Messaging.MessageSession session) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler.Microsoft#ServiceBus#Messaging#IMessageSessionAsyncHandler#OnCloseSessionAsync(Microsoft.ServiceBus.Messaging.MessageSession)" />
      <MemberSignature Language="VB.NET" Value="Function OnCloseSessionAsync (session As MessageSession) As Task Implements IMessageSessionAsyncHandler.OnCloseSessionAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnCloseSessionAsync(Microsoft.ServiceBus.Messaging.MessageSession)</InterfaceMember>
      </Implements>
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
        <param name="session">閉じているセッションです。</param>
        <summary>セッションが非同期に閉じられたときに発生するイベントを発生させます。</summary>
        <returns>非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnMessageAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IMessageSessionAsyncHandler.OnMessageAsync (Microsoft.ServiceBus.Messaging.MessageSession session, Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnMessageAsync(class Microsoft.ServiceBus.Messaging.MessageSession session, class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler.Microsoft#ServiceBus#Messaging#IMessageSessionAsyncHandler#OnMessageAsync(Microsoft.ServiceBus.Messaging.MessageSession,Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Function OnMessageAsync (session As MessageSession, message As BrokeredMessage) As Task Implements IMessageSessionAsyncHandler.OnMessageAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnMessageAsync(Microsoft.ServiceBus.Messaging.MessageSession,Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
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
        <param name="session">メッセージ セッションです。</param>
        <param name="message">仲介型メッセージです。</param>
        <summary>セッションがある、仲介型メッセージときに発生するイベントを表します。</summary>
        <returns>非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnSessionLostAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IMessageSessionAsyncHandler.OnSessionLostAsync (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnSessionLostAsync(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler.Microsoft#ServiceBus#Messaging#IMessageSessionAsyncHandler#OnSessionLostAsync(System.Exception)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnSessionLostAsync(System.Exception)</InterfaceMember>
      </Implements>
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
        <param name="exception">失われたセッションの原因となった例外が発生しました。</param>
        <summary>セッションが失われたときに発生するイベントを発生させます。</summary>
        <returns>非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseSessionAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCloseSessionAsync (Microsoft.ServiceBus.Messaging.MessageSession session);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseSessionAsync(class Microsoft.ServiceBus.Messaging.MessageSession session) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler.OnCloseSessionAsync(Microsoft.ServiceBus.Messaging.MessageSession)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCloseSessionAsync (session As MessageSession) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnCloseSessionAsync : Microsoft.ServiceBus.Messaging.MessageSession -&gt; System.Threading.Tasks.Task&#xA;override this.OnCloseSessionAsync : Microsoft.ServiceBus.Messaging.MessageSession -&gt; System.Threading.Tasks.Task" Usage="messageSessionAsyncHandler.OnCloseSessionAsync session" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnCloseSessionAsync(Microsoft.ServiceBus.Messaging.MessageSession)</InterfaceMember>
      </Implements>
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
        <param name="session">閉じているセッションです。</param>
        <summary>セッションが非同期に閉じられたときに発生するイベントを発生させます。</summary>
        <returns>非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task OnMessageAsync (Microsoft.ServiceBus.Messaging.MessageSession session, Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnMessageAsync(class Microsoft.ServiceBus.Messaging.MessageSession session, class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler.OnMessageAsync(Microsoft.ServiceBus.Messaging.MessageSession,Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnMessageAsync (session As MessageSession, message As BrokeredMessage) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnMessageAsync : Microsoft.ServiceBus.Messaging.MessageSession * Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task" Usage="messageSessionAsyncHandler.OnMessageAsync (session, message)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnMessageAsync(Microsoft.ServiceBus.Messaging.MessageSession,Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
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
        <param name="session">メッセージ セッションです。</param>
        <param name="message">仲介型メッセージです。</param>
        <summary>セッションがある、仲介型メッセージときに発生するイベントを表します。</summary>
        <returns>非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnSessionLostAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnSessionLostAsync (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnSessionLostAsync(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler.OnSessionLostAsync(System.Exception)" />
      <MemberSignature Language="F#" Value="abstract member OnSessionLostAsync : Exception -&gt; System.Threading.Tasks.Task&#xA;override this.OnSessionLostAsync : Exception -&gt; System.Threading.Tasks.Task" Usage="messageSessionAsyncHandler.OnSessionLostAsync exception" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnSessionLostAsync(System.Exception)</InterfaceMember>
      </Implements>
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
        <param name="exception">失われたセッションの原因となった例外が発生しました。</param>
        <summary>セッションが失われたときに発生するイベントを発生させます。</summary>
        <returns>非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>