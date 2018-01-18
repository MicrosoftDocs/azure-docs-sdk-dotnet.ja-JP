<Type Name="FabricInvalidAtomicGroupException" FullName="System.Fabric.FabricInvalidAtomicGroupException">
  <TypeSignature Language="C#" Value="public class FabricInvalidAtomicGroupException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricInvalidAtomicGroupException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricInvalidAtomicGroupException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricInvalidAtomicGroupException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricInvalidAtomicGroupException = class&#xA;    inherit FabricException" />
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
      <para><span data-ttu-id="191ab-101">Service Fabric atomic グループが有効ではない場合にスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="191ab-101">The exception that is thrown when the Service Fabric atomic group is invalid.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidAtomicGroupException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidAtomicGroupException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="191ab-102">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidAtomicGroupException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.Unknown" />です。</span><span class="sxs-lookup"><span data-stu-id="191ab-102">Initializes a new instance of <see cref="T:System.Fabric.FabricInvalidAtomicGroupException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.Unknown" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidAtomicGroupException (System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidAtomicGroupException.#ctor(System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidAtomicGroupException : System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricInvalidAtomicGroupException" Usage="new System.Fabric.FabricInvalidAtomicGroupException errorCode" />
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
          <para><span data-ttu-id="191ab-103">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="191ab-103">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="191ab-104">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidAtomicGroupException" />クラスを指定したエラー コード。</span><span class="sxs-lookup"><span data-stu-id="191ab-104">Initializes a new instance of <see cref="T:System.Fabric.FabricInvalidAtomicGroupException" /> class with a specified error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidAtomicGroupException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidAtomicGroupException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidAtomicGroupException : string -&gt; System.Fabric.FabricInvalidAtomicGroupException" Usage="new System.Fabric.FabricInvalidAtomicGroupException message" />
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
          <para><span data-ttu-id="191ab-105">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="191ab-105">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="191ab-106">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidAtomicGroupException" />指定したエラー メッセージを使用します。</span><span class="sxs-lookup"><span data-stu-id="191ab-106">Initializes a new instance of <see cref="T:System.Fabric.FabricInvalidAtomicGroupException" /> with a specified error message.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricInvalidAtomicGroupException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidAtomicGroupException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidAtomicGroupException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricInvalidAtomicGroupException" Usage="new System.Fabric.FabricInvalidAtomicGroupException (info, context)" />
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
          <para><span data-ttu-id="191ab-107"><see cref="T:System.Runtime.Serialization.SerializationInfo" />を含むオブジェクトがスローされた例外オブジェクト データをシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="191ab-107">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="191ab-108">転送元または転送先に関するコンテキスト情報を格納する <see cref="T:System.Runtime.Serialization.StreamingContext" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="191ab-108">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="191ab-109">Context パラメーターは将来使用するために予約されており、null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="191ab-109">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="191ab-110">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidAtomicGroupException" />コンテキストを指定して、シリアル化されたオブジェクトのデータからのクラスです。</span><span class="sxs-lookup"><span data-stu-id="191ab-110">Initializes a new instance of <see cref="T:System.Fabric.FabricInvalidAtomicGroupException" /> class from a serialized object data, with a specified context.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidAtomicGroupException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidAtomicGroupException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidAtomicGroupException : string * Exception -&gt; System.Fabric.FabricInvalidAtomicGroupException" Usage="new System.Fabric.FabricInvalidAtomicGroupException (message, inner)" />
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
          <para><span data-ttu-id="191ab-111">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="191ab-111">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="191ab-112">内部例外が指定されていない場合、現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="191ab-112">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="191ab-113"><see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="191ab-113">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="191ab-114">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidAtomicGroupException" />指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="191ab-114">Initializes a new instance of <see cref="T:System.Fabric.FabricInvalidAtomicGroupException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidAtomicGroupException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidAtomicGroupException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidAtomicGroupException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricInvalidAtomicGroupException" Usage="new System.Fabric.FabricInvalidAtomicGroupException (message, errorCode)" />
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
          <para><span data-ttu-id="191ab-115">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="191ab-115">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="191ab-116">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="191ab-116">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="191ab-117">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidAtomicGroupException" />クラスを指定したメッセージとエラー コード。</span><span class="sxs-lookup"><span data-stu-id="191ab-117">Initializes a new instance of <see cref="T:System.Fabric.FabricInvalidAtomicGroupException" /> class with specified message and error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricInvalidAtomicGroupException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidAtomicGroupException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidAtomicGroupException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricInvalidAtomicGroupException" Usage="new System.Fabric.FabricInvalidAtomicGroupException (info, context, errorCode)" />
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
          <para><span data-ttu-id="191ab-118"><see cref="T:System.Runtime.Serialization.SerializationInfo" />を含むオブジェクトがスローされた例外オブジェクト データをシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="191ab-118">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="191ab-119">転送元または転送先に関するコンテキスト情報を格納する <see cref="T:System.Runtime.Serialization.StreamingContext" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="191ab-119">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="191ab-120">Context パラメーターは将来使用するために予約されており、null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="191ab-120">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="191ab-121">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="191ab-121">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="191ab-122">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidAtomicGroupException" />指定のコンテキストとエラー コードを含む、シリアル化されたオブジェクトのデータからのクラスです。</span><span class="sxs-lookup"><span data-stu-id="191ab-122">Initializes a new instance of <see cref="T:System.Fabric.FabricInvalidAtomicGroupException" /> class from a serialized object data, with specified context and error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidAtomicGroupException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidAtomicGroupException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidAtomicGroupException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricInvalidAtomicGroupException" Usage="new System.Fabric.FabricInvalidAtomicGroupException (message, inner, errorCode)" />
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
          <para><span data-ttu-id="191ab-123">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="191ab-123">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="191ab-124">内部例外が指定されていない場合、現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="191ab-124">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="191ab-125"><see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="191ab-125">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="191ab-126">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="191ab-126">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="191ab-127">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricInvalidAtomicGroupException" />クラスを指定したエラー メッセージ、この例外と、指定されたエラー コードの原因となった内部例外への参照。</span><span class="sxs-lookup"><span data-stu-id="191ab-127">Initializes a new instance of <see cref="T:System.Fabric.FabricInvalidAtomicGroupException" /> class with a specified error message, a reference to the inner exception that is the cause of this exception, and a specified error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>