<Type Name="MessagingEntityAlreadyExistsException" FullName="Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException">
  <TypeSignature Language="C#" Value="public sealed class MessagingEntityAlreadyExistsException : Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessagingEntityAlreadyExistsException extends Microsoft.Azure.NotificationHubs.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessagingEntityAlreadyExistsException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type MessagingEntityAlreadyExistsException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="6f638-101">エラーが存在するメッセージング エンティティを既にシグナリングに対してスローされる例外を表します。</span><span class="sxs-lookup"><span data-stu-id="6f638-101">Represents the exception that is thrown for signaling messaging entity already exists errors.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityAlreadyExistsException (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (entityName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException entityName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="6f638-102">エンティティの名前。</span><span class="sxs-lookup"><span data-stu-id="6f638-102">The name of the entity.</span></span></param>
        <summary><span data-ttu-id="6f638-103">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" />エンティティの名前を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="6f638-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" /> class with the name of the entity.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityAlreadyExistsException (string entityName, Microsoft.Azure.NotificationHubs.Tracing.TrackingContext trackingContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string entityName, class Microsoft.Azure.NotificationHubs.Tracing.TrackingContext trackingContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException.#ctor(System.String,Microsoft.Azure.NotificationHubs.Tracing.TrackingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException : string * Microsoft.Azure.NotificationHubs.Tracing.TrackingContext -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException (entityName, trackingContext)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="trackingContext" Type="Microsoft.Azure.NotificationHubs.Tracing.TrackingContext" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="6f638-104">エンティティの名前。</span><span class="sxs-lookup"><span data-stu-id="6f638-104">The name of the entity.</span></span></param>
        <param name="trackingContext"><span data-ttu-id="6f638-105">操作の追跡、トランザクションが関連付けられているコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="6f638-105">The context information associated by a transaction tracking the operation.</span></span></param>
        <summary><span data-ttu-id="6f638-106"><see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6f638-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityAlreadyExistsException (string message, Microsoft.Azure.NotificationHubs.Tracing.TrackingContext trackingContext, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class Microsoft.Azure.NotificationHubs.Tracing.TrackingContext trackingContext, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException.#ctor(System.String,Microsoft.Azure.NotificationHubs.Tracing.TrackingContext,System.Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException : string * Microsoft.Azure.NotificationHubs.Tracing.TrackingContext * Exception -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" Usage="new Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException (message, trackingContext, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="trackingContext" Type="Microsoft.Azure.NotificationHubs.Tracing.TrackingContext" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="6f638-107">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="6f638-107">The error message that explains the reason for the exception.</span></span></param>
        <param name="trackingContext"><span data-ttu-id="6f638-108">操作の追跡、トランザクションが関連付けられているコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="6f638-108">The context information associated by a transaction tracking the operation.</span></span></param>
        <param name="innerException"><span data-ttu-id="6f638-109">現在の例外の原因となった内部例外。</span><span class="sxs-lookup"><span data-stu-id="6f638-109">The inner exception that is the cause of the current exception.</span></span></param>
        <summary><span data-ttu-id="6f638-110"><see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6f638-110">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingEntityAlreadyExistsException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="messagingEntityAlreadyExistsException.GetObjectData (info, context)" />
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
        <param name="info"><span data-ttu-id="6f638-111">スローされた例外に関するシリアル化されたオブジェクト データ。</span><span class="sxs-lookup"><span data-stu-id="6f638-111">The serialized object data about the exception being thrown.</span></span></param>
        <param name="context"><span data-ttu-id="6f638-112">転送元または変換先に関する文脈情報。</span><span class="sxs-lookup"><span data-stu-id="6f638-112">The contextual information about the source or destinations.</span></span></param>
        <summary><span data-ttu-id="6f638-113">例外に関するデータをシリアル化情報を追加します。</span><span class="sxs-lookup"><span data-stu-id="6f638-113">Populates the serialization information with data about the exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>