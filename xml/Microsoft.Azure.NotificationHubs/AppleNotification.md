<Type Name="AppleNotification" FullName="Microsoft.Azure.NotificationHubs.AppleNotification">
  <TypeSignature Language="C#" Value="public sealed class AppleNotification : Microsoft.Azure.NotificationHubs.Notification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AppleNotification extends Microsoft.Azure.NotificationHubs.Notification" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.AppleNotification" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AppleNotification&#xA;Inherits Notification" />
  <TypeSignature Language="F#" Value="type AppleNotification = class&#xA;    inherit Notification" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Notification</BaseTypeName>
  </Base>
  <Interfaces></Interfaces>
  <Docs>
    <summary><span data-ttu-id="d50a2-101">Apple 通知を表します。</span><span class="sxs-lookup"><span data-stu-id="d50a2-101">Represents the Apple notification.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppleNotification (string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AppleNotification.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jsonPayload As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AppleNotification : string -&gt; Microsoft.Azure.NotificationHubs.AppleNotification" Usage="new Microsoft.Azure.NotificationHubs.AppleNotification jsonPayload" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="d50a2-102">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="d50a2-102">The JSON payload.</span></span></param>
        <summary><span data-ttu-id="d50a2-103"><see cref="T:Microsoft.Azure.NotificationHubs.AppleNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d50a2-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.AppleNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppleNotification (string jsonPayload, Nullable&lt;DateTime&gt; expiry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string jsonPayload, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expiry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AppleNotification.#ctor(System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jsonPayload As String, expiry As Nullable(Of DateTime))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AppleNotification : string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.NotificationHubs.AppleNotification" Usage="new Microsoft.Azure.NotificationHubs.AppleNotification (jsonPayload, expiry)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="expiry" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="d50a2-104">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="d50a2-104">The JSON payload.</span></span></param>
        <param name="expiry"><span data-ttu-id="d50a2-105">通知の有効期限です。</span><span class="sxs-lookup"><span data-stu-id="d50a2-105">The expiration of the notification.</span></span></param>
        <summary><span data-ttu-id="d50a2-106"><see cref="T:Microsoft.Azure.NotificationHubs.AppleNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d50a2-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.AppleNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppleNotification (string jsonPayload, string tag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string jsonPayload, string tag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AppleNotification.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jsonPayload As String, tag As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AppleNotification : string * string -&gt; Microsoft.Azure.NotificationHubs.AppleNotification" Usage="new Microsoft.Azure.NotificationHubs.AppleNotification (jsonPayload, tag)" />
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
        <param name="jsonPayload"><span data-ttu-id="d50a2-107">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="d50a2-107">The JSON payload.</span></span></param>
        <param name="tag"><span data-ttu-id="d50a2-108">通知タグです。</span><span class="sxs-lookup"><span data-stu-id="d50a2-108">The notification tag.</span></span></param>
        <summary><span data-ttu-id="d50a2-109"><see cref="T:Microsoft.Azure.NotificationHubs.AppleNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d50a2-109">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.AppleNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppleNotification (string jsonPayload, Nullable&lt;DateTime&gt; expiry, string tag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string jsonPayload, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expiry, string tag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AppleNotification.#ctor(System.String,System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jsonPayload As String, expiry As Nullable(Of DateTime), tag As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AppleNotification : string * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.NotificationHubs.AppleNotification" Usage="new Microsoft.Azure.NotificationHubs.AppleNotification (jsonPayload, expiry, tag)" />
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
        <Parameter Name="expiry" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="tag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="d50a2-110">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="d50a2-110">The JSON payload.</span></span></param>
        <param name="expiry"><span data-ttu-id="d50a2-111">通知の有効期限です。</span><span class="sxs-lookup"><span data-stu-id="d50a2-111">The expiration of the notification.</span></span></param>
        <param name="tag"><span data-ttu-id="d50a2-112">通知タグです。</span><span class="sxs-lookup"><span data-stu-id="d50a2-112">The notification tag.</span></span></param>
        <summary><span data-ttu-id="d50a2-113"><see cref="T:Microsoft.Azure.NotificationHubs.AppleNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d50a2-113">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.AppleNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expiry">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Expiry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Expiry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AppleNotification.Expiry" />
      <MemberSignature Language="VB.NET" Value="Public Property Expiry As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Expiry : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.AppleNotification.Expiry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d50a2-114">取得または通知の有効期限日時を設定します。</span><span class="sxs-lookup"><span data-stu-id="d50a2-114">Gets or sets the expiration date and time of the notification.</span></span></summary>
        <value><span data-ttu-id="d50a2-115">有効期限の日付と通知の時刻。</span><span class="sxs-lookup"><span data-stu-id="d50a2-115">The expiration date and time of the notification.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidateAndPopulateHeaders">
      <MemberSignature Language="C#" Value="protected override void OnValidateAndPopulateHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidateAndPopulateHeaders() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AppleNotification.OnValidateAndPopulateHeaders" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidateAndPopulateHeaders ()" />
      <MemberSignature Language="F#" Value="override this.OnValidateAndPopulateHeaders : unit -&gt; unit" Usage="appleNotification.OnValidateAndPopulateHeaders " />
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
            <span data-ttu-id="d50a2-116">検証し、ヘッダーを追加します。</span><span class="sxs-lookup"><span data-stu-id="d50a2-116">Validate and populates the headers.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformType">
      <MemberSignature Language="C#" Value="protected override string PlatformType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PlatformType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AppleNotification.PlatformType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property PlatformType As String" />
      <MemberSignature Language="F#" Value="member this.PlatformType : string" Usage="Microsoft.Azure.NotificationHubs.AppleNotification.PlatformType" />
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
            <span data-ttu-id="d50a2-117">プラットフォームの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="d50a2-117">Gets the type of the platform.</span></span>
            </summary>
        <value>
            <span data-ttu-id="d50a2-118">プラットフォームの種類。</span><span class="sxs-lookup"><span data-stu-id="d50a2-118">The type of the platform.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>