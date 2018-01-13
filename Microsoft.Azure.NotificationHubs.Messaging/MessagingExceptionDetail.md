<Type Name="MessagingExceptionDetail" FullName="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail">
  <TypeSignature Language="C#" Value="public sealed class MessagingExceptionDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessagingExceptionDetail extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessagingExceptionDetail" />
  <TypeSignature Language="F#" Value="type MessagingExceptionDetail = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="c45f4-101">メッセージングの例外の詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="c45f4-101">Provides the details of the messaging exception.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CorrelationFiltersExceeded">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail CorrelationFiltersExceeded (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail CorrelationFiltersExceeded(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.CorrelationFiltersExceeded(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CorrelationFiltersExceeded (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member CorrelationFiltersExceeded : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.CorrelationFiltersExceeded message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="c45f4-102">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c45f4-102">The descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="c45f4-103">関連付けフィルターの例外の詳細を返しますでは、エラーを超えました。</span><span class="sxs-lookup"><span data-stu-id="c45f4-103">Returns the exception details for the correlation filters exceeded error.</span></span></summary>
        <returns><span data-ttu-id="c45f4-104">関連付けフィルターの例外の詳細は、エラーを超えています。</span><span class="sxs-lookup"><span data-stu-id="c45f4-104">The exception details for the correlation filters exceeded error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityConflict">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityConflict (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityConflict(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityConflict(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityConflict (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityConflict : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityConflict message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="c45f4-105">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c45f4-105">The descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="c45f4-106">エンティティの競合エラーは例外の詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="c45f4-106">Returns the exception details for the entity conflict error.</span></span></summary>
        <returns><span data-ttu-id="c45f4-107">エンティティの競合エラーは例外の詳細。</span><span class="sxs-lookup"><span data-stu-id="c45f4-107">The exception details for the entity conflict error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityConflictOperationInProgress">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityConflictOperationInProgress (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityConflictOperationInProgress(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityConflictOperationInProgress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityConflictOperationInProgress (entityName As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityConflictOperationInProgress : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityConflictOperationInProgress entityName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="c45f4-108">エンティティの名前。</span><span class="sxs-lookup"><span data-stu-id="c45f4-108">Name of the entity.</span></span></param>
        <summary>
            <span data-ttu-id="c45f4-109">新しいインスタンスを作成、 <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" /> ConflictOperationInProgress エラー コードを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="c45f4-109">Creates a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" /> class with ConflictOperationInProgress error code.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c45f4-110">Exception クラスのインスタンス</span><span class="sxs-lookup"><span data-stu-id="c45f4-110">The exception class instance</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityGone">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityGone (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityGone(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityGone(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityGone (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityGone : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityGone message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="c45f4-111">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c45f4-111">The descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="c45f4-112">エンティティになったエラーの例外の詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="c45f4-112">Returns the exception details for the entity gone error.</span></span></summary>
        <returns><span data-ttu-id="c45f4-113">エンティティの例外の詳細は、エラーになった。</span><span class="sxs-lookup"><span data-stu-id="c45f4-113">The exception details for the entity gone error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityNotFound">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityNotFound (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityNotFound(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityNotFound(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityNotFound (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityNotFound : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityNotFound message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="c45f4-114">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c45f4-114">The descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="c45f4-115">エンティティが見つからないというエラーの例外の詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="c45f4-115">Returns the exception details for the entity not found error.</span></span></summary>
        <returns><span data-ttu-id="c45f4-116">エンティティの例外の詳細には、エラーで見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="c45f4-116">The exception details for the entity not found error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityUpdateConflict">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityUpdateConflict (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityUpdateConflict(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityUpdateConflict(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityUpdateConflict (entityName As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityUpdateConflict : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityUpdateConflict entityName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="c45f4-117">エンティティの名前。</span><span class="sxs-lookup"><span data-stu-id="c45f4-117">The name of the entity.</span></span></param>
        <summary><span data-ttu-id="c45f4-118">エンティティの更新の競合エラーは例外の詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="c45f4-118">Returns the exception details for the entity update conflict error.</span></span></summary>
        <returns><span data-ttu-id="c45f4-119">エンティティの例外の詳細は、競合エラーを更新します。</span><span class="sxs-lookup"><span data-stu-id="c45f4-119">The exception details for the entity update conflict error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public int ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As Integer" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : int" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c45f4-120">エラー コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="c45f4-120">Gets the error code.</span></span></summary>
        <value><span data-ttu-id="c45f4-121">エラー コード。</span><span class="sxs-lookup"><span data-stu-id="c45f4-121">The error code.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorLevel">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevelType ErrorLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail/ErrorLevelType ErrorLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorLevel As MessagingExceptionDetail.ErrorLevelType" />
      <MemberSignature Language="F#" Value="member this.ErrorLevel : Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevelType" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail+ErrorLevelType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c45f4-122">エラー レベルを取得します。</span><span class="sxs-lookup"><span data-stu-id="c45f4-122">Gets the error level.</span></span></summary>
        <value><span data-ttu-id="c45f4-123">値のいずれか、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevelType" />列挙します。</span><span class="sxs-lookup"><span data-stu-id="c45f4-123">One of the values of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevelType" /> enumeration.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubAtFullCapacity">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EventHubAtFullCapacity (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EventHubAtFullCapacity(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EventHubAtFullCapacity(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EventHubAtFullCapacity (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EventHubAtFullCapacity : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EventHubAtFullCapacity message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="c45f4-124">例外メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c45f4-124">The exception message.</span></span></param>
        <summary>
            <span data-ttu-id="c45f4-125">新しいインスタンスを作成、 <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" /> EventHubAtFullCapacity エラー コードを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="c45f4-125">Creates a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" /> class with EventHubAtFullCapacity error code.</span></span>
            </summary>
        <returns><span data-ttu-id="c45f4-126">Exception クラスのインスタンス</span><span class="sxs-lookup"><span data-stu-id="c45f4-126">The exception class instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c45f4-127">例外についてのわかりやすいメッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="c45f4-127">Gets the descriptive message about the exception.</span></span></summary>
        <value><span data-ttu-id="c45f4-128">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c45f4-128">The descriptive message about the exception.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReconstructExceptionDetail">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail ReconstructExceptionDetail (int errorCode, string message, Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevelType errorLevel);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail ReconstructExceptionDetail(int32 errorCode, string message, valuetype Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail/ErrorLevelType errorLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ReconstructExceptionDetail(System.Int32,System.String,Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevelType)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReconstructExceptionDetail (errorCode As Integer, message As String, errorLevel As MessagingExceptionDetail.ErrorLevelType) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member ReconstructExceptionDetail : int * string * Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevelType -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ReconstructExceptionDetail (errorCode, message, errorLevel)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="errorCode" Type="System.Int32" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorLevel" Type="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail+ErrorLevelType" />
      </Parameters>
      <Docs>
        <param name="errorCode"><span data-ttu-id="c45f4-129">エラー コード。</span><span class="sxs-lookup"><span data-stu-id="c45f4-129">The error code.</span></span></param>
        <param name="message"><span data-ttu-id="c45f4-130">例外メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c45f4-130">The exception message.</span></span></param>
        <param name="errorLevel"><span data-ttu-id="c45f4-131">エラー レベル。</span><span class="sxs-lookup"><span data-stu-id="c45f4-131">The error level.</span></span></param>
        <summary>
            <span data-ttu-id="c45f4-132">新しいインスタンスを作成、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" />クラスをカスタム エラー コード。</span><span class="sxs-lookup"><span data-stu-id="c45f4-132">Creates a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" /> class with a custom error code.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c45f4-133">Exception クラスのインスタンス</span><span class="sxs-lookup"><span data-stu-id="c45f4-133">The exception class instance</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerBusy">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail ServerBusy (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail ServerBusy(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ServerBusy(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ServerBusy (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member ServerBusy : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ServerBusy message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="c45f4-134">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c45f4-134">The descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="c45f4-135">Server busy エラー例外の詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="c45f4-135">Returns the exception details for the server busy error.</span></span></summary>
        <returns><span data-ttu-id="c45f4-136">サーバーの例外の詳細には、エラーがビジー状態です。</span><span class="sxs-lookup"><span data-stu-id="c45f4-136">The exception details for the server busy error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlFiltersExceeded">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail SqlFiltersExceeded (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail SqlFiltersExceeded(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.SqlFiltersExceeded(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlFiltersExceeded (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member SqlFiltersExceeded : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.SqlFiltersExceeded message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="c45f4-137">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c45f4-137">The descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="c45f4-138">SQL フィルターの例外の詳細を返しますでは、エラーを超えました。</span><span class="sxs-lookup"><span data-stu-id="c45f4-138">Returns the exception details for the SQL filters exceeded error.</span></span></summary>
        <returns><span data-ttu-id="c45f4-139">SQL フィルターの例外の詳細は、エラーを超えています。</span><span class="sxs-lookup"><span data-stu-id="c45f4-139">The exception details for the SQL filters exceeded error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreLockLost">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail StoreLockLost (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail StoreLockLost(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.StoreLockLost(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function StoreLockLost (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member StoreLockLost : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.StoreLockLost message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="c45f4-140">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c45f4-140">The descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="c45f4-141">返します。 ストアの例外の詳細は、失われたエラーをロックします。</span><span class="sxs-lookup"><span data-stu-id="c45f4-141">Returns the exception details for the store lock lost error.</span></span></summary>
        <returns><span data-ttu-id="c45f4-142">ストアの例外の詳細は、失われたエラーをロックします。</span><span class="sxs-lookup"><span data-stu-id="c45f4-142">The exception details for the store lock lost error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionsExceeded">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail SubscriptionsExceeded (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail SubscriptionsExceeded(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.SubscriptionsExceeded(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SubscriptionsExceeded (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member SubscriptionsExceeded : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.SubscriptionsExceeded message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="c45f4-143">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c45f4-143">The descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="c45f4-144">サブスクリプションの場合、例外の詳細を返しますでは、エラーを超えました。</span><span class="sxs-lookup"><span data-stu-id="c45f4-144">Returns the exception details for the subscriptions exceeded error.</span></span></summary>
        <returns><span data-ttu-id="c45f4-145">サブスクリプションの場合、例外の詳細は、エラーを超えています。</span><span class="sxs-lookup"><span data-stu-id="c45f4-145">The exception details for the subscriptions exceeded error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnknownDetail">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail UnknownDetail (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail UnknownDetail(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.UnknownDetail(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UnknownDetail (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member UnknownDetail : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.UnknownDetail message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="c45f4-146">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c45f4-146">The descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="c45f4-147">不明な詳細エラーの例外の詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="c45f4-147">Returns the exception details for the unknown detail error.</span></span></summary>
        <returns><span data-ttu-id="c45f4-148">不明な詳細エラーの例外の詳細。</span><span class="sxs-lookup"><span data-stu-id="c45f4-148">The exception details for the unknown detail error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnspecifiedInternalError">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail UnspecifiedInternalError (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail UnspecifiedInternalError(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.UnspecifiedInternalError(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UnspecifiedInternalError (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member UnspecifiedInternalError : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.UnspecifiedInternalError message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="c45f4-149">例外に関する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c45f4-149">The descriptive message about the exception.</span></span></param>
        <summary><span data-ttu-id="c45f4-150">未指定の内部エラーの例外の詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="c45f4-150">Returns the exception details for the unspecified internal error.</span></span></summary>
        <returns><span data-ttu-id="c45f4-151">未指定の内部エラーの例外の詳細。</span><span class="sxs-lookup"><span data-stu-id="c45f4-151">The exception details for the unspecified internal error.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>