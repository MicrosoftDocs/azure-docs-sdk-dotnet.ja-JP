<Type Name="MultiShardException" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException">
  <TypeSignature Language="C#" Value="public class MultiShardException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MultiShardException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiShardException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type MultiShardException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1704:IdentifiersShouldBeSpelledCorrectly", MessageId="Multi")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f0e71-101">MultiShardException はシャードに対して操作を実行するときに発生した例外を表します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-101">A MultiShardException represents an exception that occured when performing operations against a shard.</span></span>
            <span data-ttu-id="f0e71-102">シャードと発生した expection 両方 id に関する情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-102">It provides information about both the identity of the shard and the expection that occurred.</span></span>
            <span data-ttu-id="f0e71-103">、例外の性質によって 1 つ、複数のシャードのクエリを再実行してください、ターゲット、expection を得られるをシャードに直接クエリを実行するしたり最後に SSMS などの一般的なツールを使用して、シャードに対して手動でクエリを実行できます。</span><span class="sxs-lookup"><span data-stu-id="f0e71-103">Depending on the nature of the exception, one can try re-running the multi-shard query, execute a separate query targeted directly at the shard(s) on that yielded the expection, or lastly execute the query manually against the shard using a common tool such as SSMS.</span></span>  
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f0e71-104">MultiShardException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-104">Initializes a new instance of the MultiShardException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardException (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.#ctor(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException shardLocation" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="shardLocation" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
      </Parameters>
      <Docs>
        <param name="shardLocation"> <span data-ttu-id="f0e71-105">例外が発生した、シャードの場所を指定します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-105">specifies the location of the shard where the exception occurred.</span></span></param>
        <summary>
            <span data-ttu-id="f0e71-106">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />シャードを指定した場所を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="f0e71-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" /> class with the specified shard location.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"> <span data-ttu-id="f0e71-107">シャードで発生した例外を指定します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-107">specifies the exception encountered at the shard.</span></span></param>
        <summary>
            <span data-ttu-id="f0e71-108">指定されたエラー メッセージで MultiShardException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-108">Initializes a new instance of the MultiShardException class with the specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardException (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.#ctor(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * Exception -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException (shardLocation, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="shardLocation" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="shardLocation"> <span data-ttu-id="f0e71-109">例外が発生した、シャードの場所を指定します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-109">specifies the location of the shard where the exception occurred.</span></span></param>
        <param name="inner"> <span data-ttu-id="f0e71-110">シャードで発生した例外を指定します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-110">specifies the exception encountered at the shard.</span></span></param>
        <summary>
            <span data-ttu-id="f0e71-111">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />クラス シャードを指定した場所と例外を使用します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-111">Initializes a new instance of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" /> class with the specified shard location and exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardException (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.#ctor(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException (shardLocation, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="shardLocation" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardLocation"> <span data-ttu-id="f0e71-112">例外が発生した、シャードの場所を指定します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-112">specifies the location of the shard where the exception occurred.</span></span></param>
        <param name="message"> <span data-ttu-id="f0e71-113">例外の原因を説明するメッセージを指定します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-113">specifices the message that explains the reason for the exception.</span></span></param>
        <summary>
            <span data-ttu-id="f0e71-114">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />シャードを指定した場所とエラー メッセージを使用します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-114">Initializes a new instance of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" /> class with the specified shard location and error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MultiShardException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
            <span data-ttu-id="f0e71-115"><see cref="T:System.Runtime.Serialization.SerializationInfo" />スローされた例外に関するシリアル化されたオブジェクト データを保持するを参照してください。</span><span class="sxs-lookup"><span data-stu-id="f0e71-115">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> see that holds the serialized object data about the exception being thrown.</span></span>
            </param>
        <param name="context">
            <span data-ttu-id="f0e71-116">転送元または転送先についてのコンテキスト情報を含む <see cref="T:System.Runtime.Serialization.StreamingContext" /> です。</span><span class="sxs-lookup"><span data-stu-id="f0e71-116">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> that contains contextual information about the source or destination.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0e71-117">シリアル化されたデータを持つ MultiShardException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-117">Initializes a new instance of the MultiShardException class with serialized data.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException : string * Exception -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"> <span data-ttu-id="f0e71-118">例外の原因を説明するメッセージを指定します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-118">specifices the message that explains the reason for the exception.</span></span></param>
        <param name="innerException"> <span data-ttu-id="f0e71-119">シャードで発生した例外を指定します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-119">specifies the exception encountered at the shard.</span></span></param>
        <summary>
            <span data-ttu-id="f0e71-120">指定されたエラー メッセージとは、この例外の原因となった内部例外への参照を使用して、MultiShardException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-120">Initializes a new instance of the MultiShardException class with the specified error message and the reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardException (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation, string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation, string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.#ctor(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String,System.Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * string * Exception -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException (shardLocation, message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="shardLocation" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="shardLocation"> <span data-ttu-id="f0e71-121">例外が発生した、シャードの場所を指定します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-121">specifies the location of the shard where the exception occurred.</span></span></param>
        <param name="message"> <span data-ttu-id="f0e71-122">例外の原因を説明するメッセージを指定します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-122">specifices the message that explains the reason for the exception.</span></span></param>
        <param name="inner"> <span data-ttu-id="f0e71-123">シャードで発生した例外を指定します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-123">specifies the exception encountered at the shard.</span></span></param>
        <summary>
            <span data-ttu-id="f0e71-124">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />した、シャードを指定した場所のエラー メッセージ、例外が発生しました。</span><span class="sxs-lookup"><span data-stu-id="f0e71-124">Initializes a new instance of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" /> class with the specified shard location, error message and exception encountered.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f0e71-125"><paramref name="shardLocation" />が null です</span><span class="sxs-lookup"><span data-stu-id="f0e71-125">The <paramref name="shardLocation" /> is null</span></span> </exception>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="multiShardException.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
          <span data-ttu-id="f0e71-126"><see cref="T:System.Runtime.Serialization.SerializationInfo" />データを読み込む先のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f0e71-126"><see cref="T:System.Runtime.Serialization.SerializationInfo" /> object to populate with data.</span></span></param>
        <param name="context"><span data-ttu-id="f0e71-127">転送先<see cref="T:System.Runtime.Serialization.StreamingContext" />このシリアル化のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f0e71-127">The destination <see cref="T:System.Runtime.Serialization.StreamingContext" /> object for this serialization.</span></span></param>
        <summary>
            <span data-ttu-id="f0e71-128">指定された設定<see cref="T:System.Runtime.Serialization.SerializationInfo" />ターゲット オブジェクトをシリアル化データとパラメーターが必要です。</span><span class="sxs-lookup"><span data-stu-id="f0e71-128">Populates the provided <see cref="T:System.Runtime.Serialization.SerializationInfo" /> parameter with the data needed to serialize the target object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardLocation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation ShardLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation ShardLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.ShardLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ShardLocation As ShardLocation" />
      <MemberSignature Language="F#" Value="member this.ShardLocation : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.ShardLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0e71-129">この例外に関連付けられているシャード</span><span class="sxs-lookup"><span data-stu-id="f0e71-129">The shard associated with this exception</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="multiShardException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f0e71-130">現在の <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" /> の文字列表現を作成して返します。</span><span class="sxs-lookup"><span data-stu-id="f0e71-130">Creates and returns a string representation of the current <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f0e71-131">現在の例外の文字列表現。</span><span class="sxs-lookup"><span data-stu-id="f0e71-131">String representation of the current exception.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>