<Type Name="OutputDirectory" FullName="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory">
  <TypeSignature Language="C#" Value="public class OutputDirectory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutputDirectory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory" />
  <TypeSignature Language="VB.NET" Value="Public Class OutputDirectory" />
  <TypeSignature Language="F#" Value="type OutputDirectory = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cc0c8-101">ジョブの出力ディレクトリです。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-101">Output directory for the job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputDirectory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cc0c8-102">OutputDirectory クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-102">Initializes a new instance of the OutputDirectory class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputDirectory (string id, string pathPrefix, string pathSuffix = null, string type = null, Nullable&lt;bool&gt; createNew = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string pathPrefix, string pathSuffix, string type, valuetype System.Nullable`1&lt;bool&gt; createNew) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, pathPrefix As String, Optional pathSuffix As String = null, Optional type As String = null, Optional createNew As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.OutputDirectory : string * string * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.OutputDirectory" Usage="new Microsoft.Azure.Management.BatchAI.Models.OutputDirectory (id, pathPrefix, pathSuffix, type, createNew)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="pathPrefix" Type="System.String" />
        <Parameter Name="pathSuffix" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="createNew" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="cc0c8-103">出力ディレクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-103">The name for the output directory.</span></span></param>
        <param name="pathPrefix"><span data-ttu-id="cc0c8-104">出力ディレクトリを作成するプレフィックスのパス。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-104">The prefix path where the output directory will be created.</span></span></param>
        <param name="pathSuffix"><span data-ttu-id="cc0c8-105">出力ディレクトリを作成するサフィックス パスです。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-105">The suffix path where the output directory will be created.</span></span></param>
        <param name="type"><span data-ttu-id="cc0c8-106">ジョブの出力ディレクトリの種類を指定する列挙です。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-106">An enumeration, which specifies the type of job output directory.</span></span></param>
        <param name="createNew"><span data-ttu-id="cc0c8-107">新しいディレクトリを作成する場合は true です。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-107">True to create new directory.</span></span></param>
        <summary>
            <span data-ttu-id="cc0c8-108">OutputDirectory クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-108">Initializes a new instance of the OutputDirectory class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNew">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CreateNew { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CreateNew" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.CreateNew" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateNew As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CreateNew : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.CreateNew" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createNew")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc0c8-109">取得または設定を新しいディレクトリを作成する場合。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-109">Gets or sets true to create new directory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="cc0c8-110">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-110">Default is true.</span></span> <span data-ttu-id="cc0c8-111">False の場合、ディレクトリは作成されていないと、ユーザーが指定したディレクトリのパスを指定できます。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-111">If false, then the directory is not created and can be any directory path that the user specifies.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc0c8-112">取得または出力ディレクトリの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-112">Gets or sets the name for the output directory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="cc0c8-113">AZ_BATCHAI_OUTPUT_id 環境変数として、ジョブの利用可能な場合もなります。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-113">It will be available for the job as an environment variable under AZ_BATCHAI_OUTPUT_id.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PathPrefix">
      <MemberSignature Language="C#" Value="public string PathPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PathPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.PathPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property PathPrefix As String" />
      <MemberSignature Language="F#" Value="member this.PathPrefix : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.PathPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pathPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc0c8-114">取得または出力ディレクトリを作成するプレフィックスのパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-114">Gets or sets the prefix path where the output directory will be created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="cc0c8-115">注: これは、プレフィックスへの絶対パスです。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-115">NOTE: This is an absolute path to prefix.</span></span> <span data-ttu-id="cc0c8-116">例: </span><span class="sxs-lookup"><span data-stu-id="cc0c8-116">E.g.</span></span>
            <span data-ttu-id="cc0c8-117">$AZ_BATCHAI_MOUNT_ROOT/MyNFS/MyLogs です。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-117">$AZ_BATCHAI_MOUNT_ROOT/MyNFS/MyLogs.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PathSuffix">
      <MemberSignature Language="C#" Value="public string PathSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PathSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.PathSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property PathSuffix As String" />
      <MemberSignature Language="F#" Value="member this.PathSuffix : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.PathSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pathSuffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc0c8-118">取得または出力ディレクトリを作成するサフィックスのパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-118">Gets or sets the suffix path where the output directory will be created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="cc0c8-119">出力ディレクトリを作成するサフィックス パスです。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-119">The suffix path where the output directory will be created.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc0c8-120">取得または出力ディレクトリのジョブの種類を指定する列挙体を設定します。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-120">Gets or sets an enumeration, which specifies the type of job output directory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="cc0c8-121">既定値は、カスタムです。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-121">Default value is Custom.</span></span> <span data-ttu-id="cc0c8-122">使用可能な値は、モデル、ログ、概要、およびカスタムです。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-122">The possible values are Model, Logs, Summary, and Custom.</span></span> <span data-ttu-id="cc0c8-123">ユーザーは、1 つのディレクトリに複数の列挙型を使用できます。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-123">Users can use multiple enums for a single directory.</span></span> <span data-ttu-id="cc0c8-124">例:</span><span class="sxs-lookup"><span data-stu-id="cc0c8-124">Eg.</span></span> <span data-ttu-id="cc0c8-125">outPutType 'モデルでは、ログ、Summary' を = です。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-125">outPutType='Model,Logs, Summary'.</span></span> <span data-ttu-id="cc0c8-126">使用可能な値が含まれます: 'モデル'、'ログ'、'概要'、'custom'</span><span class="sxs-lookup"><span data-stu-id="cc0c8-126">Possible values include: 'model', 'logs', 'summary', 'custom'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="outputDirectory.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cc0c8-127">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-127">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cc0c8-128">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cc0c8-128">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>