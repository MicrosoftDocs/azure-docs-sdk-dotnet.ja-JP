<Type Name="ExceptionReceivedEventArgs" FullName="Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs">
  <TypeSignature Language="C#" Value="public sealed class ExceptionReceivedEventArgs : EventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExceptionReceivedEventArgs extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExceptionReceivedEventArgs&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type ExceptionReceivedEventArgs = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><see cref="E:Microsoft.ServiceBus.Messaging.OnMessageOptions.ExceptionReceived" /> イベントのデータを提供します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionReceivedEventArgs (Exception exception, string action);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Exception exception, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs.#ctor(System.Exception,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs : Exception * string -&gt; Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs" Usage="new Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs (exception, action)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="action" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="exception">このイベント データが属する例外。</param>
        <param name="action">イベントに関連付けられたアクション。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public string Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As String" />
      <MemberSignature Language="F#" Value="member this.Action : string" Usage="Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
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
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
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
  </Members>
</Type>