<Type Name="ApplicationType" FullName="System.Fabric.Query.ApplicationType">
  <TypeSignature Language="C#" Value="public sealed class ApplicationType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationType extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ApplicationType" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationType" />
  <TypeSignature Language="F#" Value="type ApplicationType = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="2607c-101">アプリケーションの種類を表します。</span><span class="sxs-lookup"><span data-stu-id="2607c-101">Represents an application type.</span></span></para>
    </summary>
    <remarks>
      <para>
                    <span data-ttu-id="2607c-102">アプリケーションの種類は、サービスの種類の集まりで構成されているアプリケーションの分類です。</span><span class="sxs-lookup"><span data-stu-id="2607c-102">An application type is a categorization of an application and consists of a bundle of service types.</span></span>
                    <span data-ttu-id="2607c-103">詳細については、この説明は<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model">ドキュメント</see>です。</span><span class="sxs-lookup"><span data-stu-id="2607c-103">Details are described in this <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model">document</see>.</span></span>
                </para>
      <para>
                    <span data-ttu-id="2607c-104">アプリケーションの種類には、それを含むサービスのコード パッケージなどの機能を備えたアプリケーションに必要なすべてが含まれます。</span><span class="sxs-lookup"><span data-stu-id="2607c-104">An application type contains all that is needed for a functioning application, such as the code packages for the services it encompasses.</span></span> <span data-ttu-id="2607c-105">アプリケーション マニフェストも含まれています。</span><span class="sxs-lookup"><span data-stu-id="2607c-105">It also contains an application manifest.</span></span> <span data-ttu-id="2607c-106">アプリケーションがアプリケーションの種類からインスタンス化されるときに、アプリケーションの種類に関連付けられているアプリケーション マニフェストを無効にできます。</span><span class="sxs-lookup"><span data-stu-id="2607c-106">When an application is instantiated from an application type, the application manifest associated with the application type can be overridden.</span></span> <span data-ttu-id="2607c-107">アプリケーションを作成する前に、アプリケーションの種類をアップロードする必要があります。</span><span class="sxs-lookup"><span data-stu-id="2607c-107">The application type must be uploaded before an application can be created.</span></span>
                    </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationTypeDefinitionKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ApplicationTypeDefinitionKind ApplicationTypeDefinitionKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ApplicationTypeDefinitionKind ApplicationTypeDefinitionKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.ApplicationTypeDefinitionKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeDefinitionKind As ApplicationTypeDefinitionKind" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeDefinitionKind : System.Fabric.Query.ApplicationTypeDefinitionKind" Usage="System.Fabric.Query.ApplicationType.ApplicationTypeDefinitionKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationTypeDefinitionKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2607c-108">定義の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="2607c-108">Gets the definition kind.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2607c-109">定義の種類の列挙で定義されている値の 1 つを含む<see cref="P:System.Fabric.Query.ApplicationType.ApplicationTypeDefinitionKind" />です。</span><span class="sxs-lookup"><span data-stu-id="2607c-109">The definition kind which contains one of the values defined in the enumeration <see cref="P:System.Fabric.Query.ApplicationType.ApplicationTypeDefinitionKind" />.</span></span></para>
          <para><span data-ttu-id="2607c-110">Service Fabric アプリケーションの種類を定義するユーザー userd メカニズムを指定します。</span><span class="sxs-lookup"><span data-stu-id="2607c-110">Specifies the mechanism the user userd to define a Service Fabric application type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.Query.ApplicationType.ApplicationTypeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2607c-111">アプリケーションの種類名を取得します。</span><span class="sxs-lookup"><span data-stu-id="2607c-111">Gets the application type name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2607c-112">アプリケーション マニフェストで定義されているアプリケーションの種類名です。</span><span class="sxs-lookup"><span data-stu-id="2607c-112">The application type name which is defined in the application manifest.</span></span> <span data-ttu-id="2607c-113">この値は、アプリケーション タイプ バージョンと共に、アプリケーションの種類の一意の識別子を作成します。</span><span class="sxs-lookup"><span data-stu-id="2607c-113">This value, in conjunction with the application type version create a unique identifier for the application type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeVersion">
      <MemberSignature Language="C#" Value="public string ApplicationTypeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.ApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeVersion : string" Usage="System.Fabric.Query.ApplicationType.ApplicationTypeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2607c-114">アプリケーション タイプのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="2607c-114">Gets the application type version.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2607c-115">アプリケーション マニフェストで定義されているアプリケーションの種類のバージョン。</span><span class="sxs-lookup"><span data-stu-id="2607c-115">The application type version which is defined in the application manifest.</span></span> <span data-ttu-id="2607c-116">この値は、アプリケーションの種類名と共に、アプリケーションの種類の一意の識別子を作成します。</span><span class="sxs-lookup"><span data-stu-id="2607c-116">This value, in conjunction with the application type name create a unique identifier for the application type.</span></span> <span data-ttu-id="2607c-117">この値を数値の値にする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="2607c-117">This value need not be numerical in value.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultParameters">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationParameterList DefaultParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ApplicationParameterList DefaultParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.DefaultParameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultParameters As ApplicationParameterList" />
      <MemberSignature Language="F#" Value="member this.DefaultParameters : System.Fabric.Description.ApplicationParameterList" Usage="System.Fabric.Query.ApplicationType.DefaultParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationParameterList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2607c-118">アプリケーションのパラメーターの既定値を取得します。</span><span class="sxs-lookup"><span data-stu-id="2607c-118">Gets the default application parameters.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2607c-119">アプリケーション マニフェストで定義されている既定のアプリケーション パラメーター。</span><span class="sxs-lookup"><span data-stu-id="2607c-119">The default application parameters defined in the application manifest.</span></span> <span data-ttu-id="2607c-120">アプリケーションがこのアプリケーションの種類からインスタンス化されると、これらのパラメータはオーバーライドされない限りを使用します。</span><span class="sxs-lookup"><span data-stu-id="2607c-120">When an application is instantiated from this application type, these are the parameters used unless they are overridden.</span></span> <span data-ttu-id="2607c-121">インスタンス化されたアプリケーションは、このプロパティで定義されているだけでなく定義されている複数のアプリケーション パラメーターもあります。</span><span class="sxs-lookup"><span data-stu-id="2607c-121">The instantiated application may also have more application parameters defined in addition to the ones defined in this property.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ApplicationTypeStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ApplicationTypeStatus Status" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As ApplicationTypeStatus" />
      <MemberSignature Language="F#" Value="member this.Status : System.Fabric.Query.ApplicationTypeStatus" Usage="System.Fabric.Query.ApplicationType.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationTypeStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2607c-122">アプリケーションの種類のステータスを取得します。</span><span class="sxs-lookup"><span data-stu-id="2607c-122">Gets the application type status.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2607c-123">列挙体で定義されている値の 1 つを含むアプリケーションの種類のステータス<see cref="M:System.Fabric.Query.ApplicationTypeStatus.#ctor" />です。</span><span class="sxs-lookup"><span data-stu-id="2607c-123">The application type status which contains one of the values defined in the enumeration <see cref="M:System.Fabric.Query.ApplicationTypeStatus.#ctor" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusDetails">
      <MemberSignature Language="C#" Value="public string StatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDetails" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.StatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.StatusDetails : string" Usage="System.Fabric.Query.ApplicationType.StatusDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2607c-124">アプリケーションの種類のステータスの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="2607c-124">Gets the application type status details.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2607c-125">アプリケーションの種類のステータスの詳細。</span><span class="sxs-lookup"><span data-stu-id="2607c-125">The application type status details.</span></span> <span data-ttu-id="2607c-126">これには、このアプリケーションの種類のプロビジョニングに関連する情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="2607c-126">This contains information pertaining to provisioning of this application type.</span></span>
            <span data-ttu-id="2607c-127">プロビジョニング、中に、進行状況に関する情報が含まれます。</span><span class="sxs-lookup"><span data-stu-id="2607c-127">During provision, this contains progress information.</span></span> <span data-ttu-id="2607c-128">失敗プロビジョニングする必要があります、これにより、エラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="2607c-128">Should provisioning fail, this provides the error message.</span></span>
            <span data-ttu-id="2607c-129">このフィールドは空白のままそれ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="2607c-129">This field is left blank otherwise.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>