<Type Name="GcmNotification" FullName="Microsoft.Azure.NotificationHubs.GcmNotification">
  <TypeSignature Language="C#" Value="public sealed class GcmNotification : Microsoft.Azure.NotificationHubs.Notification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit GcmNotification extends Microsoft.Azure.NotificationHubs.Notification" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.GcmNotification" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class GcmNotification&#xA;Inherits Notification" />
  <TypeSignature Language="F#" Value="type GcmNotification = class&#xA;    inherit Notification" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Notification</BaseTypeName>
  </Base>
  <Interfaces></Interfaces>
  <Docs>
    <summary><span data-ttu-id="451ff-101">Google Cloud Messaging の通知を表します。</span><span class="sxs-lookup"><span data-stu-id="451ff-101">Represents a Google Cloud Messaging notification.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GcmNotification (string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.GcmNotification.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jsonPayload As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.GcmNotification : string -&gt; Microsoft.Azure.NotificationHubs.GcmNotification" Usage="new Microsoft.Azure.NotificationHubs.GcmNotification jsonPayload" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="451ff-102">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="451ff-102">The JSON payload.</span></span></param>
        <summary><span data-ttu-id="451ff-103"><see cref="T:Microsoft.Azure.NotificationHubs.GcmNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="451ff-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.GcmNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GcmNotification (string jsonPayload, string tag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string jsonPayload, string tag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.GcmNotification.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jsonPayload As String, tag As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.GcmNotification : string * string -&gt; Microsoft.Azure.NotificationHubs.GcmNotification" Usage="new Microsoft.Azure.NotificationHubs.GcmNotification (jsonPayload, tag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This method is obsolete.")</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="451ff-104">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="451ff-104">The JSON payload.</span></span></param>
        <param name="tag"><span data-ttu-id="451ff-105">通知タグです。</span><span class="sxs-lookup"><span data-stu-id="451ff-105">The notification tag.</span></span></param>
        <summary><span data-ttu-id="451ff-106"><see cref="T:Microsoft.Azure.NotificationHubs.GcmNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="451ff-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.GcmNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidateAndPopulateHeaders">
      <MemberSignature Language="C#" Value="protected override void OnValidateAndPopulateHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidateAndPopulateHeaders() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.GcmNotification.OnValidateAndPopulateHeaders" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidateAndPopulateHeaders ()" />
      <MemberSignature Language="F#" Value="override this.OnValidateAndPopulateHeaders : unit -&gt; unit" Usage="gcmNotification.OnValidateAndPopulateHeaders " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="451ff-107">検証し、ヘッダーを追加します。</span><span class="sxs-lookup"><span data-stu-id="451ff-107">Validate and populates the headers.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformType">
      <MemberSignature Language="C#" Value="protected override string PlatformType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PlatformType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.GcmNotification.PlatformType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property PlatformType As String" />
      <MemberSignature Language="F#" Value="member this.PlatformType : string" Usage="Microsoft.Azure.NotificationHubs.GcmNotification.PlatformType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="451ff-108">プラットフォームの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="451ff-108">Gets the type of the platform.</span></span>
            </summary>
        <value>
            <span data-ttu-id="451ff-109">プラットフォームの種類。</span><span class="sxs-lookup"><span data-stu-id="451ff-109">The type of the platform.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>