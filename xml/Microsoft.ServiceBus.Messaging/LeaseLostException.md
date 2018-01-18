<Type Name="LeaseLostException" FullName="Microsoft.ServiceBus.Messaging.LeaseLostException">
  <TypeSignature Language="C#" Value="public class LeaseLostException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit LeaseLostException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.LeaseLostException" />
  <TypeSignature Language="VB.NET" Value="Public Class LeaseLostException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type LeaseLostException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="1106d-101">サービスのリースが失われたときに発生する例外を表します。</span><span class="sxs-lookup"><span data-stu-id="1106d-101">Represents an exception that occurs when the service lease has been lost.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LeaseLostException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.LeaseLostException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="1106d-102">既定値を使用して <see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1106d-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" /> class using default values.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LeaseLostException (Microsoft.ServiceBus.Messaging.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.Messaging.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.LeaseLostException.#ctor(Microsoft.ServiceBus.Messaging.Lease)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.LeaseLostException : Microsoft.ServiceBus.Messaging.Lease -&gt; Microsoft.ServiceBus.Messaging.LeaseLostException" Usage="new Microsoft.ServiceBus.Messaging.LeaseLostException lease" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="1106d-103">メッセージのリースです。</span><span class="sxs-lookup"><span data-stu-id="1106d-103">The messaging lease.</span></span></param>
        <summary><span data-ttu-id="1106d-104">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" />クラスの指定されたリースを使用します。</span><span class="sxs-lookup"><span data-stu-id="1106d-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" /> class using specified lease.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LeaseLostException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.LeaseLostException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.LeaseLostException : string -&gt; Microsoft.ServiceBus.Messaging.LeaseLostException" Usage="new Microsoft.ServiceBus.Messaging.LeaseLostException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="1106d-105">エラーに関連付けられているメッセージ。</span><span class="sxs-lookup"><span data-stu-id="1106d-105">The message associated with the error.</span></span></param>
        <summary><span data-ttu-id="1106d-106">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" />クラスの指定したエラー メッセージを使用します。</span><span class="sxs-lookup"><span data-stu-id="1106d-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" /> class using specified error message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LeaseLostException (Microsoft.ServiceBus.Messaging.Lease lease, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.Messaging.Lease lease, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.LeaseLostException.#ctor(Microsoft.ServiceBus.Messaging.Lease,System.Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.LeaseLostException : Microsoft.ServiceBus.Messaging.Lease * Exception -&gt; Microsoft.ServiceBus.Messaging.LeaseLostException" Usage="new Microsoft.ServiceBus.Messaging.LeaseLostException (lease, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="1106d-107">メッセージのリースです。</span><span class="sxs-lookup"><span data-stu-id="1106d-107">The messaging lease.</span></span></param>
        <param name="innerException"><span data-ttu-id="1106d-108">例外の原因となったエラー。</span><span class="sxs-lookup"><span data-stu-id="1106d-108">The error that caused the exception.</span></span></param>
        <summary><span data-ttu-id="1106d-109">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" />クラスの指定されたリースと、例外の原因となったエラーを使用します。</span><span class="sxs-lookup"><span data-stu-id="1106d-109">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" /> class using specified lease and the error that caused the exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected LeaseLostException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.LeaseLostException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.LeaseLostException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.ServiceBus.Messaging.LeaseLostException" Usage="new Microsoft.ServiceBus.Messaging.LeaseLostException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="1106d-110">例外に関するシリアル化された情報です。</span><span class="sxs-lookup"><span data-stu-id="1106d-110">The serialized information about the exception.</span></span></param>
        <param name="context"><span data-ttu-id="1106d-111">転送元または転送先に関するコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="1106d-111">The contextual information about the source or destination.</span></span></param>
        <summary><span data-ttu-id="1106d-112">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" />クラスの指定した情報とコンテキストを使用します。</span><span class="sxs-lookup"><span data-stu-id="1106d-112">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" /> class using specified information and context.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LeaseLostException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.LeaseLostException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.LeaseLostException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.LeaseLostException" Usage="new Microsoft.ServiceBus.Messaging.LeaseLostException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="1106d-113">エラーに関連付けられているメッセージ。</span><span class="sxs-lookup"><span data-stu-id="1106d-113">The message associated with the error.</span></span></param>
        <param name="innerException"><span data-ttu-id="1106d-114">例外の原因となったエラー。</span><span class="sxs-lookup"><span data-stu-id="1106d-114">The error that caused the exception.</span></span></param>
        <summary><span data-ttu-id="1106d-115">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" />クラスを使用するエラー メッセージと内部例外を指定します。</span><span class="sxs-lookup"><span data-stu-id="1106d-115">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" /> class using specified error message and inner exception.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.LeaseLostException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="leaseLostException.GetObjectData (info, context)" />
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
        <param name="info"><span data-ttu-id="1106d-116">データを読み込む先の <see cref="T:System.Runtime.Serialization.SerializationInfo" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1106d-116">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object to populate with data.</span></span></param>
        <param name="context"><span data-ttu-id="1106d-117">宛先 (StreamingContext を参照してください) このシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="1106d-117">The destination (see StreamingContext) for this serialization.</span></span></param>
        <summary><span data-ttu-id="1106d-118"><see cref="T:System.Runtime.Serialization.SerializationInfo" /> に、対象のオブジェクトをシリアル化するために必要なデータを設定します。</span><span class="sxs-lookup"><span data-stu-id="1106d-118">Populates a <see cref="T:System.Runtime.Serialization.SerializationInfo" /> with the data needed to serialize the target object.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lease">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.Lease Lease { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.Lease Lease" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.LeaseLostException.Lease" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Lease As Lease" />
      <MemberSignature Language="F#" Value="member this.Lease : Microsoft.ServiceBus.Messaging.Lease" Usage="Microsoft.ServiceBus.Messaging.LeaseLostException.Lease" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.Lease</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="1106d-119">取得またはサービス リースを設定します。</span><span class="sxs-lookup"><span data-stu-id="1106d-119">Gets or sets the service lease.</span></span></summary>
        <value><span data-ttu-id="1106d-120">サービス リースします。</span><span class="sxs-lookup"><span data-stu-id="1106d-120">The service lease.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>