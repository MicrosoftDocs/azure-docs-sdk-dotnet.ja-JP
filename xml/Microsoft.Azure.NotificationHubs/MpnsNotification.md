<Type Name="MpnsNotification" FullName="Microsoft.Azure.NotificationHubs.MpnsNotification">
  <TypeSignature Language="C#" Value="public sealed class MpnsNotification : Microsoft.Azure.NotificationHubs.Notification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MpnsNotification extends Microsoft.Azure.NotificationHubs.Notification" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.MpnsNotification" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MpnsNotification&#xA;Inherits Notification" />
  <TypeSignature Language="F#" Value="type MpnsNotification = class&#xA;    inherit Notification" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Notification</BaseTypeName>
  </Base>
  <Interfaces></Interfaces>
  <Docs>
    <summary><span data-ttu-id="8687e-101">Microsoft プッシュ通知サービス (MPNS) の通知を提供します。</span><span class="sxs-lookup"><span data-stu-id="8687e-101">Provides notification for Microsoft Push Notification Service (MPNS).</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsNotification (string payLoad);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string payLoad) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsNotification.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (payLoad As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.MpnsNotification : string -&gt; Microsoft.Azure.NotificationHubs.MpnsNotification" Usage="new Microsoft.Azure.NotificationHubs.MpnsNotification payLoad" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="payLoad" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="payLoad"><span data-ttu-id="8687e-102">ペイロード。</span><span class="sxs-lookup"><span data-stu-id="8687e-102">The payload.</span></span></param>
        <summary><span data-ttu-id="8687e-103"><see cref="T:Microsoft.Azure.NotificationHubs.MpnsNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8687e-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.MpnsNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsNotification (System.Xml.XmlDocument payLoad);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Xml.XmlDocument payLoad) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsNotification.#ctor(System.Xml.XmlDocument)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (payLoad As XmlDocument)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.MpnsNotification : System.Xml.XmlDocument -&gt; Microsoft.Azure.NotificationHubs.MpnsNotification" Usage="new Microsoft.Azure.NotificationHubs.MpnsNotification payLoad" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="payLoad" Type="System.Xml.XmlDocument" />
      </Parameters>
      <Docs>
        <param name="payLoad"><span data-ttu-id="8687e-104">ペイロード。</span><span class="sxs-lookup"><span data-stu-id="8687e-104">The payload.</span></span></param>
        <summary><span data-ttu-id="8687e-105"><see cref="T:Microsoft.Azure.NotificationHubs.MpnsNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8687e-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.MpnsNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsNotification (string payLoad, System.Collections.Generic.IDictionary&lt;string,string&gt; mpnsHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string payLoad, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; mpnsHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsNotification.#ctor(System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (payLoad As String, mpnsHeaders As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.MpnsNotification : string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.NotificationHubs.MpnsNotification" Usage="new Microsoft.Azure.NotificationHubs.MpnsNotification (payLoad, mpnsHeaders)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="payLoad" Type="System.String" />
        <Parameter Name="mpnsHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="payLoad"><span data-ttu-id="8687e-106">ペイロード。</span><span class="sxs-lookup"><span data-stu-id="8687e-106">The payload.</span></span></param>
        <param name="mpnsHeaders"><span data-ttu-id="8687e-107">MPNS ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="8687e-107">The MPNS headers.</span></span></param>
        <summary><span data-ttu-id="8687e-108"><see cref="T:Microsoft.Azure.NotificationHubs.MpnsNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8687e-108">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.MpnsNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="8687e-109">ペイロード</span><span class="sxs-lookup"><span data-stu-id="8687e-109">payLoad</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsNotification (string payLoad, string tag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string payLoad, string tag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsNotification.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (payLoad As String, tag As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.MpnsNotification : string * string -&gt; Microsoft.Azure.NotificationHubs.MpnsNotification" Usage="new Microsoft.Azure.NotificationHubs.MpnsNotification (payLoad, tag)" />
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
        <Parameter Name="payLoad" Type="System.String" />
        <Parameter Name="tag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="payLoad"><span data-ttu-id="8687e-110">ペイロード。</span><span class="sxs-lookup"><span data-stu-id="8687e-110">The payload.</span></span></param>
        <param name="tag"><span data-ttu-id="8687e-111">通知タグです。</span><span class="sxs-lookup"><span data-stu-id="8687e-111">The notification tag.</span></span></param>
        <summary><span data-ttu-id="8687e-112"><see cref="T:Microsoft.Azure.NotificationHubs.MpnsNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8687e-112">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.MpnsNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsNotification (System.Xml.XmlDocument payLoad, System.Collections.Generic.IDictionary&lt;string,string&gt; mpnsHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Xml.XmlDocument payLoad, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; mpnsHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsNotification.#ctor(System.Xml.XmlDocument,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (payLoad As XmlDocument, mpnsHeaders As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.MpnsNotification : System.Xml.XmlDocument * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.NotificationHubs.MpnsNotification" Usage="new Microsoft.Azure.NotificationHubs.MpnsNotification (payLoad, mpnsHeaders)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="payLoad" Type="System.Xml.XmlDocument" />
        <Parameter Name="mpnsHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="payLoad"><span data-ttu-id="8687e-113">ペイロード。</span><span class="sxs-lookup"><span data-stu-id="8687e-113">The payload.</span></span></param>
        <param name="mpnsHeaders"><span data-ttu-id="8687e-114">MPNS ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="8687e-114">The MPNS headers.</span></span></param>
        <summary><span data-ttu-id="8687e-115"><see cref="T:Microsoft.Azure.NotificationHubs.MpnsNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8687e-115">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.MpnsNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsNotification (System.Xml.XmlDocument payLoad, string tag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Xml.XmlDocument payLoad, string tag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsNotification.#ctor(System.Xml.XmlDocument,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (payLoad As XmlDocument, tag As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.MpnsNotification : System.Xml.XmlDocument * string -&gt; Microsoft.Azure.NotificationHubs.MpnsNotification" Usage="new Microsoft.Azure.NotificationHubs.MpnsNotification (payLoad, tag)" />
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
        <Parameter Name="payLoad" Type="System.Xml.XmlDocument" />
        <Parameter Name="tag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="payLoad"><span data-ttu-id="8687e-116">ペイロード。</span><span class="sxs-lookup"><span data-stu-id="8687e-116">The payload.</span></span></param>
        <param name="tag"><span data-ttu-id="8687e-117">通知タグです。</span><span class="sxs-lookup"><span data-stu-id="8687e-117">The notification tag.</span></span></param>
        <summary><span data-ttu-id="8687e-118"><see cref="T:Microsoft.Azure.NotificationHubs.MpnsNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8687e-118">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.MpnsNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsNotification (string payLoad, System.Collections.Generic.IDictionary&lt;string,string&gt; mpnsHeaders, string tag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string payLoad, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; mpnsHeaders, string tag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsNotification.#ctor(System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (payLoad As String, mpnsHeaders As IDictionary(Of String, String), tag As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.MpnsNotification : string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string -&gt; Microsoft.Azure.NotificationHubs.MpnsNotification" Usage="new Microsoft.Azure.NotificationHubs.MpnsNotification (payLoad, mpnsHeaders, tag)" />
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
        <Parameter Name="payLoad" Type="System.String" />
        <Parameter Name="mpnsHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="tag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="payLoad"><span data-ttu-id="8687e-119">ペイロード。</span><span class="sxs-lookup"><span data-stu-id="8687e-119">The payload.</span></span></param>
        <param name="mpnsHeaders"><span data-ttu-id="8687e-120">MPNS ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="8687e-120">The MPNS headers.</span></span></param>
        <param name="tag"><span data-ttu-id="8687e-121">通知タグです。</span><span class="sxs-lookup"><span data-stu-id="8687e-121">The notification tag.</span></span></param>
        <summary><span data-ttu-id="8687e-122"><see cref="T:Microsoft.Azure.NotificationHubs.MpnsNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8687e-122">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.MpnsNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="8687e-123">ペイロードが null または空の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8687e-123">Thrown if the payload is null or empty</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsNotification (System.Xml.XmlDocument payLoad, System.Collections.Generic.IDictionary&lt;string,string&gt; mpnsHeaders, string tag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Xml.XmlDocument payLoad, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; mpnsHeaders, string tag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsNotification.#ctor(System.Xml.XmlDocument,System.Collections.Generic.IDictionary{System.String,System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (payLoad As XmlDocument, mpnsHeaders As IDictionary(Of String, String), tag As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.MpnsNotification : System.Xml.XmlDocument * System.Collections.Generic.IDictionary&lt;string, string&gt; * string -&gt; Microsoft.Azure.NotificationHubs.MpnsNotification" Usage="new Microsoft.Azure.NotificationHubs.MpnsNotification (payLoad, mpnsHeaders, tag)" />
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
        <Parameter Name="payLoad" Type="System.Xml.XmlDocument" />
        <Parameter Name="mpnsHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="tag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="payLoad"><span data-ttu-id="8687e-124">ペイロード。</span><span class="sxs-lookup"><span data-stu-id="8687e-124">The payload.</span></span></param>
        <param name="mpnsHeaders"><span data-ttu-id="8687e-125">MPNS ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="8687e-125">The MPNS headers.</span></span></param>
        <param name="tag"><span data-ttu-id="8687e-126">通知タグです。</span><span class="sxs-lookup"><span data-stu-id="8687e-126">The notification tag.</span></span></param>
        <summary><span data-ttu-id="8687e-127"><see cref="T:Microsoft.Azure.NotificationHubs.MpnsNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8687e-127">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.MpnsNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidateAndPopulateHeaders">
      <MemberSignature Language="C#" Value="protected override void OnValidateAndPopulateHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidateAndPopulateHeaders() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.MpnsNotification.OnValidateAndPopulateHeaders" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidateAndPopulateHeaders ()" />
      <MemberSignature Language="F#" Value="override this.OnValidateAndPopulateHeaders : unit -&gt; unit" Usage="mpnsNotification.OnValidateAndPopulateHeaders " />
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
            <span data-ttu-id="8687e-128">検証し、ヘッダーを追加します。</span><span class="sxs-lookup"><span data-stu-id="8687e-128">Validate and populates the headers.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformType">
      <MemberSignature Language="C#" Value="protected override string PlatformType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PlatformType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.MpnsNotification.PlatformType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property PlatformType As String" />
      <MemberSignature Language="F#" Value="member this.PlatformType : string" Usage="Microsoft.Azure.NotificationHubs.MpnsNotification.PlatformType" />
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
            <span data-ttu-id="8687e-129">プラットフォームの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="8687e-129">Gets the type of the platform.</span></span>
            </summary>
        <value>
            <span data-ttu-id="8687e-130">プラットフォームの種類。</span><span class="sxs-lookup"><span data-stu-id="8687e-130">The type of the platform.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>