<Type Name="CommunicationClientEventArgs&lt;TCommunicationClient&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;">
  <TypeSignature Language="C#" Value="public class CommunicationClientEventArgs&lt;TCommunicationClient&gt; : EventArgs where TCommunicationClient : ICommunicationClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CommunicationClientEventArgs`1&lt;(class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient) TCommunicationClient&gt; extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1" />
  <TypeSignature Language="VB.NET" Value="Public Class CommunicationClientEventArgs(Of TCommunicationClient)&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type CommunicationClientEventArgs&lt;'CommunicationClient (requires 'CommunicationClient :&gt; ICommunicationClient)&gt; = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TCommunicationClient">
      <Constraints>
        <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TCommunicationClient"><span data-ttu-id="53cf0-101">クライアントの通信の種類</span><span class="sxs-lookup"><span data-stu-id="53cf0-101">Type of communication client</span></span></typeparam>
    <summary>
            <span data-ttu-id="53cf0-102">通信のクライアント接続切断イベント ハンドラーの引数を指定します。</span><span class="sxs-lookup"><span data-stu-id="53cf0-102">Specifies the arguments for the communication client connected/disconnected events handler.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CommunicationClientEventArgs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Client">
      <MemberSignature Language="C#" Value="public TCommunicationClient Client { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TCommunicationClient Client" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1.Client" />
      <MemberSignature Language="VB.NET" Value="Public Property Client As TCommunicationClient" />
      <MemberSignature Language="F#" Value="member this.Client : 'CommunicationClient with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.Client" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TCommunicationClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="53cf0-103">通信のクライアントが、イベントが発生しました。</span><span class="sxs-lookup"><span data-stu-id="53cf0-103">Communication client for which the event is fired.</span></span>
            </summary>
        <value><span data-ttu-id="53cf0-104">クライアントの通信</span><span class="sxs-lookup"><span data-stu-id="53cf0-104">Communication client</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>