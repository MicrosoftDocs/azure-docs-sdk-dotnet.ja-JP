<Type Name="TransferException" FullName="Microsoft.WindowsAzure.Storage.DataMovement.TransferException">
  <TypeSignature Language="C#" Value="public class TransferException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit TransferException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type TransferException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="483a5-101">Blob/FileTransferJobs によってスローされた例外の基本例外クラスです。</span><span class="sxs-lookup"><span data-stu-id="483a5-101">Base exception class for exceptions thrown by Blob/FileTransferJobs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="483a5-102"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="483a5-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException (Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As TransferErrorCode)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException errorCode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode" />
      </Parameters>
      <Docs>
        <param name="errorCode"><span data-ttu-id="483a5-103">エラー コードを転送します。</span><span class="sxs-lookup"><span data-stu-id="483a5-103">Transfer error code.</span></span></param>
        <summary>
            <span data-ttu-id="483a5-104"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="483a5-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : string -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="483a5-105">エラーを説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="483a5-105">The message that describes the error.</span></span></param>
        <summary>
            <span data-ttu-id="483a5-106"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="483a5-106">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException (Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As TransferErrorCode, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode * string -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException (errorCode, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="errorCode"><span data-ttu-id="483a5-107">エラー コードを転送します。</span><span class="sxs-lookup"><span data-stu-id="483a5-107">Transfer error code.</span></span></param>
        <param name="message"><span data-ttu-id="483a5-108">例外メッセージ。</span><span class="sxs-lookup"><span data-stu-id="483a5-108">Exception message.</span></span></param>
        <summary>
            <span data-ttu-id="483a5-109"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="483a5-109">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TransferException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="483a5-110">シリアル化情報。</span><span class="sxs-lookup"><span data-stu-id="483a5-110">Serialization information.</span></span></param>
        <param name="context"><span data-ttu-id="483a5-111">ストリーミング コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="483a5-111">Streaming context.</span></span></param>
        <summary>
            <span data-ttu-id="483a5-112"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="483a5-112">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException (string message, Exception ex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception ex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, ex As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : string * Exception -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException (message, ex)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="ex" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="483a5-113">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="483a5-113">The error message that explains the reason for the exception.</span></span></param>
        <param name="ex"><span data-ttu-id="483a5-114">内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="483a5-114">The exception that is the cause of the current exception, or a null reference if no inner exception is specified.</span></span></param>
        <summary>
            <span data-ttu-id="483a5-115"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="483a5-115">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferException (Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode, string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode errorCode, string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.#ctor(Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As TransferErrorCode, message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException : Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode * string * Exception -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferException" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferException (errorCode, message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="errorCode"><span data-ttu-id="483a5-116">エラー コードを転送します。</span><span class="sxs-lookup"><span data-stu-id="483a5-116">Transfer error code.</span></span></param>
        <param name="message"><span data-ttu-id="483a5-117">例外メッセージ。</span><span class="sxs-lookup"><span data-stu-id="483a5-117">Exception message.</span></span></param>
        <param name="innerException"><span data-ttu-id="483a5-118">内部例外。</span><span class="sxs-lookup"><span data-stu-id="483a5-118">Inner exception.</span></span></param>
        <summary>
            <span data-ttu-id="483a5-119"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="483a5-119">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As TransferErrorCode" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferException.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.DataMovement.TransferErrorCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="483a5-120">詳細なエラー コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="483a5-120">Gets the detailed error code.</span></span>
            </summary>
        <value><span data-ttu-id="483a5-121">例外のエラー コード。</span><span class="sxs-lookup"><span data-stu-id="483a5-121">The error code of the exception.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="transferException.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="483a5-122">シリアル化情報オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="483a5-122">Serialization info object.</span></span></param>
        <param name="context"><span data-ttu-id="483a5-123">ストリーミング コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="483a5-123">Streaming context.</span></span></param>
        <summary>
            <span data-ttu-id="483a5-124">例外をシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="483a5-124">Serializes the exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>