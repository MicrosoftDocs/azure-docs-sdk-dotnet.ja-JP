<Type Name="FabricNotReadableException" FullName="System.Fabric.FabricNotReadableException">
  <TypeSignature Language="C#" Value="public class FabricNotReadableException : System.Fabric.FabricTransientException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricNotReadableException extends System.Fabric.FabricTransientException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricNotReadableException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricNotReadableException&#xA;Inherits FabricTransientException" />
  <TypeSignature Language="F#" Value="type FabricNotReadableException = class&#xA;    inherit FabricTransientException" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricTransientException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.MaintainabilityRules", "SA1402:FileMayOnlyContainASingleClass", Justification="Exception")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="2c1cf-101">サービス パーティションとレプリカのどちらに同意できない場合にスローされる例外を読み取ります。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-101">The exception that is thrown when a service partition or a replica cannot accept reads.</span></span>
            </para>
    </summary>
    <remarks>
      <para>
            <span data-ttu-id="2c1cf-102">例外は、次の 2 つのシナリオに表示されることができます。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-102">The exception can be seen in the following 2 scenarios :</span></span>
                1. <span data-ttu-id="2c1cf-103">パーティションには、読み取りのクォーラムがありません。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-103">The partition does not have a read quorum.</span></span>
                2. <span data-ttu-id="2c1cf-104">サービスがからを読み取ろうとして、 <see href="https://msdn.microsoft.com/library/azure/dn707635.aspx">IdleSecondary レプリカ</see>です。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-104">The service is trying to read from an <see href="https://msdn.microsoft.com/library/azure/dn707635.aspx">IdleSecondary replica</see>.</span></span>
            </para>
      <para>
            <span data-ttu-id="2c1cf-105">処理<see cref="T:System.Fabric.FabricNotReadableException" />の<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">信頼性の高いコレクション</see>: 場合<see cref="T:System.Fabric.FabricNotReadableException" />がサービスに表示され、クライアントの呼び出しで例外をキャッチする必要があります、現在のトランザクションを破棄する必要がありますを新しいすべての操作を再試行する必要がありますトランザクション オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-105">Handling <see cref="T:System.Fabric.FabricNotReadableException" /> for <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">Reliable Collections</see> : If <see cref="T:System.Fabric.FabricNotReadableException" /> is seen by the service or a client call, the exception should be caught, current transaction should be disposed and all the operations should be retried with a new transaction object.</span></span>
            <span data-ttu-id="2c1cf-106">読み取りの状態は最終的に付与するまたは非再試行可能な例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-106">Read status will eventually be granted or a non-retriable exception will be thrown.</span></span> <span data-ttu-id="2c1cf-107">省略可能なバックオフを再試行する前に追加できます。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-107">An optional backoff can be added before retrying.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricNotReadableException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricNotReadableException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="2c1cf-108">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricNotReadableException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.Unknown" />です。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-108">Initializes a new instance of <see cref="T:System.Fabric.FabricNotReadableException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.Unknown" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricNotReadableException (System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricNotReadableException.#ctor(System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricNotReadableException : System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricNotReadableException" Usage="new System.Fabric.FabricNotReadableException errorCode" />
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
          <para><span data-ttu-id="2c1cf-109">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-109">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2c1cf-110">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricNotReadableException" />クラスを指定したエラー コード。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-110">Initializes a new instance of <see cref="T:System.Fabric.FabricNotReadableException" /> class with a specified error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricNotReadableException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricNotReadableException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricNotReadableException : string -&gt; System.Fabric.FabricNotReadableException" Usage="new System.Fabric.FabricNotReadableException message" />
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
          <para><span data-ttu-id="2c1cf-111">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-111">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2c1cf-112">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricNotReadableException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.Unknown" />と指定したエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-112">Initializes a new instance of <see cref="T:System.Fabric.FabricNotReadableException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.Unknown" /> and a specified error message.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricNotReadableException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricNotReadableException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricNotReadableException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricNotReadableException" Usage="new System.Fabric.FabricNotReadableException (info, context)" />
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
          <para><span data-ttu-id="2c1cf-113"><see cref="T:System.Runtime.Serialization.SerializationInfo" />を含むオブジェクトがスローされた例外オブジェクト データをシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-113">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="2c1cf-114">転送元または転送先に関するコンテキスト情報を格納する <see cref="T:System.Runtime.Serialization.StreamingContext" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-114">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="2c1cf-115">Context パラメーターは将来使用するために予約されており、null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-115">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2c1cf-116">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricNotReadableException" />コンテキストを指定して、シリアル化されたオブジェクトのデータからのクラスです。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-116">Initializes a new instance of <see cref="T:System.Fabric.FabricNotReadableException" /> class from a serialized object data, with a specified context.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricNotReadableException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricNotReadableException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricNotReadableException : string * Exception -&gt; System.Fabric.FabricNotReadableException" Usage="new System.Fabric.FabricNotReadableException (message, inner)" />
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
          <para><span data-ttu-id="2c1cf-117">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-117">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="2c1cf-118">内部例外が指定されていない場合、現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-118">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="2c1cf-119"><see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-119">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="2c1cf-120">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricNotReadableException" />指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-120">Initializes a new instance of <see cref="T:System.Fabric.FabricNotReadableException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricNotReadableException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricNotReadableException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricNotReadableException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricNotReadableException" Usage="new System.Fabric.FabricNotReadableException (message, errorCode)" />
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
          <para><span data-ttu-id="2c1cf-121">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-121">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="2c1cf-122">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-122">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2c1cf-123">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricNotReadableException" />クラスは、指定したエラー メッセージとエラー コード。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-123">Initializes a new instance of <see cref="T:System.Fabric.FabricNotReadableException" /> class with specified error message and error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricNotReadableException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricNotReadableException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricNotReadableException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricNotReadableException" Usage="new System.Fabric.FabricNotReadableException (info, context, errorCode)" />
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
          <para><span data-ttu-id="2c1cf-124"><see cref="T:System.Runtime.Serialization.SerializationInfo" />を含むオブジェクトがスローされた例外オブジェクト データをシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-124">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="2c1cf-125">転送元または転送先に関するコンテキスト情報を格納する <see cref="T:System.Runtime.Serialization.StreamingContext" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-125">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="2c1cf-126">Context パラメーターは将来使用するために予約されており、null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-126">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="2c1cf-127">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-127">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2c1cf-128">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricNotReadableException" />指定のコンテキストとエラー コードを含む、シリアル化されたオブジェクトのデータからのクラスです。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-128">Initializes a new instance of <see cref="T:System.Fabric.FabricNotReadableException" /> class from a serialized object data, with specified context and error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricNotReadableException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricNotReadableException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricNotReadableException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricNotReadableException" Usage="new System.Fabric.FabricNotReadableException (message, inner, errorCode)" />
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
          <para><span data-ttu-id="2c1cf-129">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-129">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="2c1cf-130">内部例外が指定されていない場合、現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-130">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="2c1cf-131"><see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-131">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="2c1cf-132">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-132">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="2c1cf-133">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricNotReadableException" />クラスを指定したエラー メッセージ、この例外と、指定されたエラー コードの原因となった内部例外への参照。</span><span class="sxs-lookup"><span data-stu-id="2c1cf-133">Initializes a new instance of <see cref="T:System.Fabric.FabricNotReadableException" /> class with a specified error message, a reference to the inner exception that is the cause of this exception, and a specified error code.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>