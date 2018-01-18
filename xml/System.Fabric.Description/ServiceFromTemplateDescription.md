<Type Name="ServiceFromTemplateDescription" FullName="System.Fabric.Description.ServiceFromTemplateDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceFromTemplateDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceFromTemplateDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceFromTemplateDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceFromTemplateDescription" />
  <TypeSignature Language="F#" Value="type ServiceFromTemplateDescription = class" />
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
            <span data-ttu-id="11a47-101">現在のアプリケーション マニフェストであらかじめ定義されているサービス テンプレートから作成される Service Fabric サービスについて説明します。</span><span class="sxs-lookup"><span data-stu-id="11a47-101">Describes a Service Fabric service to be created from Service Template that is pre-defined in the current Application Manifest.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceFromTemplateDescription (Uri applicationName, Uri serviceName, string serviceDnsName, string serviceTypeName, System.Fabric.Description.ServicePackageActivationMode servicePackageActivationMode, byte[] initializationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, class System.Uri serviceName, string serviceDnsName, string serviceTypeName, valuetype System.Fabric.Description.ServicePackageActivationMode servicePackageActivationMode, unsigned int8[] initializationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceFromTemplateDescription.#ctor(System.Uri,System.Uri,System.String,System.String,System.Fabric.Description.ServicePackageActivationMode,System.Byte[])" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceFromTemplateDescription : Uri * Uri * string * string * System.Fabric.Description.ServicePackageActivationMode * byte[] -&gt; System.Fabric.Description.ServiceFromTemplateDescription" Usage="new System.Fabric.Description.ServiceFromTemplateDescription (applicationName, serviceName, serviceDnsName, serviceTypeName, servicePackageActivationMode, initializationData)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="serviceDnsName" Type="System.String" />
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="servicePackageActivationMode" Type="System.Fabric.Description.ServicePackageActivationMode" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="11a47-102">サービスが作成されるアプリケーションのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="11a47-102">The Service Fabric Name of the application under which the service will be created.</span></span></param>
        <param name="serviceName"><span data-ttu-id="11a47-103">作成するサービスの名前です。</span><span class="sxs-lookup"><span data-stu-id="11a47-103">Name of the service to create.</span></span></param>
        <param name="serviceDnsName"><span data-ttu-id="11a47-104">作成するサービスの DNS 名。</span><span class="sxs-lookup"><span data-stu-id="11a47-104">DNS name of the service to create.</span></span></param>
        <param name="serviceTypeName"><span data-ttu-id="11a47-105">ServiceType の名前です。</span><span class="sxs-lookup"><span data-stu-id="11a47-105">Name of ServiceType.</span></span> <span data-ttu-id="11a47-106">サービス マニフェストで指定された ServiceTypeName と同じにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="11a47-106">This has to be same as the ServiceTypeName specified in the Service Manifest.</span></span></param>
        <param name="servicePackageActivationMode">
          <span data-ttu-id="11a47-107"><see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービスの作成を使用します。</span><span class="sxs-lookup"><span data-stu-id="11a47-107"><see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> to use for service creation.</span></span>
            </param>
        <param name="initializationData"><span data-ttu-id="11a47-108">サービスに渡される初期化データ。</span><span class="sxs-lookup"><span data-stu-id="11a47-108">Initialization data that will be passed to service.</span></span></param>
        <summary>
            <span data-ttu-id="11a47-109">インスタンスを作成<see cref="T:System.Fabric.Description.ServiceFromTemplateDescription" />指定パラメーターを使用します。</span><span class="sxs-lookup"><span data-stu-id="11a47-109">Creates an instance of <see cref="T:System.Fabric.Description.ServiceFromTemplateDescription" /> with specified parameter.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.ServiceFromTemplateDescription.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11a47-110">サービスが作成されるアプリケーションのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="11a47-110">The Service Fabric Name of the application under which the service will be created.</span></span>
            </summary>
        <value>
            <span data-ttu-id="11a47-111">返します<see cref="T:System.Uri" />Service Fabric アプリケーションの名前を表すです。</span><span class="sxs-lookup"><span data-stu-id="11a47-111">Returns <see cref="T:System.Uri" /> representing Service Fabric application name.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializationData">
      <MemberSignature Language="C#" Value="public byte[] InitializationData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] InitializationData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.InitializationData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InitializationData As Byte()" />
      <MemberSignature Language="F#" Value="member this.InitializationData : byte[]" Usage="System.Fabric.Description.ServiceFromTemplateDescription.InitializationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11a47-112">取得または作成されるときに、サービス グループのインスタンスまたはレプリカへ渡される初期化データを設定します。</span><span class="sxs-lookup"><span data-stu-id="11a47-112">Gets or sets the initialization data that will be passed to service group instances or replicas when they are created.</span></span>
            </summary>
        <value>
          <para><span data-ttu-id="11a47-113"><see cref="T:System.Byte" /> の配列を返します。</span><span class="sxs-lookup"><span data-stu-id="11a47-113">Returns an array of <see cref="T:System.Byte" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceDnsName">
      <MemberSignature Language="C#" Value="public string ServiceDnsName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceDnsName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.ServiceDnsName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceDnsName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceDnsName : string" Usage="System.Fabric.Description.ServiceFromTemplateDescription.ServiceDnsName" />
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
            <span data-ttu-id="11a47-114">作成するサービスの DNS 名。</span><span class="sxs-lookup"><span data-stu-id="11a47-114">The DNS name of the service to create.</span></span>
            </summary>
        <value>
            <span data-ttu-id="11a47-115">返します<see cref="T:System.String" />Service Fabric サービスの DNS 名を表すです。</span><span class="sxs-lookup"><span data-stu-id="11a47-115">Returns <see cref="T:System.String" /> representing Service Fabric service DNS name.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Description.ServiceFromTemplateDescription.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11a47-116">作成するサービスの名前です。</span><span class="sxs-lookup"><span data-stu-id="11a47-116">Name of the service to create.</span></span>
            </summary>
        <value>
            <span data-ttu-id="11a47-117">返します<see cref="T:System.Uri" />Service Fabric サービスの名前を表すです。</span><span class="sxs-lookup"><span data-stu-id="11a47-117">Returns <see cref="T:System.Uri" /> representing Service Fabric service name.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationMode">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServicePackageActivationMode ServicePackageActivationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServicePackageActivationMode ServicePackageActivationMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.ServicePackageActivationMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationMode As ServicePackageActivationMode" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationMode : System.Fabric.Description.ServicePackageActivationMode" Usage="System.Fabric.Description.ServiceFromTemplateDescription.ServicePackageActivationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePackageActivationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="11a47-118">取得または設定、<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービス。</span><span class="sxs-lookup"><span data-stu-id="11a47-118">Gets or sets the <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> of service.</span></span>
            </summary>
        <value>
             <span data-ttu-id="11a47-119"><see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> 列挙型。</span><span class="sxs-lookup"><span data-stu-id="11a47-119">An <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> enumeration.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string" Usage="System.Fabric.Description.ServiceFromTemplateDescription.ServiceTypeName" />
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
            <span data-ttu-id="11a47-120">作成するサービスの種類の名前です。</span><span class="sxs-lookup"><span data-stu-id="11a47-120">Name of the service type to create.</span></span>
            </summary>
        <value>
            <span data-ttu-id="11a47-121">返します<see cref="T:System.String" />Service Fabric サービスの型名を表すです。</span><span class="sxs-lookup"><span data-stu-id="11a47-121">Returns <see cref="T:System.String" /> representing Service Fabric service type name.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>