<Type Name="GcmRegistrationDescription" FullName="Microsoft.Azure.NotificationHubs.GcmRegistrationDescription">
  <TypeSignature Language="C#" Value="public class GcmRegistrationDescription : Microsoft.Azure.NotificationHubs.RegistrationDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GcmRegistrationDescription extends Microsoft.Azure.NotificationHubs.RegistrationDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.GcmRegistrationDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class GcmRegistrationDescription&#xA;Inherits RegistrationDescription" />
  <TypeSignature Language="F#" Value="type GcmRegistrationDescription = class&#xA;    inherit RegistrationDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.RegistrationDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="GcmRegistrationDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="cd8a0-101">GCM 登録の説明を表します。</span><span class="sxs-lookup"><span data-stu-id="cd8a0-101">Represents a description of GCM registration.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GcmRegistrationDescription (Microsoft.Azure.NotificationHubs.GcmRegistrationDescription sourceRegistration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.NotificationHubs.GcmRegistrationDescription sourceRegistration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.GcmRegistrationDescription.#ctor(Microsoft.Azure.NotificationHubs.GcmRegistrationDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sourceRegistration As GcmRegistrationDescription)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.GcmRegistrationDescription : Microsoft.Azure.NotificationHubs.GcmRegistrationDescription -&gt; Microsoft.Azure.NotificationHubs.GcmRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.GcmRegistrationDescription sourceRegistration" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceRegistration" Type="Microsoft.Azure.NotificationHubs.GcmRegistrationDescription" />
      </Parameters>
      <Docs>
        <param name="sourceRegistration"><span data-ttu-id="cd8a0-102">登録のソース。</span><span class="sxs-lookup"><span data-stu-id="cd8a0-102">The source of the registration.</span></span></param>
        <summary><span data-ttu-id="cd8a0-103"><see cref="T:Microsoft.Azure.NotificationHubs.GcmRegistrationDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cd8a0-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.GcmRegistrationDescription" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GcmRegistrationDescription (string gcmRegistrationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string gcmRegistrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.GcmRegistrationDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (gcmRegistrationId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.GcmRegistrationDescription : string -&gt; Microsoft.Azure.NotificationHubs.GcmRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.GcmRegistrationDescription gcmRegistrationId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="gcmRegistrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="gcmRegistrationId"><span data-ttu-id="cd8a0-104">GCM 登録 id。</span><span class="sxs-lookup"><span data-stu-id="cd8a0-104">The GCM registration ID.</span></span></param>
        <summary><span data-ttu-id="cd8a0-105"><see cref="T:Microsoft.Azure.NotificationHubs.GcmRegistrationDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cd8a0-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.GcmRegistrationDescription" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GcmRegistrationDescription (string gcmRegistrationId, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string gcmRegistrationId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.GcmRegistrationDescription.#ctor(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (gcmRegistrationId As String, tags As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.GcmRegistrationDescription : string * seq&lt;string&gt; -&gt; Microsoft.Azure.NotificationHubs.GcmRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.GcmRegistrationDescription (gcmRegistrationId, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="gcmRegistrationId" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="gcmRegistrationId"><span data-ttu-id="cd8a0-106">GCM 登録 id。</span><span class="sxs-lookup"><span data-stu-id="cd8a0-106">The GCM registration ID.</span></span></param>
        <param name="tags"><span data-ttu-id="cd8a0-107">説明のタグ。</span><span class="sxs-lookup"><span data-stu-id="cd8a0-107">The description tags.</span></span></param>
        <summary><span data-ttu-id="cd8a0-108"><see cref="T:Microsoft.Azure.NotificationHubs.GcmRegistrationDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cd8a0-108">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.GcmRegistrationDescription" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GcmRegistrationId">
      <MemberSignature Language="C#" Value="public string GcmRegistrationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GcmRegistrationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.GcmRegistrationDescription.GcmRegistrationId" />
      <MemberSignature Language="VB.NET" Value="Public Property GcmRegistrationId As String" />
      <MemberSignature Language="F#" Value="member this.GcmRegistrationId : string with get, set" Usage="Microsoft.Azure.NotificationHubs.GcmRegistrationDescription.GcmRegistrationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="GcmRegistrationId", Order=2001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cd8a0-109">取得または設定の GCM 登録 id。</span><span class="sxs-lookup"><span data-stu-id="cd8a0-109">Gets or sets the GCM registration ID.</span></span></summary>
        <value><span data-ttu-id="cd8a0-110">GCM 登録 id。</span><span class="sxs-lookup"><span data-stu-id="cd8a0-110">The GCM registration ID.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>