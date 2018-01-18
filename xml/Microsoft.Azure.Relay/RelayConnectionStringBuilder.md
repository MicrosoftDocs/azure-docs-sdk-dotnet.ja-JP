<Type Name="RelayConnectionStringBuilder" FullName="Microsoft.Azure.Relay.RelayConnectionStringBuilder">
  <TypeSignature Language="C#" Value="public class RelayConnectionStringBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RelayConnectionStringBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.RelayConnectionStringBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class RelayConnectionStringBuilder" />
  <TypeSignature Language="F#" Value="type RelayConnectionStringBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fccf1-101">作成し、接続文字列の内容を管理します。</span><span class="sxs-lookup"><span data-stu-id="fccf1-101">Creates and manages the contents of connection strings.</span></span> <span data-ttu-id="fccf1-102">このクラスは、リレーの名前空間を操作するための接続文字列を構築するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="fccf1-102">You can use this class to construct a connection string for working with a Relay namespace.</span></span> <span data-ttu-id="fccf1-103">既存の接続文字列で基本的な検証を実行するも使用できます。</span><span class="sxs-lookup"><span data-stu-id="fccf1-103">It can also be used to perform basic validation on an existing connection string.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayConnectionStringBuilder ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayConnectionStringBuilder.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="fccf1-104"><see cref="T:Microsoft.Azure.Relay.RelayConnectionStringBuilder" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fccf1-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Relay.RelayConnectionStringBuilder" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayConnectionStringBuilder (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayConnectionStringBuilder.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.RelayConnectionStringBuilder : string -&gt; Microsoft.Azure.Relay.RelayConnectionStringBuilder" Usage="new Microsoft.Azure.Relay.RelayConnectionStringBuilder connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="fccf1-105">接続文字列、Azure 管理ポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fccf1-105">The connection string, which can be obtained from the Azure Management Portal.</span></span></param>
        <summary>
            <span data-ttu-id="fccf1-106">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Relay.RelayConnectionStringBuilder" />指定した既存の接続文字列にします。</span><span class="sxs-lookup"><span data-stu-id="fccf1-106">Initializes a new instance of a <see cref="T:Microsoft.Azure.Relay.RelayConnectionStringBuilder" /> with a specified existing connection string.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="fccf1-107">ConnectionString が null または空の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fccf1-107">Thrown if connectionString is null or empty.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException">
            <span data-ttu-id="fccf1-108">場合にスロー<see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.OperationTimeout" />は正数でない<see cref="T:System.TimeSpan" />です。</span><span class="sxs-lookup"><span data-stu-id="fccf1-108">Thrown if <see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.OperationTimeout" /> is a non-positive <see cref="T:System.TimeSpan" />.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="fccf1-109">キーまたは値のいずれか、キー値のペアがない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fccf1-109">Thrown if a key value pair is missing either a key or a value.</span></span>
            <span data-ttu-id="fccf1-110">場合にスロー<see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.Endpoint" />が指定されているが、有効な絶対パスではない<see cref="T:System.Uri" />です。</span><span class="sxs-lookup"><span data-stu-id="fccf1-110">Thrown if <see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.Endpoint" /> is specified but is not a valid absolute <see cref="T:System.Uri" />.</span></span>
            <span data-ttu-id="fccf1-111">場合にスロー<see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.OperationTimeout" />が指定されているが、有効ではありません<see cref="T:System.TimeSpan" />形式です。</span><span class="sxs-lookup"><span data-stu-id="fccf1-111">Thrown if <see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.OperationTimeout" /> is specified but is not a valid <see cref="T:System.TimeSpan" /> format.</span></span>
            <span data-ttu-id="fccf1-112">サポートされていないキー名が指定されている場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fccf1-112">Thrown if an unsupported key name is specified.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public Uri Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.Endpoint : Uri with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="fccf1-113">取得またはリレーの名前空間アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="fccf1-113">Gets or sets the Relay namespace address.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="fccf1-114">エンドポイントが設定されている場合にスローされますを null にします。</span><span class="sxs-lookup"><span data-stu-id="fccf1-114">Thrown if Endpoint is being set to null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="fccf1-115">エンドポイント設定されている場合にスローされます、<see cref="T:System.Uri" />絶対ではないです。</span><span class="sxs-lookup"><span data-stu-id="fccf1-115">Thrown if Endpoint is being set to a <see cref="T:System.Uri" />  which is not absolute.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.EntityPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="fccf1-116">取得または、HybridConnection のエンティティのパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="fccf1-116">Gets or sets the entity path for the HybridConnection.</span></span></summary>
        <value><span data-ttu-id="fccf1-117">エンティティのパスを返します。</span><span class="sxs-lookup"><span data-stu-id="fccf1-117">Returns the entity path.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="fccf1-118">取得または設定、<see cref="T:System.TimeSpan" />操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="fccf1-118">Gets or sets the <see cref="T:System.TimeSpan" /> that specifies how long the operation has to complete before timing out.</span></span></summary>
        <value><span data-ttu-id="fccf1-119">操作がタイムアウトまでに完了する必要がある時間を指定する <see cref="T:System.TimeSpan" />。既定値は、1 分です。</span><span class="sxs-lookup"><span data-stu-id="fccf1-119">The <see cref="T:System.TimeSpan" /> that specifies how long the operation has to complete before timing out. The default value is one minute.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="fccf1-120">OperationTimeout が正数でない時間帯に設定されている場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fccf1-120">Thrown if OperationTimeout is set to a non-positive TimeSpan.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKey">
      <MemberSignature Language="C#" Value="public string SharedAccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKey : string with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="fccf1-121">取得または接続の認証用の共有アクセス キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="fccf1-121">Gets or sets the shared access key for the connection authentication.</span></span></summary>
        <value><span data-ttu-id="fccf1-122">接続の認証用の共有アクセス キー。</span><span class="sxs-lookup"><span data-stu-id="fccf1-122">The shared access key for the connection authentication.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKeyName">
      <MemberSignature Language="C#" Value="public string SharedAccessKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKeyName : string with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="fccf1-123">取得または共有アクセス キーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="fccf1-123">Gets or sets the name of the shared access key.</span></span></summary>
        <value><span data-ttu-id="fccf1-124">共有アクセス キーの名前。</span><span class="sxs-lookup"><span data-stu-id="fccf1-124">The name of the shared access key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessSignature">
      <MemberSignature Language="C#" Value="public string SharedAccessSignature { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessSignature" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessSignature" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessSignature As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessSignature : string with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessSignature" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="fccf1-125">取得または SAS トークンを設定します。</span><span class="sxs-lookup"><span data-stu-id="fccf1-125">Gets or sets the SAS token.</span></span></summary>
        <value><span data-ttu-id="fccf1-126">構成された SAS トークンを返します。</span><span class="sxs-lookup"><span data-stu-id="fccf1-126">Returns the configured SAS token.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayConnectionStringBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="relayConnectionStringBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="fccf1-127">現在のオブジェクトを表す接続文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="fccf1-127">Creates a connectionString that represents the current object.</span></span></summary>
        <returns><span data-ttu-id="fccf1-128">現在のオブジェクトを表す接続文字列。</span><span class="sxs-lookup"><span data-stu-id="fccf1-128">A connectionString that represents the current object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>