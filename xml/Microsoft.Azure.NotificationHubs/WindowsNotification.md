<Type Name="WindowsNotification" FullName="Microsoft.Azure.NotificationHubs.WindowsNotification">
  <TypeSignature Language="C#" Value="public sealed class WindowsNotification : Microsoft.Azure.NotificationHubs.Notification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit WindowsNotification extends Microsoft.Azure.NotificationHubs.Notification" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.WindowsNotification" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class WindowsNotification&#xA;Inherits Notification" />
  <TypeSignature Language="F#" Value="type WindowsNotification = class&#xA;    inherit Notification" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Notification</BaseTypeName>
  </Base>
  <Interfaces></Interfaces>
  <Docs>
    <summary><span data-ttu-id="6b377-101">Windows の通知を表します。</span><span class="sxs-lookup"><span data-stu-id="6b377-101">Represents the Windows notification.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsNotification (string payLoad);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string payLoad) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsNotification.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (payLoad As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.WindowsNotification : string -&gt; Microsoft.Azure.NotificationHubs.WindowsNotification" Usage="new Microsoft.Azure.NotificationHubs.WindowsNotification payLoad" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="payLoad" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="payLoad"><span data-ttu-id="6b377-102">ペイロード。</span><span class="sxs-lookup"><span data-stu-id="6b377-102">The payload.</span></span></param>
        <summary><span data-ttu-id="6b377-103"><see cref="T:Microsoft.Azure.NotificationHubs.WindowsNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6b377-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.WindowsNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsNotification (System.Xml.XmlDocument payLoad);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Xml.XmlDocument payLoad) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsNotification.#ctor(System.Xml.XmlDocument)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (payLoad As XmlDocument)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.WindowsNotification : System.Xml.XmlDocument -&gt; Microsoft.Azure.NotificationHubs.WindowsNotification" Usage="new Microsoft.Azure.NotificationHubs.WindowsNotification payLoad" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="payLoad" Type="System.Xml.XmlDocument" />
      </Parameters>
      <Docs>
        <param name="payLoad"><span data-ttu-id="6b377-104">ペイロード。</span><span class="sxs-lookup"><span data-stu-id="6b377-104">The payload.</span></span></param>
        <summary><span data-ttu-id="6b377-105"><see cref="T:Microsoft.Azure.NotificationHubs.WindowsNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6b377-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.WindowsNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsNotification (string payLoad, System.Collections.Generic.IDictionary&lt;string,string&gt; wnsHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string payLoad, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; wnsHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsNotification.#ctor(System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (payLoad As String, wnsHeaders As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.WindowsNotification : string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.NotificationHubs.WindowsNotification" Usage="new Microsoft.Azure.NotificationHubs.WindowsNotification (payLoad, wnsHeaders)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="payLoad" Type="System.String" />
        <Parameter Name="wnsHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="payLoad"><span data-ttu-id="6b377-106">ペイロード。</span><span class="sxs-lookup"><span data-stu-id="6b377-106">The payload.</span></span></param>
        <param name="wnsHeaders"><span data-ttu-id="6b377-107">WNS ヘッダーの一覧。</span><span class="sxs-lookup"><span data-stu-id="6b377-107">A list of WNS headers.</span></span></param>
        <summary><span data-ttu-id="6b377-108"><see cref="T:Microsoft.Azure.NotificationHubs.WindowsNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6b377-108">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.WindowsNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsNotification (string payLoad, string tag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string payLoad, string tag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsNotification.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (payLoad As String, tag As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.WindowsNotification : string * string -&gt; Microsoft.Azure.NotificationHubs.WindowsNotification" Usage="new Microsoft.Azure.NotificationHubs.WindowsNotification (payLoad, tag)" />
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
        <param name="payLoad"><span data-ttu-id="6b377-109">ペイロード。</span><span class="sxs-lookup"><span data-stu-id="6b377-109">The payload.</span></span></param>
        <param name="tag"><span data-ttu-id="6b377-110">通知タグです。</span><span class="sxs-lookup"><span data-stu-id="6b377-110">The notification tag.</span></span></param>
        <summary><span data-ttu-id="6b377-111"><see cref="T:Microsoft.Azure.NotificationHubs.WindowsNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6b377-111">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.WindowsNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsNotification (System.Xml.XmlDocument payLoad, System.Collections.Generic.IDictionary&lt;string,string&gt; wnsHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Xml.XmlDocument payLoad, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; wnsHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsNotification.#ctor(System.Xml.XmlDocument,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (payLoad As XmlDocument, wnsHeaders As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.WindowsNotification : System.Xml.XmlDocument * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.NotificationHubs.WindowsNotification" Usage="new Microsoft.Azure.NotificationHubs.WindowsNotification (payLoad, wnsHeaders)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="payLoad" Type="System.Xml.XmlDocument" />
        <Parameter Name="wnsHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="payLoad"><span data-ttu-id="6b377-112">ペイロード。</span><span class="sxs-lookup"><span data-stu-id="6b377-112">The payload.</span></span></param>
        <param name="wnsHeaders"><span data-ttu-id="6b377-113">WNS ヘッダーの一覧。</span><span class="sxs-lookup"><span data-stu-id="6b377-113">A list of WNS headers.</span></span></param>
        <summary><span data-ttu-id="6b377-114"><see cref="T:Microsoft.Azure.NotificationHubs.WindowsNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6b377-114">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.WindowsNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsNotification (System.Xml.XmlDocument payLoad, string tag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Xml.XmlDocument payLoad, string tag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsNotification.#ctor(System.Xml.XmlDocument,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (payLoad As XmlDocument, tag As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.WindowsNotification : System.Xml.XmlDocument * string -&gt; Microsoft.Azure.NotificationHubs.WindowsNotification" Usage="new Microsoft.Azure.NotificationHubs.WindowsNotification (payLoad, tag)" />
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
        <param name="payLoad"><span data-ttu-id="6b377-115">ペイロード。</span><span class="sxs-lookup"><span data-stu-id="6b377-115">The payload.</span></span></param>
        <param name="tag"><span data-ttu-id="6b377-116">通知タグです。</span><span class="sxs-lookup"><span data-stu-id="6b377-116">The notification tag.</span></span></param>
        <summary><span data-ttu-id="6b377-117"><see cref="T:Microsoft.Azure.NotificationHubs.WindowsNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6b377-117">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.WindowsNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsNotification (string payLoad, System.Collections.Generic.IDictionary&lt;string,string&gt; wnsHeaders, string tag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string payLoad, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; wnsHeaders, string tag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsNotification.#ctor(System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (payLoad As String, wnsHeaders As IDictionary(Of String, String), tag As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.WindowsNotification : string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string -&gt; Microsoft.Azure.NotificationHubs.WindowsNotification" Usage="new Microsoft.Azure.NotificationHubs.WindowsNotification (payLoad, wnsHeaders, tag)" />
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
        <Parameter Name="wnsHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="tag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="payLoad"><span data-ttu-id="6b377-118">ペイロード。</span><span class="sxs-lookup"><span data-stu-id="6b377-118">The payload.</span></span></param>
        <param name="wnsHeaders"><span data-ttu-id="6b377-119">WNS ヘッダーの一覧。</span><span class="sxs-lookup"><span data-stu-id="6b377-119">A list of WNS headers.</span></span></param>
        <param name="tag"><span data-ttu-id="6b377-120">通知タグです。</span><span class="sxs-lookup"><span data-stu-id="6b377-120">The notification tag.</span></span></param>
        <summary><span data-ttu-id="6b377-121"><see cref="T:Microsoft.Azure.NotificationHubs.WindowsNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6b377-121">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.WindowsNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsNotification (System.Xml.XmlDocument payLoad, System.Collections.Generic.IDictionary&lt;string,string&gt; wnsHeaders, string tag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Xml.XmlDocument payLoad, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; wnsHeaders, string tag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsNotification.#ctor(System.Xml.XmlDocument,System.Collections.Generic.IDictionary{System.String,System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (payLoad As XmlDocument, wnsHeaders As IDictionary(Of String, String), tag As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.WindowsNotification : System.Xml.XmlDocument * System.Collections.Generic.IDictionary&lt;string, string&gt; * string -&gt; Microsoft.Azure.NotificationHubs.WindowsNotification" Usage="new Microsoft.Azure.NotificationHubs.WindowsNotification (payLoad, wnsHeaders, tag)" />
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
        <Parameter Name="wnsHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="tag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="payLoad"><span data-ttu-id="6b377-122">ペイロード。</span><span class="sxs-lookup"><span data-stu-id="6b377-122">The payload.</span></span></param>
        <param name="wnsHeaders"><span data-ttu-id="6b377-123">WNS ヘッダーの一覧。</span><span class="sxs-lookup"><span data-stu-id="6b377-123">A list of WNS headers.</span></span></param>
        <param name="tag"><span data-ttu-id="6b377-124">通知タグです。</span><span class="sxs-lookup"><span data-stu-id="6b377-124">The notification tag.</span></span></param>
        <summary><span data-ttu-id="6b377-125"><see cref="T:Microsoft.Azure.NotificationHubs.WindowsNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6b377-125">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.WindowsNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidateAndPopulateHeaders">
      <MemberSignature Language="C#" Value="protected override void OnValidateAndPopulateHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidateAndPopulateHeaders() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsNotification.OnValidateAndPopulateHeaders" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidateAndPopulateHeaders ()" />
      <MemberSignature Language="F#" Value="override this.OnValidateAndPopulateHeaders : unit -&gt; unit" Usage="windowsNotification.OnValidateAndPopulateHeaders " />
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
            <span data-ttu-id="6b377-126">検証し、ヘッダーを追加します。</span><span class="sxs-lookup"><span data-stu-id="6b377-126">Validate and populates the headers.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformType">
      <MemberSignature Language="C#" Value="protected override string PlatformType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PlatformType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.WindowsNotification.PlatformType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property PlatformType As String" />
      <MemberSignature Language="F#" Value="member this.PlatformType : string" Usage="Microsoft.Azure.NotificationHubs.WindowsNotification.PlatformType" />
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
            <span data-ttu-id="6b377-127">プラットフォームの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="6b377-127">Gets the type of the platform.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6b377-128">プラットフォームの種類。</span><span class="sxs-lookup"><span data-stu-id="6b377-128">The type of the platform.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>