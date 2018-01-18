<Type Name="NotificationHubClient" FullName="Microsoft.Azure.NotificationHubs.NotificationHubClient">
  <TypeSignature Language="C#" Value="public class NotificationHubClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NotificationHubClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />
  <TypeSignature Language="VB.NET" Value="Public Class NotificationHubClient" />
  <TypeSignature Language="F#" Value="type NotificationHubClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="2289c-101">通知ハブのクライアントを表します。</span><span class="sxs-lookup"><span data-stu-id="2289c-101">Represents a notification hub client.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelNotificationAsync (string scheduledNotificationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelNotificationAsync(string scheduledNotificationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CancelNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelNotificationAsync (scheduledNotificationId As String) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelNotificationAsync : string -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.CancelNotificationAsync scheduledNotificationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scheduledNotificationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scheduledNotificationId"><span data-ttu-id="2289c-102">定期的な通知の識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-102">The scheduled notification identifier.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-103">通知を非同期的に取り消します。</span><span class="sxs-lookup"><span data-stu-id="2289c-103">Cancels the notification asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="2289c-104">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-104">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAdmNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt; CreateAdmNativeRegistrationAsync (string admRegistrationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt; CreateAdmNativeRegistrationAsync(string admRegistrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAdmNativeRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAdmNativeRegistrationAsync (admRegistrationId As String) As Task(Of AdmRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAdmNativeRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt;" Usage="notificationHubClient.CreateAdmNativeRegistrationAsync admRegistrationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="admRegistrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="admRegistrationId"><span data-ttu-id="2289c-105">管理登録の識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-105">The administrative registration identifier.</span></span></param>
        <summary><span data-ttu-id="2289c-106">ネイティブの管理の登録を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-106">Asynchronously creates a native administrative registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-107">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2289c-107">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAdmNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt; CreateAdmNativeRegistrationAsync (string admRegistrationId, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt; CreateAdmNativeRegistrationAsync(string admRegistrationId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAdmNativeRegistrationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAdmNativeRegistrationAsync (admRegistrationId As String, tags As IEnumerable(Of String)) As Task(Of AdmRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAdmNativeRegistrationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt;" Usage="notificationHubClient.CreateAdmNativeRegistrationAsync (admRegistrationId, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="admRegistrationId" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="admRegistrationId"><span data-ttu-id="2289c-108">管理登録の識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-108">The administrative registration identifier.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-109">登録用のタグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-109">The tags for the registration.</span></span></param>
        <summary><span data-ttu-id="2289c-110">ネイティブの管理の登録を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-110">Asynchronously creates a native administrative registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-111">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2289c-111">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAdmTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt; CreateAdmTemplateRegistrationAsync (string admRegistrationId, string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt; CreateAdmTemplateRegistrationAsync(string admRegistrationId, string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAdmTemplateRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAdmTemplateRegistrationAsync (admRegistrationId As String, jsonPayload As String) As Task(Of AdmTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAdmTemplateRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateAdmTemplateRegistrationAsync (admRegistrationId, jsonPayload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="admRegistrationId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="admRegistrationId"><span data-ttu-id="2289c-112">管理登録の識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-112">The administrative registration identifier.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="2289c-113">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-113">The JSON payload.</span></span></param>
        <summary><span data-ttu-id="2289c-114">管理用テンプレート登録を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-114">Asynchronously creates an administrative template registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-115">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2289c-115">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAdmTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt; CreateAdmTemplateRegistrationAsync (string admRegistrationId, string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt; CreateAdmTemplateRegistrationAsync(string admRegistrationId, string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAdmTemplateRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAdmTemplateRegistrationAsync (admRegistrationId As String, jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of AdmTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAdmTemplateRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateAdmTemplateRegistrationAsync (admRegistrationId, jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="admRegistrationId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="admRegistrationId"><span data-ttu-id="2289c-116">管理登録の識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-116">The administrative registration identifier.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="2289c-117">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-117">The JSON payload.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-118">タグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-118">The tags.</span></span></param>
        <summary><span data-ttu-id="2289c-119">管理用テンプレート登録を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-119">Asynchronously creates an administrative template registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-120">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2289c-120">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAppleNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt; CreateAppleNativeRegistrationAsync (string deviceToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt; CreateAppleNativeRegistrationAsync(string deviceToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAppleNativeRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAppleNativeRegistrationAsync (deviceToken As String) As Task(Of AppleRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAppleNativeRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt;" Usage="notificationHubClient.CreateAppleNativeRegistrationAsync deviceToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceToken"><span data-ttu-id="2289c-121">デバイス トークンです。</span><span class="sxs-lookup"><span data-stu-id="2289c-121">The device token.</span></span></param>
        <summary><span data-ttu-id="2289c-122">Apple のネイティブ登録を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-122">Asynchronously creates an Apple native registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-123">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-123">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAppleNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt; CreateAppleNativeRegistrationAsync (string deviceToken, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt; CreateAppleNativeRegistrationAsync(string deviceToken, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAppleNativeRegistrationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAppleNativeRegistrationAsync (deviceToken As String, tags As IEnumerable(Of String)) As Task(Of AppleRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAppleNativeRegistrationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt;" Usage="notificationHubClient.CreateAppleNativeRegistrationAsync (deviceToken, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceToken" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="deviceToken"><span data-ttu-id="2289c-124">デバイス トークンです。</span><span class="sxs-lookup"><span data-stu-id="2289c-124">The device token.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-125">タグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-125">The tags.</span></span></param>
        <summary><span data-ttu-id="2289c-126">Apple のネイティブ登録を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-126">Asynchronously creates an Apple native registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-127">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-127">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAppleTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt; CreateAppleTemplateRegistrationAsync (string deviceToken, string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt; CreateAppleTemplateRegistrationAsync(string deviceToken, string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAppleTemplateRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAppleTemplateRegistrationAsync (deviceToken As String, jsonPayload As String) As Task(Of AppleTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAppleTemplateRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateAppleTemplateRegistrationAsync (deviceToken, jsonPayload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceToken" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceToken"><span data-ttu-id="2289c-128">デバイス トークンです。</span><span class="sxs-lookup"><span data-stu-id="2289c-128">The device token.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="2289c-129">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-129">The JSON payload.</span></span></param>
        <summary><span data-ttu-id="2289c-130">非同期的に、Apple のテンプレート登録を作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-130">Asynchronously creates an Apple template registration.</span></span> <span data-ttu-id="2289c-131">作成時に追加のプロパティを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="2289c-131">To specify additional properties at creation, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" /> method.</span></span></summary>
        <returns><span data-ttu-id="2289c-132">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-132">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAppleTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt; CreateAppleTemplateRegistrationAsync (string deviceToken, string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt; CreateAppleTemplateRegistrationAsync(string deviceToken, string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAppleTemplateRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAppleTemplateRegistrationAsync (deviceToken As String, jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of AppleTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAppleTemplateRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateAppleTemplateRegistrationAsync (deviceToken, jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceToken" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="deviceToken"><span data-ttu-id="2289c-133">デバイス トークンです。</span><span class="sxs-lookup"><span data-stu-id="2289c-133">The device token.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="2289c-134">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-134">The JSON payload.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-135">タグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-135">The tags.</span></span></param>
        <summary><span data-ttu-id="2289c-136">非同期的に、Apple のテンプレート登録を作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-136">Asynchronously creates an Apple template registration.</span></span> <span data-ttu-id="2289c-137">作成時に追加のプロパティを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="2289c-137">To specify additional properties at creation, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" /> method.</span></span></summary>
        <returns><span data-ttu-id="2289c-138">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-138">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBaiduNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt; CreateBaiduNativeRegistrationAsync (string userId, string channelId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt; CreateBaiduNativeRegistrationAsync(string userId, string channelId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateBaiduNativeRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBaiduNativeRegistrationAsync (userId As String, channelId As String) As Task(Of BaiduRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateBaiduNativeRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt;" Usage="notificationHubClient.CreateBaiduNativeRegistrationAsync (userId, channelId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="channelId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="userId"><span data-ttu-id="2289c-139">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-139">The user identifier.</span></span></param>
        <param name="channelId"><span data-ttu-id="2289c-140">チャネルの識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-140">The channel identifier.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-141">非同期的に baidu ネイティブ登録を作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-141">Creates the baidu native registration asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="2289c-142">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-142">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBaiduNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt; CreateBaiduNativeRegistrationAsync (string userId, string channelId, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt; CreateBaiduNativeRegistrationAsync(string userId, string channelId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateBaiduNativeRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBaiduNativeRegistrationAsync (userId As String, channelId As String, tags As IEnumerable(Of String)) As Task(Of BaiduRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateBaiduNativeRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt;" Usage="notificationHubClient.CreateBaiduNativeRegistrationAsync (userId, channelId, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="channelId" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="userId"><span data-ttu-id="2289c-143">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-143">The user identifier.</span></span></param>
        <param name="channelId"><span data-ttu-id="2289c-144">チャネルの識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-144">The channel identifier.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-145">タグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-145">The tags.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-146">非同期的に baidu ネイティブ登録を作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-146">Creates the baidu native registration asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="2289c-147">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-147">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBaiduTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt; CreateBaiduTemplateRegistrationAsync (string userId, string channelId, string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt; CreateBaiduTemplateRegistrationAsync(string userId, string channelId, string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateBaiduTemplateRegistrationAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBaiduTemplateRegistrationAsync (userId As String, channelId As String, jsonPayload As String) As Task(Of BaiduTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateBaiduTemplateRegistrationAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateBaiduTemplateRegistrationAsync (userId, channelId, jsonPayload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="channelId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="userId"><span data-ttu-id="2289c-148">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-148">The user identifier.</span></span></param>
        <param name="channelId"><span data-ttu-id="2289c-149">チャネルの識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-149">The channel identifier.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="2289c-150">Json ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-150">The json payload.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-151">非同期的に baidu テンプレート登録を作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-151">Creates the baidu template registration asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="2289c-152">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-152">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBaiduTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt; CreateBaiduTemplateRegistrationAsync (string userId, string channelId, string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt; CreateBaiduTemplateRegistrationAsync(string userId, string channelId, string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateBaiduTemplateRegistrationAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBaiduTemplateRegistrationAsync (userId As String, channelId As String, jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of BaiduTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateBaiduTemplateRegistrationAsync : string * string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateBaiduTemplateRegistrationAsync (userId, channelId, jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="channelId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="userId"><span data-ttu-id="2289c-153">ユーザーの識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-153">The user identifier.</span></span></param>
        <param name="channelId"><span data-ttu-id="2289c-154">チャネルの識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-154">The channel identifier.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="2289c-155">Json ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-155">The json payload.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-156">タグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-156">The tags.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-157">非同期的に baidu テンプレート登録を作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-157">Creates the baidu template registration asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="2289c-158">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-158">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateClientFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.NotificationHubClient CreateClientFromConnectionString (string connectionString, string notificationHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.NotificationHubClient CreateClientFromConnectionString(string connectionString, string notificationHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateClientFromConnectionString(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateClientFromConnectionString (connectionString As String, notificationHubPath As String) As NotificationHubClient" />
      <MemberSignature Language="F#" Value="static member CreateClientFromConnectionString : string * string -&gt; Microsoft.Azure.NotificationHubs.NotificationHubClient" Usage="Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateClientFromConnectionString (connectionString, notificationHubPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="notificationHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="2289c-159">接続文字列。</span><span class="sxs-lookup"><span data-stu-id="2289c-159">The connection string.</span></span></param>
        <param name="notificationHubPath"><span data-ttu-id="2289c-160">通知ハブのパス。</span><span class="sxs-lookup"><span data-stu-id="2289c-160">The notification hub path.</span></span></param>
        <summary><span data-ttu-id="2289c-161">接続文字列からクライアントを作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-161">Creates a client from connection string.</span></span></summary>
        <returns><span data-ttu-id="2289c-162">作成された <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />。</span><span class="sxs-lookup"><span data-stu-id="2289c-162">The created <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateClientFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.NotificationHubClient CreateClientFromConnectionString (string connectionString, string notificationHubPath, bool enableTestSend);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.NotificationHubClient CreateClientFromConnectionString(string connectionString, string notificationHubPath, bool enableTestSend) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateClientFromConnectionString(System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateClientFromConnectionString (connectionString As String, notificationHubPath As String, enableTestSend As Boolean) As NotificationHubClient" />
      <MemberSignature Language="F#" Value="static member CreateClientFromConnectionString : string * string * bool -&gt; Microsoft.Azure.NotificationHubs.NotificationHubClient" Usage="Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateClientFromConnectionString (connectionString, notificationHubPath, enableTestSend)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="notificationHubPath" Type="System.String" />
        <Parameter Name="enableTestSend" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="2289c-163">接続文字列。</span><span class="sxs-lookup"><span data-stu-id="2289c-163">The connection string.</span></span></param>
        <param name="notificationHubPath"><span data-ttu-id="2289c-164">通知ハブのパス。</span><span class="sxs-lookup"><span data-stu-id="2289c-164">The notification hub path.</span></span></param>
        <param name="enableTestSend"><span data-ttu-id="2289c-165">テスト送信; を有効にする場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="2289c-165">true to enable test send; otherwise, false.</span></span></param>
        <summary><span data-ttu-id="2289c-166">接続文字列からクライアントを作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-166">Creates a client from connection string.</span></span></summary>
        <returns><span data-ttu-id="2289c-167">作成された <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />。</span><span class="sxs-lookup"><span data-stu-id="2289c-167">The created <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateGcmNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt; CreateGcmNativeRegistrationAsync (string gcmRegistrationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt; CreateGcmNativeRegistrationAsync(string gcmRegistrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateGcmNativeRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateGcmNativeRegistrationAsync (gcmRegistrationId As String) As Task(Of GcmRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateGcmNativeRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt;" Usage="notificationHubClient.CreateGcmNativeRegistrationAsync gcmRegistrationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="gcmRegistrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="gcmRegistrationId"><span data-ttu-id="2289c-168">GCM 登録 id。</span><span class="sxs-lookup"><span data-stu-id="2289c-168">The GCM registration ID.</span></span></param>
        <summary><span data-ttu-id="2289c-169">ネイティブの GCM 登録を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-169">Asynchronously creates GCM native registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-170">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-170">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateGcmNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt; CreateGcmNativeRegistrationAsync (string gcmRegistrationId, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt; CreateGcmNativeRegistrationAsync(string gcmRegistrationId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateGcmNativeRegistrationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateGcmNativeRegistrationAsync (gcmRegistrationId As String, tags As IEnumerable(Of String)) As Task(Of GcmRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateGcmNativeRegistrationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt;" Usage="notificationHubClient.CreateGcmNativeRegistrationAsync (gcmRegistrationId, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="gcmRegistrationId" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="gcmRegistrationId"><span data-ttu-id="2289c-171">GCM 登録 id。</span><span class="sxs-lookup"><span data-stu-id="2289c-171">The GCM registration ID.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-172">タグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-172">The tags.</span></span></param>
        <summary><span data-ttu-id="2289c-173">ネイティブの GCM 登録を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-173">Asynchronously creates GCM native registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-174">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-174">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateGcmTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt; CreateGcmTemplateRegistrationAsync (string gcmRegistrationId, string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt; CreateGcmTemplateRegistrationAsync(string gcmRegistrationId, string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateGcmTemplateRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateGcmTemplateRegistrationAsync (gcmRegistrationId As String, jsonPayload As String) As Task(Of GcmTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateGcmTemplateRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateGcmTemplateRegistrationAsync (gcmRegistrationId, jsonPayload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="gcmRegistrationId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="gcmRegistrationId"><span data-ttu-id="2289c-175">GCM 登録 id。</span><span class="sxs-lookup"><span data-stu-id="2289c-175">The GCM registration ID.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="2289c-176">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-176">The JSON payload.</span></span></param>
        <summary><span data-ttu-id="2289c-177">テンプレートの GCM 登録を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-177">Asynchronously creates GCM template registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-178">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-178">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateGcmTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt; CreateGcmTemplateRegistrationAsync (string gcmRegistrationId, string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt; CreateGcmTemplateRegistrationAsync(string gcmRegistrationId, string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateGcmTemplateRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateGcmTemplateRegistrationAsync (gcmRegistrationId As String, jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of GcmTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateGcmTemplateRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateGcmTemplateRegistrationAsync (gcmRegistrationId, jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="gcmRegistrationId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="gcmRegistrationId"><span data-ttu-id="2289c-179">GCM 登録 id。</span><span class="sxs-lookup"><span data-stu-id="2289c-179">The GCM registration ID.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="2289c-180">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-180">The JSON payload.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-181">タグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-181">The tags.</span></span></param>
        <summary><span data-ttu-id="2289c-182">テンプレートの GCM 登録を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-182">Asynchronously creates GCM template registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-183">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-183">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMpnsNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt; CreateMpnsNativeRegistrationAsync (string channelUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt; CreateMpnsNativeRegistrationAsync(string channelUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateMpnsNativeRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMpnsNativeRegistrationAsync (channelUri As String) As Task(Of MpnsRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateMpnsNativeRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt;" Usage="notificationHubClient.CreateMpnsNativeRegistrationAsync channelUri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="channelUri"><span data-ttu-id="2289c-184">チャネル URI です。</span><span class="sxs-lookup"><span data-stu-id="2289c-184">The channel URI.</span></span></param>
        <summary><span data-ttu-id="2289c-185">ネイティブの MPNS 登録を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-185">Asynchronously creates MPNS native registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-186">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-186">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMpnsNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt; CreateMpnsNativeRegistrationAsync (string channelUri, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt; CreateMpnsNativeRegistrationAsync(string channelUri, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateMpnsNativeRegistrationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMpnsNativeRegistrationAsync (channelUri As String, tags As IEnumerable(Of String)) As Task(Of MpnsRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateMpnsNativeRegistrationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt;" Usage="notificationHubClient.CreateMpnsNativeRegistrationAsync (channelUri, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="channelUri"><span data-ttu-id="2289c-187">チャネル URI です。</span><span class="sxs-lookup"><span data-stu-id="2289c-187">The channel URI.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-188">タグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-188">The tags.</span></span></param>
        <summary><span data-ttu-id="2289c-189">ネイティブの MPNS 登録を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-189">Asynchronously creates MPNS native registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-190">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-190">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMpnsTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt; CreateMpnsTemplateRegistrationAsync (string channelUri, string xmlTemplate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt; CreateMpnsTemplateRegistrationAsync(string channelUri, string xmlTemplate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateMpnsTemplateRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMpnsTemplateRegistrationAsync (channelUri As String, xmlTemplate As String) As Task(Of MpnsTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateMpnsTemplateRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateMpnsTemplateRegistrationAsync (channelUri, xmlTemplate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="xmlTemplate" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="channelUri"><span data-ttu-id="2289c-191">チャネル URI です。</span><span class="sxs-lookup"><span data-stu-id="2289c-191">The channel URI.</span></span></param>
        <param name="xmlTemplate"><span data-ttu-id="2289c-192">XML テンプレートです。</span><span class="sxs-lookup"><span data-stu-id="2289c-192">The XML template.</span></span></param>
        <summary><span data-ttu-id="2289c-193">テンプレートの MPNS 登録を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-193">Asynchronously creates MPNS template registration.</span></span> <span data-ttu-id="2289c-194">作成時に追加のプロパティを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="2289c-194">To specify additional properties at creation, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" /> method.</span></span></summary>
        <returns><span data-ttu-id="2289c-195">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-195">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMpnsTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt; CreateMpnsTemplateRegistrationAsync (string channelUri, string xmlTemplate, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt; CreateMpnsTemplateRegistrationAsync(string channelUri, string xmlTemplate, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateMpnsTemplateRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMpnsTemplateRegistrationAsync (channelUri As String, xmlTemplate As String, tags As IEnumerable(Of String)) As Task(Of MpnsTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateMpnsTemplateRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateMpnsTemplateRegistrationAsync (channelUri, xmlTemplate, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="xmlTemplate" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="channelUri"><span data-ttu-id="2289c-196">チャネル URI です。</span><span class="sxs-lookup"><span data-stu-id="2289c-196">The channel URI.</span></span></param>
        <param name="xmlTemplate"><span data-ttu-id="2289c-197">XML テンプレートです。</span><span class="sxs-lookup"><span data-stu-id="2289c-197">The XML template.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-198">タグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-198">The tags.</span></span></param>
        <summary><span data-ttu-id="2289c-199">テンプレートの MPNS 登録を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-199">Asynchronously creates MPNS template registration.</span></span> <span data-ttu-id="2289c-200">作成時に追加のプロパティを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="2289c-200">To specify additional properties at creation, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" /> method.</span></span></summary>
        <returns><span data-ttu-id="2289c-201">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-201">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateInstallation">
      <MemberSignature Language="C#" Value="public void CreateOrUpdateInstallation (Microsoft.Azure.NotificationHubs.Installation installation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CreateOrUpdateInstallation(class Microsoft.Azure.NotificationHubs.Installation installation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateOrUpdateInstallation(Microsoft.Azure.NotificationHubs.Installation)" />
      <MemberSignature Language="F#" Value="member this.CreateOrUpdateInstallation : Microsoft.Azure.NotificationHubs.Installation -&gt; unit" Usage="notificationHubClient.CreateOrUpdateInstallation installation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installation" Type="Microsoft.Azure.NotificationHubs.Installation" />
      </Parameters>
      <Docs>
        <param name="installation"><span data-ttu-id="2289c-202">デバイスのインストールのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2289c-202">The device installation object.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-203">作成するか、デバイスのインストールを更新します。</span><span class="sxs-lookup"><span data-stu-id="2289c-203">Creates or updates a device installation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateInstallationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateOrUpdateInstallationAsync (Microsoft.Azure.NotificationHubs.Installation installation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateOrUpdateInstallationAsync(class Microsoft.Azure.NotificationHubs.Installation installation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateOrUpdateInstallationAsync(Microsoft.Azure.NotificationHubs.Installation)" />
      <MemberSignature Language="F#" Value="member this.CreateOrUpdateInstallationAsync : Microsoft.Azure.NotificationHubs.Installation -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.CreateOrUpdateInstallationAsync installation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installation" Type="Microsoft.Azure.NotificationHubs.Installation" />
      </Parameters>
      <Docs>
        <param name="installation"><span data-ttu-id="2289c-204">デバイスのインストールのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2289c-204">The device installation object.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-205">作成するか、デバイスのインストールを非同期的に更新します。</span><span class="sxs-lookup"><span data-stu-id="2289c-205">Creates or updates a device installation asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="2289c-206">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-206">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="2289c-207">インストールのオブジェクトが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2289c-207">Thrown when the installation object is null</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="2289c-208">InstallationId を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2289c-208">InstallationId must be specified</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateRegistrationAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; CreateOrUpdateRegistrationAsync&lt;T&gt; (T registration) where T : Microsoft.Azure.NotificationHubs.RegistrationDescription;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!!T&gt; CreateOrUpdateRegistrationAsync&lt;(class Microsoft.Azure.NotificationHubs.RegistrationDescription) T&gt;(!!T registration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateOrUpdateRegistrationAsync``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateOrUpdateRegistrationAsync(Of T As RegistrationDescription) (registration As T) As Task(Of T)" />
      <MemberSignature Language="F#" Value="member this.CreateOrUpdateRegistrationAsync : 'T -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)&gt; (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)" Usage="notificationHubClient.CreateOrUpdateRegistrationAsync registration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <BaseTypeName>Microsoft.Azure.NotificationHubs.RegistrationDescription</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="registration" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="2289c-209">登録の型。</span><span class="sxs-lookup"><span data-stu-id="2289c-209">The type of registration.</span></span></typeparam>
        <param name="registration"><span data-ttu-id="2289c-210">作成または更新する登録です。</span><span class="sxs-lookup"><span data-stu-id="2289c-210">The registration to be created or updated.</span></span></param>
        <summary><span data-ttu-id="2289c-211">非同期に作成またはクライアントの登録を更新します。</span><span class="sxs-lookup"><span data-stu-id="2289c-211">Asynchronously creates or updates the client registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-212">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2289c-212">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="2289c-213">RegistrationId オブジェクトが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2289c-213">Thrown when RegistrationId object is null</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateRegistrationAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; CreateRegistrationAsync&lt;T&gt; (T registration) where T : Microsoft.Azure.NotificationHubs.RegistrationDescription;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!!T&gt; CreateRegistrationAsync&lt;(class Microsoft.Azure.NotificationHubs.RegistrationDescription) T&gt;(!!T registration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRegistrationAsync(Of T As RegistrationDescription) (registration As T) As Task(Of T)" />
      <MemberSignature Language="F#" Value="member this.CreateRegistrationAsync : 'T -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)&gt; (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)" Usage="notificationHubClient.CreateRegistrationAsync registration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <BaseTypeName>Microsoft.Azure.NotificationHubs.RegistrationDescription</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="registration" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="2289c-214">登録の型。</span><span class="sxs-lookup"><span data-stu-id="2289c-214">The type of registration.</span></span></typeparam>
        <param name="registration"><span data-ttu-id="2289c-215">作成する登録です。</span><span class="sxs-lookup"><span data-stu-id="2289c-215">The registration to create.</span></span></param>
        <summary><span data-ttu-id="2289c-216">非同期的に、登録を作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-216">Asynchronously creates a registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-217">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-217">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="2289c-218">RegistrationDescription で NotificationHubPath が正しくありません。</span><span class="sxs-lookup"><span data-stu-id="2289c-218">NotificationHubPath in RegistrationDescription is not valid.</span></span>
            <span data-ttu-id="2289c-219">RegistrationId が null または空にする必要がありますか</span><span class="sxs-lookup"><span data-stu-id="2289c-219">or RegistrationId should be null or empty</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateRegistrationIdAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; CreateRegistrationIdAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; CreateRegistrationIdAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationIdAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRegistrationIdAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.CreateRegistrationIdAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="notificationHubClient.CreateRegistrationIdAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="2289c-220">登録識別子を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-220">Asynchronously creates a registration identifier.</span></span></summary>
        <returns><span data-ttu-id="2289c-221">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2289c-221">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt; CreateWindowsNativeRegistrationAsync (string channelUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt; CreateWindowsNativeRegistrationAsync(string channelUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateWindowsNativeRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateWindowsNativeRegistrationAsync (channelUri As String) As Task(Of WindowsRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateWindowsNativeRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt;" Usage="notificationHubClient.CreateWindowsNativeRegistrationAsync channelUri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="channelUri"><span data-ttu-id="2289c-222">チャネル URI です。</span><span class="sxs-lookup"><span data-stu-id="2289c-222">The channel URI.</span></span></param>
        <summary><span data-ttu-id="2289c-223">Windows のネイティブ登録情報を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-223">Asynchronously creates Windows native registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-224">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-224">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt; CreateWindowsNativeRegistrationAsync (string channelUri, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt; CreateWindowsNativeRegistrationAsync(string channelUri, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateWindowsNativeRegistrationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateWindowsNativeRegistrationAsync (channelUri As String, tags As IEnumerable(Of String)) As Task(Of WindowsRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateWindowsNativeRegistrationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt;" Usage="notificationHubClient.CreateWindowsNativeRegistrationAsync (channelUri, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="channelUri"><span data-ttu-id="2289c-225">チャネル URI です。</span><span class="sxs-lookup"><span data-stu-id="2289c-225">The channel URI.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-226">タグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-226">The tags.</span></span></param>
        <summary><span data-ttu-id="2289c-227">Windows のネイティブ登録情報を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-227">Asynchronously creates Windows native registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-228">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-228">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt; CreateWindowsTemplateRegistrationAsync (string channelUri, string xmlTemplate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt; CreateWindowsTemplateRegistrationAsync(string channelUri, string xmlTemplate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateWindowsTemplateRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateWindowsTemplateRegistrationAsync (channelUri As String, xmlTemplate As String) As Task(Of WindowsTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateWindowsTemplateRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateWindowsTemplateRegistrationAsync (channelUri, xmlTemplate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="xmlTemplate" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="channelUri"><span data-ttu-id="2289c-229">チャネル URI です。</span><span class="sxs-lookup"><span data-stu-id="2289c-229">The channel URI.</span></span></param>
        <param name="xmlTemplate"><span data-ttu-id="2289c-230">XML テンプレートです。</span><span class="sxs-lookup"><span data-stu-id="2289c-230">The XML template.</span></span></param>
        <summary><span data-ttu-id="2289c-231">Windows テンプレート登録を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-231">Asynchronously creates Windows template registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-232">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-232">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt; CreateWindowsTemplateRegistrationAsync (string channelUri, string xmlTemplate, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt; CreateWindowsTemplateRegistrationAsync(string channelUri, string xmlTemplate, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateWindowsTemplateRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateWindowsTemplateRegistrationAsync (channelUri As String, xmlTemplate As String, tags As IEnumerable(Of String)) As Task(Of WindowsTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateWindowsTemplateRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateWindowsTemplateRegistrationAsync (channelUri, xmlTemplate, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="xmlTemplate" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="channelUri"><span data-ttu-id="2289c-233">チャネル URI です。</span><span class="sxs-lookup"><span data-stu-id="2289c-233">The channel URI.</span></span></param>
        <param name="xmlTemplate"><span data-ttu-id="2289c-234">XML テンプレートです。</span><span class="sxs-lookup"><span data-stu-id="2289c-234">The XML template.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-235">タグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-235">The tags.</span></span></param>
        <summary><span data-ttu-id="2289c-236">Windows テンプレート登録を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-236">Asynchronously creates Windows template registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-237">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-237">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteInstallation">
      <MemberSignature Language="C#" Value="public void DeleteInstallation (string installationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteInstallation(string installationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteInstallation(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteInstallation (installationId As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteInstallation : string -&gt; unit" Usage="notificationHubClient.DeleteInstallation installationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="installationId"><span data-ttu-id="2289c-238">インストールの識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-238">The installation identifier.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-239">インストールを削除します。</span><span class="sxs-lookup"><span data-stu-id="2289c-239">Deletes the installation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteInstallationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteInstallationAsync (string installationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteInstallationAsync(string installationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteInstallationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteInstallationAsync (installationId As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteInstallationAsync : string -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.DeleteInstallationAsync installationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="installationId"><span data-ttu-id="2289c-240">インストールの識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-240">The installation identifier.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-241">インストールを非同期的に削除します。</span><span class="sxs-lookup"><span data-stu-id="2289c-241">Deletes the installation asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="2289c-242">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-242">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="2289c-243">InstallationId オブジェクトが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2289c-243">Thrown when the installationId object is null</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRegistrationAsync (Microsoft.Azure.NotificationHubs.RegistrationDescription registration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRegistrationAsync(class Microsoft.Azure.NotificationHubs.RegistrationDescription registration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteRegistrationAsync(Microsoft.Azure.NotificationHubs.RegistrationDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRegistrationAsync (registration As RegistrationDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRegistrationAsync : Microsoft.Azure.NotificationHubs.RegistrationDescription -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.DeleteRegistrationAsync registration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="registration" Type="Microsoft.Azure.NotificationHubs.RegistrationDescription" />
      </Parameters>
      <Docs>
        <param name="registration"><span data-ttu-id="2289c-244">削除する登録です。</span><span class="sxs-lookup"><span data-stu-id="2289c-244">The registration to delete.</span></span></param>
        <summary><span data-ttu-id="2289c-245">非同期的に、登録を削除します。</span><span class="sxs-lookup"><span data-stu-id="2289c-245">Asynchronously deletes the registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-246">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-246">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="2289c-247">登録オブジェクトが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2289c-247">Thrown when registration object is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRegistrationAsync (string registrationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRegistrationAsync(string registrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRegistrationAsync (registrationId As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRegistrationAsync : string -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.DeleteRegistrationAsync registrationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="registrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="registrationId"><span data-ttu-id="2289c-248">登録 id。</span><span class="sxs-lookup"><span data-stu-id="2289c-248">The registration ID.</span></span></param>
        <summary><span data-ttu-id="2289c-249">非同期的に、登録を削除します。</span><span class="sxs-lookup"><span data-stu-id="2289c-249">Asynchronously deletes the registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-250">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-250">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRegistrationAsync (string registrationId, string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRegistrationAsync(string registrationId, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRegistrationAsync (registrationId As String, etag As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.DeleteRegistrationAsync (registrationId, etag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="registrationId" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="registrationId"><span data-ttu-id="2289c-251">登録 id。</span><span class="sxs-lookup"><span data-stu-id="2289c-251">The registration ID.</span></span></param>
        <param name="etag"><span data-ttu-id="2289c-252">エンティティ タグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-252">The entity tag.</span></span></param>
        <summary><span data-ttu-id="2289c-253">非同期的に、登録を削除します。</span><span class="sxs-lookup"><span data-stu-id="2289c-253">Asynchronously deletes the registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-254">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-254">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="2289c-255">RegistrationId</span><span class="sxs-lookup"><span data-stu-id="2289c-255">registrationId</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteRegistrationsByChannelAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRegistrationsByChannelAsync (string pnsHandle);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRegistrationsByChannelAsync(string pnsHandle) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteRegistrationsByChannelAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRegistrationsByChannelAsync (pnsHandle As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRegistrationsByChannelAsync : string -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.DeleteRegistrationsByChannelAsync pnsHandle" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pnsHandle" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pnsHandle"><span data-ttu-id="2289c-256">PNS が処理されます。</span><span class="sxs-lookup"><span data-stu-id="2289c-256">The PNS handle.</span></span></param>
        <summary><span data-ttu-id="2289c-257">非同期的にチャネルでの登録を削除します。</span><span class="sxs-lookup"><span data-stu-id="2289c-257">Asynchronously deletes the registrations by channel.</span></span></summary>
        <returns><span data-ttu-id="2289c-258">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-258">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="2289c-259">pnsHandle</span><span class="sxs-lookup"><span data-stu-id="2289c-259">pnsHandle</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="EnableTestSend">
      <MemberSignature Language="C#" Value="public bool EnableTestSend { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableTestSend" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubClient.EnableTestSend" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnableTestSend As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableTestSend : bool" Usage="Microsoft.Azure.NotificationHubs.NotificationHubClient.EnableTestSend" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2289c-260">取得またはクライアントにテスト送信が有効かどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="2289c-260">Gets or sets a value indicating whether the client enables a test send.</span></span></summary>
        <value><span data-ttu-id="2289c-261">クライアントでは、テストの場合は true を送信します。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="2289c-261">true if the client enables a test send; otherwise, false.</span></span></value>
        <remarks>
            <span data-ttu-id="2289c-262">テストの送信が有効になっているときに、以下の処理が行われます。</span><span class="sxs-lookup"><span data-stu-id="2289c-262">When test send is enabled, the following occurs:</span></span>
            <ul><li><span data-ttu-id="2289c-263">すべての通知では、送信呼び出しごとに最大 10 個のデバイスにのみアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="2289c-263">All notifications only reach up to 10 devices for each send call.</span></span></li><li><span data-ttu-id="2289c-264"><b>送信 \*</b>メソッドには、これらすべての通知配信の結果の一覧が返されます。</span><span class="sxs-lookup"><span data-stu-id="2289c-264">The <b>Send\*</b> methods return a list of the outcomes for all those notification deliveries.</span></span> <span data-ttu-id="2289c-265">返される結果は、製品利用統計情報に表示されることと同じです。</span><span class="sxs-lookup"><span data-stu-id="2289c-265">The possible outcomes are the same as displayed in telemetry.</span></span> <span data-ttu-id="2289c-266">結果には、認証エラー、エラー、正常に配信したファイル、およびなどの調整などが含まれています。</span><span class="sxs-lookup"><span data-stu-id="2289c-266">Outcomes includes things like authentication errors, throttling errors, successful deliveries, and so on.</span></span></li></ul><p><span data-ttu-id="2289c-267">このモードは、実稼働環境ではなくテスト目的でのみが着信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-267">This mode is for test purposes only, not for production, and is throttled.</span></span></p></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllRegistrationsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetAllRegistrationsAsync (int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetAllRegistrationsAsync(int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetAllRegistrationsAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllRegistrationsAsync (top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetAllRegistrationsAsync : int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetAllRegistrationsAsync top" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="top"><span data-ttu-id="2289c-268">登録の場所です。</span><span class="sxs-lookup"><span data-stu-id="2289c-268">The location of the registration.</span></span></param>
        <summary><span data-ttu-id="2289c-269">この通知ハブのすべての登録を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="2289c-269">Asynchronously retrieves all registrations in this notification hub.</span></span></summary>
        <returns><span data-ttu-id="2289c-270">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-270">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllRegistrationsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetAllRegistrationsAsync (string continuationToken, int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetAllRegistrationsAsync(string continuationToken, int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetAllRegistrationsAsync(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllRegistrationsAsync (continuationToken As String, top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetAllRegistrationsAsync : string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetAllRegistrationsAsync (continuationToken, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="continuationToken"><span data-ttu-id="2289c-271">継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="2289c-271">The continuation token.</span></span></param>
        <param name="top"><span data-ttu-id="2289c-272">登録の場所です。</span><span class="sxs-lookup"><span data-stu-id="2289c-272">The location of the registration.</span></span></param>
        <summary><span data-ttu-id="2289c-273">この通知ハブのすべての登録を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="2289c-273">Asynchronously retrieves all registrations in this notification hub.</span></span></summary>
        <returns><span data-ttu-id="2289c-274">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-274">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBaseUri">
      <MemberSignature Language="C#" Value="public Uri GetBaseUri ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Uri GetBaseUri() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetBaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBaseUri () As Uri" />
      <MemberSignature Language="F#" Value="member this.GetBaseUri : unit -&gt; Uri" Usage="notificationHubClient.GetBaseUri " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="2289c-275">BaseUri 添付プロパティの値を取得します。</span><span class="sxs-lookup"><span data-stu-id="2289c-275">Gets the value of the BaseUri attached property.</span></span></summary>
        <returns><span data-ttu-id="2289c-276">指定された要素のベース URI。</span><span class="sxs-lookup"><span data-stu-id="2289c-276">The base URI of a given element.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInstallation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Installation GetInstallation (string installationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.NotificationHubs.Installation GetInstallation(string installationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetInstallation(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetInstallation (installationId As String) As Installation" />
      <MemberSignature Language="F#" Value="member this.GetInstallation : string -&gt; Microsoft.Azure.NotificationHubs.Installation" Usage="notificationHubClient.GetInstallation installationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Installation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="installationId"><span data-ttu-id="2289c-277">インストールの識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-277">The installation identifier.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-278">デバイスのインストールのオブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="2289c-278">Gets a device installation object.</span></span>
            </summary>
        <returns><span data-ttu-id="2289c-279">デバイスのインストール オブジェクト</span><span class="sxs-lookup"><span data-stu-id="2289c-279">The device installation object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInstallationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.Installation&gt; GetInstallationAsync (string installationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.Installation&gt; GetInstallationAsync(string installationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetInstallationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetInstallationAsync (installationId As String) As Task(Of Installation)" />
      <MemberSignature Language="F#" Value="member this.GetInstallationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.Installation&gt;" Usage="notificationHubClient.GetInstallationAsync installationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.Installation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="installationId"><span data-ttu-id="2289c-280">インストールの識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-280">The installation identifier.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-281">インストールを非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="2289c-281">Gets the installation asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="2289c-282">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-282">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="2289c-283">InstallationId オブジェクトが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2289c-283">Thrown when the installationId object is null</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; GetNotificationHubJobAsync (string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; GetNotificationHubJobAsync(string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetNotificationHubJobAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubJobAsync (jobId As String) As Task(Of NotificationHubJob)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubJobAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;" Usage="notificationHubClient.GetNotificationHubJobAsync jobId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="2289c-284">使用して新しいジョブを作成した後、ジョブ Id が返される<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob)" />です。</span><span class="sxs-lookup"><span data-stu-id="2289c-284">The jobId is returned after creating a new job using <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob)" />.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-285">JobId を指定したを返します、関連付けられている<see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />です。</span><span class="sxs-lookup"><span data-stu-id="2289c-285">Given a jobId, returns the associated <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />.</span></span> <span data-ttu-id="2289c-286">このメソッドを使用して、そのジョブに完了し、失敗、または、処理中であるかどうかに表示するジョブの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="2289c-286">This method is used to get the status of the job to see if that job completed, failed, or is still in progress.</span></span>
            <span data-ttu-id="2289c-287">この API は、標準の名前空間のできるだけです。</span><span class="sxs-lookup"><span data-stu-id="2289c-287">This API is only available for Standard namespaces.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2289c-288">現在の状態、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob)" />です。</span><span class="sxs-lookup"><span data-stu-id="2289c-288">The current state of the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob)" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubJobsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt; GetNotificationHubJobsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt; GetNotificationHubJobsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetNotificationHubJobsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubJobsAsync () As Task(Of IEnumerable(Of NotificationHubJob))" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubJobsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt;" Usage="notificationHubClient.GetNotificationHubJobsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2289c-289">返しますのすべての既知<see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s。</span><span class="sxs-lookup"><span data-stu-id="2289c-289">Returns all known <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s.</span></span> <span data-ttu-id="2289c-290">このメソッドを使用して、それらのジョブが完了、失敗したか、まだ進行中かどうかをすべてのジョブの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="2289c-290">This method is used to get the status of all job to see if those jobs completed, failed, or are still in progress.</span></span>
            <span data-ttu-id="2289c-291">この API は、標準の名前空間のできるだけです。</span><span class="sxs-lookup"><span data-stu-id="2289c-291">This API is only available for Standard namespaces.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2289c-292">現在の状態、 <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s。</span><span class="sxs-lookup"><span data-stu-id="2289c-292">The current state of the <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationOutcomeDetailsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationDetails&gt; GetNotificationOutcomeDetailsAsync (string notificationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationDetails&gt; GetNotificationOutcomeDetailsAsync(string notificationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetNotificationOutcomeDetailsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationOutcomeDetailsAsync (notificationId As String) As Task(Of NotificationDetails)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationOutcomeDetailsAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationDetails&gt;" Usage="notificationHubClient.GetNotificationOutcomeDetailsAsync notificationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationDetails&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notificationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="notificationId">
          <span data-ttu-id="2289c-293"><see cref="P:Microsoft.Azure.NotificationHubs.NotificationOutcome.NotificationId" />これには、送信 \* を呼び出すときに返されました。</span><span class="sxs-lookup"><span data-stu-id="2289c-293"><see cref="P:Microsoft.Azure.NotificationHubs.NotificationOutcome.NotificationId" /> which was returned when calling Send\*.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-294">送信 \* 操作の結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="2289c-294">Retrieves the results of a Send\* operation.</span></span> <span data-ttu-id="2289c-295">送信 \* が完了した場合これで、送信が処理されている場合、結果を中間または最終結果を取得できます。</span><span class="sxs-lookup"><span data-stu-id="2289c-295">This can retrieve intermediate results if the send is being processed or final results if the Send\* has completed.</span></span> <span data-ttu-id="2289c-296">この API は、標準の名前空間に対してのみ呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="2289c-296">This API can only be called for Standard namespaces.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2289c-297">によって表される、送信操作の結果、<see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />です。</span><span class="sxs-lookup"><span data-stu-id="2289c-297">The result of the Send operation, as expressed by a <see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="2289c-298">notificationId</span><span class="sxs-lookup"><span data-stu-id="2289c-298">notificationId</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationAsync&lt;TRegistrationDescription&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TRegistrationDescription&gt; GetRegistrationAsync&lt;TRegistrationDescription&gt; (string registrationId) where TRegistrationDescription : Microsoft.Azure.NotificationHubs.RegistrationDescription;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!!TRegistrationDescription&gt; GetRegistrationAsync&lt;(class Microsoft.Azure.NotificationHubs.RegistrationDescription) TRegistrationDescription&gt;(string registrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetRegistrationAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRegistrationAsync(Of TRegistrationDescription As RegistrationDescription) (registrationId As String) As Task(Of TRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;'RegistrationDescription (requires 'RegistrationDescription :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)&gt; (requires 'RegistrationDescription :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)" Usage="notificationHubClient.GetRegistrationAsync registrationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TRegistrationDescription">
          <Constraints>
            <BaseTypeName>Microsoft.Azure.NotificationHubs.RegistrationDescription</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="registrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TRegistrationDescription"><span data-ttu-id="2289c-299">登録の説明の種類。</span><span class="sxs-lookup"><span data-stu-id="2289c-299">The type of registration description.</span></span></typeparam>
        <param name="registrationId"><span data-ttu-id="2289c-300">登録 id。</span><span class="sxs-lookup"><span data-stu-id="2289c-300">The registration ID.</span></span></param>
        <summary><span data-ttu-id="2289c-301">指定された ID の登録を非同期的に取得します。</span><span class="sxs-lookup"><span data-stu-id="2289c-301">Asynchronously retrieves a registration with a given ID.</span></span> <span data-ttu-id="2289c-302">登録の種類によって異なります、指定した<paramref name="TRegistrationDescription" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="2289c-302">The type of the registration depends upon the specified <paramref name="TRegistrationDescription" /> parameter.</span></span></summary>
        <returns><span data-ttu-id="2289c-303">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-303">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="2289c-304">RegistrationId が null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2289c-304">Thrown when registrationId is null</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationsByChannelAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByChannelAsync (string pnsHandle, int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByChannelAsync(string pnsHandle, int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetRegistrationsByChannelAsync(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRegistrationsByChannelAsync (pnsHandle As String, top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRegistrationsByChannelAsync : string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetRegistrationsByChannelAsync (pnsHandle, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pnsHandle" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="pnsHandle"><span data-ttu-id="2289c-305">PNS が処理されます。</span><span class="sxs-lookup"><span data-stu-id="2289c-305">The PNS handle.</span></span></param>
        <param name="top"><span data-ttu-id="2289c-306">登録の場所です。</span><span class="sxs-lookup"><span data-stu-id="2289c-306">The location of the registration.</span></span></param>
        <summary><span data-ttu-id="2289c-307">チャネルによって、登録を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="2289c-307">Asynchronously gets the registrations by channel.</span></span></summary>
        <returns><span data-ttu-id="2289c-308">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-308">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationsByChannelAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByChannelAsync (string pnsHandle, string continuationToken, int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByChannelAsync(string pnsHandle, string continuationToken, int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetRegistrationsByChannelAsync(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRegistrationsByChannelAsync (pnsHandle As String, continuationToken As String, top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRegistrationsByChannelAsync : string * string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetRegistrationsByChannelAsync (pnsHandle, continuationToken, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pnsHandle" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="pnsHandle"><span data-ttu-id="2289c-309">PNS が処理されます。</span><span class="sxs-lookup"><span data-stu-id="2289c-309">The PNS handle.</span></span></param>
        <param name="continuationToken"><span data-ttu-id="2289c-310">継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="2289c-310">The continuation token.</span></span></param>
        <param name="top"><span data-ttu-id="2289c-311">登録の場所です。</span><span class="sxs-lookup"><span data-stu-id="2289c-311">The location of the registration.</span></span></param>
        <summary><span data-ttu-id="2289c-312">チャネルによって、登録を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="2289c-312">Asynchronously gets the registrations by channel.</span></span></summary>
        <returns><span data-ttu-id="2289c-313">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-313">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="2289c-314">pnsHandle</span><span class="sxs-lookup"><span data-stu-id="2289c-314">pnsHandle</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationsByTagAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByTagAsync (string tag, int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByTagAsync(string tag, int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetRegistrationsByTagAsync(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRegistrationsByTagAsync (tag As String, top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRegistrationsByTagAsync : string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetRegistrationsByTagAsync (tag, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tag" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="tag"><span data-ttu-id="2289c-315">タグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-315">The tag.</span></span></param>
        <param name="top"><span data-ttu-id="2289c-316">場所の登録を取得する場所です。</span><span class="sxs-lookup"><span data-stu-id="2289c-316">The location where to get the registrations.</span></span></param>
        <summary><span data-ttu-id="2289c-317">タグで、登録を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="2289c-317">Asynchronously gets the registrations by tag.</span></span></summary>
        <returns><span data-ttu-id="2289c-318">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-318">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationsByTagAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByTagAsync (string tag, string continuationToken, int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByTagAsync(string tag, string continuationToken, int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetRegistrationsByTagAsync(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRegistrationsByTagAsync (tag As String, continuationToken As String, top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRegistrationsByTagAsync : string * string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetRegistrationsByTagAsync (tag, continuationToken, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tag" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="tag"><span data-ttu-id="2289c-319">タグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-319">The tag.</span></span></param>
        <param name="continuationToken"><span data-ttu-id="2289c-320">継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="2289c-320">The continuation token.</span></span></param>
        <param name="top"><span data-ttu-id="2289c-321">場所の登録を取得する場所です。</span><span class="sxs-lookup"><span data-stu-id="2289c-321">The location where to get the registrations.</span></span></param>
        <summary><span data-ttu-id="2289c-322">タグで、登録を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="2289c-322">Asynchronously gets the registrations by tag.</span></span></summary>
        <returns><span data-ttu-id="2289c-323">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-323">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="2289c-324">タグのオブジェクトが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2289c-324">Thrown when tag object is null</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="PatchInstallation">
      <MemberSignature Language="C#" Value="public void PatchInstallation (string installationId, System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; operations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void PatchInstallation(string installationId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.PatchInstallation(System.String,System.Collections.Generic.IList{Microsoft.Azure.NotificationHubs.PartialUpdateOperation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub PatchInstallation (installationId As String, operations As IList(Of PartialUpdateOperation))" />
      <MemberSignature Language="F#" Value="member this.PatchInstallation : string * System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; -&gt; unit" Usage="notificationHubClient.PatchInstallation (installationId, operations)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
        <Parameter Name="operations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt;" />
      </Parameters>
      <Docs>
        <param name="installationId"><span data-ttu-id="2289c-325">インストールの識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-325">The installation identifier.</span></span></param>
        <param name="operations"><span data-ttu-id="2289c-326">更新操作のコレクション。</span><span class="sxs-lookup"><span data-stu-id="2289c-326">The collection of update operations.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-327">修正プログラムのインストール。</span><span class="sxs-lookup"><span data-stu-id="2289c-327">Patches the installation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchInstallationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PatchInstallationAsync (string installationId, System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; operations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PatchInstallationAsync(string installationId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.PatchInstallationAsync(System.String,System.Collections.Generic.IList{Microsoft.Azure.NotificationHubs.PartialUpdateOperation})" />
      <MemberSignature Language="VB.NET" Value="Public Function PatchInstallationAsync (installationId As String, operations As IList(Of PartialUpdateOperation)) As Task" />
      <MemberSignature Language="F#" Value="member this.PatchInstallationAsync : string * System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.PatchInstallationAsync (installationId, operations)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
        <Parameter Name="operations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt;" />
      </Parameters>
      <Docs>
        <param name="installationId"><span data-ttu-id="2289c-328">インストールの識別子です。</span><span class="sxs-lookup"><span data-stu-id="2289c-328">The installation identifier.</span></span></param>
        <param name="operations"><span data-ttu-id="2289c-329">更新操作のコレクション。</span><span class="sxs-lookup"><span data-stu-id="2289c-329">The collection of update operations.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-330">インストールを修正プログラムには、次の非同期的にします。</span><span class="sxs-lookup"><span data-stu-id="2289c-330">Patches the installation asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="2289c-331">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-331">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="2289c-332">InstallationId または操作のオブジェクトが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2289c-332">Thrown when the installationId or operations object is null</span></span>
            </exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="2289c-333">操作リストが空の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2289c-333">Thrown when the operations list is empty</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RegistrationExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; RegistrationExistsAsync (string registrationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; RegistrationExistsAsync(string registrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.RegistrationExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegistrationExistsAsync (registrationId As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RegistrationExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="notificationHubClient.RegistrationExistsAsync registrationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="registrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="registrationId"><span data-ttu-id="2289c-334">登録 id。</span><span class="sxs-lookup"><span data-stu-id="2289c-334">The registration ID.</span></span></param>
        <summary><span data-ttu-id="2289c-335">非同期的に、登録が既に存在することを示します。</span><span class="sxs-lookup"><span data-stu-id="2289c-335">Asynchronously indicates that the registration already exists.</span></span></summary>
        <returns><span data-ttu-id="2289c-336">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-336">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, DateTimeOffset scheduledTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, valuetype System.DateTimeOffset scheduledTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.ScheduleNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.ScheduleNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;" Usage="notificationHubClient.ScheduleNotificationAsync (notification, scheduledTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="scheduledTime" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="notification"><span data-ttu-id="2289c-337">通知です。</span><span class="sxs-lookup"><span data-stu-id="2289c-337">The notification.</span></span></param>
        <param name="scheduledTime"><span data-ttu-id="2289c-338">スケジュールされた時刻。</span><span class="sxs-lookup"><span data-stu-id="2289c-338">The scheduled time.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-339">通知を非同期的にスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="2289c-339">Schedules the notification asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="2289c-340">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-340">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, DateTimeOffset scheduledTime, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, valuetype System.DateTimeOffset scheduledTime, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.ScheduleNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.DateTimeOffset,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="F#" Value="member this.ScheduleNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * DateTimeOffset * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;" Usage="notificationHubClient.ScheduleNotificationAsync (notification, scheduledTime, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="scheduledTime" Type="System.DateTimeOffset" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="notification"><span data-ttu-id="2289c-341">通知です。</span><span class="sxs-lookup"><span data-stu-id="2289c-341">The notification.</span></span></param>
        <param name="scheduledTime"><span data-ttu-id="2289c-342">スケジュールされた時刻。</span><span class="sxs-lookup"><span data-stu-id="2289c-342">The scheduled time.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-343">タグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-343">The tags.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-344">通知を非同期的にスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="2289c-344">Schedules the notification asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="2289c-345">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-345">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="2289c-346">タグのオブジェクトが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2289c-346">Thrown when tags object is null</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="2289c-347">タグの引数は、少なくとも 1 つのタグを含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="2289c-347">tags argument should contain atleast one tag</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ScheduleNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, DateTimeOffset scheduledTime, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, valuetype System.DateTimeOffset scheduledTime, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.ScheduleNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.DateTimeOffset,System.String)" />
      <MemberSignature Language="F#" Value="member this.ScheduleNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * DateTimeOffset * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;" Usage="notificationHubClient.ScheduleNotificationAsync (notification, scheduledTime, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="scheduledTime" Type="System.DateTimeOffset" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="notification"><span data-ttu-id="2289c-348">通知です。</span><span class="sxs-lookup"><span data-stu-id="2289c-348">The notification.</span></span></param>
        <param name="scheduledTime"><span data-ttu-id="2289c-349">スケジュールされた時刻。</span><span class="sxs-lookup"><span data-stu-id="2289c-349">The scheduled time.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="2289c-350">タグ式です。</span><span class="sxs-lookup"><span data-stu-id="2289c-350">The tag expression.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-351">通知を非同期的にスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="2289c-351">Schedules the notification asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="2289c-352">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-352">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAdmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync (string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync(string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAdmNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAdmNativeNotificationAsync (jsonPayload As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAdmNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAdmNativeNotificationAsync jsonPayload" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="2289c-353">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-353">The JSON payload.</span></span></param>
        <summary><span data-ttu-id="2289c-354">管理用のネイティブ通知を非同期的に送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-354">Asynchronously sends the administrative native notification.</span></span></summary>
        <returns><span data-ttu-id="2289c-355">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2289c-355">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAdmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync (string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync(string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAdmNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAdmNativeNotificationAsync (jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAdmNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAdmNativeNotificationAsync (jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="2289c-356">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-356">The JSON payload.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-357">タグ。</span><span class="sxs-lookup"><span data-stu-id="2289c-357">The tags.</span></span></param>
        <summary><span data-ttu-id="2289c-358">管理用のネイティブ通知を非同期的に送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-358">Asynchronously sends the administrative native notification.</span></span></summary>
        <returns><span data-ttu-id="2289c-359">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2289c-359">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAdmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync (string jsonPayload, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync(string jsonPayload, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAdmNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAdmNativeNotificationAsync (jsonPayload As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAdmNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAdmNativeNotificationAsync (jsonPayload, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="2289c-360">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-360">The JSON payload.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="2289c-361">タグ式です。</span><span class="sxs-lookup"><span data-stu-id="2289c-361">The tag expression.</span></span></param>
        <summary><span data-ttu-id="2289c-362">管理用のネイティブ通知を非同期的に送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-362">Asynchronously sends the administrative native notification.</span></span></summary>
        <returns><span data-ttu-id="2289c-363">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2289c-363">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAppleNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync (string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync(string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAppleNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAppleNativeNotificationAsync (jsonPayload As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAppleNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAppleNativeNotificationAsync jsonPayload" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="2289c-364">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-364">The JSON payload.</span></span></param>
        <summary><span data-ttu-id="2289c-365">Apple ネイティブ通知を非同期的に送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-365">Asynchronously sends an Apple native notification.</span></span> <span data-ttu-id="2289c-366">有効期限を指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="2289c-366">To specify an expiry, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="2289c-367">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-367">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAppleNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync (string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync(string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAppleNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAppleNativeNotificationAsync (jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAppleNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAppleNativeNotificationAsync (jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="2289c-368">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-368">The JSON payload.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-369">以外の空のセット タグ (最大 20 タグ)。</span><span class="sxs-lookup"><span data-stu-id="2289c-369">A non-empty set of tags (maximum 20 tags).</span></span> <span data-ttu-id="2289c-370">セット内の各文字列は、1 つのタグを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="2289c-370">Each string in the set can contain a single tag.</span></span></param>
        <summary><span data-ttu-id="2289c-371">非同期的にネイティブ通知を Apple に非-空タグのセット (最大 20) を送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-371">Asynchronously sends an Apple native notification to a non-empty set of tags (maximum 20).</span></span> <span data-ttu-id="2289c-372">これは、ブール型 Or でタグが付けられた式と同じ ("| |") です。</span><span class="sxs-lookup"><span data-stu-id="2289c-372">This is equivalent to a tagged expression with boolean ORs ("||").</span></span> <span data-ttu-id="2289c-373">有効期限を指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="2289c-373">To specify an expiry, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="2289c-374">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-374">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAppleNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync (string jsonPayload, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync(string jsonPayload, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAppleNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAppleNativeNotificationAsync (jsonPayload As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAppleNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAppleNativeNotificationAsync (jsonPayload, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="2289c-375">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-375">The JSON payload.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="2289c-376">タグ式は、論理演算子を使用して構築された任意のブール式 AND (&amp;&amp;)、または (|)、されません (!)、かっこを丸めるとします。</span><span class="sxs-lookup"><span data-stu-id="2289c-376">A tag expression is any boolean expression constructed using the logical operators AND (&amp;&amp;), OR (||), NOT (!), and round parentheses.</span></span> <span data-ttu-id="2289c-377">例: (A | |B) &amp; &amp; !C.</span><span class="sxs-lookup"><span data-stu-id="2289c-377">For example: (A || B) &amp;&amp; !C.</span></span> <span data-ttu-id="2289c-378">式には、Or のみが使用されている場合は、最大で 20 タグが含まれてことができます。</span><span class="sxs-lookup"><span data-stu-id="2289c-378">If an expression uses only ORs, it can contain at most 20 tags.</span></span> <span data-ttu-id="2289c-379">その他の式は、6 つのタグに制限されます。</span><span class="sxs-lookup"><span data-stu-id="2289c-379">Other expressions are limited to 6 tags.</span></span> <span data-ttu-id="2289c-380">1 つのタグ"A"が有効な式であることを注意してください。</span><span class="sxs-lookup"><span data-stu-id="2289c-380">Note that a single tag "A" is a valid expression.</span></span></param>
        <summary><span data-ttu-id="2289c-381">非同期的に (1 つのタグ「タグ」は有効なタグ式) タグ式に Apple ネイティブ通知を送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-381">Asynchronously sends an Apple native notification to a tag expression (a single tag "tag" is a valid tag expression).</span></span> <span data-ttu-id="2289c-382">有効期限を指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="2289c-382">To specify an expiry, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="2289c-383">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-383">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBaiduNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendBaiduNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBaiduNativeNotificationAsync (message As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendBaiduNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendBaiduNativeNotificationAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="2289c-384">これは、json 要求です。</span><span class="sxs-lookup"><span data-stu-id="2289c-384">This is a json request.</span></span> <span data-ttu-id="2289c-385">Baidu、json 形式のドキュメント<a href="http://push.baidu.com/doc/restapi/restapi">ここ</a>です。</span><span class="sxs-lookup"><span data-stu-id="2289c-385">Baidu documents the format for the json <a href="http://push.baidu.com/doc/restapi/restapi">here</a>.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-386">Baidu ネイティブ通知を送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-386">Sends a Baidu native notification.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="2289c-387"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />これには、送信操作の結果について説明します。</span><span class="sxs-lookup"><span data-stu-id="2289c-387"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" /> which describes the result of the Send operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBaiduNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync (string message, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync(string message, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendBaiduNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBaiduNativeNotificationAsync (message As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendBaiduNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendBaiduNativeNotificationAsync (message, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="2289c-388">これは、json 要求です。</span><span class="sxs-lookup"><span data-stu-id="2289c-388">This is a json request.</span></span> <span data-ttu-id="2289c-389">Baidu、json 形式のドキュメント<a href="http://push.baidu.com/doc/restapi/restapi">ここ</a>です。</span><span class="sxs-lookup"><span data-stu-id="2289c-389">Baidu documents the format for the json <a href="http://push.baidu.com/doc/restapi/restapi">here</a>.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-390">以外の空のセット タグ (最大 20 タグ)。</span><span class="sxs-lookup"><span data-stu-id="2289c-390">A non-empty set of tags (maximum 20 tags).</span></span> <span data-ttu-id="2289c-391">セット内の各文字列は、1 つのタグを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="2289c-391">Each string in the set can contain a single tag.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-392">(1 つのタグ「タグ」は有効なタグ式) タグ式には、Baidu ネイティブ通知を送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-392">Sends Baidu native notification to a tag expression (a single tag "tag" is a valid tag expression).</span></span>
            </summary>
        <returns>
          <span data-ttu-id="2289c-393"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />これには、送信操作の結果について説明します。</span><span class="sxs-lookup"><span data-stu-id="2289c-393"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" /> which describes the result of the Send operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBaiduNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync (string message, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync(string message, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendBaiduNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBaiduNativeNotificationAsync (message As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendBaiduNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendBaiduNativeNotificationAsync (message, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="2289c-394">これは、json 要求です。</span><span class="sxs-lookup"><span data-stu-id="2289c-394">This is a json request.</span></span> <span data-ttu-id="2289c-395">Baidu、json 形式のドキュメント<a href="http://push.baidu.com/doc/restapi/restapi">ここ</a>です。</span><span class="sxs-lookup"><span data-stu-id="2289c-395">Baidu documents the format for the json <a href="http://push.baidu.com/doc/restapi/restapi">here</a>.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="2289c-396">タグ式は、論理演算子を使用して構築された任意のブール式 AND (&amp;&amp;)、または (|)、されません (!)、かっこを丸めるとします。</span><span class="sxs-lookup"><span data-stu-id="2289c-396">A tag expression is any boolean expression constructed using the logical operators AND (&amp;&amp;), OR (||), NOT (!), and round parentheses.</span></span> <span data-ttu-id="2289c-397">例: (A | |B) &amp; &amp; !C.</span><span class="sxs-lookup"><span data-stu-id="2289c-397">For example: (A || B) &amp;&amp; !C.</span></span> <span data-ttu-id="2289c-398">式には、Or のみが使用されている場合は、最大で 20 タグが含まれてことができます。</span><span class="sxs-lookup"><span data-stu-id="2289c-398">If an expression uses only ORs, it can contain at most 20 tags.</span></span> <span data-ttu-id="2289c-399">その他の式は、6 つのタグに制限されます。</span><span class="sxs-lookup"><span data-stu-id="2289c-399">Other expressions are limited to 6 tags.</span></span> <span data-ttu-id="2289c-400">1 つのタグ"A"が有効な式であることを注意してください。</span><span class="sxs-lookup"><span data-stu-id="2289c-400">Note that a single tag "A" is a valid expression.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-401">(1 つのタグ「タグ」は有効なタグ式) タグ式には、Baidu ネイティブ通知を送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-401">Sends Baidu native notification to a tag expression (a single tag "tag" is a valid tag expression).</span></span>
            </summary>
        <returns>
          <span data-ttu-id="2289c-402"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />これには、送信操作の結果について説明します。</span><span class="sxs-lookup"><span data-stu-id="2289c-402"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" /> which describes the result of the Send operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendGcmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync (string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync(string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendGcmNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendGcmNativeNotificationAsync (jsonPayload As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendGcmNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendGcmNativeNotificationAsync jsonPayload" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="2289c-403">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-403">The JSON payload.</span></span></param>
        <summary><span data-ttu-id="2289c-404">GCM ネイティブ通知を非同期的に送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-404">Asynchronously sends GCM native notification.</span></span></summary>
        <returns><span data-ttu-id="2289c-405">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-405">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendGcmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync (string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync(string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendGcmNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendGcmNativeNotificationAsync (jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendGcmNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendGcmNativeNotificationAsync (jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="2289c-406">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-406">The JSON payload.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-407">以外の空のセット タグ (最大 20 タグ)。</span><span class="sxs-lookup"><span data-stu-id="2289c-407">A non-empty set of tags (maximum 20 tags).</span></span> <span data-ttu-id="2289c-408">セット内の各文字列は、1 つのタグを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="2289c-408">Each string in the set can contain a single tag.</span></span></param>
        <summary><span data-ttu-id="2289c-409">非同期的に GCM ネイティブ通知を非-空タグのセット (最大 20) を送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-409">Asynchronously sends a GCM native notification to a non-empty set of tags (max 20).</span></span> <span data-ttu-id="2289c-410">これは、ブール型 Or とタグ式と同じ ("| |") です。</span><span class="sxs-lookup"><span data-stu-id="2289c-410">This is equivalent to a tag expression with boolean ORs ("||").</span></span></summary>
        <returns><span data-ttu-id="2289c-411">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-411">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendGcmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync (string jsonPayload, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync(string jsonPayload, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendGcmNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendGcmNativeNotificationAsync (jsonPayload As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendGcmNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendGcmNativeNotificationAsync (jsonPayload, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="2289c-412">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-412">The JSON payload.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="2289c-413">タグ式は、論理演算子を使用して構築された任意のブール式 AND (&amp;&amp;)、または (|)、されません (!)、かっこを丸めるとします。</span><span class="sxs-lookup"><span data-stu-id="2289c-413">A tag expression is any boolean expression constructed using the logical operators AND (&amp;&amp;), OR (||), NOT (!), and round parentheses.</span></span> <span data-ttu-id="2289c-414">例: (A | |B) &amp; &amp; !C.</span><span class="sxs-lookup"><span data-stu-id="2289c-414">For example: (A || B) &amp;&amp; !C.</span></span> <span data-ttu-id="2289c-415">式には、Or のみが使用されている場合は、最大で 20 タグが含まれてことができます。</span><span class="sxs-lookup"><span data-stu-id="2289c-415">If an expression uses only ORs, it can contain at most 20 tags.</span></span> <span data-ttu-id="2289c-416">その他の式は、6 つのタグに制限されます。</span><span class="sxs-lookup"><span data-stu-id="2289c-416">Other expressions are limited to 6 tags.</span></span> <span data-ttu-id="2289c-417">1 つのタグ"A"が有効な式であることを注意してください。</span><span class="sxs-lookup"><span data-stu-id="2289c-417">Note that a single tag "A" is a valid expression.</span></span></param>
        <summary><span data-ttu-id="2289c-418">非同期的に (1 つのタグ「タグ」は有効なタグ式) タグ式に GCM ネイティブ通知を送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-418">Asynchronously sends GCM native notification to a tag expression (a single tag "tag" is a valid tag expression).</span></span></summary>
        <returns><span data-ttu-id="2289c-419">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-419">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendMpnsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync (string nativePayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync(string nativePayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendMpnsNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendMpnsNativeNotificationAsync (nativePayload As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendMpnsNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendMpnsNativeNotificationAsync nativePayload" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nativePayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nativePayload"><span data-ttu-id="2289c-420">ネイティブのペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-420">The native payload.</span></span></param>
        <summary><span data-ttu-id="2289c-421">MPNS ネイティブ通知を非同期的に送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-421">Asynchronously sends MPNS native notification.</span></span> <span data-ttu-id="2289c-422">MPNS のヘッダーを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="2289c-422">To specify headers for MPNS, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="2289c-423">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-423">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendMpnsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync (string nativePayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync(string nativePayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendMpnsNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendMpnsNativeNotificationAsync (nativePayload As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendMpnsNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendMpnsNativeNotificationAsync (nativePayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nativePayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="nativePayload"><span data-ttu-id="2289c-424">通知のペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-424">The notification payload.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-425">以外の空のセット タグ (最大 20 タグ)。</span><span class="sxs-lookup"><span data-stu-id="2289c-425">A non-empty set of tags (maximum 20 tags).</span></span> <span data-ttu-id="2289c-426">セット内の各文字列は、1 つのタグを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="2289c-426">Each string in the set can contain a single tag.</span></span></param>
        <summary><span data-ttu-id="2289c-427">非同期 MPNS ネイティブ通知を非-空タグのセット (最大 20) を送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-427">Asynchronously sends MPNS native notification to a non-empty set of tags (maximum 20).</span></span> <span data-ttu-id="2289c-428">これは、ブール型 Or とタグ式と同じ ("| |") です。</span><span class="sxs-lookup"><span data-stu-id="2289c-428">This is equivalent to a tag expression with boolean ORs ("||").</span></span> <span data-ttu-id="2289c-429">MPNS のヘッダーを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="2289c-429">To specify headers for MPNS, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="2289c-430">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-430">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendMpnsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync (string nativePayload, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync(string nativePayload, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendMpnsNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendMpnsNativeNotificationAsync (nativePayload As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendMpnsNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendMpnsNativeNotificationAsync (nativePayload, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nativePayload" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nativePayload"><span data-ttu-id="2289c-431">ネイティブのペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-431">The native payload.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="2289c-432">タグ式は、論理演算子を使用して構築された任意のブール式 AND (&amp;&amp;)、または (|)、されません (!)、かっこを丸めるとします。</span><span class="sxs-lookup"><span data-stu-id="2289c-432">A tag expression is any boolean expression constructed using the logical operators AND (&amp;&amp;), OR (||), NOT (!), and round parentheses.</span></span> <span data-ttu-id="2289c-433">例: (A | |B) &amp; &amp; !C.</span><span class="sxs-lookup"><span data-stu-id="2289c-433">For example: (A || B) &amp;&amp; !C.</span></span> <span data-ttu-id="2289c-434">式には、Or のみが使用されている場合は、最大で 20 タグが含まれてことができます。</span><span class="sxs-lookup"><span data-stu-id="2289c-434">If an expression uses only ORs, it can contain at most 20 tags.</span></span> <span data-ttu-id="2289c-435">その他の式は、6 つのタグに制限されます。</span><span class="sxs-lookup"><span data-stu-id="2289c-435">Other expressions are limited to 6 tags.</span></span> <span data-ttu-id="2289c-436">1 つのタグ"A"が有効な式であることを注意してください。</span><span class="sxs-lookup"><span data-stu-id="2289c-436">Note that a single tag "A" is a valid expression.</span></span></param>
        <summary><span data-ttu-id="2289c-437">非同期的に (1 つのタグ「タグ」は有効なタグ式) タグ式に MPNS ネイティブ通知を送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-437">Asynchronously sends MPNS native notification to a tag expression (a single tag "tag" is a valid tag expression).</span></span> <span data-ttu-id="2289c-438">MPNS のヘッダーを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="2289c-438">To specify headers for MPNS, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="2289c-439">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-439">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />
      <MemberSignature Language="F#" Value="member this.SendNotificationAsync : Microsoft.Azure.NotificationHubs.Notification -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendNotificationAsync notification" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
      </Parameters>
      <Docs>
        <param name="notification"><span data-ttu-id="2289c-440">送信する通知。</span><span class="sxs-lookup"><span data-stu-id="2289c-440">The notification to send.</span></span></param>
        <summary><span data-ttu-id="2289c-441">非同期通知を非-空タグのセット (最大 20) を送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-441">Asynchronously sends a notification to a non-empty set of tags (max 20).</span></span> <span data-ttu-id="2289c-442">これは、ブール型 Or とタグ式と同じ ("| |") です。</span><span class="sxs-lookup"><span data-stu-id="2289c-442">This is equivalent to a tag expression with boolean ORs ("||").</span></span></summary>
        <returns><span data-ttu-id="2289c-443">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-443">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="2289c-444">通知</span><span class="sxs-lookup"><span data-stu-id="2289c-444">notification</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SendNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="F#" Value="member this.SendNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendNotificationAsync (notification, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="notification"><span data-ttu-id="2289c-445">送信する通知。</span><span class="sxs-lookup"><span data-stu-id="2289c-445">The notification to send.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-446">以外の空のセット タグ (最大 20 タグ)。</span><span class="sxs-lookup"><span data-stu-id="2289c-446">A non-empty set of tags (max 20 tags).</span></span> <span data-ttu-id="2289c-447">セット内の各文字列は、1 つのタグを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="2289c-447">Each string in the set can contain a single tag.</span></span></param>
        <summary><span data-ttu-id="2289c-448">非同期通知を非-空タグのセット (最大 20) を送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-448">Asynchronously sends a notification to a non-empty set of tags (max 20).</span></span> <span data-ttu-id="2289c-449">これは、ブール型 Or とタグ式と同じ ("| |") です。</span><span class="sxs-lookup"><span data-stu-id="2289c-449">This is equivalent to a tag expression with boolean ORs ("||").</span></span></summary>
        <returns><span data-ttu-id="2289c-450">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-450">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="2289c-451">通知またはタグのオブジェクトが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2289c-451">Thrown when notification or tag object is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="2289c-452">通知します。Tag プロパティを null することはできませんまたはタグの引数は atleat 1 つのタグを含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="2289c-452">notification.Tag property should not be null or tags argument should contain atleat one tag</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SendNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.String)" />
      <MemberSignature Language="F#" Value="member this.SendNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendNotificationAsync (notification, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="notification"><span data-ttu-id="2289c-453">送信する通知。</span><span class="sxs-lookup"><span data-stu-id="2289c-453">The notification to send.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="2289c-454">タグ式は、論理演算子を使用して構築された任意のブール式 AND (&amp;&amp;)、または (|)、されません (!)、かっこを丸めるとします。</span><span class="sxs-lookup"><span data-stu-id="2289c-454">A tag expression is any boolean expression constructed using the logical operators AND (&amp;&amp;), OR (||), NOT (!), and round parentheses.</span></span> <span data-ttu-id="2289c-455">例: (A | |B) &amp; &amp; !C.</span><span class="sxs-lookup"><span data-stu-id="2289c-455">For example: (A || B) &amp;&amp; !C.</span></span> <span data-ttu-id="2289c-456">式には、Or のみが使用されている場合は、最大で 20 タグが含まれてことができます。</span><span class="sxs-lookup"><span data-stu-id="2289c-456">If an expression uses only ORs, it can contain at most 20 tags.</span></span> <span data-ttu-id="2289c-457">その他の式は、6 つのタグに制限されます。</span><span class="sxs-lookup"><span data-stu-id="2289c-457">Other expressions are limited to 6 tags.</span></span> <span data-ttu-id="2289c-458">1 つのタグ"A"が有効な式であることを注意してください。</span><span class="sxs-lookup"><span data-stu-id="2289c-458">Note that a single tag "A" is a valid expression.</span></span></param>
        <summary><span data-ttu-id="2289c-459">非同期的に (1 つのタグ「タグ」は有効なタグ式) タグ式に通知を送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-459">Asynchronously sends a notification to a tag expression (a single tag "tag" is a valid tag expression).</span></span></summary>
        <returns><span data-ttu-id="2289c-460">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-460">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="2289c-461">通知</span><span class="sxs-lookup"><span data-stu-id="2289c-461">notification</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="2289c-462">通知します。Tag プロパティを null にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="2289c-462">notification.Tag property should be null</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SendTemplateNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendTemplateNotificationAsync(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendTemplateNotificationAsync (properties As IDictionary(Of String, String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendTemplateNotificationAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendTemplateNotificationAsync properties" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="2289c-463">テンプレートのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="2289c-463">The properties of the template.</span></span></param>
        <summary><span data-ttu-id="2289c-464">テンプレート通知を非同期的に送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-464">Asynchronously sends a template notification.</span></span></summary>
        <returns><span data-ttu-id="2289c-465">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-465">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendTemplateNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; properties, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendTemplateNotificationAsync(System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendTemplateNotificationAsync (properties As IDictionary(Of String, String), tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendTemplateNotificationAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendTemplateNotificationAsync (properties, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="2289c-466">テンプレートのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="2289c-466">The properties of the template.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-467">以外の空のセット タグ (最大 20 タグ)。</span><span class="sxs-lookup"><span data-stu-id="2289c-467">A non-empty set of tags (maximum 20 tags).</span></span> <span data-ttu-id="2289c-468">セット内の各文字列は、1 つのタグを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="2289c-468">Each string in the set can contain a single tag.</span></span></param>
        <summary><span data-ttu-id="2289c-469">非同期に非-空タグのセット (最大 20) のテンプレート通知を送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-469">Asynchronously sends a template notification to a non-empty set of tags (maximum 20).</span></span> <span data-ttu-id="2289c-470">これは、ブール型 Or とタグ式と同じ ("| |") です。</span><span class="sxs-lookup"><span data-stu-id="2289c-470">This is equivalent to a tag expression with boolean ORs ("||").</span></span></summary>
        <returns><span data-ttu-id="2289c-471">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-471">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendTemplateNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; properties, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendTemplateNotificationAsync(System.Collections.Generic.IDictionary{System.String,System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendTemplateNotificationAsync (properties As IDictionary(Of String, String), tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendTemplateNotificationAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendTemplateNotificationAsync (properties, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="2289c-472">テンプレートのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="2289c-472">The properties of the template.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="2289c-473">タグ式は、論理演算子を使用して構築された任意のブール式 AND (&amp;&amp;)、または (|)、されません (!)、かっこを丸めるとします。</span><span class="sxs-lookup"><span data-stu-id="2289c-473">A tag expression is any boolean expression constructed using the logical operators AND (&amp;&amp;), OR (||), NOT (!), and round parentheses.</span></span> <span data-ttu-id="2289c-474">例: (A | |B) &amp; &amp; !C.</span><span class="sxs-lookup"><span data-stu-id="2289c-474">For example: (A || B) &amp;&amp; !C.</span></span> <span data-ttu-id="2289c-475">式には、Or のみが使用されている場合は、最大で 20 タグが含まれてことができます。</span><span class="sxs-lookup"><span data-stu-id="2289c-475">If an expression uses only ORs, it can contain at most 20 tags.</span></span> <span data-ttu-id="2289c-476">その他の式は、6 つのタグに制限されます。</span><span class="sxs-lookup"><span data-stu-id="2289c-476">Other expressions are limited to 6 tags.</span></span> <span data-ttu-id="2289c-477">1 つのタグ"A"が有効な式であることを注意してください。</span><span class="sxs-lookup"><span data-stu-id="2289c-477">Note that a single tag "A" is a valid expression.</span></span></param>
        <summary><span data-ttu-id="2289c-478">非同期的に (1 つのタグ「タグ」は有効なタグ式) タグ式に、テンプレート通知を送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-478">Asynchronously sends a template notification to a tag expression (a single tag "tag" is a valid tag expression).</span></span></summary>
        <returns><span data-ttu-id="2289c-479">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-479">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendWindowsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync (string windowsNativePayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync(string windowsNativePayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendWindowsNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendWindowsNativeNotificationAsync (windowsNativePayload As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendWindowsNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendWindowsNativeNotificationAsync windowsNativePayload" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="windowsNativePayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="windowsNativePayload"><span data-ttu-id="2289c-480">Windows ネイティブ ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-480">The Windows native payload.</span></span></param>
        <summary><span data-ttu-id="2289c-481">Windows のネイティブ通知を非同期的に送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-481">Asynchronously sends a Windows native notification.</span></span> <span data-ttu-id="2289c-482">WNS のヘッダーを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="2289c-482">To specify headers for WNS, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="2289c-483">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-483">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendWindowsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync (string windowsNativePayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync(string windowsNativePayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendWindowsNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendWindowsNativeNotificationAsync (windowsNativePayload As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendWindowsNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendWindowsNativeNotificationAsync (windowsNativePayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="windowsNativePayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="windowsNativePayload"><span data-ttu-id="2289c-484">Windows ネイティブ ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-484">The Windows native payload.</span></span></param>
        <param name="tags"><span data-ttu-id="2289c-485">以外の空のセット タグ (最大 20 タグ)。</span><span class="sxs-lookup"><span data-stu-id="2289c-485">A non-empty set of tags (max 20 tags).</span></span> <span data-ttu-id="2289c-486">セット内の各文字列は、1 つのタグを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="2289c-486">Each string in the set can contain a single tag.</span></span></param>
        <summary><span data-ttu-id="2289c-487">非同期に非-空タグのセット (最大 20) の Windows ネイティブ通知を送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-487">Asynchronously sends a Windows native notification to a non-empty set of tags (max 20).</span></span> <span data-ttu-id="2289c-488">これは、ブール型 Or とタグ式と同じ ("| |") です。</span><span class="sxs-lookup"><span data-stu-id="2289c-488">This is equivalent to a tag expression with boolean ORs ("||").</span></span> <span data-ttu-id="2289c-489">WNS のヘッダーを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="2289c-489">To specify headers for WNS, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="2289c-490">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-490">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendWindowsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync (string windowsNativePayload, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync(string windowsNativePayload, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendWindowsNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendWindowsNativeNotificationAsync (windowsNativePayload As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendWindowsNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendWindowsNativeNotificationAsync (windowsNativePayload, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="windowsNativePayload" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="windowsNativePayload"><span data-ttu-id="2289c-491">Windows ネイティブ ペイロード。</span><span class="sxs-lookup"><span data-stu-id="2289c-491">The Windows native payload.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="2289c-492">タグ式は、論理演算子を使用して構築された任意のブール式 AND (&amp;&amp;)、または (|)、されません (!)、かっこを丸めるとします。</span><span class="sxs-lookup"><span data-stu-id="2289c-492">A tag expression is any boolean expression constructed using the logical operators AND (&amp;&amp;), OR (||), NOT (!), and round parentheses.</span></span> <span data-ttu-id="2289c-493">例: (A | |B) &amp; &amp; !C.</span><span class="sxs-lookup"><span data-stu-id="2289c-493">For example: (A || B) &amp;&amp; !C.</span></span> <span data-ttu-id="2289c-494">式には、Or のみが使用されている場合は、最大で 20 タグが含まれてことができます。</span><span class="sxs-lookup"><span data-stu-id="2289c-494">If an expression uses only ORs, it can contain at most 20 tags.</span></span> <span data-ttu-id="2289c-495">その他の式は、6 つのタグに制限されます。</span><span class="sxs-lookup"><span data-stu-id="2289c-495">Other expressions are limited to 6 tags.</span></span> <span data-ttu-id="2289c-496">1 つのタグ"A"が有効な式であることを注意してください。</span><span class="sxs-lookup"><span data-stu-id="2289c-496">Note that a single tag "A" is a valid expression.</span></span></param>
        <summary><span data-ttu-id="2289c-497">(1 つのタグ「タグ」は有効なタグ式) タグ式に、Windows ネイティブ通知を非同期的に送信します。</span><span class="sxs-lookup"><span data-stu-id="2289c-497">Asynchronously sends a Windows native notification to a tag expression (a single tag "tag" is a valid tag expression).</span></span> <span data-ttu-id="2289c-498">WNS のヘッダーを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="2289c-498">To specify headers for WNS, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="2289c-499">非同期操作を完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-499">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitNotificationHubJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; SubmitNotificationHubJobAsync (Microsoft.Azure.NotificationHubs.NotificationHubJob job);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; SubmitNotificationHubJobAsync(class Microsoft.Azure.NotificationHubs.NotificationHubJob job) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubmitNotificationHubJobAsync (job As NotificationHubJob) As Task(Of NotificationHubJob)" />
      <MemberSignature Language="F#" Value="member this.SubmitNotificationHubJobAsync : Microsoft.Azure.NotificationHubs.NotificationHubJob -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;" Usage="notificationHubClient.SubmitNotificationHubJobAsync job" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.NotificationHubs.NotificationHubJob" />
      </Parameters>
      <Docs>
        <param name="job"><span data-ttu-id="2289c-500"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />登録をエクスポートするには、登録をインポートまたは登録を作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-500">The <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" /> to export registrations, import registrations, or create registrations.</span></span></param>
        <summary>
            <span data-ttu-id="2289c-501"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" /> を作成します。</span><span class="sxs-lookup"><span data-stu-id="2289c-501">Creates a <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />.</span></span> <span data-ttu-id="2289c-502">この API は、標準の名前空間のできるだけです。</span><span class="sxs-lookup"><span data-stu-id="2289c-502">This API is only available for Standard namespaces.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2289c-503">送信済み<see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s。</span><span class="sxs-lookup"><span data-stu-id="2289c-503">The submitted <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRegistrationAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; UpdateRegistrationAsync&lt;T&gt; (T registration) where T : Microsoft.Azure.NotificationHubs.RegistrationDescription;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!!T&gt; UpdateRegistrationAsync&lt;(class Microsoft.Azure.NotificationHubs.RegistrationDescription) T&gt;(!!T registration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.UpdateRegistrationAsync``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRegistrationAsync(Of T As RegistrationDescription) (registration As T) As Task(Of T)" />
      <MemberSignature Language="F#" Value="member this.UpdateRegistrationAsync : 'T -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)&gt; (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)" Usage="notificationHubClient.UpdateRegistrationAsync registration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <BaseTypeName>Microsoft.Azure.NotificationHubs.RegistrationDescription</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="registration" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="2289c-504">登録の型。</span><span class="sxs-lookup"><span data-stu-id="2289c-504">The type of registration.</span></span></typeparam>
        <param name="registration"><span data-ttu-id="2289c-505">更新する登録です。</span><span class="sxs-lookup"><span data-stu-id="2289c-505">The registration to update.</span></span></param>
        <summary><span data-ttu-id="2289c-506">非同期的に、登録を更新します。</span><span class="sxs-lookup"><span data-stu-id="2289c-506">Asynchronously updates the registration.</span></span></summary>
        <returns><span data-ttu-id="2289c-507">更新プログラムが終了するときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="2289c-507">A task that will complete when the update finishes.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="2289c-508">RegistrationId または ETag オブジェクトが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2289c-508">Thrown when RegistrationId or ETag object is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>