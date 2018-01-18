<Type Name="FabricTransientException" FullName="System.Fabric.FabricTransientException">
  <TypeSignature Language="C#" Value="public class FabricTransientException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricTransientException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricTransientException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransientException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricTransientException = class&#xA;    inherit FabricException" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.MaintainabilityRules", "SA1402:FileMayOnlyContainASingleClass", Justification="Exception")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="c2d2c-101">この例外は、一時的な環境またはランタイム環境のため、操作の失敗を示します。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-101">The exception that indicates failure of an operation due to a transient environmental or runtime circumstance.</span></span></para>
      <para><span data-ttu-id="c2d2c-102">処理<see cref="T:System.Fabric.FabricTransientException" />の<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">信頼性の高いコレクション</see>: ユーザーが推奨されているこの例外をキャッチし、トランザクションを中止し、新しいトランザクションですべての操作を再試行してください</span><span class="sxs-lookup"><span data-stu-id="c2d2c-102">Handling <see cref="T:System.Fabric.FabricTransientException" /> for <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">Reliable Collections</see> : The user is suggested to catch this exception, abort the transaction and retry all operations with a new Transaction</span></span>
                </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="c2d2c-103">たとえばレプリカのクォーラムが一時的に到達不能状態に陥ったことが原因で操作に失敗する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-103">For example, an operation may fail because a quorum of replicas is temporarily not reachable.</span></span> <span data-ttu-id="c2d2c-104"><see cref="T:System.Fabric.FabricTransientException" />を再試行する失敗した操作に対応しています。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-104">The <see cref="T:System.Fabric.FabricTransientException" /> corresponds to failed operations that can be tried again.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransientException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricTransientException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="c2d2c-105">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricTransientException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.Unknown" />です。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-105">Initializes a new instance of <see cref="T:System.Fabric.FabricTransientException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.Unknown" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransientException (System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricTransientException.#ctor(System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricTransientException : System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricTransientException" Usage="new System.Fabric.FabricTransientException errorCode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="errorCode">
          <para><span data-ttu-id="c2d2c-106">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-106">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c2d2c-107">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricTransientException" />クラスを指定したエラー コード。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-107">Initializes a new instance of <see cref="T:System.Fabric.FabricTransientException" /> class with a specified error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransientException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricTransientException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricTransientException : string -&gt; System.Fabric.FabricTransientException" Usage="new System.Fabric.FabricTransientException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="c2d2c-108">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-108">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c2d2c-109">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricTransientException" />メッセージが指定されたクラスです。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-109">Initializes a new instance of <see cref="T:System.Fabric.FabricTransientException" /> class with a specified message.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricTransientException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricTransientException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricTransientException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricTransientException" Usage="new System.Fabric.FabricTransientException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
          <para><span data-ttu-id="c2d2c-110"><see cref="T:System.Runtime.Serialization.SerializationInfo" />を含むオブジェクトがスローされた例外オブジェクト データをシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-110">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="c2d2c-111">転送元または転送先に関するコンテキスト情報を格納する <see cref="T:System.Runtime.Serialization.StreamingContext" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-111">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="c2d2c-112">Context パラメーターは将来使用するために予約されており、null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-112">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c2d2c-113">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricTransientException" />、指定した情報を持つクラス コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-113">Initializes a new instance of <see cref="T:System.Fabric.FabricTransientException" /> class with specified info, context.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransientException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricTransientException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricTransientException : string * Exception -&gt; System.Fabric.FabricTransientException" Usage="new System.Fabric.FabricTransientException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="c2d2c-114">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-114">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="c2d2c-115">内部例外が指定されていない場合、現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-115">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="c2d2c-116"><see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-116">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c2d2c-117">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricTransientException" />指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-117">Initializes a new instance of <see cref="T:System.Fabric.FabricTransientException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransientException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricTransientException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricTransientException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricTransientException" Usage="new System.Fabric.FabricTransientException (message, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="c2d2c-118">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-118">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="c2d2c-119">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-119">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c2d2c-120">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricTransientException" />クラスを指定したメッセージとエラー コード。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-120">Initializes a new instance of <see cref="T:System.Fabric.FabricTransientException" /> class with specified message and error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricTransientException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricTransientException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricTransientException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricTransientException" Usage="new System.Fabric.FabricTransientException (info, context, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="info">
          <para><span data-ttu-id="c2d2c-121"><see cref="T:System.Runtime.Serialization.SerializationInfo" />を含むオブジェクトがスローされた例外オブジェクト データをシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-121">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="c2d2c-122">転送元または転送先に関するコンテキスト情報を格納する <see cref="T:System.Runtime.Serialization.StreamingContext" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-122">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="c2d2c-123">Context パラメーターは将来使用するために予約されており、null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-123">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="c2d2c-124">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-124">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c2d2c-125">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricTransientException" />クラスを指定した情報、コンテキストおよびエラー コード。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-125">Initializes a new instance of <see cref="T:System.Fabric.FabricTransientException" /> class with specified info, context and error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransientException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricTransientException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricTransientException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricTransientException" Usage="new System.Fabric.FabricTransientException (message, inner, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="c2d2c-126">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-126">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="c2d2c-127">内部例外が指定されていない場合、現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-127">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="c2d2c-128"><see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-128">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="c2d2c-129">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-129">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c2d2c-130">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricTransientException" />クラスを指定したエラー メッセージ、この例外と、指定されたエラー コードの原因となった内部例外への参照。</span><span class="sxs-lookup"><span data-stu-id="c2d2c-130">Initializes a new instance of <see cref="T:System.Fabric.FabricTransientException" /> class with a specified error message, a reference to the inner exception that is the cause of this exception, and a specified error code.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>