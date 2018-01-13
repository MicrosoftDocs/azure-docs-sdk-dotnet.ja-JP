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
    <summary><see cref="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.ExceptionReceivedHandler" /> イベントのデータを提供します。</summary>
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
        <param name="exception">このイベント データが属する例外。</param>
        <param name="action">イベントに関連付けられたアクション。</param>
        <param name="endpoint">この例外が発生したときに使用されるエンドポイント。</param>
        <param name="entityName">この例外が発生したときに使用するエンティティのパス。</param>
        <param name="clientId">クライアント Id に関連付けるために使用できる、 <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" />、 <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />、<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageSender" />または<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />例外が発生します。</param>
        <summary><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" /> クラスの新しいインスタンスを初期化します。</summary>
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
        <summary>親クラスがこのイベント データが属している例外を取得します。</summary>
        <value>例外、親クラスによって生成されたこのイベント データが属しています。</value>
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
            例外 (アクション、名前空間名、およびエンティティ パス) のコンテキストを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>