<Type Name="MobileServiceEvent&lt;T&gt;" FullName="Microsoft.WindowsAzure.MobileServices.Eventing.MobileServiceEvent&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class MobileServiceEvent&lt;T&gt; : Microsoft.WindowsAzure.MobileServices.Eventing.MobileServiceEvent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceEvent`1&lt;T&gt; extends Microsoft.WindowsAzure.MobileServices.Eventing.MobileServiceEvent" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Eventing.MobileServiceEvent`1" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceEvent(Of T)&#xA;Inherits MobileServiceEvent" />
  <TypeSignature Language="F#" Value="type MobileServiceEvent&lt;'T&gt; = class&#xA;    inherit MobileServiceEvent" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.MobileServices.Eventing.MobileServiceEvent</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T"><span data-ttu-id="c8608-101">このイベントのペイロードの型。</span><span class="sxs-lookup"><span data-stu-id="c8608-101">The type of payload in this event.</span></span></typeparam>
    <summary>
            <span data-ttu-id="c8608-102">厳密に型指定のペイロードを使用したモバイル サービス イベントを表します。</span><span class="sxs-lookup"><span data-stu-id="c8608-102">Represents a mobile service event with a strongly typed payload.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceEvent (string name, T payload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, !T payload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Eventing.MobileServiceEvent`1.#ctor(System.String,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, payload As T)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.Eventing.MobileServiceEvent&lt;'T&gt; : string * 'T -&gt; Microsoft.WindowsAzure.MobileServices.Eventing.MobileServiceEvent&lt;'T&gt;" Usage="new Microsoft.WindowsAzure.MobileServices.Eventing.MobileServiceEvent&lt;'T&gt; (name, payload)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="payload" Type="T" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c8608-103">イベントの名前です。</span><span class="sxs-lookup"><span data-stu-id="c8608-103">The event name.</span></span></param>
        <param name="payload"><span data-ttu-id="c8608-104">このイベントに関連付けられているペイロード。</span><span class="sxs-lookup"><span data-stu-id="c8608-104">The payload associated with this event.</span></span></param>
        <summary>
            <span data-ttu-id="c8608-105">指定されたイベント名とペイロードを使用して MobileServiceEvent のインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c8608-105">Initializes an instance of the MobileServiceEvent using the specified event name and payload.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Payload">
      <MemberSignature Language="C#" Value="public T Payload { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Payload" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Eventing.MobileServiceEvent`1.Payload" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Payload As T" />
      <MemberSignature Language="F#" Value="member this.Payload : 'T" Usage="Microsoft.WindowsAzure.MobileServices.Eventing.MobileServiceEvent&lt;'T&gt;.Payload" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8608-106">イベント ペイロードを取得します。</span><span class="sxs-lookup"><span data-stu-id="c8608-106">Gets the event payload.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>