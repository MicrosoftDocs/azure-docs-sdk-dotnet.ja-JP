<Type Name="MessagingExceptionDetail" FullName="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail">
  <TypeSignature Language="C#" Value="public sealed class MessagingExceptionDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessagingExceptionDetail extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessagingExceptionDetail" />
  <TypeSignature Language="F#" Value="type MessagingExceptionDetail = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="e0d8a-101">メッセージングの例外の詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-101">Provides the details of the messaging exception.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CorrelationFiltersExceeded">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail CorrelationFiltersExceeded (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail CorrelationFiltersExceeded(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.CorrelationFiltersExceeded(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CorrelationFiltersExceeded (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member CorrelationFiltersExceeded : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.CorrelationFiltersExceeded message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="e0d8a-102">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-102">A descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="e0d8a-103">関連付けフィルターの例外の詳細を返しますでは、エラーを超えました。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-103">Returns the exception details for the correlation filters exceeded error.</span></span></summary>
        <returns><span data-ttu-id="e0d8a-104">関連付けフィルターの例外の詳細は、エラーを超えています。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-104">The exception details for the correlation filters exceeded error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataCommunicationError">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail DataCommunicationError (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail DataCommunicationError(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.DataCommunicationError(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DataCommunicationError (entityName As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member DataCommunicationError : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.DataCommunicationError entityName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityConflict">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityConflict (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityConflict(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityConflict(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityConflict (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityConflict : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityConflict message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="e0d8a-105">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-105">A descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="e0d8a-106">エンティティの競合エラーは例外の詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-106">Returns the exception details for the entity conflict error.</span></span></summary>
        <returns><span data-ttu-id="e0d8a-107">エンティティの競合エラーは例外の詳細。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-107">The exception details for the entity conflict error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityConflictOperationInProgress">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityConflictOperationInProgress (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityConflictOperationInProgress(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityConflictOperationInProgress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityConflictOperationInProgress (entityName As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityConflictOperationInProgress : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityConflictOperationInProgress entityName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="e0d8a-108">メッセージング エンティティの名前です。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-108">The name of the messaging entity.</span></span></param>
        <summary><span data-ttu-id="e0d8a-109">進行中のエラーで、エンティティの競合は例外の詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-109">Returns the exception details for an entity conflict in progress error.</span></span> <span data-ttu-id="e0d8a-110">競合する作成が既にある場合に発生するしたり対象のエンティティに対する保留中の呼び出しを削除できます。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-110">This can occur if there is already a conflicting create or delete call pending on the entity in question.</span></span></summary>
        <returns><span data-ttu-id="e0d8a-111"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-111">Returns <see cref="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityGone">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityGone (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityGone(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityGone(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityGone (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityGone : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityGone message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="e0d8a-112">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-112">A descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="e0d8a-113">エンティティになったエラーの例外の詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-113">Returns the exception details for the entity gone error.</span></span></summary>
        <returns><span data-ttu-id="e0d8a-114">エンティティの例外の詳細は、エラーになった。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-114">The exception details for the entity gone error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityNotFound">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityNotFound (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityNotFound(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityNotFound(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityNotFound (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityNotFound : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityNotFound message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="e0d8a-115">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-115">A descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="e0d8a-116">エンティティが見つからないというエラーの例外の詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-116">Returns the exception details for the entity not found error.</span></span></summary>
        <returns><span data-ttu-id="e0d8a-117">エンティティの例外の詳細には、エラーで見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-117">The exception details for the entity not found error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityUpdateConflict">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityUpdateConflict (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityUpdateConflict(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityUpdateConflict(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityUpdateConflict (entityName As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityUpdateConflict : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityUpdateConflict entityName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="e0d8a-118">エンティティの名前。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-118">The name of the entity.</span></span></param>
        <summary><span data-ttu-id="e0d8a-119">エンティティの更新の競合エラーは例外の詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-119">Returns the exception details for the entity update conflict error.</span></span></summary>
        <returns><span data-ttu-id="e0d8a-120">エンティティの例外の詳細は、競合エラーを更新します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-120">The exception details for the entity update conflict error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public int ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As Integer" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : int" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e0d8a-121">エラー コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-121">Gets the error code.</span></span></summary>
        <value><span data-ttu-id="e0d8a-122">エラー コード。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-122">The error code.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorLevel">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorLevelType ErrorLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.MessagingExceptionDetail/ErrorLevelType ErrorLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorLevel As MessagingExceptionDetail.ErrorLevelType" />
      <MemberSignature Language="F#" Value="member this.ErrorLevel : Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorLevelType" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail+ErrorLevelType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e0d8a-123">エラー レベルを取得します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-123">Gets the error level.</span></span></summary>
        <value><span data-ttu-id="e0d8a-124">値のいずれか、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorLevelType" />列挙します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-124">One of the values of the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorLevelType" /> enumeration.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubAtFullCapacity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EventHubAtFullCapacity (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EventHubAtFullCapacity(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EventHubAtFullCapacity(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EventHubAtFullCapacity (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EventHubAtFullCapacity : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EventHubAtFullCapacity message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="e0d8a-125">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-125">A descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="e0d8a-126">返し例外の詳細と、Event Hub が最大能力で返します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-126">Returns the exception details when an Event Hub is at full capacity.</span></span> </summary>
        <returns><span data-ttu-id="e0d8a-127"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-127">Returns <see cref="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e0d8a-128">例外についてのわかりやすいメッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-128">Gets the descriptive message about the exception.</span></span></summary>
        <value><span data-ttu-id="e0d8a-129">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-129">The descriptive message about the exception.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublisherRevoked">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail PublisherRevoked (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail PublisherRevoked(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.PublisherRevoked(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PublisherRevoked (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member PublisherRevoked : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.PublisherRevoked message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="e0d8a-130">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-130">A descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="e0d8a-131">例外に関する詳細と、Event Hubs のパブリッシャーを返しますが取り消されました。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-131">Returns the exception details when an Event Hubs publisher has been revoked.</span></span></summary>
        <returns><span data-ttu-id="e0d8a-132"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-132">Returns <see cref="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerBusy">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail ServerBusy (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail ServerBusy(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ServerBusy(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ServerBusy (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member ServerBusy : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ServerBusy message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="e0d8a-133">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-133">A descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="e0d8a-134">Server busy エラー例外の詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-134">Returns the exception details for the server busy error.</span></span></summary>
        <returns><span data-ttu-id="e0d8a-135">サーバーの例外の詳細には、エラーがビジー状態です。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-135">The exception details for the server busy error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlFiltersExceeded">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail SqlFiltersExceeded (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail SqlFiltersExceeded(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.SqlFiltersExceeded(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlFiltersExceeded (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member SqlFiltersExceeded : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.SqlFiltersExceeded message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="e0d8a-136">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-136">A descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="e0d8a-137">SQL フィルターの例外の詳細を返しますでは、エラーを超えました。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-137">Returns the exception details for the SQL filters exceeded error.</span></span></summary>
        <returns><span data-ttu-id="e0d8a-138">SQL フィルターの例外の詳細は、エラーを超えています。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-138">The exception details for the SQL filters exceeded error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreLockLost">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail StoreLockLost (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail StoreLockLost(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.StoreLockLost(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function StoreLockLost (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member StoreLockLost : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.StoreLockLost message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="e0d8a-139">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-139">A descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="e0d8a-140">返します。 ストアの例外の詳細は、失われたエラーをロックします。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-140">Returns the exception details for the store lock lost error.</span></span></summary>
        <returns><span data-ttu-id="e0d8a-141">ストアの例外の詳細は、失われたエラーをロックします。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-141">The exception details for the store lock lost error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionsExceeded">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail SubscriptionsExceeded (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail SubscriptionsExceeded(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.SubscriptionsExceeded(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SubscriptionsExceeded (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member SubscriptionsExceeded : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.SubscriptionsExceeded message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="e0d8a-142">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-142">A descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="e0d8a-143">サブスクリプションの場合、例外の詳細を返しますでは、エラーを超えました。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-143">Returns the exception details for the subscriptions exceeded error.</span></span></summary>
        <returns><span data-ttu-id="e0d8a-144">サブスクリプションの場合、例外の詳細は、エラーを超えています。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-144">The exception details for the subscriptions exceeded error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnknownDetail">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail UnknownDetail (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail UnknownDetail(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.UnknownDetail(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UnknownDetail (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member UnknownDetail : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.UnknownDetail message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="e0d8a-145">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-145">A descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="e0d8a-146">不明な詳細エラーの例外の詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-146">Returns the exception details for the unknown detail error.</span></span></summary>
        <returns><span data-ttu-id="e0d8a-147">不明な詳細エラーの例外の詳細。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-147">The exception details for the unknown detail error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnspecifiedInternalError">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail UnspecifiedInternalError (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail UnspecifiedInternalError(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.UnspecifiedInternalError(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UnspecifiedInternalError (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member UnspecifiedInternalError : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.UnspecifiedInternalError message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="e0d8a-148">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-148">A descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="e0d8a-149">未指定の内部エラーの例外の詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-149">Returns the exception details for the unspecified internal error.</span></span></summary>
        <returns><span data-ttu-id="e0d8a-150">未指定の内部エラーの例外の詳細。</span><span class="sxs-lookup"><span data-stu-id="e0d8a-150">The exception details for the unspecified internal error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>