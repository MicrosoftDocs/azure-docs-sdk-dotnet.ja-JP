<Type Name="Notification" FullName="Microsoft.Azure.NotificationHubs.Notification">
  <TypeSignature Language="C#" Value="public abstract class Notification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Notification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Notification" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Notification" />
  <TypeSignature Language="F#" Value="type Notification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="6897f-101">対象のタグを含む汎用的な通知ハブの通知を表す抽象クラスです。</span><span class="sxs-lookup"><span data-stu-id="6897f-101">Abstract class representing a generic notification hub notification, including the target tag.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Notification (System.Collections.Generic.IDictionary&lt;string,string&gt; additionalHeaders, string tag);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; additionalHeaders, string tag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Notification.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (additionalHeaders As IDictionary(Of String, String), tag As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Notification : System.Collections.Generic.IDictionary&lt;string, string&gt; * string -&gt; Microsoft.Azure.NotificationHubs.Notification" Usage="new Microsoft.Azure.NotificationHubs.Notification (additionalHeaders, tag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="tag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="additionalHeaders"><span data-ttu-id="6897f-102">追加ヘッダーです。</span><span class="sxs-lookup"><span data-stu-id="6897f-102">The additional headers.</span></span></param>
        <param name="tag"><span data-ttu-id="6897f-103">通知タグです。</span><span class="sxs-lookup"><span data-stu-id="6897f-103">The notification tag.</span></span></param>
        <summary><span data-ttu-id="6897f-104"><see cref="T:Microsoft.Azure.NotificationHubs.Notification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6897f-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Notification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddOrUpdateHeader">
      <MemberSignature Language="C#" Value="protected void AddOrUpdateHeader (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void AddOrUpdateHeader(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Notification.AddOrUpdateHeader(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub AddOrUpdateHeader (key As String, value As String)" />
      <MemberSignature Language="F#" Value="member this.AddOrUpdateHeader : string * string -&gt; unit" Usage="notification.AddOrUpdateHeader (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="6897f-105">ヘッダーのキー。</span><span class="sxs-lookup"><span data-stu-id="6897f-105">The header key.</span></span></param>
        <param name="value"><span data-ttu-id="6897f-106">ヘッダーの値です。</span><span class="sxs-lookup"><span data-stu-id="6897f-106">The value of the header.</span></span></param>
        <summary><span data-ttu-id="6897f-107">追加または指定されたキーと値を持つヘッダーを更新します。</span><span class="sxs-lookup"><span data-stu-id="6897f-107">Add or updates a header with a given key and value.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public string Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Notification.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As String" />
      <MemberSignature Language="F#" Value="member this.Body : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Notification.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6897f-108">取得または通知の本文を設定します。</span><span class="sxs-lookup"><span data-stu-id="6897f-108">Gets or sets the body of the notification.</span></span></summary>
        <value><span data-ttu-id="6897f-109">通知の本文。</span><span class="sxs-lookup"><span data-stu-id="6897f-109">The body of the notification.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Notification.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Notification.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6897f-110">取得または通知のコンテンツの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="6897f-110">Gets or sets the content type of the notification.</span></span></summary>
        <value><span data-ttu-id="6897f-111">通知のコンテンツの種類。</span><span class="sxs-lookup"><span data-stu-id="6897f-111">The content type of the notification.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.Dictionary&lt;string,string&gt; Headers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.Dictionary`2&lt;string, string&gt; Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Notification.Headers" />
      <MemberSignature Language="VB.NET" Value="Public Property Headers As Dictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Headers : System.Collections.Generic.Dictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.Notification.Headers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6897f-112">取得または通知に関連付けられたヘッダーの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="6897f-112">Gets or sets a list of headers associated with the notification.</span></span></summary>
        <value><span data-ttu-id="6897f-113">通知に関連付けられたヘッダーの一覧。</span><span class="sxs-lookup"><span data-stu-id="6897f-113">A list of headers associated with the notification.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidateAndPopulateHeaders">
      <MemberSignature Language="C#" Value="protected abstract void OnValidateAndPopulateHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnValidateAndPopulateHeaders() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Notification.OnValidateAndPopulateHeaders" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnValidateAndPopulateHeaders ()" />
      <MemberSignature Language="F#" Value="abstract member OnValidateAndPopulateHeaders : unit -&gt; unit" Usage="notification.OnValidateAndPopulateHeaders " />
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
        <summary><span data-ttu-id="6897f-114">検証し、ヘッダーを追加します。</span><span class="sxs-lookup"><span data-stu-id="6897f-114">Validate and populates the headers.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformType">
      <MemberSignature Language="C#" Value="protected abstract string PlatformType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PlatformType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Notification.PlatformType" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride ReadOnly Property PlatformType As String" />
      <MemberSignature Language="F#" Value="member this.PlatformType : string" Usage="Microsoft.Azure.NotificationHubs.Notification.PlatformType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6897f-115">通知のプラットフォームの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="6897f-115">Gets the platform type of the notification.</span></span></summary>
        <value><span data-ttu-id="6897f-116">通知のプラットフォームの種類。</span><span class="sxs-lookup"><span data-stu-id="6897f-116">The platform type of the notification.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tag">
      <MemberSignature Language="C#" Value="public string Tag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Notification.Tag" />
      <MemberSignature Language="VB.NET" Value="Public Property Tag As String" />
      <MemberSignature Language="F#" Value="member this.Tag : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Notification.Tag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This property is obsolete.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6897f-117">取得または通知タグを設定します。</span><span class="sxs-lookup"><span data-stu-id="6897f-117">Gets or sets the notification tag.</span></span></summary>
        <value><span data-ttu-id="6897f-118">通知タグです。</span><span class="sxs-lookup"><span data-stu-id="6897f-118">The notification tag.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>