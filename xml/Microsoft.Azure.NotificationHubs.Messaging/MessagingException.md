<Type Name="MessagingException" FullName="Microsoft.Azure.NotificationHubs.Messaging.MessagingException">
  <TypeSignature Language="C#" Value="public class MessagingException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MessagingException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="VB.NET" Value="Public Class MessagingException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type MessagingException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="2edb5-101">信号メッセージング エラーに対してスローされる例外を表します。</span><span class="sxs-lookup"><span data-stu-id="2edb5-101">Represents the exception that is thrown for signaling messaging errors.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessagingException : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessagingException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="2edb5-102">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="2edb5-102">The error message that explains the reason for the exception.</span></span></param>
        <summary><span data-ttu-id="2edb5-103">指定したエラー メッセージを使用して、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2edb5-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingException" /> class with a specified error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MessagingException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessagingException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessagingException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="2edb5-104">シリアル化情報。</span><span class="sxs-lookup"><span data-stu-id="2edb5-104">The serialization information.</span></span></param>
        <param name="context"><span data-ttu-id="2edb5-105">ストリーム コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="2edb5-105">The streaming context.</span></span></param>
        <summary><span data-ttu-id="2edb5-106">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />クラスをシリアル化情報とストリーム コンテキストを使用します。</span><span class="sxs-lookup"><span data-stu-id="2edb5-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingException" /> class with serialization information and streaming context.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessagingException : string * Exception -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessagingException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="2edb5-107">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="2edb5-107">The error message that explains the reason for the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="2edb5-108">現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="2edb5-108">The exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="2edb5-109">指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2edb5-109">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingException (string message, bool isTransientError, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, bool isTransientError, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingException.#ctor(System.String,System.Boolean,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, isTransientError As Boolean, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessagingException : string * bool * Exception -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessagingException (message, isTransientError, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="isTransientError" Type="System.Boolean" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="2edb5-110">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="2edb5-110">The error message that explains the reason for the exception.</span></span></param>
        <param name="isTransientError"><span data-ttu-id="2edb5-111">例外が; 一時的な場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="2edb5-111">true if the exception is transient; otherwise, false.</span></span></param>
        <param name="innerException"><span data-ttu-id="2edb5-112">現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="2edb5-112">The exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="2edb5-113"><see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2edb5-113">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingException" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public override sealed System.Collections.IDictionary Data { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.IDictionary Data" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.MessagingException.Data" />
      <MemberSignature Language="VB.NET" Value="Public Overrides NotOverridable ReadOnly Property Data As IDictionary" />
      <MemberSignature Language="F#" Value="member this.Data : System.Collections.IDictionary" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingException.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IDictionary</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2edb5-114">例外に関連付けられているデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="2edb5-114">Gets the data associated with the exception.</span></span></summary>
        <value><span data-ttu-id="2edb5-115">例外に関連付けられているデータ。</span><span class="sxs-lookup"><span data-stu-id="2edb5-115">The data associated with the exception.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Detail">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail Detail { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail Detail" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.MessagingException.Detail" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Detail As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="member this.Detail : Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingException.Detail" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2edb5-116">取得またはメッセージングの例外の詳細情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="2edb5-116">Gets or sets the detail information of the messaging exception.</span></span></summary>
        <value><span data-ttu-id="2edb5-117">メッセージングの例外の詳細情報。</span><span class="sxs-lookup"><span data-stu-id="2edb5-117">The detail information of the messaging exception.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="messagingException.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="2edb5-118">スローされた例外に関するシリアル化されたオブジェクト データ。</span><span class="sxs-lookup"><span data-stu-id="2edb5-118">The serialized object data about the exception being thrown.</span></span></param>
        <param name="context"><span data-ttu-id="2edb5-119">転送元または変換先に関する文脈情報。</span><span class="sxs-lookup"><span data-stu-id="2edb5-119">The contextual information about the source or destinations.</span></span></param>
        <summary><span data-ttu-id="2edb5-120">例外に関するデータをシリアル化情報を追加します。</span><span class="sxs-lookup"><span data-stu-id="2edb5-120">Populates the serialization information with data about the exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsTransient">
      <MemberSignature Language="C#" Value="public bool IsTransient { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsTransient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.MessagingException.IsTransient" />
      <MemberSignature Language="VB.NET" Value="Public Property IsTransient As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsTransient : bool with get, set" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingException.IsTransient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2edb5-121">取得または例外が一時的なものかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="2edb5-121">Gets or sets a value indicating whether the exception is transient.</span></span> <span data-ttu-id="2edb5-122">操作を再試行するかどうかを決定するには、このプロパティを確認します。</span><span class="sxs-lookup"><span data-stu-id="2edb5-122">Check this property to determine if the operation should be retried.</span></span></summary>
        <value><span data-ttu-id="2edb5-123">例外が; 一時的な場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="2edb5-123">true if the exception is transient; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTime Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.MessagingException.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTime" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingException.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2edb5-124">取得またはメッセージングの例外が発生した時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="2edb5-124">Gets or sets the time at which the messaging exception occurred.</span></span></summary>
        <value><span data-ttu-id="2edb5-125">メッセージングの例外が発生した時刻。</span><span class="sxs-lookup"><span data-stu-id="2edb5-125">The time at which the messaging exception occurred.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>