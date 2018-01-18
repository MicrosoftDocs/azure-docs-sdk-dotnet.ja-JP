<Type Name="MessagingEntityAlreadyExistsException" FullName="Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException">
  <TypeSignature Language="C#" Value="public sealed class MessagingEntityAlreadyExistsException : Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessagingEntityAlreadyExistsException extends Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessagingEntityAlreadyExistsException&#xA;Inherits MessagingException" />
  <TypeSignature Language="F#" Value="type MessagingEntityAlreadyExistsException = class&#xA;    inherit MessagingException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessagingException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="60c07-101">エラーが存在するメッセージング エンティティを既にシグナリングに対してスローされる例外を表します。</span><span class="sxs-lookup"><span data-stu-id="60c07-101">Represents the exception that is thrown for signaling messaging entity already exists errors.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityAlreadyExistsException (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (entityName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException : string -&gt; Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException" Usage="new Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException entityName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="60c07-102">エンティティの名前。</span><span class="sxs-lookup"><span data-stu-id="60c07-102">The name of the entity.</span></span></param>
        <summary><span data-ttu-id="60c07-103">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException" />エンティティの名前を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="60c07-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException" /> class with the name of the entity.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityAlreadyExistsException (string entityName, Microsoft.ServiceBus.Tracing.TrackingContext trackingContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string entityName, class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException.#ctor(System.String,Microsoft.ServiceBus.Tracing.TrackingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException : string * Microsoft.ServiceBus.Tracing.TrackingContext -&gt; Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException" Usage="new Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException (entityName, trackingContext)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
      </Parameters>
      <Docs>
        <param name="entityName"> <span data-ttu-id="60c07-104">エンティティの名前。</span><span class="sxs-lookup"><span data-stu-id="60c07-104">Name of the entity.</span></span> </param>
        <param name="trackingContext"> <span data-ttu-id="60c07-105">TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="60c07-105">The TrackingContext.</span></span> </param>
        <summary> <span data-ttu-id="60c07-106">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="60c07-106">Constructor.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEntityAlreadyExistsException (string message, Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException.#ctor(System.String,Microsoft.ServiceBus.Tracing.TrackingContext,System.Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException : string * Microsoft.ServiceBus.Tracing.TrackingContext * Exception -&gt; Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException" Usage="new Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException (message, trackingContext, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">        <span data-ttu-id="60c07-107">メッセージ。</span><span class="sxs-lookup"><span data-stu-id="60c07-107">The message.</span></span> </param>
        <param name="trackingContext"> <span data-ttu-id="60c07-108">追跡コンテキスト</span><span class="sxs-lookup"><span data-stu-id="60c07-108">the tracking context</span></span></param>
        <param name="innerException"> <span data-ttu-id="60c07-109">内部例外。</span><span class="sxs-lookup"><span data-stu-id="60c07-109">The inner exception.</span></span> </param>
        <summary> <span data-ttu-id="60c07-110">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="60c07-110">Constructor.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="messagingEntityAlreadyExistsException.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="60c07-111">スローされた例外に関するシリアル化されたオブジェクト データ。</span><span class="sxs-lookup"><span data-stu-id="60c07-111">The serialized object data about the exception being thrown.</span></span></param>
        <param name="context"><span data-ttu-id="60c07-112">転送元または変換先に関する文脈情報。</span><span class="sxs-lookup"><span data-stu-id="60c07-112">The contextual information about the source or destinations.</span></span></param>
        <summary><span data-ttu-id="60c07-113">例外に関するデータをシリアル化情報を追加します。</span><span class="sxs-lookup"><span data-stu-id="60c07-113">Populates the serialization information with data about the exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>