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
    <summary>指定したコンテキスト<see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />クライアントで発生する例外。</summary>
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
        <param name="action">例外に関連付けられたアクション。</param>
        <param name="endpoint">例外に関連付けられているエンドポイントです。</param>
        <param name="entityPath">例外に関連付けられているエンティティのパス。</param>
        <param name="clientId">クライアント Id に関連付けるために使用できる、 <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" />、 <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />、<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageSender" />または<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />例外が発生します。</param>
        <summary><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedContext" /> クラスの新しいインスタンスを初期化します。</summary>
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
        <summary>イベントに関連付けられたアクションを取得します。</summary>
        <value>イベントに関連付けられたアクション。</value>
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
        <summary>送信者、受信者、またはこの例外が発生したセッションに関連付けられているクライアント Id。</summary>
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
        <summary>この例外が発生したときに使用する名前空間の名前。</summary>
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
        <summary>この例外が発生したときに使用するエンティティのパス。</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>